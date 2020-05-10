# From the Duckett HTML book

### Chapter 2: “Text” (pp.40-61)

**Headings**
<h1>This is a Main Heading</h1>
<h2>This is a Level 2 Heading</h2>
<h3>This is a Level 3 Heading</h3>
<h4>This is a Level 4 Heading</h4>
<h5>This is a Level 5 Heading</h5>
<h6>This is a Level 6 Heading</h6>

**Paragraphs**
<p>Text is easier to understand when it is split up
into units of text. For example, a book may have
chapters. Chapters can have subheadings. Under
each heading there will be one or more
paragraphs.</p>

**Bold & It alic**
<b>key features</b>
<i>Endeavour</i>

**Superscript & Subscript**
<p>On the 4<sup>th</sup> of September you will learn
about E=MC<sup>2</sup>.</p>
<p>The amount of CO<sub>2</sub> in the atmosphere
grew by 2ppm in 2009<sub>1</sub>.</p>

**Line Breaks & Horizontal Rules**
<p>The Earth<br />gets one hundred tons heavier
every day<br />due to falling space dust.</p>

<p>Venus is the only planet that rotates
clockwise.</p>
<hr /> //to make breaks between <p>
  
 ***Strong & Emphasis***
 <p><strong>Beware:</strong> Pickpockets operate in
this area.</p>
<p>This toy has many small pieces and is <strong>not
suitable for children under five years old.
</strong></p>

<p>I <em>think</em> Ivy was the first.</p>
<p>I think <em>Ivy</em> was the first.</p>
<p>I think Ivy was the <em>first</em>.</p>

**Quotations**
<blockquote cite="http://en.wikipedia.org/wiki/
Winnie-the-Pooh">
<p>Did you ever stop to think, and forget to start
again?</p>
</blockquote>
<p>As A.A. Milne said, <q>Some people talk to
animals. Not many listen though. That's the
problem.</q></p>

**Abbreviations & Acronyms**
<p><abbr title="Professor">Prof</abbr> Stephen
Hawking is a theoretical physicist and
cosmologist.</p>
<p><acronym title="National Aeronautics and Space
Administration">NASA</acronym> do some crazy
space stuff.</p>

***<address>***
  
  ### Chapter 10: Ch.10 “Introducing CSS” (pp.226-245)
  
  **Understanding CSS:Thinking Insi de the Box**
  The key to understanding how CSS works is to imagine that there is an invisible box around
every HTML element.

**example:**
<!DOCTYPE html>
<html>
<head>
<title>Introducing CSS</title>
<link href="css/example.css" type="text/css"
rel="stylesheet" />
</head>
<body>
<h1>From Garden to Plate</h1>
<p>A <i>potager</i> is a French term for an
ornamental vegetable or kitchen garden ... </p>
<h2>What to Plant</h2>
<p>Plants are chosen as much for their functionality
as for their color and form ... </p>
</body>
</html>
body {
font-family: Arial, Verdana, sans-serif;}
h1, h2 {
color: #ee3e80;}
p {
color: #665544;}

  
 # From the Duckett JS book:
 ### Chapter 2: “Basic JavaScript Instructions” (pp.53-84)
 
 **STATEMENTS**
 var today= new Date{);
var hourNow = today.getHours{) ;
var greeting;
if (hourNow > 18) {
greeting= 'Good evening';
else if (hourNow > 12) {
greeting= 'Good afternoon';
else if (hourNow > O) {
greeting 'Good morning';
else {
greeting 'Welcome';
document.write(greeting) ;

**WHAT IS A VARIABLE?**
c02/example.html
<!DOCTYPE html>
<html>
<head>
1111., .• ,
<title>JavaScript &amp; jQuery - Chapter 2: Basic JavaScript Instructions -
Example</ title>
<link rel="stylesheet" href="css/c02.css" />
</head>
<body>
<hl>Elderflower</hl>
<div id="content">
<div id="greeting" class="message">Hello! </div>
<table>
<tr>
<td>Custom sign: </ td>
<td id="userSign"></ td>
</ tr>
<tr>
<td>Total tiles: </td>
<td id="ti l es "></td>
</tr>
<tr>
<td>Subtotal: </td>
<td id="subTotal">$</ td>
</ tr>
<tr>
<td>Shipping: </ td>
<td id="shipping">$</td>
</tr>
<tr>
<td>Grand total: </td>
<td id="grandTotal ">S</td>
</tr>
</ table>
<a href="D" class="action">Pay Now</ a>
</div>
<script src="js/ example.js"></ script>
</body>
</html>
