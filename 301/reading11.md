# EJS

When creating quick on-the-fly Node applications, an easy and fast way to template our application is sometimes necessary.

EJS is among the most popular tempate view engines for node.js and expressjs with 4.2k stars at github and over 5.5m downloads per week at npm.
EJS simply stands for Embedded JavaScript templates, and we can use it both server-side or client-side. At this story, we’ll focus on the server-side.

npm in the above commands stands for the node package manager, a place where install all the dependencies. –save flag is no longer needed after Node 5.0.0 version, as all the modules that we now install will be added to dependencies.
Now, the first thing we need to do is to set EJS as our templating engine with Express which is a Node.js web application server framework, which is specifically designed for building single-page, multi-page, and hybrid web applications. It has become the standard server framework for node.js.

The default behavior of EJS is that it looks into the ‘views’ folder for the templates to render. So, let’s make a ‘views’ folder in our main node project folder and make a file named “home.ejs” which is to be served on some desired request in our node project.

EJS partials make it possible to create reusable views. In a real-world application, there can be over 100 HTML files with the same footer. To reduce the development time of such a website, the partials become handy.

With the partials, we can create a single footer partial file and reuse it across all the pages on the website. Partials improve productivity because in the case of maintenance, changing the code at a single point changes all the occurrences in the pages reusing the partial.

## Routes

In the routes folder, we store the JavaScript files containing the logic that is executed whenever a certain route is visited.

In our case whenever you visit 121.0.0.1:5000/ when the development server is running, the logic in our IndexRoute.js file will be executed to respond to the request.

In the root project directory, create a file named IndexRouter.js and add the code snippets below into it.

## Basic Syntax(Tags):

* <% 'Scriptlet' tag, for control-flow, no output
* <%= Outputs the value into the template (HTML escaped)
* <%- Outputs the unescaped value into the template

EJS is a simple templating language that lets you generate HTML markup with plain JavaScript. No religiousness about how to organize things. No reinvention of iteration and control-flow. It's just plain JavaScript.

* Use plain JavaScript

We love JavaScript. It's a totally friendly language. All templating languages grow to be Turing-complete. Just cut out the middle-man, and use JS!

* Fast development time

Don't waste time and attention figuring out arcane new syntax because 'elegance' — or how to preprocess your data so it will actually render right.

* Simple syntax

JavaScript code in simple, straightforward scriptlet tags. Just write JavaScript that emits the HTML you want, and get the job done!

* Speedy execution

We all know how fast V8 and the other JavaScript runtimes have gotten. EJS caches the intermediate JS functions for fast execution.

* Easy debugging

It's easy to debug EJS errors: your errors are plain JavaScript exceptions, with template line-numbers included.

* Active development

EJS has a large community of active users, and the library is under active development. We're happy to answer your questions or give you help.

Now that you have learned how to use EJS template tags and partials, create a website that reuses a footer and implements conditional statements within the EJS template.