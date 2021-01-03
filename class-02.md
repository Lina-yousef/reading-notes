**Basics of HTML, CSS & JS**

**Html Text** 

- **Headings** :(h1-h6) HTML has six levels of headings with different sizes.
- **Paragraphs** : (p) To create a paragraph.
- **Bold** : <b> To make characters appear bold.
- **italic** : <i>  To make characters appear italic.
- **Superscript** : <sup> to contain characters that should be superscript, used for raising a number to a power.
- **Subscript** : <sub> to contain characters that should be subscript ,used with foot notes or chemical formulas such as H2O .
- **Line Break** : <br/> To show paragraph or heading on a new line. 
- **Horizontal Rule** : <hr/> To create a break between themes.

**Visual editors** 

Usually have two views of the page you are creating: a visual editor and a code view.such as:Dreamweaver. 

**Semantic Markup**

Text elements that are not intended to affect the structure of web pages, but they add extra information to the pages.

- <strong>  : for content with strong importance.show the contents in bold.
- <em>      : emphasis that subtly changes the meaning of a sentence. show the contents in italic.

**quotations** 

- <blockquote> : used for longer quotes that take up an entire paragraph.
- <q>          : s used for shorter quotes that sit within a paragraph.

**Abbreviations** : <abbr> A title attribute on the opening tag ,used to specify the full term.
**Acronyms** : <acronym>  To spell out the full form of the acronym
**Citation** : <cite> When referencing a piece of work like a book ,to indicate where the citation is from.
**Definitions** : <dfn> to indicate the defining instance of a new term.
**<address>** : to contain contact details for the author of the page.

**Changes to Content** 
- <ins> : to show content that has been inserted into a document.
- <del> : to show text that has been deleted from it.
- <s>   : to indicates something that is no longer accurate (but that should not be deleted). 

**CSS**

**What CSS does ?**

CSS allows you to create rules that specify how the content of an element should appear.

CSS rules usually appear in a separate document,although appear within an HTML page.
A CSS rules are made up of selectors. it contians two parts:

* Selector :
- Universal Selector * {} 
- Type Selector h1, h2, h3 {} 
- Class Selector .{} 
- ID Selector # {} 
- Child Selector li>a {} 
- Descendant Selector p a {} 
- Adjacent Sibling Selector h1+p {} 
- General Sibling Selector h1~p {}

Declaration (properity : value ;).

External CSS : adding link in html Head , and styling inside CSS. 
Internal CSS : adding link in html Head.

**JavaScriot**

A script is a series of instructions that a computer can follow one-by-one. 
Each instruction or step is known as a statement. 

**comments** : to explain what your code does , by adding /*  */ , // 

**variable** : temporarily store for data it needs to do its job. 

**DATA TYPES** 
- Numeric (0-9)
- String (text)
- Boolean (T/F)

* **6 RULES FOR NAMING VARIABLES :**
- The name must begin with (letter, dollar sign ($), underscore (_)). It must not start with a number.
- The name musn't use (dash(-) or a period (.) ).
- You can't use keywords or reserved words.
- All variables are case sensitive.
- Use a name that describes the kind of information that the variable stores. eg: var firstName ;
- Use capital letter for the first letter of every word after the first word eg:firstName.

Array :A special type of variable stores a list of values.

**Expression** :
- EXPRESSIONS that just assign a value to a variable. (var color = 'beige';)
- EXPRESSIONS that use two or more values to return a single value.(var area = 3 * 2; )

**Mathematical operators**
![](.png)


**Decisions and Loops** 

**Desision Making** 
* There are two component to a desision:
- An expression is evaluated , which returns a value.
- A conditional statment says what to do on a ginen situation.

**IF STATEMENTS** : Checking if the condition evaluates to :
- True the first statement will executed.
- False the second statement will executed.


**Comparison**

You can evaluate a situation by comparing one value in the script to what expect it might be , the result will be Boolean (T/F).

Is equal ==
Is not equal !=
Strict equal ===
Strict not equal !=
In any condition there is :

One operator
Two operands (values / variables)
Logical Operators

Allow you to compare the results of more than one comparison operator.

Logical AND &&
Logical OR	 
Logical NOT !

[Previous](class-01.md)  | [Home](README.md) | [Next](class-03.md)





