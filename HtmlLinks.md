## HTML Links
* Links are created using the `<a>` element. Users can click on anything between the opening` <a> `tag and the closing `</a> `tag. You specify which page you want to link to using the href attribute.
* <a> element which has an attribute called href. The value of the href attribute is the page that you want people to go to when they click on the link.
* **Absolute URLs** URL stands for Uniform Resource Locator,An absolute URL starts with the domain name for that site, and can be followed by the path to a specific page. If no page is specified, the site will display the homepage.
* When you are linking to other pages within the same site, you do not need to specify the domain name in the URL. You
can use a shorthand known as a relative URL.
* **Relative URLs** When linking to other pages within the same site, you can use relative URLs. These are like a shorthand version of absolute URLs because you do not need to specify the domain name.





### chapter15 
* **Block-level elements** start on a new line.
* **Inline elements** flow in between surrounding text.

* **Controlling the Position of Elements**
* CSS has the following positioning schemes that allow you to control the layout of a page:
     1. **Normal flow** Every block-level element appears on a new line, causing each item to appear lower down the page than the previous one. Even if you specify the width of the boxes and there is space for two elements to sit  ide-byside, they will not appear next to each other. This is the default behavior (unless you tell the browser to do something else).
     2. **Relative Positioning** This moves an element from the position it would be in normal flow, shifting it to the  op, right, bottom, or left of where it would have been placed. This does not affect the position of surrounding  elements; they stay in the position they would be in in normal flow.
     3. **Absolute positioning** This positions the element in relation to its containing element. It is taken out of normal flow, meaning that it does not affect the position of any surrounding elements (as they simply ignore the space it would have taken up). Absolutely positioned elements move as users scroll up and down the page.

* To indicate where a box should be positioned, you may also need to use box offset properties to tell the browser how  far from the top or bottom and left or right it should be placed.
     1. **Fixed Positioning** This is a form of absolute positioning that positions the element in relation to the browser window.
     2. **Floating Elements** Floating an element allows you to take that element out of normal flow and position it to the far left or right of a containing box. The floated element becomes a block-level element around which other content can flow.
         


### JavaScript Book 
#### Chapter 3 “Functions, Methods, and Objects”
* Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of st atements.

* To create a Function, you give it a name and then write the statements needed to achieve its task inside the curly braces. This is known as a **function declaration**.

* **FUNCTION DECLARATION** A function declaration creates a function that you can ca ll later in your code. It is the type of function you have seen so far in this book.

#### function declaration
* **Calling Function**: you can then execute all of the statements between its curly braces with just one line code,when you call a function that has parameters, you specify the values it should use in the parentheses that follow its name. The values are called arguments, and they can be provided as values or variables.
* some functions return information to the code that called them. For example, when they perform calculations, they return the result,Functions can return more than one value using an array. For example, this function calculates the area and volume of a box.
* Expressions produce a value. They can be used where values are expected. If a function is placed where a browser expects to see an expression.
