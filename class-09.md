# Forms
HTML Forms are required, when you want to collect some data from the site visitor. For example, during user registration you would like to collect information such as name, email address, credit card, etc.

A form will take input from the site visitor and then will post it to a back-end application such as CGI, ASP Script or PHP script etc. The back-end application will perform required processing on the passed data based on defined business logic inside the application.

There are various form elements available like text fields, textarea fields, drop-down menus, radio buttons, checkboxes, etc.   
## HTML Form Controls   
1. Text Input Controls   
2. Checkboxes Controls   
3. Radio Box Controls   
4. Select Box Controls   
5. File Select boxes   
6. Hidden Controls   
7. Clickable Buttons   
8. Submit and Reset Button   
## Single-line text input controls
This control is used for items that require only one line of user input, such as search boxes or names. They are created using HTML `<input>` tag.   
## Password input controls   
This is also a single-line text input but it masks the character as soon as a user enters it. They are also created using HTML `<input>` tag but type attribute is set to password.   
## Multiple-Line Text Input Controls   
This is used when the user is required to give details that may be longer than a single sentence. Multi-line input controls are created using HTML `<textarea>` tag.   
## Checkbox Control
Checkboxes are used when more than one option is required to be selected. They are also created using HTML `<input>` tag but type attribute is set to checkbox..    
## Radio Button Control   
Radio buttons are used when out of many options, just one option is required to be selected. They are also created using HTML `<input>` tag but type attribute is set to radio.   
## Select Box Control
A select box, also called drop down box which provides option to list down various options in the form of drop down list, from where a user can select one or more options.   
## File Upload Box
If you want to allow a user to upload a file to your web site, you will need to use a file upload box, also known as a file select box. This is also created using the `<input>` element but type attribute is set to file.     
## Hidden Form Controls
Hidden form controls are used to hide data inside the page which later on can be pushed to the server. This control hides inside the code and does not appear on the actual page. For example, following hidden form is being used to keep current page number. When a user will click next page then the value of hidden control will be sent to the web server and there it will decide which page will be displayed next based on the passed current page.   
# Tables
There are several types of information
that need to be displayed in a grid or
table. For example: sports results, stock
reports, train timetables.   
A table represents information in a grid format.
Examples of tables include financial reports, TV
schedules, and sports results.   
## Basic Table Structure
### `<table>`
The `<table>` element is used
to create a table. The contents
of the table are written out row
by row.
### `<tr>`
You indicate the start of each
row using the opening `<tr>` tag.
(The tr stands for table row.)
It is followed by one or more
`<td>` elements (one for each cell
in that row).   
### `<td>`
Each cell of a table is
represented using a `<td>`
element. (The td stands for
table data.)
At the end of each cell you use a
closing `</td>` tag.   
### `<th>`
The `<th`> element is used just
like the `<td>` element but its
purpose is to represent the
heading for either a column or
a row. (The th stands for table
heading.)
## Spanning ColumnS
Sometimes you may need the
entries in a table to stretch
across more than one column.
The colspan attribute can be
used on a `<th>` or `<td>` element
and indicates how many columns
that cell should run across.   
## Spanning Rows
You may also need entries in
a table to stretch down across
more than one row.
The rowspan attribute can be
used on a `<th>` or `<td>` element
to indicate how many rows a cell
should span down the table.    
## Long Tables
There are three elements that
help distinguish between the
main content of the table and
the first and last rows (which can
contain different content).
These elements help people
who use screen readers and also
allow you to style these sections
in a different manner than the
rest of the table (as you will see
when you learn about CSS).   
There are three elements that
help distinguish between the
main content of the table and
the first and last rows (which can
contain different content).
These elements help people
who use screen readers and also
allow you to style these sections
in a different manner than the
rest of the table (as you will see
when you learn about CSS).   
## `<thead>`
The headings of the table should
sit inside the `<thead>` element.
## `<tbody>`
The body should sit inside the
`<tbody>` element.
## `<tfoot>`
The footer belongs inside the
`<tfoot>` element.
## Width & Spacing
There are some outdated
attributes which you should not
use on new websites. You may,
however, come across some
of them when looking at older
code, so I will mention them
here. All of these attributes have
been replaced by the use of CSS.   
## Border & Background
The border attribute was used
on both the `<table>` and `<td>`
elements to indicate the width of
the border in pixels.
The bgcolor attribute was used
to indicate background colors
of either the entire table or
individual table cells. The value
is usually a hex code.   
# lists
Lists are a fundamental part of HTML! They are useful in things like blog posts for listing out steps, recipes for listing ingredients, or items in a navigation menu. Not only are they an opportunity for styling, but they have accessibility implications. For example, the number of items in a list is announced in a screen reader to give some context to the list.   
Before you do anything too fancy, know that there is quite few settings for list-style-type that might cover your needs out of the gate.   
## Image Bullets
The best bet is using a background-image on a pseudo-element. You’d think list-style-image would be the way to go, but it’s extremely limited. For example, you can’t position it or even resize it.   
## Inside vs. Outside
Things line up nicer with list-style-position: outside; (the default value), but the list markers render outside the box, so you have to be careful not to cut them off. They could hang off the edge of the browser window, or overflow: hidden; will hide them completely. The last two examples here have a trick to mimic the nicer alignment while rendering inside the element.   
## Colored Bullets
Three ways here:

::marker (newest and easiest)
Classic pseudo-element style
background-image (this one is an SVG Data URL so you can manipulate the color from the CSS)    
# Events
Events are actions or occurrences that happen in the system you are programming, which the system tells you about so you can respond to them in some way if desired. For example, if the user selects a button on a webpage, you might want to respond to that action by displaying an information box. In this article, we discuss some important concepts surrounding events, and look at how they work in browsers. This won't be an exhaustive study; just what you need to know at this stage.   
## A series of fortunate events
As mentioned above, events are actions or occurrences that happen in the system you are programming — the system produces (or "fires") a signal of some kind when an event occurs, and provides a mechanism by which an action can be automatically taken (that is, some code running) when the event occurs. For example, in an airport, when the runway is clear for take off, a signal is communicated to the pilot. As a result, the plane can safely takeoff.   
In the case of the Web, events are fired inside the browser window, and tend to be attached to a specific item that resides in it — this might be a single element, set of elements, the HTML document loaded in the current tab, or the entire browser window. There are many different types of events that can occur.   
You can gather from this (and from glancing at the MDN Event reference) that there are a lot of events that can be responded to.     

Each available event has an event handler, which is a block of code (usually a JavaScript function that you as a programmer create) that runs when the event fires. When such a block of code is defined to run in response to an event, we say we are registering an event handler. Note: Event handlers are sometimes called event listeners — they are pretty much interchangeable for our purposes, although strictly speaking, they work together. The listener listens out for the event happening, and the handler is the code that is run in response to it happening.      
## Ways of using web events
There are a number of ways to add event listener code to web pages so it runs when the associated event fires. In this section, we review the various mechanisms and discuss which ones you should use.   
* Event handler properties   
The onclick property is the event handler property being used in this situation. It is essentially a property like any other available on the button (e.g. btn.textContent, or btn.style), but it is a special type — when you set it to be equal to some code, that code is run when the event fires on the button.    
* Inline event handlers   
The earliest method of registering event handlers found on the Web involved event handler HTML attributes (or inline event handlers) like the one shown above — the attribute value is literally the JavaScript code you want to run when the event occurs. The above example invokes a function defined inside a `<script>` element on the same page, but you could also insert JavaScript directly inside the attribute.    
You can find HTML attribute equivalents for many of the event handler properties; however, you shouldn't use these — they are considered bad practice. It might seem easy to use an event handler attribute if you are doing something really quick, but they quickly become unmanageable and inefficient.   
For a start, it is not a good idea to mix up your HTML and your JavaScript, as it becomes hard to parse — keeping your JavaScript separate is best practice; if it is in a separate file you can apply it to multiple HTML documents.    
* addEventListener() and removeEventListener()    
The newest type of event mechanism is defined in the Document Object Model (DOM) Level 2 Events Specification, which provides browsers with a new function — addEventListener(). This functions in a similar way to the event handler properties, but the syntax is obviously different. We could rewrite our random color.   
