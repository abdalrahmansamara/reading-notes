# Links
Links are created using the `<a>` element. Users can click on anything
between the opening `<a>` tag and the closing `</a>` tag. You specify
which page you want to link to using the href attribute.   
Links are created using the `<a>`
element which has an attribute
called href. The value of the
href attribute is the page that
you want people to go to when
they click on the link.    
## Directory Structure
On larger websites it's a good idea to organize your code by placing the
pages for each different section of the site into a new folder. Folders on a
website are sometimes referred to as directories.   
1. Structure   
The diagram on the right shows
the directory structure for a
fictional entertainment listings
website called ExampleArts.
2. Relationships   
The relationship between
files and folders on a website
is described using the same
terminology as a family tree.   
3. Homepages   
The main homepage of a site
written in HTML (and the
homepages of each section in a
child folder) is called index.html.   
## Relative URLs   
Relative URLs can be used when linking to pages within your own
website. They provide a shorthand way of telling the browser where to
find your files.   
## Email Links
mailto   
To create a link that starts up
the user's email program and
addresses an email to a specified
email address, you use the `<a>`
element. However, this time the
value of the href attribute starts
with mailto: and is followed by
the email address you want the
email to be sent to.
On the right you can see that
an email link looks just like any
other link but, when it is clicked
on, the user's email program
will open a new email message
and address it to the person
specified in the link.    
## Opening Links in a New Window [target]
If you want a link to open in a
new window, you can use the
target attribute on the opening
`<a>` tag. The value of this
attribute should be _blank.
# Layout
Block-level boxes start on a new line and act as the main building blocks
of any layout, while inline boxes flow between surrounding text. You can
control how much space each box takes up by setting the width of the
boxes (and sometimes the height, too). To separate boxes, you can use
borders, margins, padding, and background colors.   
## Controlling the Position of Elements   
CSS has the following positioning schemes that allow you to control
the layout of a page: normal flow, relative positioning, and absolute
positioning. You specify the positioning scheme using the position
property in CSS. You can also float elements using the float property.   
##  Normal flow
In normal flow, each block-level
element sits on top of the next
one. Since this is the default
way in which browsers treat
HTML elements, you do not
need a CSS property to indicate
that elements should appear
in normal flow, but the syntax
would be:   `position: static;`   
## position:relative
Relative positioning moves an
element in relation to where it
would have been in normal flow.
For example, you can move it 10
pixels lower than it would have
been in normal flow or 20% to
the right.   
## position:absolute
When the position property
is given a value of absolute,
the box is taken out of normal
flow and no longer affects the
position of other elements on
the page. (They act like it is not
there.)   
## Overlapping Elements z-index
When you use relative, fixed, or
absolute positioning, boxes can
overlap. If boxes do overlap, the
elements that appear later in the
HTML code sit on top of those
that are earlier in the page.   
If you want to control which
element sits on top, you can use
the z-index property. Its value
is a number, and the higher the
number the closer that element
is to the front. For example, an
element with a z-index of 10
will appear over the top of one
with a z-index of 5.   
## Floating Elements float
The float property allows you
to take an element in normal
flow and place it as far to the
left or right of the containing
element as possible.
Anything else that sits inside
the containing element will
flow around the element that is
floated.   
## using Float to Place Elements Side-by-Side
A lot of layouts place boxes
next to each other. The float
property is commonly used to
achieve this.   
## Clearing Floats
The clear property allows you
to say that no element (within
the same containing element)
should touch the left or righthand
sides of a box. It can take
the following values   
* You can include multiple CSS files in one page.   
* CSS Frameworks provide rules for common tasks.
*   Grids help create professional and flexible designs.   
* Designers keep pages within 960-1000 pixels wide,
and indicate what the site is about within the top 600
pixels (to demonstrate its relevance without scrolling).   
# Functions
Functions let you group a series of statements together to perform a
specific task. If different parts of a script repeat the same task, you can
reuse the function (rather than repeating the same set of st atements).   
## ANONYMOUS FUNCTIONS & FUNCTION EXPRESSIONS
Expressions produce a value. They can be used where values are expected.
If a function is placed where a browser expects to see an expression,
(e.g., as an argument to a function), then it gets treated as an expression.   
## FUNCTION DECLARATION
A function declaration creates a function that you
can ca ll later in your code. It is the type of function
you have seen so far in this book.
In order to call the function later in your code, you
must give it a name, so these are known as named
functions. Below, a function called area() is
declared, which can then be called using its name.   
## FUNCTION EXPRESSION
If you put a function where the interpreter would
expect to see an expression, then it is treated as an
expression, and it is known as a function expression.
In function expressions, the name is usually omitted.
A function with no name is called an anonymous
function. Below, the function is stored in a variable
called area. It can be called like any function created
with a function declaration.   
# 6 Reasons for Pair Programming
Iterative loops. Code reviews. Fast feedback. Error checking and linting. These are software engineering practices that have proven to dramatically improve the quality of code developers produce. What if you can could get all of this, instantaneously, while typing code line by line and character by character? You can, with pair programming, a technique common to many agile work environments.   

More “two heads are better than one” than “stop reading over my shoulder,” pair programming is the practice of two developers sharing a single workstation to interactively tackle a coding task together. At Code Fellows, pair programing is one way we foster a collaborative environment while developing key industry skills.   
# Why pair program?
While learning to code, developers likely study several programming languages. Similar to a foreign language class, there are four fundamental skills that help anyone learn a new language: Listening: hearing and interpreting the vocabulary Speaking: using the correct words to communicate an idea Reading: understanding what written language intends to convey Writing: producing from scratch a meaningful    
* Greater efficiency   
It is a common misconception that pair programming takes a lot longer and is less efficient. In reality, when two people focus on the same code base, it is easier to catch mistakes in the making.   
* Engaged collaboration
When two programmers focus on the same code, the experience is more engaging and both programmers are more focused than if they were working alone.     
* Learning from fellow students   
Everyone has a different approach to problem solving; working with a teammate can expose developers to techniques they otherwise would not have thought of. If one developer has a unique approach to a specific problem, pair programming exposes the other developer to a new solution.   
* Social skills   
Pair programming is great for improving social skills. When working with someone who has a different coding style, communication is key. This can become more difficult when two programmers have different personalities.   
* Job interview readiness   
A common step in many interview processes involves pair programming between a current employee and an applicant, either in person or through a shared screen.   
* Work environment readiness   
Many companies that utilize pair programing expect to train fresh hires from CS-degree programs on how they operate to actually deliver a product. Code Fellows graduates who are already familiar with how pairing works can hit the ground running at a new job, with one less hurdle to overcome.   