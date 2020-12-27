**Design web pages with CSS**

**What CSS does ?**

CSS allows you to create rules that specify how the content of an element should appear.

CSS rules usually appear in a separate document,although appear within an HTML page.
.A CSS rules are made up of selectors . it contians two parts:
- Selector : - Universal Selector * {}
             - Type Selector h1, h2, h3 {}
             - **Class Selector**  .{} 
             - **ID Selector**   # {}
             - Child Selector   li>a {}
             - Descendant Selector p a {}
             - Adjacent Sibling Selector h1+p {}
             - General Sibling Selector h1~p {} 

- Declaration (properity : value ;).

External CSS : adding link in html Head <link rel="stylesheet" href="style.css">. and styling inside CSS.
Internal CSS : adding link in html Head <style type="text/css"> and styling inside HTML.

**Colors**

**How to specify colors?** 

1) Foreground Color (color:)
   To specify the color of text inside an element by three ways:

1- rgb values : specify how much R,G,B . eg: rgb(100,100,90)
2- hex codes  : six-digit codes that represent the amount of R,G,B. eg: #ee3e80
3- color names: 147 predefined color names. eg:DarkCyan.

2) (background-color:) 
   Sets the color of the background for the box.
   You can specify your background color in the same three ways.

**Color terminology and contrast:**

Computer monitors are made up of thousands of tiny squares called **pixels**.
The color of every pixel is expressed in terms of a mix of R,G,B .
To find the color use a *color picker*.

* TO  represent values for red, green and blue :

- RGB Values : expressed as numbers between 0 and 255. 
- Hex Codes  : expressed in hexadecimal code.
- Color Names: expressed by predefined names .

Hue:represented as a color circle /or shown as a slider with values from (0 to 360).
Saturation :  the amount of gray in a color , At maximum NO gray 100% / At minimum mostly gray 0% .
Brightness :  the amount of black in a color, At maximum NO black 100% / At minimum mostly black 0%.
lightness  :  the amount of white (lightness) or black (darkness) , ( 0% black , 100% white , 50% normal).

* Contrast
- Low Contrast  : Text is harder to read .
- High Contrast : Text is easier to read .
- Medium Contrast:For long spans of text.

**Opacity**
 The value is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity). 
 - (opacity, rgba) : eg: rgba(55,100,100,.5) = rgba(55,100,100,50%)
 - (hsl, hsla)     : hue (0 and 360 degrees) / saturation (%) /lightness (%) / alpha (betweem 0 - 1.0 or %)
                     eg: hsl((0,0%,78%)  / hsla(0,100%,100%,0.5) .


[Previous](Read04.md)  | [Home](README.md) | [Next](Read06a.md)