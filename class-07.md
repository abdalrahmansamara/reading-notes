# Domain Modeling
Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.   
Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.   
* When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
* Model its attributes with a constructor function that defines and initializes properties.
* Model its behaviors with small methods that focus on doing one job well.
* Create instances using the new keyword followed by a call to a constructor function.
* Store the newly created object in a variable so you can access its properties and methods from outside.
* Use the this variable within methods so you can access the object's properties and methods from inside.

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
# Objects
## CREATING MANY OBJECTS: CONSTRUCTOR NOTATION
Sometimes you will want several objects to represent similar things.
Object constructors can use a function as a template for creating objects.
First, create the template with the object's properties and methods.    
## This
The keyword this is commonly used inside functions and objects.
Where the function is declared alters what this means. It always refers
to one object, usually the object in which the function operates.   
* A function in global scope       
When a function is created at the top level of a script
(that is, not inside another object or function), then it
is in the global scope or global context.
The default object in this context is the window
object. so when this is used inside a function in the
global context it refers to the window object.
* A golbal scope     
All global variables also become properties of the
window object. so when a function is in the global
context, you can access global variables using the
window object, as well as its other properties.    
* a method of an object   
When a function is defined inside an object, it
becomes a method. In a method, this refers to the
containing object.   
* function expression as method   
If a named function has been defined in global
scope, and it is then used as a method of an object,
this refers to the object it is contained within.   