# Chapter 5: “Images” (pp.94-125)
-The <img> element is used to add images to a web page.
-You must always specify a src attribute to indicate the
source of an image and an alt attribute to describe the content of an image.
-You should save images at the size you will be using them on the web page and in the appropriate format.
-Photographs are best saved as JPEGs; illustrations or logos that use flat colors are better saved as GIFs.

**Adding Images**
<img src="images/quokka.jpg" alt="A family of
quokka" title="The quokka is an Australian
marsupial that is similar in size to the
domestic cat." />

**Figure and Figure Caption**
<figure>
<img src="images/otters.jpg" alt="Photograph of
two sea otters floating in water">
<br />
<figcaption>Sea otters hold hands when they
sleep so they don't drift away from each
other.</figcaption>
</figure>

**Aligning Images Vertically**
<img src="images/bird.gif" alt="Bird" width="100" height="100" align="top" />

**Aligning Images Horizontally**
<img src="images/bird.gif" alt="Bird" width="100" height="100" align="left" />

# Chapter 11: “Color” (pp.246-263)

-Color not only brings your s XX ite to life, but also helps convey the mood and evokes reactions.
- There are three ways to specify colors in CSS:
RGB values, hex codes, and color names.
- Color pickers can help you find the color you want.
- It is important to ensure that there is enough contrast between any text and the background color (otherwise
people will not be able to read your content).
- CSS3 has introduced an extra value for RGB colors to indicate opacity. It is known as RGBA.
- CSS3 also allows you to specify colors as HSL values,with an optional opacity value. It is known as HSLA.

**example**
<!DOCTYPE html>
<html>
<head>
<title>Color</title>
<style type="text/css">
body {
background-color: silver;
color: white;
padding: 20px;
font-family: Arial, Verdana, sans-serif;}
h1 {
background-color: #ffffff;
background-color: hsla(0,100%,100%,0.5);
color: #64645A;
padding: inherit;}
p {
padding: 5px;
margin: 0px;}
p.zero {
background-color: rgb(238,62,128);}
p.one {
background-color: rgb(244,90,139);}
p.two {
background-color: rgb(243,106,152);}
p.three {
background-color: rgb(244,123,166);}
p.four {
background-color: rgb(245,140,178);}
p.five {
background-color: rgb(246,159,192);}
p.six {
background-color: rgb(245,176,204);}
p.seven {
background-color: rgb(0,187,136);}
p.eight {
background-color: rgb(140,202,242);}
p.nine {
background-color: rgb(114,193,240);}
COLOR 260
Example
COLOR
p.ten {
background-color: rgb(84,182,237);}
p.eleven {
background-color: rgb(48,170,233);}
p.twelve {
background-color: rgb(0,160,230);}
p.thirteen {
background-color: rgb(0,149,226);}
p.fourteen {
background-color: rgb(0,136,221);}
</style>
</head>
<body>
<h1>pH Scale</h1>
<p class="fourteen">14.0 VERY ALKALINE</p>
<p class="thirteen">13.0</p>
<p class="twelve">12.0</p>
<p class="eleven">11.0</p>
<p class="ten">10.0</p>
<p class="nine">9.0</p>
<p class="eight">8.0</p>
<p class="seven">7.0 NEUTRAL</p>
<p class="six">6.0</p>
<p class="five">5.0</p>
<p class="four">4.0</p>
<p class="three">3.0</p>
<p class="two">2.0</p>
<p class="one">1.0</p>
<p class="zero">0.0 VERY ACID</p>
</body>
</html>

# Chapter 12: “Text” (pp.264-299)

**Specifying Typefaces font-family**
body {
font-family: Georgia, Times, serif;}
h1, h2 {font-family: Arial, Verdana, sans-serif;}
.credits {font-family: "Courier New", Courier,monospace;}

**Size of Type font-size**
body {font-family: Arial, Verdana, sans-serif;font-size: 12px;}
h1 {font-size: 200%;}
h2 {font-size: 1.3em;}

**UpperCase & LowerCase**
h1 {text-transform: uppercase;}
h2 {text-transform: lowercase;}
.credits {text-transform: capitalize;}

**text-decoration**
.credits {text-decoration: underline;}
a {text-decoration: none;}

**text-align**
h1 {text-align: left;}
p {text-align: justify;}
.credits {text-align: right;}

**text-indent**
h1 {
background-image: url("images/logo.gif");background-repeat: no-repeat;text-indent: -9999px;}
.credits {text-indent: 20px;}

**:link, :visited**
a:link {color: deeppink;text-decoration: none;}
a:visited {color: black;}
a:hover {color: deeppink;text-decoration: underline;}
a:active {color: darkcyan;}
