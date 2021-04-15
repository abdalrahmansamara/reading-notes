# Images
Controlling the size and alignment of
your images using CSS keeps rules that
affect the presentation of your page in
the CSS and out of the HTML markup.   
## Controlling sizes of images in CSS   
You can control the size of an
image using the width and
height properties in CSS, just
like you can for any other box.
Specifying image sizes helps
pages to load more smoothly
because the HTML and CSS
code will often load before the
images, and telling the browser
how much space to leave for an
image allows it to render the rest
of the page without waiting for
the image to download.   
You might think that your site
is likely to have images of all
different sizes, but a lot of sites
use the same sized image across
many of their pages.    
## AligNi ng images Using CSS    
Rather than using the <img>
element's align attribute, web
page authors are increasingly
using the float property to align
images. There are two ways that
this is commonly achieved:    
1. The float property is added
to the class that was created to
represent the size of the image.    
2. New classes are created with
names such as align-left or
align-right to align the images
to the left or right of the page.
These class names are used in
addition to classes that indicate
the size of the image.    
## Centering images using CSS   
By default, images are inline
elements. This means that they
flow within the surrounding text.
In order to center an image, it
should be turned into a blocklevel
element using the display
property with a value of block.
Once it has been made into a
block-level element, there are
two common ways in which you
can horizontally center an image:    
1. On the containing element,
you can use the text-align
property with a value of center.    
2. On the image itself, you can
use the use the margin property
and set the values of the left and
right margins to auto.     
## Background Images
The background-image
property allows you to place
an image behind any HTML
element. This could be the entire
page or just part of the page. By
default, a background image will
repeat to fill the entire box.    
The path to the image follows
the letters url, and it is put
inside parentheses and quotes.    
Background images are often
the last thing on the page to
load (which can make a website
seem slow to load). As with any
images you use online, if the
size of the file is large it will take
longer to download.    
## Background Position
When an image is not being
repeated, you can use the
background-position
property to specify where in the
browser window the background
image should be placed.   
This property usually has a pair
of values. The first represents
the horizontal position and the
second represents the vertical.    
# Search Engine Optimization (SEO)
Search engine optimization (or
SEO) is the practice of trying
to help your site appear nearer
the top of search engine results
when people look for the topics
that your website covers.    
At the heart of SEO is the idea of
working out which terms people
are likely to enter into a search
engine to find your site and then
using these terms in the right
places on your site to increase
the chances that search engines
will show a link to your site in
their results.    
In order to determine who comes
first in the search results, search
engines do not only look at what
appears on your site. They also
consider how many sites link
to you (and how relevant those
links are). For this reason, SEO
is often split into two areas:
on-page techniques and off-page
techniques.    
## What is SEO & Why is it Important?
Search engine optimization is the process of optimizing web pages and their content to be easily discoverable by users searching for terms relevant to your website. The term SEO also describes the process of making web pages easier for search engine indexing software, known as "crawlers," to find, scan, and index your site.   
While the concept of SEO is relatively straightforward, many newcomers to SEO still have questions about the specifics, such as:    
* How do you “optimize” for your site or your company’s site for search engines?
* How do you know how much time to spend on SEO?
* How can you differentiate “good” SEO advice from “bad” or harmful SEO advice?
## What Actually Works for Driving SEO Traffic from Search Engines?    
It’s important to note that Google is responsible for the majority of the search engine traffic in the world. This may vary from one industry to another, but it’s likely that Google is the dominant player in the search results that your business or website would want to show up in, but the best practices outlined in this guide will help you to position your site and its content to rank in other search engines, as well.    
Google’s algorithm is extremely complex, but at a high level:    
* Google is looking for pages that contain high-quality, relevant information relevant to the searcher’s query.     
* Google's algorithm determines relevance by “crawling” (or reading) your website’s content and evaluating (algorithmically) whether that content is relevant to what the searcher is looking for, based on the keywords it contains and other factors (known as "ranking signals").     
* Google determines “quality” by a number of means, but a site's link profile - the number and quality of other websites that link to a page and site as a whole - is among the most important.     
## SEO Keyword Research & Keyword Targeting Best Practices    
The first step in search engine optimization is to determine what you’re actually optimizing for. This means identifying terms people are searching for, also known as “keywords,” that you want your website to rank for in search engines like Google.    

For example, you may want your widget company to show up when people look for “widgets,” and maybe when they type in things like “buy widgets.” The figure below shows search volume, or the estimated number of searches for a specific term, over a period of time:    
There are several key factors to take into account when determining the keywords you want to target on your site:    
1. Search Volume – The first factor to consider is how many people are actually searching for a given keyword. The more people there are searching for a keyword, the bigger the potential audience you stand to reach. Conversely, if no one is searching for a keyword, there is no audience available to find your content through search.    
2. Relevance – A term may be frequently searched for, but that does not necessarily mean that it is relevant to your prospects. Keyword relevance, or the connection between content on a site and the user's search query, is a crucial ranking signal.    
3. Competition – Keywords with higher search volume can drive significant amounts of traffic, but competition for premium positioning in the search engine results pages can be intense.     
Unfortunately, Google has stopped delivering a lot of the information about what people are searching for to analytics providers. Google does make some of this data available in their free Webmaster Tools interface (if you haven’t set up an account, this is a very valuable SEO tool both for unearthing search query data and for diagnosing various technical SEO issues).      
Once you’ve taken the time to understand your prospects, have looked at the keywords driving traffic to your competitors and related sites, and have looked at the terms driving traffic to your own site, you need to work to understand which terms you can conceivably rank for and where the best opportunities actually lie.     
## On-Page Optimization for SEO    
Once you have your keyword list, the next step is actually implementing your targeted keywords into your site’s content. Each page on your site should be targeting a core term, as well as a “basket” of related terms. In his overview of the perfectly optimized page, Rand Fishkin offers a nice visual of what a well (or perfectly).      
## Title Tags    
While Google is working to better understand the actual meaning of a page and de-emphasizing (and even punishing) aggressive and manipulative use of keywords, including the term (and related terms) that you want to rank for in your pages is still valuable. And the single most impactful place you can put your keyword is your page’s title tag.    
## Alt Attributes    
How you mark up your images can impact not only the way that search engines perceive your page, but also how much search traffic from image search your site generates. An alt attribute is an HTML element that allows you to provide alternative information for an image if a user can’t view it. Your images may break over time (files get deleted, users have difficulty connecting to your site, etc.) so having a useful description of the image can be helpful from an overall usability perspective. This also gives you another opportunity – outside of your content – to help search engines understand what your page is about.     
You don’t want to “keyword stuff” and cram your core keyword and every possible variation of it into your alt attribute. In fact, if it doesn’t fit naturally into the description, don’t include your target keyword here at all. Just be sure not to skip the alt attribute, and try to give a thorough, accurate description of the image (imagine you’re describing it to someone who can’t see it – that’s what it’s there for!).     