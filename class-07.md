# Domain Modeling
* **Domain modeling:** is the process of creating a conceptual model in code for a specific problem.
* **object-oriented:** An entity that stores data in properties and encapsulates behaviors in methods.

### Summary
Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

* Here's some tips to follow when building your own domain models.

1. When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
2. Model its attributes with a constructor function that defines and initializes properties.
3. Model its behaviors with small methods that focus on doing one job well.
1. Create instances using the new keyword followed by a call to a constructor function.
3. Store the newly created object in a variable so you can access its properties and methods from outside.
1. Use the this variable within methods so you can access the object's properties and methods from inside.

# Tables
**Table:** represents information in a grid format.
Examples of tables include financial reports, TV
schedules, and sports results.

### Basic Table Structure:
* < table >:
The < table > element is used
to create a table. The contents
of the table are written out row
by row.
* < tr >:
You indicate the start of each
row using the opening < tr > tag.
(The tr stands for table row.)
It is followed by one or more
< td > elements (one for each cell
in that row).
At the end of the row you use a
closing < /tr> tag.
* < td >:
Each cell of a table is
represented using a < td >
element. (The td stands for
table data.)
At the end of each cell you use a
closing < /td> tag.
* < th>
The < th> element is used just
like the < td> element but its
purpose is to represent the
heading for either a column or
a row. (The th stands for table
heading.)
* < thead>
The headings of the table should
sit inside the < thead> element.
* < tbody>
The body should sit inside the
< tbody> element.
* < tfoot>
The footer belongs inside the
< tfoot> element.

# Objects
* ### toolkit has three compartments:
1. **BROWSER OBJECT
MODEL**:
The Browser Object Model contains
objects that represent the current
browser window or tab. It contains
objects that model things like
browser history and the
device's screen.

2. **DOCUMENT OBJECT
MODEL**: The Document Object Model uses
objects to create a representation of
the current page. It creates a new
object for each element (and each
individual section of text)
within the page.
3. **GLOBAL JAVASCRIPT
OBJECTS**:
The global JavaScript objects
represent things that the JavaScript
language needs to create a model
of. For example, there is an
object that deals only with
dates and times.

### Below is some window properties and its description:


![properties and descrition](https://www.mediafire.com/convkey/5ca4/1odrbnhpw3afyktzg.jpg)

### Also we have window methods and its description:

![methods0](https://www.mediafire.com/convkey/d9ec/c4lrimow8sve2xvzg.jpg)

## THE DOCUMENT OBJECT
### Here are some properties of the document object and its description:
![properties](https://www.mediafire.com/convkey/0168/orhsowic4io2yjxzg.jpg)

### The following are a few of the methods that select content or update the content of a page.

![methods](https://www.mediafire.com/convkey/def3/um90cn0vxnx35lhzg.jpg)

* In an object, variables are known as properties of the
*object; functions are known as methods of the object.
* Web browsers implement objects that represent both
the browser window and the document loaded into the
browser window.
* JavaScript also has several built-in objects such as
String, Number, Math, and Date. Their properties and
methods offer functionality that help you write scripts.
* Arrays and objects can be used to create complex data
sets (and both can contain the other).

