# Images
There are many reasons why you might
want to add an image to a web page: you
might want to include a logo, photograph,
illustration, diagram, or chart.   
Images can be used to set the
tone for a site in less time than
it takes to read a description. If
you do not have photographs
to use on your website, there
are companies who sell stock
images; these are images you pay to use (there is a list of stock
photography websites below).
Remember that all images are
subject to copyright, and you
can get in trouble for simply
taking photographs from
another website.   
As a website grows, keeping
images in a separate folder
helps you understand how the
site is organized. Here you can
see an example of the files for
a website; all of the images are
stored in a folder called images.   
## Adding Images
To add an image into the page
you need to use an `<img>`
element. This is an empty
element (which means there is
no closing tag). It must carry the
following two attributes: src, alt and title.   
## Tools to Edit & Save Images
The most popular tool amongst
web professionals is Adobe
Photoshop. (In fact, professional
web designers often use this
software to design entire sites.)
The full version of Photoshop is
expensive, but there is a cheaper
version called Photoshop
Elements which would suit the
needs of most beginners.   
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
# Text
The properties that allow you to control
the appearance of text can be split into
two groups:   
* Those that would have the same effect on text no matter
what font you were using (including the color of text and
the spacing between words and letters)   
* Those that directly affect t ●● he font and its appearance
(including the typeface, whether it is regular, bold or italic,
and the size of the text)   
There are several ways to use fonts other than those listed on the
previous page. However, typefaces are subject to copyright, so the
techniques you can choose from are limited by their respective licenses.   
## `font-family`
The font-family property
allows you to specify the
typeface that should be used for
any text inside the element(s) to
which a CSS rule applies.
The value of this property is the
name of the typeface you want
to use.
The people who are visiting
your site need the typeface you
have specified installed on their
computer in order for it to be
displayed.   
## `font-size`
The font-size property enables
you to specify a size for the
font. There are several ways to
specify the size of a font.   
## `@font-face`
@font-face allows you to use
a font, even if it is not installed
on the computer of the person
browsing, by allowing you to
specify a path to a copy of the
font, which will be downloaded if
it is not on the user's machine.
Because this technique allows
a version of the font to be
downloaded to the user's
computer, it is important that the
license for the font permits it to
be used in this way.   
## `text-transform`
The text-transform property
is used to change the case of
text giving it one of the following
values:   
* uppercase   
This causes the text to appear
uppercase.
* lowercase   
This causes the text to appear
lowercase.
* capitalize   
This causes the first letter of
each word to appear capitalized.
## `letter-spacing, word-spacing`
Kerning is the term
typographers use for the space
between each letter. You can
control the space between each
letter with the letter-spacing
property.
It is particularly helpful to
increase the kerning when
your heading or sentence is
all in uppercase. If your text is
in sentence (or normal) case,
increasing or decreasing the
kerning can make it harder to
read.   
## `text-shadow`
The text-shadow property has
become commonly used despite
lacking support in all browsers.
It is used to create a drop
shadow, which is a dark version
of the word just behind it and
slightly offset. It can also be used
to create an embossed effect by
adding a shadow that is slightly
lighter than the text.
The value of this property is
quite complicated because it can
take three lengths and a color for
the drop shadow.   
## Responding to Users
:hover, :active, :focus
:hover
This is applied when a user
hovers over an element with a
pointing device such as a mouse.
This has commonly been used
to change the appearance of
links and buttons when a user
places their cursor over them. It
is worth noting that such events
do not work on devices that use
touch screens (such as the iPad)
because the screen is not able to
tell when someone is hovering
their finger over an element.    
:active
This is applied when an element
is being activated by a user; for
example, when a button is being
pressed or a link being clicked.
Sometimes this is used to make
a button or link feel more like it
is being pressed by changing the
style or position of the element
slightly.    
:focus
This is applied when an element
has focus. Any element that
you can interact with, such as a
link you can click on or any form
control can have focus.    
