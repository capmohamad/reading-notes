What's a Table

A table represents information in a grid format.
Examples of tables include financial reports, TV
schedules, and sports results,
Grids allow us to understand
complex data by referencing
information on two axes.
Each block in the grid is referred
to as a table cell. In HTML a
table is written out row by row.
<table>
<tr>
<th></th>
<th>9am</th>
<th>10am</th>
<th>11am</th>
<th>12am</th>
</tr>
<tr>
<th>Monday</th>
<td colspan="2">Geography</td>
<td>Math</td>
<td>Art</td>
</tr>
<tr>
<th>Tuesday</th>
<td colspan="3">Gym</td>
<td>Home Ec</td>
</tr>
</table>

LONG TABELS
There are three elements that
help distinguish between the
main content of the table and
the first and last rows (which can
contain different content).
These elements help people
who use screen readers and also
allow you to style these sections
in a different manner than the
rest of the table (as you will see
when you learn about CSS).

for summry aboy Tables
The <table> element is used to add tables to a web
page.
XX A table is drawn out row by row. Each row is created
with the <tr> element.
XX Inside each row there are a number of cells
represented by the <td> element (or <th> if it is a
header).
XX You can make cells of a table span more than one row
or column using the rowspan and colspan attributes.
XX For long tables you can split the table into a <thead>,
<tbody>, and <tfoot>.


Functions, Methods, and Objects JS

Method examples

In JavaScript, functions are objects. You can work with functions as if they were objects. For example,
 you can assign functions to variables, to array elements, and to other objects.
They can also be passed around as arguments to other functions or be returned from those functions.

For a start, let’s teach the user to say hello:

let user = {
  name: "John",
  age: 30
};

user.sayHi = function() {
  alert("Hello!");
};

user.sayHi(); // Hello!
Here we’ve just used a Function Expression to create a function and assign it to the property user.sayHi of the object.

Then we can call it as user.sayHi(). The user can now speak!

A function that is a property of an object is called its method.

So, here we’ve got a method sayHi of the object user. 


 Creating objects with object literals


A JavaScript object is a collection of properties where each property has a name and a value, similar to Hash, Map,
 or Dictionary in other languages. The name of a property can be any string, including an empty string. 
The value can be any value, such as a string, Boolean, number, and null, but it cannot be undefined.
 The object's properties can be defined even after you start using the object. But first,
 let's look at how we create objects in JavaScript.
The easiest way is to create a new object is with object literal notation which is bracketed by a pair of curly braces: {}.
 Properties and their values can be added as you go. In the example below we create an empty object, using object literal notation, and we are adding two properties after that:
