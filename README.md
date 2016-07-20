# JavaScript Attributes

The statements in this example use jQuery methods to change the class and id attributes of the specified HTML elements. When the values of these attributes change, new CSS rules are applied to the elements, changing how they look. Using events to trigger changes to attribute values that apply new CSS rules is a popular way to make a web page interactive.

## Components that make the app run

* The firt statement finds the third list and removes hot from the class attribute on that element. This is important to note because it affects the next statement.
* The second statement selects all li elements whose class attrubute has a value of hot. It add a new class name called favorite. Because step 1 updated the third list item, this statement affects only the first two.
