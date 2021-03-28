# SMACSS and Responsive Web Design
## Responsive Web Design:
Responsive web design is the practice of building a website suitable to work on every device and every screen size

## Responsive vs. Adaptive vs. Mobile:
Responsive generally means to react quickly and positively to any change. With responsive design websites continually and fluidly change based on different factors, such as viewport width.

**adaptive** means to be easily modified for a new purpose or situation, such as change. Adaptive websites are built to a group of preset factors.

**Responsive web design** is broken down into three main components, including flexible layouts, media queries, and flexible media.

**Flexible Layouts**
building the layout of a website with a flexible grid, capable of dynamically resizing to any width. Flexible grids are built using relative length units.

**Media Queries**
provide the ability to specify different styles for individual browser and device circumstances.

Media Features
Height & Width.
Orientation.
Aspect Ratio.
Resolution.
 
**Mobile First**
includes using styles targeted at smaller viewports as the default styles for a website, then use media queries to add styles as the viewport grows.

 **Viewport**
Using the viewport meta tag with either the height or width values will define the height or width of the viewport respectively.

 **Flexible Media**
Images, videos, and other media types need to be scalable, changing their size as the size of the viewport changes.

 **All About Floats**
There are four valid values for the float property. Left and Right float elements those directions respectively. None (the default) ensures the element will not float, and Inherit which will assume the float value from that elements parent element.

**Clearing Floats**
clear is a CSS property used usually with float cleared elements will not wrap around floated elements, but will move down past the floated elements Clear property takes 4 values:

both (clears floats coming from left and right)
left
right
none
 **The Great Collapse**
floated elements can affect the parent element that contains them if a parent element contains only floats, the height of it would collapse to nothing collapsing effects problems are fixed by clearing the float after the floated elements in the container but before the close of the container

**Techniques for Clearing Floats:**

The Empty Div Method <div style="clear: both;"></div>
The Overflow Method setting the overflow CSS property on a parent element to auto or hidden, which clears succeeding elements and the parent will expand to contain the floats
The Easy Clearing Method using the CSS pseudo selector :after to clear floats