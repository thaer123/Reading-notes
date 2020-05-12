# Chapter 3: “Lists” (pp.62-73)
There are three types of HTML lists:
-ordered,unordered, and definition.
- Ordered lists use numbers.
- Unordered lists use bullets.
- Definition lists are used to define terminology.
- Lists can be nested inside one another.
**Ordered Lists**
<ol>
<li>Chop potatoes into quarters</li>
<li>Simmer in salted water for 15-20
minutes until tender</li>
<li>Heat milk, butter and nutmeg</li>
<li>Drain potatoes and mash</li>
<li>Mix in the milk mixture</li>
</ol>
**unorder lists**&&**nested lists**
<ul>
<li>1kg King Edward potatoes</li>
<li>100ml milk</li>
<li>50g salted butter</li>
<li>Freshly grated nutmeg</li>
<li>Salt and pepper to taste</li>
</ul>
**Definition lists**
<dl>
<dt>Sashimi</dt>
<dd>Sliced raw fish that is served with
condiments such as shredded daikon radish or
ginger root, wasabi and soy sauce</dd>
<dt>Scale</dt>
<dd>A device used to accurately measure the
weight of ingredients</dd>
<dd>A technique by which the scales are removed
from the skin of a fish</dd>
<dt>Scamorze</dt>
<dt>Scamorzo</dt>
<dd>An Italian cheese usually made from whole
cow's milk (although it was traditionally made
from buffalo milk)</dd>
</dl>

# Chapter 13: “Boxes” (pp.300-329)
**box dimentions**
width, height
div.box {
height: 300px;
width: 300px;
background-color: #bbbbaa;}
p {
height: 75%;
width: 75%;
background-color: #0088dd;}

**border-style**
p.one {border-style: solid;}
p.two {border-style: dotted;}
p.three {border-style: dashed;}
p.four {border-style: double;}
p.five {border-style: groove;}
p.six {border-style: ridge;}
p.seven {border-style: inset;}
p.eight {border-style: outset;}
**Shorthand border**
p {
width: 250px;
border: 3px dotted #0088dd;}
**padding**
p {
width: 275px;
border: 2px solid #0088dd;}
p.example {
padding: 10px;}
**centering content**
body {
text-align: center;}
p {
width: 300px;
padding: 50px;
border: 20px solid #0088dd;}
p.example {
margin: 10px auto 10px auto;
text-align: left;}
# Chapter 4: “Decisions and Loops” from switch statements on (pp.162-182)
switch (level) {
case 'One ':
title= 'Level 1 ' ;
break;
case 'Two':
tit1e = 'Level 2 ' ;
break;
case ' Three' :
title = 'Level 3' ;
break ;
default :
title= 'Test';
break;}
**array && for-loop**
var scores= [24. 32, 17]; //Array of scores
var arraylength scores .l ength;// Items in array
var roundNumber = O; //Current round
var msg ''; //Message
var i ; // Counter
//Loop through the items in the array
for (i = O; i < arraylength; i++) {
//Arrays are zero based (so 0 is round 1)
//Add 1 to the current round
roundNumber = (i + l);
// Write the current round to message
msg += 'Round ' + roundNumber + ' : ';
//Get the score from the scores array
msg += scores[i] + '<br / >' ;
document .getElementByid( ' answer') .i nnerHTML msg;

Conditional statements allow your code to make
decisions about what to do next.
Comparison operators (===, ! ==, ==, ! =, <, >, <=, =>)
are used to compare two operands.
Logical operators allow you to combine more than one
set of comparison operators.
if ... else statements allow you to run one set of code
if a condition is true, and another if it is false.
switch statements allow you to compare a value
against possible outcomes (and also provides a default
option if none match).
Data types can be coerced from one type to another.
All values evaluate to either truthy or falsy.
There are three types of loop: for, while, and
do ... while. Each repeats a set of statements.










