# Forms and Events
## Forms
An HTML form is used to collect user input. The user input is most often sent to a server for processing. The HTML `<form>` element is used to create an HTML form for user input. The `<form>` element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons. The HTML `<input>` element is the most used form element. An `<input>` element can be displayed in many ways, depending on the type attribute. The `<input type="text">` defines a single-line input field for text input. The `<label>` tag defines a label for many form elements. The `<label>` element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focus on the input element. The `<input type="radio">` defines a radio button. Radio buttons let a user select ONE of a limited number of choices. The `<input type="checkbox">` defines a checkbox. Checkboxes let a user select ZERO or MORE options of a limited number of choices. The `<input type="submit">` defines a button for submitting the form data to a form-handler. The form-handler is typically a file on the server with a script for processing input data. Notice that each input field must have a `name` attribute to be submitted. 
If the `name` attribute is omitted, the value of the input field will not be sent at all.

## Events
HTML has the ability to let events trigger actions in a browser, like starting a JavaScript when a user clicks on an element. Events triggered by actions inside a HTML form.
 Events can be broken into:
 - Form Events
 - Keyboard Events
 - Mouse Events
 - Drage Events
 - Clipboard events
 - Media Events
 - Misc Events