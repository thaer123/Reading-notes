# What is the hardest thing about writing code?

**There are many common answers to this question:**

Learning a new technology
Naming things
Testing your code
Debugging
Fixing bugs
Making software maintainable
The list goes on and on.

# WHAT IS AN OBJECT?
**Java object is a combination of data and procedures working on the available data. 
An object has a state and behavior. Objects are created from templates known as classes.**

***how to creat object***
var hotel = {
name: 'Quay',
rooms : 40,
booked: 25,
checkAvailability: function() {
return this.rooms - this.booked;
}
} ;
JAVASCRIPT
var elName = document .getElementByld('hotelName');
elName.textContent =hotel .name;
var elRooms = document.getElementByid{'rooms');
elRooms .textContent = hotel .checkAvailability();

# Chapter 5: “Document Object Model” (pp.183-242)
**dom tree**
Each node is an object with methods and properties.
Scripts access and update this DOM tree (not the source HTML file).
Any changes made to the DOM tree are reflected in the browser.

**select elements**
var elements = document .getElementsByClassName('hot'); II Find hot items
if (e lements .l ength> 2) {
var el = elements[2];
el.className = 'cool';


