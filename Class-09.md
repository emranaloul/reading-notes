# Forms
## Form Controls
### Adding Text:
* Text input (single-line)
* Password input
* Text area (multi-line)
### Making Choices:
* Radio buttons
* Checkboxes
* Drop-down boxes
### Submitting Forms:
* Submit buttons
* Image buttons
* File upload
## Form Structure
* < form>
Form controls live inside a
< form> element. This element
should always carry the action
attribute and will usually have a
method and id attribute too.
* **action**
Every < form> element requires
an action attribute. Its value
is the URL for the page on the
server that will receive the
information in the form when it
is submitted.
* **method**
Forms can be sent using one of
two methods: get or post.
## Text Input
### < input>
The < input> element is used
to create several different form
controls. The value of the type
attribute determines what kind
of input they will be creating.
* **type="text"**
When the type attribute has a
value of text, it creates a singleline
text input.
* **name**
When users enter information
into a form, the server needs to
know which form control each
piece of data was entered into.
* **size**
The size attribute should not
be used on new forms.
* **maxlength** You can use the maxlength
attribute to limit the number
of characters a user may enter
into the text field.
## Password Input
* **type="password"** When the type attribute has
a value of password it creates
a text box that acts just like a
single-line text input, except
the characters are blocked out.
* **name**
The name attribute indicates
the name of the password input,
which is sent to the server with
the password the user enters.
* **size, maxlength**
It can also carry the size and
maxlength attributes like the
the single-line text input.
## Text Area
* < textarea>
The < textarea> element
is used to create a mutli-line
text input. Unlike other input
elements this is not an empty
element. It should therefore have
an opening and a closing tag.
## Radio Button
* type="radio"
Radio buttons allow users to pick
just one of a number of options.
* **name**
The name attribute is sent to
the server with the value of the
option the user selects. When
a question provides users with
options for answers in the form
of radio buttons, the value of
the name attribute should be the
same for all of the radio buttons
used to answer that question.
* **value**
The value attribute indicates
the value that is sent to the
server for the selected option.
The value of each of the buttons
in a group should be different
(so that the server knows which
option the user has selected).
* **checked**
The checked attribute can be
used to indicate which value (if
any) should be selected when
the page loads. The value of this
attribute is checked. Only one
radio button in a group should
use this attribute.
# Lists, Tables and Forms
Command | Purpose
------| -----
list-style-type | Bullet Point Styles
list-style-image | Images for Bullets
list-style-position | Positioning the Marker
list-style | List Shorthand
empty-cells | Border on Empty Cells
border-spacing, border-collapse | Gaps Between Cells
cursor | Cursor Styles

# Events
## DIFFERENT EVENT TYPES
### UI Events
![UI](https://d.top4top.io/p_1880pfcf91.png)
### Keyboard Events
![keyboard](https://g.top4top.io/p_188012kpx1.png)
### Mouse Events
![Mouse](https://l.top4top.io/p_18805hmff1.png)
### Focus Events
![Focus](https://l.top4top.io/p_18805hmff1.png)
### Form Events
![form](https://i.top4top.io/p_1880aioub1.png)
### Mutation Events
![Mutation](https://l.top4top.io/p_1880xpwqm1.png)

## HOW EVENTS TRIGGER JAVASCRIPT CODE??
1. Select the element node(s) you want the script to respond to.
2. Indicate which event on
the selected node(s) will
trigger the response.
3. State the code you want
to run when the event
occurs.
## THREE WAYS TO BIND AN EVENT TO AN ELEMENT
1. HTML EVENT HANDLER
ATTRIBUTES (DO NOT USE)
2. TRADITIONAL DOM
EVENT HANDLERS
3. USING DOM EVENT
HANDLERS