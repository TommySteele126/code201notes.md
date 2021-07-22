## HTML Lists, Control Flow with JS, and the CSS Box Model 
### HTML Book 
#### chapter 3 "Lists" :
* There are 2types of lists :  
     1. **unordered list**  `<ul>` use bullets.
     2. **ordered list** `<ol>` use numbers.
     * each type should include `<li>` to write each partition of this list,
     * you can put a several lists inside them by open new list tag and `<li>` tags and then close it and continue with the first list.

* Definition Lists : contain `<dl>` to create or start the definition list

#### chapter 13 "Boxes" :
* so every box has a width and height proparties, by default the size of box just big enough to hold its contents.
* to determine the size of box you can use:
     1. **pixels(px)**pixels have been the most popular method because they allow designers to accurately control their size.
     2. **persentage (%)** the size of the box is relative to the size of the browser window.
     3. **ems** the size of the box is based on the size of text within it. 



* **Border**: The border separates the edge of one box from another, they have a severl values to **border-width** : *thin,meduim,thick* or write the width in numbers in pixel , you can controlling the width of each side `border-top-width: vlaue ` and the same thing with other sides .**border-style** to control the style (solid,dotted,...) , and **border-color** to determine the color. also you can write all of them in one line by `border : width style color`for example `border: 2px solid black `.
* **Margin** : the distance between the border and other box betwwen , you can controled the marign-top , margin-left , .. the same thing to other sides.( If you want to center a box on the page you can set the left-margin and right-margin to auto.)
* **Padding** : the distance between the content and the border,you can controled the padding-top ,.. to other sides.

* all of margin ,border, padding will adding to the size of box.

* displye values : inline , block , inline-block , none.
 


* **border-radius** The value indicates the size of the radius in pixels. You can specify individual values
for each corner of a box using `border-top-right-radius`,`border-bottom-right-radius`,`border-bottom-left-radius`,`border-top-left-radius`. 
* To create more complex shapes, you can specify different distances for the horizontal and the vertical parts of the rounded corners for example `border-radius: 80px 50px;`


### Javascript Book 
#### Basic JavaScript Instructions
##### chapter 2 "CREATING AN ARRAY"
* You create an array and give it a name just like you would any other variable (using the var keyword followed by the name of the array). The values in the array do not need to be the same data type,so you can store a string, a number and a Boolean all in the same array.`var array_name=['aya',22,true,1.52];`.

* Values in an array are accessed as if they are in a numbered list. It is important to know that the numbering of this list starts at zero (not one).
* Each item in an array is automatically given a number called an index. This can be used to access specific items in the array.
* To retrieve the third item on the list, the array name is specified along with the index number in square brackets. `array_name[2]` . also you can change the vlaue of the third item by `array_name[2]=new value`.
* Each array has a property called **length**, which holds the number of items in the array `array_name.lenght()`.


##### chapter 4 "Decisions and Loops"
A **switch** statement starts with a variable called the switch value. Each case indicates a possible value for his variable and the code that should run if the variable matches that value.

### data types 
DATA TYPE | PURPOSE
string |Text
number| Number
Boolean |true or false
null |Empty value











