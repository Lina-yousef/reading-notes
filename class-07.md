**HTML Tables; JS Constructor Functions**

**Tables** 

A table represents information in a grid format. eg:e financial reports, TV
schedules, and sports results.

* **Structure of tables :**

- (table) : to create a table.
- (tr) : start of each row .
- (td) :represent data in cell of a table.
- (th) : to represent the heading for a column or a row.

**You can make cells of a table span more than one row or column using the rowspan and colspan attributes.**

**For Long Tables :**

* There are three elements that help distinguish between the  main content of the table and the first and last rows : 

- (thead) :The headings of the table sit inside .
- (tbody) :The body sit inside it.
- (tfoot) :The footer of the table sit inside .

**Functions, Methods, and Object**

**new** keyword : to **create a blanck object**. and you can add properity and method to the object. 

To UPDATE a value use (. or []). 

To DELETE a property usr **delete** keyword.

CREATING OBJECTS:

* using constructor function. eg :var hotel = new Object().

* to get the hotel's name: hotel .name.

* to use the method, you can use the object name followed by the method name. eg: hotel.checkAvailability() 

* **WAYS TO CREATE OBJECTS :**

- CREATE THE OBJECT, THEN ADD PROPERTIES & METHODS.
- CREATING AN OBJECT WITH PROPERTIES & METHODS.

**THIS** : used inside functions and objects. the function is declared alters what this means.

* When a function created at the top level of a script ,( not inside another object or function).

* To access items via a property name or key, use an object.

- INDIVIDUAL OBJECTS :
 var hotel = {
name: 'Quay',
rooms: 40
}
- MULTIPLE OBJECTS  : 
function Hotel (name, rooms)
this .name = name;
this.rooms = rooms;

**Then create instances of the object using the new keyword and then a call to the constructor function.**

var hotell =new Hotel ( 'Quay', 40);
var hotel2 = new Hotel ( ' Park ' , 120);


* **Array of objects or Object in array** 

 we can combined it to create a complex data structure.

 **WHAT ARE BUILT-IN OBJECTS ?**

 Browsers come with a set of built-in objects that represent things. 

 like: the browser window and the current web page shown in that window.

 * Three groups build-in object :

 - THE BROWSER OBJECT MODEL The window object : represents the current browser window or tab.

 - THE DOCUMENT OBJECT MODEL:represents the web page loaded into the current browser window or tab. 

 - GLOBAL OBJECTS: STRING OBJECT / NUMBER OBJECT / MATH OBJECT /DATE OBJECT (AND TIME) .

* **Data type :**

 - SIMPLE OR PRIMITIVE DATA TYPES :

 (1. String 2. Number 3. Boolean 4. Undefined 5. Null).

- COMPLEX DATA TYPE :6.0bject.


[Previous](class-06.md)  | [Home](README.md) | [Next](class-08.md)
