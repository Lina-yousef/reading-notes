**CSS Transforms, Transitions, and Animations**

* **Transforms**

* To position and alter elements

* **The transform property** comes in two different settings:(two-dimensional and three-dimensional). 

* Each of these come with their own individual properties and values.

* **Transform Syntax** : including the transform property followed by the value. 

div {
  webkit-transform: scale(1.5);
  moz-transform: scale(1.5);
  transform: scale(1.5);
  transform: scale(1.5);
}

* **2D Transforms**

* Two-dimensional transforms work on (x , y )axes, known as horizontal and vertical axes.
* Three-dimensional transforms work on both (x , y , z) axes.

* **2D Rotate**  

- The rotate value provides the ability to rotate an element from 0 to 360 degrees.
- Positive value : will rotate an element clockwise
- Negative value : will rotate the element counterclockwise.

* **2D Scale**

- To change the appeared size of an element.
- The default scale value is 1 .
- Any value between .99 and .01 makes an element appear smaller.
- Any value greater than or equal to 1.01 makes an element appear larger.

* **2D Translate**

- **translateX** value : will change the position of an element on the horizontal axis.
- **translateY** value : will change the position of an element on the vertical axis.

* **2D Skew**

- **skewX** value : distorts an element on the horizontal axis.
- **skewY** value : distorts an element on the vertical axis.

* **Transform Origin**

- transform-origin property can accept one or two values.
- that value is used for both the horizontal and vertical axes.

* **Perspective** : Can be set in two different ways:

- **perspective value** within the transform property on individual elements.
- **perspective property** on the parent element residing over child elements being transformed.

* **Perspective Depth Value**

- can be set as **none** or a **length measurement**.
- The **none** value turns off any perspective.
-  the **length** value will set the depth of the perspective.

* **Perspective Origin**

- same values used for **the transform-origin** property may also be used with **the perspective-origin** property.

* **3D Transforms**

**we can change elements on the z axis, giving us control of depth as well as length and width.**

* **Transitions & Animations**

- Transition to take place, an element must have a change in state
- The easiest way for determining styles for different states using (:hover, :focus, :active,:target **pseudo-classes**).

- There are four transition related properties in total:(transition-property, transition-duration, transition-timing-function, and transition-delay).

* **8 simple CSS3 transitions that will wow your users**

1. Fade in :
.fade
{
        opacity:0.5;
}
.fade:hover
{
        opacity:1;
}
2. Change color :
.color:hover
{
        background:#53a7ea;
}
3. Grow & Shrink :
.shrink:hover
{
        -webkit-transform: scale(0.8);
        -ms-transform: scale(0.8);
        transform: scale(0.8);
}
4. Rotate elements :
.rotate:hover
{
        -webkit-transform: rotateZ(-30deg);
        -ms-transform: rotateZ(-30deg);
        transform: rotateZ(-30deg);
}

.grow:hover
{
        -webkit-transform: scale(1.3);
        -ms-transform: scale(1.3);
        transform: scale(1.3);
}
5. Square to circle :

.circle:hover
{
        border-radius:50%;
}
6. 3D shadow :
.threed:hover
{
        box-shadow:
                1px 1px #53a7ea,
                2px 2px #53a7ea,
                3px 3px #53a7ea;
        -webkit-transform: translateX(-3px);
        transform: translateX(-3px);
}
7. Swing :
.swing:hover
{
        -webkit-animation: swing 1s ease;
        animation: swing 1s ease;
        -webkit-animation-iteration-count: 1;
        animation-iteration-count: 1;
}

8. Inset border :
.border:hover
{
        box-shadow: inset 0 0 0 25px #53a7ea;
}


[Previous](class-13.md)  | [Home](README.md) | [Next](class-15.md)
