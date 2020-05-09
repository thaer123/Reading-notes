# Duckett HTML book :

# Introduction (pp.2-11):
### **1: HTML**

*We will spend the first chapter looking at how HTML is used to create web pages. You will see that you start by writing down the words you want to appear on your page. You then add tags or elements to the words so that the browser knows what is a heading, where a paragraph begins and ends, and so on.

The rest of this section introduces the tags you have at your disposal to create web pages, grouped into chapters on: text, lists, links, images, tables, forms, video audio and flash, and miscellaneous elements.

I should warn you that the examples in the first nine chapters are not exciting to look at, yet they are the foundation of every web page. The following chapters on CSS will show you how to make your pages look a lot more interesting.*

### **2: CSS**

We start this section with a chapter that explains how CSS uses rules to enable you to control the styling and layout of web pages. We then go on to look at the wide variety of CSS properties you can use in your CSS rules. These properties generally fall into one of two categories:

Presentation: How to control things like the color of text, the fonts you want to use and the size of those fonts, how to add background colors to pages (or parts of a page), and how to add background images.

Layout: How to control where the different elements are positioned on the screen. You will also learn several techniques that professionals use to make their pages more attractive.


# How Websites Are Created

*Small websites are often written just using HTML and CSS.

*Larger websites — in particular those that are updated regularly and use a content management system (CMS), blogging tools, or e-commerce software — often make use of more complex technologies on the web server, but these technologies are actually used to produce HTML and CSS that is then sent to the browser. So, if your site uses these technologies, you will be able to use your new HTML and CSS knowledge to take more control over how your site looks.

*Larger, more complex sites like these may use a database to store data, and programming languages such as PHP, ASP.Net, Java, or Ruby on the web server, but you do not need to know these technologies to improve what the user sees. The skills you'll learn in this book should be enough to help you on that road.

**HTML5 & CSS3

Since the web was first created there have been several versions of HTML and CSS — each intended to be an improvement on the previous version.

At the time of writing this book, HTML5 & CSS3 were still being developed. Although they had not been finalized, many browsers were already supporting some features of these languages and a lot of people were using the latest code on their websites. I have therefore chosen to teach you these latest versions.

Because HTML5 and CSS3 build on previous versions of these languages, learning these means you will also be able to understand the earlier versions of them. I have added clear notes when the code is new and also when it might not work in older browsers.


## How the Web Works

1.When you connect to the web,you do so via an Internet ServiceProvider (ISP). You type adomain name or web addressinto your browser to visit a site;for example: google.com,bbc.co.uk, microsoft.com.

2.Your computer contacts anetwork of servers called Domain Name System (DNS) servers. These act like phonebooks; they tell your computer the IP address associated with the requested domain name.An Ipaddress is a number of up to 12 digits separated by periods / full stops. Everydevice connected to the webhas a unique IP address; it islike the phone number for thatcomputer.

3.The unique number that the DNS server returns to your computer allows your browser to contact the web server that hosts the website you requested. A web server is a computer that is constantly connected to the web, and is set up especially to send web pages to users.



## HTML Chapter 1: “Structure” (pp.12-39)

**How Pages Use Structure**
Think about the stories you read in a newspaper: for each story, there will be a headline, some text, and possibly some images. If the article is a long piece, there may be subheadings that split the story into separate sections or quotes from those involved. Structure helps readers understand the stories in the newspaper.

 
The structure is very similar when a news story is viewed online (although it may also feature audio or video). This is illustrated on the right with a copy of a newspaper alongside the corresponding article on its website.
 

Now think about a very different type of document — an insurance form. Insurance forms often have headings for different sections, and each section contains a list of questions with areas for you to fill in details or checkboxes to tick. Again, the structure is very similar online.

**HTML Describes the Structure of Pages**

In the browser window you can see a web page that features exactly the same content as the Word document you met on the page 18. To describe the structure of a web page, we add code to the words we want to appear on the page.

You can see the HTML code for this page below. Don't worry about what the code means yet. We start to look at it in more detail on the next page. Note that the HTML code is in blue, and the text you see on screen is in black.



<html>

<body>

<h1>This is the Main Heading</h1>

<p>This text might be an introduction to the rest of the page. And if the page is a long one it might be split up into several sub-headings.<p>

<h2>This is a Sub-Heading</h2>

<p>Many long articles have sub-headings so to help you follow the structure of what is being written. There may even be sub-sub-headings (or lower-level headings).</p>

<h2>Another Sub-Heading</h2>

<p>Here you can see another sub-heading.</p>

</body>

</html>



The HTML code (in blue) is made up of characters that live inside angled brackets — these are called HTML elements. Elements are usually made up of two tags: an opening tag and a closing tag. (The closing tag has an extra forward slash in it.) Each HTML element tells the browser something about the information that sits between its opening and closing tags.


## HTML Chapter 8: “Extra Markup” (p.176-199)

**Extra Markup
DOCTYPEs**

Because there have been several versions of HTML, each web page should begin with a DOCTYPE declaration to tell a browser which version of HTML the page is using (although browsers usually display the page even if it is not included). We will therefore be including one in each example for the rest of the book.

As you will see when we come to look at CSS and its box model on page 316, the use of a DOCTYPE can also help the browser to render a page correctly.

Because XHTML was written in XML, you will sometimes see pages that use the XHTML strict DOCTYPE start with the optional XML declaration. Where this is used, it should be the first thing in a document. There must be nothing before it, not even a space.

HTML5
<!DOCTYPE html>

HTML 4
<!DOCTYPE html PUBLIC
"-//W3C//DTD HTML 4.01 Transitional//EN"
"http://www.w3.org/TR/html4/loose.dtd">

Transitional XHTML 1.0
<!DOCTYPE html PUBLIC
"-//W3C//DTD XHTML 1.0 Transitional//EN"
"http://www.w3.org/TR/xhtml1/DTD/
xhtml1-transitional.dtd">

Strict XHTML 1.0
<!DOCTYPE html PUBLIC
"-//W3C//DTD XHTML 1.0 Strict//EN"
"http://www.w3.org/TR/xhtml1/DTD/
xhtml1-strict.dtd">

XML Declaration
<?xml version="1.0" ?>

**comments ArticleinHTML
exampl:**

	<!-- start	of introduction -->
	<h1>Current Exhibitions</h1>
	<h2>Olafur	Eliasson</h2>
	<!-- end of introduction -->
	<!-- start	of main text -->
	<p>Olafur Eliasson was born in Copenhagen, Denmark
	in 1967	to Icelandic parents.</p>
	<p>He is known for sculptures and large-scale
	installation art employing elemental materials
	such as	light, water, and air temperature to
	enhance	the viewer's experience.</p>

<!-- end of main text -->

<!--

<a href="mailto:info@example.org">Contact</a> -->
 
 
**ID Attribute
example:**

<p>Water and air. So very commonplace are these substances, they hardly attract attention - and yet they vouchsafe our very existence.</p>

<p	id="pullquote">Every time I view the sea I feel a calming sense of security, as if visiting my ancestral home; I embark on a voyage of seeing.
</p>

<p>Mystery of mysteries, water and air are right there before us in the sea.</p>

**Block Elements
example:**

<h1>Hiroshi Sugimoto</h1>

<p>The dates for the ORIGIN OF ART exhibition are as follows:</p>

<ul>

<li>Science: 21 Nov - 20 Feb 2010/11</li>

<li>Architecture: 6 Mar - 15 May 2011</li>

<li>History: 29 May - 21 Aug 2011</li>

<li>Religion: 28 Aug - 6 Nov 2011</li>

</ul>

**nline ElementsArticle
example:**

Timed to a single revolution of the planet around the sun at a 23.4 degrees tilt that plays out the rhythm of the seasons, this <em>Origins of Art</em> cycle is organized around four themes: <b>science, architecture, history</b> and <b>religion</b>.

**IFrames
example:

<iframe

width="450"

height="350"

src="http://maps.google.co.uk/maps?q=moma+new+york&amp;
output=embed">

</iframe>

#### Escape Characters
<

>

&

"
 









Less-than sign

&lt;

&#60;


Greater-than sign

&gt;

&amp;


Ampersand

&amp;

&#38;


Quotation mark

&quot;

&#34;
 









¢

£

¥

¤

©

®


™
 









Cent sign


&cent;

&#162;


Pound sign

&pound;

&#163;


Yen sign

&yen;

&#165;


Euro sign

&euro;

&#8364;


Copyright symbol

&copy;

&#169;


Registered trademark

&reg;

&#174;


Trademark

&trade;

&#8482;
 

‘

'

“

”

×

÷
 
Left single quote

&lsquo;

&#8216;


Right single quote

&rsquo;

&#8217;


Left double quotes

&ldquo;

&#8220;


Right double quotes

&rdquo;

&#8221;


Multiplication sign

&times;

&#215;


Division sign

&divide;

&#247;
 


## Example EXTRA MARKUP

<!DOCTYPE html PUBLIC

"-//W3C//DTD HTML 4.01 Transitional//EN"

"http://www.w3.org/TR/html4/loose.dtd">

<html>

<head>

<meta name="description" content="Telephone, email and directions for The Art Bookshop, London, UK" />
<title>Contact The Art Bookshop, London UK</title>

</head>

<body>

<div id="header">

<h1>The Art Book Shop</h1>

<ul>

<li><a href="index.html">home</a></li> <li><a href="index.html">new publications</a>
</li>

<li class="current-page">

<a href="index.html">contact</a></li>

</ul>

</div><!-- end header -->

<div id="content">

<p>Charing Cross Road, London, WC2, UK</p> <p><span class="contact">Telephone</span>
0207 946 0946</p>

<p><span class="contact">Email</span> <a href="mailto:books@example.com"> books@example.com</a></p>
<iframe width="425" height="275" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="http://maps.google.co.uk/maps?f=q&amp; source=s_q&amp;hl=en&amp;geocode=&amp; q=charing+cross+road+london&amp;output=embed"> </iframe>

</div><!-- end content -->

<p>&copy; The Art Bookshop</p>

</body>

</html>


## HTML Chapter 17: “HTML5 Layout” (pp.428-451):

HTML5 is introducing a new set of
elements that help define the structure of
a page.

For a long time, web page authors used <div> elements to group
together related elements on the page (such as the elements that form a
header, an article, footer or sidebar). Authors used class or id attributes
to indicate the role of the <div> element in the structure of the page.
  
**example:**

<body>
<div id="page">
<div id="header">
<div id="content">
<div id="footer">
<div id=
"sidebar">
<div id="nav">
<div class="article">
<div class="article">
  
 #### Headers & Footers
<header> <footer>
  
  **example:**
  
  <header>
<h1>Yoko's Kitchen</h1>
<nav>
<ul>
<li><a href="" class="current">home</a></li>
<li><a href="">classes</a></li>
<li><a href="">catering</a></li>
<li><a href="">about</a></li>
<li><a href="">contact</a></li>
</ul>
</nav>
</header>
<footer>
&copy; 2011 Yoko's Kitchen
</footer>

#### Navigation
<nav>
  
  **example:**

<nav>
<ul>
<li><a href="" class="current">home</a></li>
<li><a href="">classes</a></li>
<li><a href="">catering</a></li>
<li><a href="">about</a></li>
<li><a href="">contact</a></li>
</ul>
</nav>

#### Articles
<article>
  
  **example:**
  
  <article>
<figure>
<img src="images/bok-choi.jpg" alt="Bok Choi" />
<figcaption>Bok Choi</figcaption>
</figure>
<hgroup>
<h2>Japanese Vegetarian</h2>
<h3>Five week course in London</h3>
</hgroup>
<p>A five week introduction to traditional
Japanese vegetarian meals, teaching you a
selection of rice and noodle dishes.</p>
</article>
<article>
<figure>
<img src="images/teriyaki.jpg"
alt="Teriyaki sauce" />
<figcaption>Teriyaki Sauce</figcaption>
</figure>
<hgroup>
<h2>Sauces Masterclass</h2>
<h3>One day workshop</h3>
</hgroup>
<p>An intensive one-day course looking at how to
create the most delicious sauces for use in a
range of Japanese cookery.</p>
</article>

#### Figures
<figure> <figcaption>
  Examples of usage include:
●● Images
●● Videos
●● Graphs
●● Diagrams
●● Code samples
●● Text that supports the main
body of an article
  
  **example:**
  
  <figure>
<img src="images/bok-choi.jpg" alt="Bok Choi" />
<figcaption>Bok Choi</figcaption>
</figure>


##  Example HTML5 LAYOUT

<!DOCTYPE html>
<html>
<head>
<title>HTML5 Layout</title>
<style type="text/css">
header, section, footer, aside, nav, article, figure, figcaption {
display: block;}
body {
color: #666666;
background-color: #f9f8f6;
background-image: url("images/dark-wood.jpg");
background-position: center;
font-family: Georgia, times, serif;
line-height: 1.4em;
margin: 0px;}
.wrapper {
width: 940px;
margin: 20px auto 20px auto;
border: 2px solid #000000;
background-color: #ffffff;}
header {
height: 160px;
background-image: url(images/header.jpg);}
h1 {
text-indent: -9999px;
width: 940px;
height: 130px;
margin: 0px;}
nav, footer {
clear: both;
color: #ffffff;
background-color: #aeaca8;
height: 30px;}
nav ul {
margin: 0px;
padding: 5px 0px 5px 30px;}
nav li {
display: inline;
margin-right: 40px;}
nav li a {
HTML5 LAYOUT 446
Example
HTML5 LAYOU T
color: #ffffff;}
nav li a:hover, nav li a.current {
color: #000000;}
section.courses {
float: left;
width: 659px;
border-right: 1px solid #eeeeee;}
article {
clear: both;
overflow: auto;
width: 100%;}
hgroup {
margin-top:40px;}
figure {
float: left;
width: 290px;
height: 220px;
padding: 5px;
margin: 20px;
border: 1px solid #eeeeee;}
figcaption {
font-size: 90%;
text-align: left;}
aside {
width: 230px;
float: left;
padding: 0px 0px 0px 20px;}
aside section a {
display: block;
padding: 10px;
border-bottom: 1px solid #eeeeee;}
aside section a:hover {
color: #985d6a;
background-color: #efefef;}
a {
color: #de6581;
text-decoration: none;}
h1, h2, h3 {
font-weight: normal;}
h2 {
447 HTML5 LAYOUT
Example
HTML5 LAYOU T
margin: 10px 0px 5px 0px;
padding: 0px;}
h3 {
margin: 0px 0px 10px 0px;
color: #de6581;}
aside h2 {
padding: 30px 0px 10px 0px;
color: #de6581;}
footer {
font-size: 80%;
padding: 7px 0px 0px 20px;}
</style>
<!--[if lt IE 9]>
<script src="http://html5shiv.googlecode.com/svn/trunk/html5.js"></script>
<![endif]-->
</head>
<body>
<div class="wrapper">
<header>
<h1>Yoko's Kitchen</h1>
<nav>
<ul>
<li><a href="" class="current">home</a></li>
<li><a href="">classes</a></li>
<li><a href="">catering</a></li>
<li><a href="">about</a></li>
<li><a href="">contact</a></li>
</ul>
</nav>
</header>
<section class="courses">
<article>
<figure>
<img src="images/bok-choi.jpg" alt="Bok Choi" />
<figcaption>Bok Choi</figcaption>
</figure>
<hgroup>
<h2>Japanese Vegetarian</h2>
<h3>Five week course in London</h3>
</hgroup>
HTML5 LAYOUT 448
Example
HTML5 LAYOU T
<p>A five week introduction to traditional Japanese vegetarian meals,
teaching you a selection of rice and noodle dishes.</p>
</article>
<article>
<figure>
<img src="images/teriyaki.jpg" alt="Teriyaki sauce" />
<figcaption>Teriyaki Sauce</figcaption>
</figure>
<hgroup>
<h2>Sauces Masterclass</h2>
<h3>One day workshop</h3>
</hgroup>
<p>An intensive one-day course looking at how to create the most delicious
sauces for use in a range of Japanese cookery.</p>
</article>
</section>
<aside>
<section class="popular-recipes">
<h2>Popular Recipes</h2>
<a href="">Yakitori (grilled chicken)</a>
<a href="">Tsukune (minced chicken patties)</a>
<a href="">Okonomiyaki (savory pancakes)</a>
<a href="">Mizutaki (chicken stew)</a>
</section>
<section class="contact-details">
<h2>Contact</h2>
<p>Yoko's Kitchen<br />
27 Redchurch Street<br />
Shoreditch<br />
London E2 7DP</p>
</section>
</aside>
<footer>
&copy; 2011 Yoko's Kitchen
</footer>
</div><!-- .wrapper -->
</body>
</html>
  
 # HTML Chapter 18: “Process & Design” (pp.452-475)
  
  **This section discusses a process that
you can use when you are creating a new
website.**


**Why People Visit YOUR Website**

***Key Motivations***
●● Are they looking for general
entertainment or do they
need to achieve a specific
goal?
●● If there is a specific goal, is
it a personal or professional
one?
●● Do they see spending time on
this activity as essential or a
luxury?

***Specific Goals***
●● Do they want general
information / research (such
as background on a topic /
company), or are they after
something specific (such as a
particular fact or information
on a product)?
●● Are they already familiar with
the service or product that
you offer or do they need to
be introduced to it?
●● Are they looking for time
sensitive information, such as
the latest news or updates on
a particular topic?
●● Do they want to discover
information about a specific
product or service to help
them decide whether to buy
it or not?
●● Do they need to contact you?
If so, can they visit in person
(which might require opening
hours and a map)? Or might
they need email or telephone
contact details?


  #### Summary
**PROCESS & Design**
It's important to understand w XX ho your target audience
is, why they would come to your site, what information
they want to find and when they are likely to return.
XX Site maps allow you to plan the structure of a site.
XX Wireframes allow you to organize the information that
will need to go on each page.
XX Design is about communication. Visual hierarchy helps
visitors understand what you are trying to tell them.
XX You can differentiate between pieces of information
using size, color, and style.
XX You can use grouping and similarity to help simplify
the information you present.


## Duckett JS book


**A script is a series of instructions that the computer
can follow in order to achieve a goal.
Each time the script runs, it might only use a subset of
all the instructions.
Computers approach tasks in a different way than
humans, so your instructions must let the computer
solve the task prggrammatically.
To approach writing a script, break down your goal into
a series of tasks and then work out each step needed
to complete that task (a flowchart can help).**

## JS Chapter 1: “The ABC of Programming” (pp.11-52)

HOW HTML, CSS,
& JAVASCRIPT FIT
TOGETHER
Before diving into the JavaScript language, you
need to know how it will fit together with the
HTML and CSS in your web pages.
Web developers usually talk
about three languages that
are used to create web pages:
HTML, CSS, and JavaScript.
<html>
CONTENT LAYER
. html files
This is where the content of
the page lives. The HTML gives
the page structure and adds
semantics.
Where possible, aim to keep the
three languages in separate files,
with the HTML page linking to
CSS and JavaScript files.
{css}
PRESENTATION LAYER
.css files
The CSS enhances the HTML
page with rules that state how
the HTML content is presented
(backgrounds, borders, box
dimensions, colors, fonts, etc.).
Programmers often refer to this as a separation of concerns.
8 THE ABC OF PROGRAMMING
Each language forms a separate
layer with a different purpose.
Each layer, from left to right.
builds on the previous one.
j avascri pt()
BEHAVIOR LAYER
.js files
This is where we can change
how the page behaves, adding
interact ivity. We will aim to keep
as much of our JavaScript as
possible in separate files.
  
  **example1:**
  
  var today= new Date();
var hourNow = today.getHours();
var greeting;
if (hourNow > 18) {
greeting= 'Good evening!';
else if (hourNow > 12) {
greeting = ' Good afternoon!';
else if (hourNow > 0) {
greeting = 'Good morni ng!';
else {
greeting = 'Welcome! ' ;
document .write( ' <h3>' +greeting + ' </ h3>');

**example2:**

<!DOCTYPE html>
<html>
<head>
<title>Constructive &amp; Co.</ title>
<link rel ="stylesheet" href="css/ cOl.css" />
</ head>
<body>
<hl>Constructive &amp; Co. </ hl>
<script src="js/ add-content.js"></ script>
<p>For all orders and i nquiries please cal l
<em>SSS-3344</ em></ p>
</ body>
</html>

**example3:**

<!DOCTYPE html>
<html >
<head>
<title>Constructive &amp; Co.</title>
<li nk rel ="stylesheet" href="css/ cOl .css" />
</ head>
<body>
<hl>Constructive &amp; Co.</hl>
<script>document.write(' <h3>Welcome !</h3>');
</script>
<p>For all orders and inquiries please call
<em>555-3344</ em></ p>
</ body>
</ html >


It is best to keep JavaScript code in its own JavaScript
file. JavaScript files are text files (like HTML pages and
CSS style sheets), but they have the . j s extension.
The HTML <script> element is used in HTML pages
to tell the browser to load the JavaScript file (rather like
the <link> element can be used to load a CSS file).
If you view the source code of the page in the browser,
the JavaScript will not have changed the HTML,
because the script works with the model of the web
page that the browser has created.
  



