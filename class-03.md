**HTML Lists, CSS Boxes, JS Control Flow**

**Lists**

* Three different types:
- Ordered lists (ol):lists where each item in the list is **numbered**.
- Unordered lists (ul) :lists that begin with a **bullet point**.
- Definition lists (dl) :a set of terms along with the **definitions** for each of those terms.

* Each item in the list is placed between  (li   /li) tag .

* Inside (dl) element you will see:
- Definition term(dt) : to contain the term being defined .
- (dd) :This is used to contain the definition.

* Nested Lists : You can put a second list inside an <li> element to create a sublist or nested list.

**Boxes** 

* CSS treats each HTML element as if it has its own box. 

* CSS use to control the dimensions, the borders, margin and padding of a box.

* CSS3 has introduced the ability to create:( image borders and rounded borders).

* Block-level boxes :can be made into **inline boxes**.

**Basic JavaScript Instructions**

**ARRAYS** 

A special type of variable. It doesn't just store one value , it stores a list of values. 
 
Using when working with : **a list** or **a set of related values**.

Example: var colors;

         colors ['white', 'black', ' custom'];

**It is important to know that the numbering of this list starts at zero**

**Decisions and Loops**

**SWITCH Statment** : Start with a variable called **switch value**

**USING SWITCH STATEMENTS**
The purpose of the switch statement is to present the user with a different message depending on which level they are at:

var msg;
var level = 2;
switch (level) {
case 1:
msg = 'Good luck on the first test ' ;
break;
case 2:
msg = 'Second of three - keep going!';
break;
case 3:
msg = ' Final round, al most there!';
break;
default :
msg = 'Good l uck!';
break;}
var el = document.getEl ementByld('answer');
el .textContent = msg; 

**There are three types of loop:**
- for  
- while
- do ... while

**Each repeats a set of statements**



[Previous](class-02.md)  | [Home](README.md) | [Next](class-04.md)
