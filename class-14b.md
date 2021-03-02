# Transforms
## Transform Syntax
* The actual syntax for the transform property is quite simple, including the transform property followed by the value. The value specifies the transform type followed by a specific amount inside parentheses.
## 2D Transforms
Elements may be distorted, or transformed, on both a two-dimensional plane or a three-dimensional plane. Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes. Three-dimensional transforms work on both the x and y axes, as well as the z axis. These three-dimensional transforms help define not only the length and width of an element, but also the depth. We’ll start by discussing how to transform elements on a two-dimensional plane, and then work our way into three-dimensional transforms.
### 2D Rotate
 The transform property accepts a handful of different values. The rotate value provides the ability to rotate an element from 0 to 360 degrees. Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise. The default point of rotation is the center of the element, 50% 50%, both horizontally and vertically. Later we will discuss how you can change this default point of rotation.

 ### 2D Scale
 Using the scale value within the transform property allows you to change the appeared size of an element. The default scale value is 1, therefore any value between .99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger.

 ## Combining Transforms

 It is common for multiple transforms to be used at once, rotating and scaling the size of an element at the same time for example. In this event multiple transforms can be combined together. To combine transforms, list the transform values within the transform property one after the other without the use of commas.

Using multiple transform declarations will not work, as each declaration will overwrite the one above it. The behavior in that case would be the same as if you were to set the height of an element numerous times.

## Transform Origin
The transform-origin property can accept one or two values. When only one value is specified, that value is used for both the horizontal and vertical axes. If two values are specified, the first is used for the horizontal axis and the second is used for the vertical axis.

## Skew
The skew transform tilts an element based on values provided on the X and Y axes. A positive X value tilts the element left, while a negative X value tilts it right. A positive Y value tilts the element down, and a negative Y value tilts it up. If an axis isn’t specified and only skew is stated then that is equivalent to skewX. Also you can include both X and Y axes to tilt the element’s angles.

## Scale
The scale transform increases or decreases the size of an element. A number larger than 1 will increase the size of the element and a decimal less than 1 will decrease the size of the element. For example, 2 would make the element twice its original size, whereas 0.5 would make the element half its original size. The size of an element can be scaled by the X-axis, Y-axis or both. The shorthand scale() will effect both axes at the same time.

## Translate
The translate transform moves an element right, left, up or down. A positive X value moves the element to the right and a negative X value moves the element to the left. A positive Y value moves the element downwards and a negative Y value moves the element upwards.