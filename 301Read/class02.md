**jQuery, Events, and The DOM**

**jQuery**

* It's JS files that you include in your website.
Offers a simple way to achieve a variety of common
JavaScript tasks quickly and consistently, across all major browsers and without any fallback code needed.

* It makes coding simpler.("Write less, do more")

1. Select elements :using CSS selectors
2. Perform tasks
3. Handle events

**Matched set / JQuery selection** 

* When select one or more elements, a jquery object is returned.

* Some JQuery methods both retrive information from ,and update the content of elements.

* JQuery objects store references to elements :

- when create a selection with JQuery, it stores a reference to the corresponding nodes in the DOM tree.

- it does not create a copy of them.

* **CHAINING**
hide(): hides the elements
delay (): creates a pause
fade In (): fades in the elements

* **ready()** : method to check the page is ready for code to work with.

* **Getting element content**

- **html() and .text()** methods both retrieve and update the content of elements.

* **replaceWith() and .remove ()**methods replace and
remove the elements.

* Inserting new elements involves two steps:

1. Create the new elements in a jQuery object
2. Use a method to insert the content into the page.

* Methods to add the content to the DOM tree:

1. **.before()**: inserts content before the selected element.
2. **.after()** : inserts content after the selected element.
3. **.prepend()**: inserts content inside the selected element, after the opening tag.
4. **.append()**: inserts content inside the selected element, before the closing tag.

* **GETTING AND SETTING ATTRIBUTE VALUES**

1. **.attr()**: can get or set a specified attribute and its value.
2. **.removeAttr()**: removes a specified attribute (and its value).
3. **.addClass()**: adds a new value to the existing value of the class attribute.It does not overwrite
existing values.
4. **.removeClass()**: removes a value from the class attribute, leaving any other class names within that attribute intact.

* **.css() method** lets you retrieve
and set the values of CSS properties.

* **.each()**: Allows you to perform one or
more statements on each of the items in the selection of elements that is returned by a
selector.

* **.on() method** is used to handle all events.

- Use a selector to create a jQuery selection.
- Use to indicate which event you want to respond to.

**Pair programming**

* pair programming commonly involves two roles:

- the Driver : the programmer who is typing and the only one whose hands are on the keyboard.

- The Navigator : uses their words to guide the Driver but does not provide any direct input to the computer.

* **Pair programming touches on all four skills:**

1. Developers explain out loud what the code should do.
2. Listen to others’ guidance.
3. Read code that others have written.
4. Write code themselves.

* Language-specific skills:

1. Greater efficiency
2. Engaged collaboration
3. Learning from fellow students
4. Social skills
5. Job interview readiness
6. Work environment readiness
