**RESPONSIVE WEB DESIGN and FLOATS** 

* Responsive web design is the practice of building a website suitable to work on every device and every screen size.

* **Responsive vs. Adaptive vs. Mobile**

*  Responsive: means to react quickly and positively to any change. change based on different factors, such as viewport width.

*  adaptive : to be easily modified for a new purpose or situation, such as change.built to a group of preset factors.

* Mobile : to build a separate website commonly on a new domain solely for mobile users.

**Three main components for Responsive web design :**

1. Flexible layouts: the practice of building the layout of a website with a flexible grid, capable of dynamically resizing to any width.
2. Media queries:  built using relative length units, most commonly percentages or em units.
3. Flexible media: not advocate the use of fixed measurement units, such as pixels or inches.

* Flexible Grid : take all of the fixed units of length and turn them into relative units.
**different ways to use media queries**

- @media rule inside of an existing style sheet.
- @import rule importing a new style sheet.

* **The orientation media feature** determines if a device is in the landscape or portrait orientation.

* **The aspect-ratio and device-aspect-ratio features** specifies the width/height pixel ratio of the targeted rendering area or output device.

* **The resolution media feature** specifies the resolution of the output device in pixel density, also known as dots per inch or **DPI**.

* **The mobile first approach** includes using styles targeted at smaller viewports as the default styles for a website, then use media queries to add styles as the viewport grows.

* User on a mobile device, commonly using a smaller viewport, shouldn’t have to load the styles for a desktop computer.

**Viewport**

* Using the viewport meta tag with either the height or width values will define the height or width of the viewport respectively. 

* **minimum-scale, maximum-scale, initial-scale, and user-scalable properties.** To control how a website is scaled on a mobile device, and how users can continue to scale a website.

* **Viewport Resolution** Letting the browser decide how to scale a website based off any viewport scale values

* The viewport meta tag will accept individual values as well as multiple values, allowing multiple viewport properties to be set at once.

**Float**

* Float is a CSS positioning property.
* Floats can be used to create entire web layouts.
* clear property: An element that has the clear property set on it will not move up adjacent to the float like the float desires, but will move itself down past the float.
