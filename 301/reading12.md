# EJS Partials

Partials come in handy when you want to reuse the same HTML across multiple views. Think of partials as functions, they make large websites easier to maintain as you don’t have to go and change a piece of text in every page it appears in. Instead, you define that reusable bundle of code in a file andinclude it wherever you need it.
Our blog will consist of a home page which lists all the blog posts and a post page which will display a single post. Our home page will look like so:

As you can see from the screenshots above, the same navigation bar and footer appear in both the home and post view. This makes them perfect candidates for partials!
Let’s go ahead and create those partials. Under the views/partials/ directory create a file callednavbar.ejs which will contain only the HTML for the navigation bar at the top of the home and post pages:

Now that we have our partials defined, we can use them in our home.ejs and post.ejs templates! In EJS, any JavaScript or non-HTML syntax you include in your templates is always surrounded by <% %> delimiters (you could change these delimiters if you really wanted to).
Including a partial in EJS is quite straightforward. You use <%- include( PARTIAL_FILE ) %> where the partial file is relative to the template you use it in.

Note: The <%- %> tags allow us to output the unescaped content onto the page (notice the -). This is important when using the include() statement since you don’t want EJS to escape your HTML characters like ‘<’, ‘>’, etc…

As you can see creating and including partials is very straightforward with EJS. I’ve intentionally left in some placeholders such as LIST_OF_POSTS, POST_TITLE, POST_AUTHOR, and POST_CONTENT so that we can take a look at how we can pass data from our Node + Express application to our views in the next section.

Previously we made a folder called views and Express knew automatically to look into that folder for our page templates. However that is the only location that Express has programmed by default. If we want Express to know where our stylesheets are located we need to direct it to them.

Partials are templates that we can write, that we can include in other templates. For example our html boilerplate, we don’t want to include on every template, that’s not very DRY.

## Linking Partials in Templates

This new command include is telling Express to pull the contents of the named template and place it in place of this command.

We know that Express is already looking in the views directory for our templates, so when we give the name of the template to be included we consider that to be the root directory, but we still have to tell it to look in the partials folder that we made. so our template name would look like this.