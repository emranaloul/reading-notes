# Lists
* ### Types of lists in HTML:
1. **Ordered list**: are lists where each item in the list is
numbered. For example, the list might be a set of steps for
a recipe that must be performed in order, or a legal contract
where each point needs to be identified by a section
number.
2. **Unordered list**: are lists that begin with a bullet point
(rather than characters that indicate order).
3. **Defeinition list**: are made up of a set of terms along with the
definitions for each of those terms.

* **Nested Lists**: You can put a second list inside an < li > element to create a sublist or nested list.

# Boxes
Command | Purpose and Using
------|-------
Box Dimensions | To set your own dimensions for a box you can use the height and width properties.
Limiting Width | the  min-width property specifies the smallest size a box can be displayed at when the browser window is narrow, and the max-width property indicates the maximum width a box can stretch to when the browser window is wide.
Limiting Height | This is achieved using the min-height and max-height properties.
Overflowing Content | The overflow property tells the browser what to do if the content contained within a box is larger than the box itself. It can have one of two values: hidden & scroll.
Border Width | The border-width property is used to control the width
of a border. The value of this property can either be given in pixels or using one of the following values: thin, medium & thick.

* ### Border, Margin & Padding

**Image Below describes  them:**

![BMP](https://i.pinimg.com/originals/f6/f6/c9/f6f6c946356774ddb886956cd94df4c9.png)

* **We have styles for border are showing in the below image:**

![border-styles](https://www.w3.org/community/webed/wiki/images/a/af/Cssed_borderstyles.png)

* **padding**: The padding property allows
you to specify how much space should appear between the content of an element and its border.

* **margin**: The margin property controls
the gap between boxes. Its value
is commonly given in pixels,
although you may also use
percentages or ems.

### Display options:
1. **Inline**: This causes a block-level
element to act like an inline
element.
1. **block**: This causes an inline element to
act like a block-level element.
1. **inline-block**: This causes a block-level
element to flow like an inline
element, while retaining other
features of a block-level element.
1. **none**: This hides an element from the
page. In this case, the element
acts as though it is not on the
page at all (although a user could
still see the content of the box if
they used the view source option
in their browser).

# Arrays
Defenition: An array is a special type of variable. It doesn't
just store one value; it stores a list of values.

### How to create an array:]
1. You create an array and give it
a name just like you would any
other variable (using the var
keyword followed by the name of
the array).
1. The values are assigned to the
array inside a pair of square
brackets, and each value is
separated by a comma.

* **Array literal**: the technique for creating
an array.
* **Values in an array** are accessed as if they are in
a numbered list. It is important to know that the
numbering of this list starts at zero (not one).

# Decesion & Loops
* **If... Else statement**: it checks a condition, if it resolves to true the first code block is executed, if the condition resolves to false the second code block is run instead.
* **Switch Statement**: a switch statement starts with a variable called the switch value, each case indicates a possible value for the cariable and the code that should run if the variable matches that value.

### TYPE COERCION & WEAK TYPING:

* Type coercion will work as below: 

Data type | Purpose
--------| -------
string |Text
number | Number
Boolean | true or false
nul | Empty 
undefined | Variable has been declared but not yet assigned a value 

### TRUTHY & FALSY VALUES

* FALSY VALUES

Value | DESCRIPTION
---| ---
var highScore = false; | The traditional Boolean false
var highScore = O; | The number zero
var highScore = ''; | NaN(Not a Number)
var highScore = 10/'score' ; | Empty value
var highScore; | A variable with no value assigned to it


* TRUTHY VALUES 

Value | DESCRIPTION
---| ---
var hi ghScore = true ; | The traditional Boolean true
var highScore = l; | Numbers other than zero
var highScore = 'carr ot ' ; | Strings with content
var highScore = 10/5; | Number calculations
var highScore = 'true'; | true written as a string
var hi ghScore = ' O' ; | Zero written as a string
var highScore = ' false'; | false written as a string

