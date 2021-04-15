# Structure
Many web pages act like electronic versions of these
documents. For example, newspapers show the same stories
in print as they do on websites; you can apply for insurance
over the web; and stores have online catalogs and e-commerce
facilities.   
In the browser window you can see a web page that features exactly
the same content. To
describe the structure of a web page, we add code to the words we want to appear on the page.    
Attributes provide additional information
about the contents of an element. They appear
on the opening tag of the element and are
made up of two parts: a name and a value,
separated by an equals sign.   
## body
You met the body element
in the first example we created.
Everything inside this element is
shown inside the main browser
window.
## head
Before the body element you
will often see a head element.
This contains information
about the page (rather than
information that is shown within
the main part of the browser
window that is highlighted in
blue on the opposite page).
You will usually find a title
element inside the head
element.   
## title
The contents of the title
element are either shown in the
top of the browser, above where
you usually type in the URL of
the page you want to visit, or
on the tab for that page (if your
browser uses tabs to allow you
to view multiple pages at the
same time).    
# the evolution of HTML versions
Each new version was designed
to be an improvement on the
last (with new elements and
attributes added and older code
removed).    
There have also been several
versions of each browser used to
view web pages, each of which
implements new code. Not all
web users, however, have the
latest browsers installed on
their computers, which means
that not everyone will be able to
view all of the latest features and
markup.    
Because there have been
several versions of HTML, each
web page should begin with a
DOCTYPE declaration to tell a
browser which version of HTML
the page is using (although
browsers usually display the
page even if it is not included).
We will therefore be including
one in each example for the rest
of the book.    
## Comments
If you want to add a comment
to your code that will not be
visible in the user's browser, you
can add the text between these
characters:   
"!-- comment goes here --" with tags instead of double coutations.
## ID Attribute
Every HTML element can carry
the id attribute. It is used to
uniquely identify that element
from other elements on the
page. Its value should start with
a letter or an underscore (not a
number or any other character).
It is important that no two
elements on the same page
have the same value for their id
attributes (otherwise the value is
no longer unique).   
## class attribute
Every HTML element can
also carry a class attribute.
Sometimes, rather than uniquely
identifying one element within
a document, you will want a
way to identify several elements
as being different from the
other elements on the page.
For example, you might have
some paragraphs of text that
contain information that is more
important than others and want
to distinguish these elements, or
you might want to differentiate
between links that point to other
pages on your own site and links
that point to external sites.    
* The meta element lives
inside the head element and
contains information about that
web page.
* It is not visible to users but
fulfills a number of purposes
such as telling search engines
about your page, who created
it, and whether or not it is time
sensitive. (If the page is time
sensitive, it can be set to expire.)    

# HTML 5 layout 
* The new HTML5 elements indicate the purpose of
different parts of a web page and help to describe
its structure.   
* The new elements provide clearer code (compared
with using multiple div elements).
* Older browsers that do not understand HTML5
elements need to be told which elements are
block-level elements.
* To make HTML5 elements work in Internet Explorer 8
(and older versions of IE), extra JavaScript is needed,
which is available free from Google.
# Designing a website
* It's important to understand your target audience
is, why they would come to your site, what information
they want to find and when they are likely to return.   
* Site maps allow you to plan the structure of a site.  
* Wireframes allow you to organize the information that
will need to go on each page.
* Design is about communication. Visual hierarchy helps
visitors understand what you are trying to tell them.
* You can differentiate between pieces of information
using size, color, and style.
* You can use grouping and similarity to help simplify
the information you present.   
# ABC of JS
A script is a series of instructions that the computer
can follow in order to achieve a goal.
Each time the script runs, it might only use a subset of
all the instructions.
Computers approach tasks in a different way than
humans, so your instructions must let the computer
solve the task prggrammatically.
To approach writing a script, break down your goal into
a series of tasks and then work out each step needed
to complete that task (a flowchart can help).   
Computers create models of the world using data.
The models use objects to represent physical things. 
Objects can have: properties that tell us about
the object; methods that perform tasks using the 
properties of that object; events which are triggered when a user interacts with the computer.
when a user interacts with the computer.
Programmers can write code to say "When this event 
occurs, run that code."
Web browsers use HTML markup to create a model 
of the web page. Each element creates its own node 
(which is a kind of object).
To make web pages interactive, you write code that 
uses the browser's model of the web page.   
It is best to keep JavaScript code in its own JavaScript 
file. JavaScript files are text files (like HTML pages and 
CSS style sheets), but they have the .js extension.
The HTML script element is used in HTML pages 
to tell the browser to load the JavaScript file (rather like 
the link tag element can be used to load a CSS file).
If you view the source code of the page in the browser, 
the JavaScript will not have changed the HTML, 
because the script works with the model of the web 
page that the browser has created.
