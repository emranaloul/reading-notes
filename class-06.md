# Objects
* Objects group together a set of variables and functions to create a model
of a something you would recognize from the real world.
* **property**: a variable is part of an object.
* **method**: a function is part of an object.
* **Key**: properties and methods have a
name and a value.
# Document Object Model
* The Document Object Model (DOM) specifies
how browsers should create a model of an HTML
page and how JavaScript can access and update the
contents of a web page while it is in the browser window.
* The DOM specifies the way in which the
browser should structure this model using
a DOM tree.

![dom tree](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/08/Js-Dom-Tree.png)

### Accessing and updating the DOM tree involves two steps:

1. Locate the node that represents the element you want to work with.
2. Use its text content, child elements, and attributes.

* ### A Nodelist is a collection of element nodes.

### When a DOM query returns a Nodelist, you may want to:
* Select one element from the NodeList.
* Loop through each item in the Nodelist and
perform the same statements on each of the
element nodes.

### You can get the items as below:

* getElementsByTagName('li ')
* getElementsByClassName('hot')
* querySe l ectorA 11 ( ' l i [id] ' )

### You can traverse the DOM  for the element node using these five properties:
1. parentNode
2. previousSibling
3. nextSibling
4. firstChild
5. lastChild

* ### When you select a text node, you can retrieve or amend the content of it using the **nodeValue** property.

### Adding Elements Using DOM Manipulation
1. Create The Element: createElement()        
2. Give It Content: createTextNode()
3. Add It To The DOM: appendChild()

### Removing Elements Via DOM Manipulation
1. Store The Element
To Be Removed In A
Variable.
2. Store The Parent Of
That Element In A
Variable.
3. Remove The Element
From Its Containing
Element.
* ### The setAttribute() method allows you to update the value of any attribute. It takes two parameters: the attribute name, and the value for the attribute.
* ### To remove an attribute from anelement, first select the element,then call removeAttribute() .It has one parameter: the name of the attribute to remove.



