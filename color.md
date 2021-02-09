# Colors in CSS
CSS works by associating rules with HTML elements. These rules govern
how the content of specified elements should be displayed. A CSS rule
contains two parts: a selector and a declaration.   
CSS declarations sit inside curly brackets and each is made up of two
parts: a property and a value, separated by a colon. You can specify
several properties in one declaration, each separated by a semi-colon.   
## css selectors
There are many different types
of CSS selector that allow you to
target rules to specific elements
in an HTML document.   
The table on the opposite page
introduces the most commonly
used CSS selectors.   
On this page, there is an HTML
file to demonstrate which
elements these CSS selectors
would apply to.   
CSS selectors are case sensitive,
so they must match element
names and attribute values
exactly.   
## External stylesheets   
All of your web pages can share
the same style sheet. This is
achieved by using the "link"
element on each HTML page of
your site to link to the same CSS
document. This means that the
same code does not need to be
repeated in every page (which
results in less code and smaller
HTML pages).   
Therefore, once the user has
downloaded the CSS stylesheet,
the rest of the site will load
faster. If you want to make a
change to how your site appears,
you only need to edit the one
CSS file and all of your pages
will be updated. For example,
you can change the style of
every "h1" element by altering the one CSS style sheet, rather
than changing the CSS rules on
every page. The HTML code
will be easier to read and edit
because it does not have lots of
CSS rules in the same document.
It is generally considered good
practice to have the content of
the site separated from the rules
that determine how it appears.   
* CSS treats each HTML e XX lement as if it appears inside
its own box and uses rules to indicate how that
element should look.
* Rules are made up of selectors (that specify the
elements the rule applies to) and declarations (that
indicate what these elements should look like).
* Declarations are made up of two parts: the properties
of the element that you want to change, and the values
of those properties. For example, the font-family
property sets the choice of font, and the value arial
specifies Arial as the preferred typeface.   

# Colors
The color property allows you
to specify the color of text inside
an element. You can specify any
color in CSS in one of three ways:   
* rgb values   
These express colors in terms
of how much red, green and
blue are used to make it up. For
example: rgb(100,100,90)   
Values for red, green, and blue
are expressed as numbers
between 0 and 255.   
* hex codes   
These are six-digit codes that
represent the amount of red,
green and blue in a color,
preceded by a pound or hash #
sign. For example: #ee3e80   
Hex values represent values
for red, green, and blue in
hexadecimal code.    
* color names   
There are 147 predefined color
names that are recognized
by browsers. For example:
DarkCyan    
Colors are represented by
predefined names. However,
they are very limited in number.   
## Background color   
html
CSS treats each HTML element
as if it appears in a box, and the
background-color property
sets the color of the background
for that box.
You can specify your choice of
background color in the same
three ways you can specify
foreground colors: RGB values,
hex codes, and color names
(covered on the next page).   
By default, most browser
windows have a white
background, but browser users
can set a background color for
their windows, so if you want
to be sure that the background
is white you can use the
background-color property on
the "body" element.   
### Saturation
Saturation refers to the amount
of gray in a color. At maximum
saturation, there would be no
gray in the color. At minimum
saturation, the color would be
mostly gray.   
### Brightness   
Brightness (or "value") refers
to how much black is in a color.
At maximum brightness, there
would be no black in the color.
At minimum brightness, the
color would be very dark.   
### Hue   
Hue is near to the colloquial idea
of color. Technically speaking
however, a color can also have
saturation and brightness as
well as hue.   
## Opacity   
CSS3 introduces the opacity
property which allows you to
specify the opacity of an element
and any of its child elements.
The value is a number between
0.0 and 1.0 (so a value of 0.5
is 50% opacity and 0.15 is 15%
opacity).   
The CSS3 rgba property allows
you to specify a color, just like
you would with an RGB value,
but adds a fourth value to
indicate opacity. This value is
known as an alpha value and is
a number between 0.0 and 1.0
(so a value of 0.5 is 50% opacity
and 0.15 is 15% opacity). The
rgba value will only affect the
element on which it is applied
(not child elements).   
* Color not only brings your s XX ite to life, but also helps
convey the mood and evokes reactions.   
* There are three ways to specify colors in CSS:
RGB values, hex codes, and color names.   
* Color pickers can help you find the color you want.   
* It is important to ensure that there is enough contrast
between any text and the background color (otherwise
people will not be able to read your content).