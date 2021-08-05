## JavaScript Book 
###  “Object Literals”
#### OBJECT and METHOD
* Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names.
* If a variable is part of an object, it is called a property. Properties te ll us about the object, such as the name of a hotel or the number of rooms it has. Each individual hotel might have a different name and a different number of rooms.
* If a function is part of an object, it is called a method.Methods represent tasks that are associated with the object. For example, you can check how many rooms are available by subtracting the number of booked rooms from the total number of rooms. 
* properties and methods have a name and a value.
* In an object, that name is called a key, each key should be a uniqe and cannot have 2 keys with the same name .


#  “Document Object Model”
* **The Document Object Model (DOM)** specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.

* The DOM specifies the way in which the browser should structure this model using a DOM tree.
* The DOM is called an object model because the model (the DOM tree) is made of objects.
* Each object represents a different part of the page loaded in the browser window.
* **Application Programming Interface (API)**. User interfaces let humans interact with programs; APls let programs (and scripts) talk to each other.
* Each node is an object with methods and properties.

1. **THE DOCUMENT NODE** it represents the entire page.
2. **ELEMENT NODES** HTML elements describe the structure of an HTML page. (The `<h l > - <h6> `elements describe what parts are headings; the `<p>` tags indicate where.
3. **ATTRIBUTE NODES** The opening tags of HTML elements can carry attributes and these are represented by attribute nodes in the DOM tree. **Attribute nodes are not children of the element that carries them; they are part of that element**
4. **TEXT NODES** Once you have accessed an element node, you can then reach the text within that element. This is stored in its own text node.



###### Accessing and updating the DOM tree involves two steps:
1. Locate the node that represents the element you want to work with.
2. Use its text content, child elements, and attributes.
