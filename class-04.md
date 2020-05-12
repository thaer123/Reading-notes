# Chapter 4: Ch.4 “Links” (pp.74-93)
**Linking to Other Sites**
<p>Movie Reviews:
<ul>
<li><a href="http://www.empireonline.com">
Empire</a></li>
<li><a href="http://www.metacritic.com">
Metacritic</a></li>
<li><a href="http://www.rottentomatoes.com">
Rotten Tomatoes</a></li>
<li><a href="http://www.variety.com">
Variety</a></li>
</ul>
</p>
**Email Links**
<a href="mailto:jon@example.org">Email Jon</a>
**target
If you want a link to open in anew window, you can use thetarget attribute on the opening
<a> tag. The value of this attribute should be _blank.
<a href="http://www.imdb.com" target="_blank">
Internet Movie Database</a> (opens in new window)

# Chapter 15: “Layout” (pp.358-404)
**A Fixed Width Layout**
<div> elements are often used as containing elements to group together sections of a page.
- Browsers display pages in normal flow unless you specify relative, absolute, or fixed positioning.
- The float property moves content to the left or right of the page and can be used to create multi-column
layouts. (Floated items require a defined width.)
- Pages can be fixed width or liquid (stretchy) layouts.
- Designers keep pages within 960-1000 pixels wide, and indicate what the site is about within the top 600
pixels (to demonstrate its relevance without scrolling).
- Grids help create professional and flexible designs.
- CSS Frameworks provide rules for common tasks.
- You can include multiple CSS files in one page.
**html example**
<body>
<div id="header">
<h1>Logo</h1>
<div id="nav">
<ul>
<li><a href="">Home</a></li>
<li><a href="">Products</a></li>
<li><a href="">Services</a></li>
<li><a href="">About</a></li>
<li><a href="">Contact</a></li>
</ul>
</div>
</div>
<div id="content">
<div id="feature">
<p>Feature</p>
</div>
<div class="article column1">
<p>Column One</p>
</div>
<div class="article column2">
<p>Column Two</p>
</div>
<div class="article column3">
<p>Column Three</p>
</div>
</div>
<div id="footer">
<p>&copy; Copyright 2011</p>
</div>
</body>
**css example:**
body {
width: 960px;
margin: 0 auto;}
#content {
overflow: auto;
height: 100%;}
#nav, #feature, #footer {
background-color: #efefef;
padding: 10px;
margin: 10px;}
.column1, .column2, .column3 {
background-color: #efefef;
width: 300px;
float: left;
margin: 10px;}
li {
display: inline;
padding: 5px;}

## Chapter 3 (first part): “Functions, Methods, and Objects” (pp.86-99 ONLY)
**WHAT IS A FUNCTION?**
Functions let you group a series of statements together to perform a
specific task. If different parts of a script repeat the same task, you can
reuse the function (rather than repeating the same set of st atements).
**example from lab 03**
function questionSeven() {
    var userFavFruit = ['apple', 'strawberry', 'orange', 'grape', 'watermelon'];

    for (var i = 0; i < 6; i++) {
        var userAnsw = prompt('Can you guess my favorite fruit?');
        var guess = userAnsw.toLowerCase();

        for (var j = 0; j < userFavFruit.length; j++){
            if (guess === userFavFruit[j]) {
                alert('Congrats you got it right!!!');
                score++;
                i = 6;
                break;
            }
        }
        if (i !==6){
            alert('Sorry wrong answer, try again');
        }
    }
}

questionSeven();

**WHAT IS AN OBJECT?**
Objects group together a set of variables and functions to create a model
of a something you would recognize from the real world. In an object,
variables and functions take on new names.
**example:**
var hotel = {
name: 'Quay',
rooms : 40,
booked: 25,
checkAvailability: function() {
return this.rooms - this.booked;
}
} ;

# 6 Reasons for Pair Programming
1. Greater efficiency
2. Engaged collaboration
3. Learning from fellow students
4. Social skills
5. Job interview readiness
6. Work environment readiness



