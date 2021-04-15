# Texts
When creating a web page, you add tags
(known as markup) to the contents of the
page. These tags provide extra meaning
and allow browsers to show users the
appropriate structure for the page.   
## Headings
HTML has six "levels" of
headings:   
* h1
* h2
* h3
* h4
* h5
* h6
Browsers display the contents of
headings at different sizes. The
contents of an h1 element is
the largest, and the contents of
an h6 element is the smallest.
The exact size at which each
browser shows the headings
can vary slightly. Users can also
adjust the size of text in their
browser. You will see how to
control the size of text, its color,
and the fonts used when we
come to look at CSS.   
## Paragraphs   
To create a paragraph, surround
the words that make up the
paragraph with an opening p
tag and closing p tag.   
## Bold & Italic   
we use the b tag for bold, and the i tag for italic.   
## Line Breaks & Horizontal Rules 
the
browser will automatically show
each new paragraph or heading
on a new line. But if you wanted
to add a line break inside the
middle of a paragraph you can
use the line break tag br.   
To create a break between
themes — such as a change of
topic in a book or a new scene
in a play — you can add a
horizontal rule between sections
using the hr  tag.   
## Strong & Emphasis
The use of the strong
element indicates that its
content has strong importance.
For example, the words
contained in this element might
be said with strong emphasis.   
The em element indicates
emphasis that subtly changes
the meaning of a sentence.
By default browsers will show
the contents of an em element
in italic.   
## Abbreviations & Acronyms
If you use an abbreviation or
an acronym, then the abbr
element can be used. A title
attribute on the opening tag is
used to specify the full term.   
## Changes to Content
The ins element can be used
to show content that has been
inserted into a document, while
the del element can show text
that has been deleted from it.   

# Introducing CSS
CSS allows you to create rules that specify how the content of
an element should appear. For example, you can specify that
the background of the page is cream, all paragraphs should
appear in gray using the Arial typeface, or that all level one
headings should be in a blue, italic, Times typeface.   
CSS allows you to create rules that control the
way that each individual box (and the contents
of that box) is presented.   
there are three ways to use css:    
1. internal css
2. external css
3. inline css   
If you specify the font-family
or color properties on the
body element, they will apply
to most child elements. This is
because the value of the
font-family property is
inherited by child elements. It
saves you from having to apply
these properties to as many
elements (and results in simpler
style sheets).   
You can compare this with
the background-color or
border properties; they are not
inherited by child elements. If
these were inherited by all child
elements then the page could
look quite messy.   
# basic JS instructions
A script is a series of instructions that a computer can follow one-by-one.
Each individual instruction or step is known as a statement.
Statements should end with a semicolon.   
A statement is an individual instruction that the
computer should follow. Each one should start on a
new line and end with a semicolon. This makes your
code easier to read and follow.   
Some statements are surrounded by curly braces;
these are known as code blocks. The closing curly
brace is not followed by a semicolon.   
## Comments
You should write comments to explain what your code does.
They help make your code easier to read and understand.
This can help you and others who read your code.   
## variables
A script will have to temporarily
store the bits of information it
needs to do its job. It can store this
data in variables.   
## Data types
* numeric Data type
* string Data type
* boolean Data type
## Creating an array
You create an array and give it
a name just like you would any
other variable (using the var
keyword followed by the name of
the array).   
The values are assigned to the
array inside a pair of square
brackets, and each value is
separated by a comma. The
values in the array do not need
to be the same data type, so you
can store a string, a number and
a Boolean all in the same array.   
## Comparison operators
we have eight comparison operators, all used in order to comapre between two sides:   
* is equal to "=="   
it compares if the value on the right is the smae to the left, regarding the value's type   
* is not equal to "!="   
it compares two values to check if the values are not equal
* strict equal (===)   
Returns true if the operands are equal and of the same type
* strict not equal (!==)   
Returns true if the operands are of the same type but not equal, or are of different type.   
* greater than (>)   
Returns true if the left operand is greater than the right operand.   
* Greater than or equal (>=)   
Returns true if the left operand is greater than or equal to the right operand.   
* Less than (<)   
Returns true if the left operand is less than the right operand.   
* Less than or equal (<=)   
Returns true if the left operand is less than or equal to the right operand.
# Logical operations
we have three logical operations   
* and (&&)   
its used to check if both the conditions are true
* or (||)  
it would return true if one of the values is true
* not (!)   
it would reverse the boolien's condition   
# Loops
they are used for iterations in general   
we have two types of loops, for loop and while loop   
Loops offer a quick and easy way to do something repeatedly. This chapter of the JavaScript Guide introduces the different iteration statements available to JavaScript.   
A while statement executes its statements as long as a specified condition evaluates to true.   
If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.   
The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while.   
