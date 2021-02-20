Article
img.large {
width: 500px;
height: 500px;}
img.medium {
width: 250px;
height: 250px;}
img.small {
width: 100px;
height: 100px;}
CSS
<img src="images/magnolia-large.jpg"
class="large" alt="Magnolia" />
<img src="images/magnolia-medium.jpg"
class="medium" alt="Magnolia" />
<img src="images/magnolia-small.jpg"
class="small" alt="Magnolia" />
chapter-16/image-sizes.html HTML
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
For example, an e-commerce site
tends to show product photos
at the same size. Or, if your site
is designed on a grid, then you
might have a selection of image
sizes that are commonly used on
all pages, such as:
Small portrait: 220 x 360
Small landscape: 330 x 210
Feature photo: 620 x 400
Whenever you use consistently
sized images across a site,
you can use CSS to control
the dimensions of the
images, instead of putting the
dimensions in the HTML.

Repeating Images   background-repeat   background-attachment

for summry abuot img You can specify the dimensions o XX f images using CSS.
This is very helpful when you use the same sized
images on several pages of your site.
XX Images can be aligned both horizontally and vertically
using CSS.
XX You can use a background image behind the box
created by any element on a page.
XX Background images can appear just once or be
repeated across the background of the box.
XX You can create image rollover effects by moving the
background position of an image.
XX To reduce the number of images your browser has to
load, you can create image sprites.

HTML Practical Information

HTML for Absolute Beginners
While many guides on the internet attempt to teach HTML using a lot of mind-boggling theory, this tutorial will instead focus on giving you the practical skills to build your first site.

The aim is to show you ‘how’ to create your first web page without spending the entire tutorial focusing too much on the “why.”

By the end of this tutorial, you will have the know-how to create a basic website and we ho


html  Practical Information


The second <script> element
is used to tell the browser about
the Flash movie, as well as which
element it should replace. This
element is actually telling the
SWFObject script five pieces
of information, which are in the
brackets:
1. The location of the .swf file:
flash/bird.swf
2. The element that the Flash
movie should replace, specified
by the value of the id attribute
on the <div> element:
bird
3. The width of the Flash movie:
400 px
4. The height of the Flash movie:
300 px
5. The minimum version of the
Flash player needed to view the
movie:
Flash Player 8