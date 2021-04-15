# Lists
There are lots of occasions when we
need to use lists. HTML provides us with
three different types:   
* Ordered lists are lists where each item in the list is
numbered. For example, the list might be a set of steps for
a recipe that must be performed in order, or a legal contract
where each point needs to be identified by a section
number.   
* Unordered lists are lists that begin with a bullet point
(rather than characters that indicate order).   
* Definition lists are made up of a set of terms along with the
definitions for each of those terms.   
Ordered lists use numbers.
* Unordered lists use bullets.
* Definition lists are used to define terminology.
* Lists can be nested inside one another.   
# Boxes
## Box Dimensions : width, height
By default a box is sized just big
enough to hold its contents. To
set your own dimensions for a
box you can use the height and
width properties.   
The most popular ways to
specify the size of a box are
to use pixels, percentages, or
ems. Traditionally, pixels have
been the most popular method
because they allow designers to
accurately control their size.   
## Limiting Width: min-width, max-width
Some page designs expand and
shrink to fit the size of the user's
screen. In such designs, the
min-width property specifies
the smallest size a box can be
displayed at when the browser
window is narrow, and the
max-width property indicates
the maximum width a box can
stretch to when the browser
window is wide.   
These are very helpful properties
to ensure that the content of
pages are legible (especially on
the smaller screens of handheld
devices). For example, you can
use the max-width property to
ensure that lines of text do not
appear too wide within a big
browser window and you can
use the min-width property
to make sure that they do not
appear too narrow.   
## Limiting Height: min-height, max-height   
In the same way that you might
want to limit the width of a box
on a page, you may also want
to limit the height of it. This is
achieved using the min-height
and max-height properties.   
The example on this page
demonstrates these properties
in action. It also shows you what
happens when the content of the
box takes up more space than
the size specified for the box.   
## overflow
The overflow property tells the
browser what to do if the content
contained within a box is larger
than the box itself. It can have
one of two values:   
### hidden
This property simply hides any
extra content that does not fit in
the box.   
### scroll
This property adds a scrollbar to
the box so that users can scroll
to see the missing content.   
## borders 
Every box has a border (even if
it is not visible or is specified to
be 0 pixels wide). The border
separates the edge of one box
from another.   
you can control the border width, style and color.    
## margin   
Margins sit outside the edge
of the border. You can set the
width of a margin to create a
gap between the borders of two
adjacent boxes.   
## padding 
Padding is the space between
the border of a box and any
content contained within it.
Adding padding can increase the
readability of its contents.   
## border-image
The border-image property
applies an image to the border of
any box. It takes a background
image and slices it into nine
pieces.   
## Arrays
An array is a special type of variable. It doesn't
just store one value; it stores a list of values.   
Arrays are especially helpful
when you do not know how
many items a list will contain
because, when you create the
array, you do not need to specify
how many values it will hold.   
## Switch Statement   
A switch statement starts with a
variable called the switch value.
Each case indicates a possible
value for this variable and the
code that should run if the
variable matches that value.   
Here, the variable named 1 eve l is the switch value.
If the value of the l eve 1 variable is the string One,
then the code for the first case is executed. If it is
Two, the second case is executed. If it is Three, the
third case is executed. If it is none of these, the code
for the defaul t case is executed.   
JavaScript can convert data
types behind the scenes to
complete an operation. This is
known as type coercion. For
example, a string 'l ' could be
converted to a number 1 in the
following expression:(' 1' > 0).
As a result, the above expression
would evaluate to true.
JavaScript is said to use weak
typing because the data type
for a value can change. Some
other languages require that you
specify what data type
each variable will be. They are
said to use strong typing.   
# Loops
they are used for iterations in general   
we have two types of loops, for loop and while loop   
Loops offer a quick and easy way to do something repeatedly. This chapter of the JavaScript Guide introduces the different iteration statements available to JavaScript.   
A while statement executes its statements as long as a specified condition evaluates to true.   
If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.   
The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while.   
* Conditional statements allow your code to make
decisions about what to do next.
* Comparison operators (===, ! ==, ==, ! =, <, >, <=, =>)
are used to compare two operands.
* Logical operators allow you to combine more than one
set of comparison operators.
* if ... else statements allow you to run one set of code
if a condition is true, and another if it is false.
* switch statements allow you to compare a value
against possible outcomes (and also provides a default
option if none match).
* Data types can be coerced from one type to another.
* All values evaluate to either truthy or falsy.
* There are three types of loop: for, while, and
do ... while. Each repeats a set of statements.