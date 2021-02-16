HTML - Forms
Advertisements

 Previous PageNext Page  
HTML Forms are required, when you want to collect some data from the site visitor. For example, during user registration you would like to collect information such as name, email address, credit card, etc.

A form will take input from the site visitor and then will post it to a back-end application such as CGI, ASP Script or PHP script etc. The back-end application will perform required processing on the passed data based on defined business logic inside the application.

There are various form elements available like text fields, textarea fields, drop-down menus, radio buttons, checkboxes, etc.

The HTML <form> tag is used to create an HTML form and it has following syntax −

<form action = "Script URL" method = "GET|POST">
   form elements like input, textarea etc.
</form>
Form Attributes
Apart from common attributes, following is a list of the most frequently used form attributes −

Sr.No	Attribute & Description
1	
action

Backend script ready to process your passed data.

2	
method

Method to be used to upload data. The most frequently used are GET and POST methods.

3	
target

Specify the target window or frame where the result of the script will be displayed. It takes values like _blank, _self, _parent etc.

4	
enctype

You can use the enctype attribute to specify how the browser encodes the data before it sends it to the server. Possible values are −

application/x-www-form-urlencoded − This is the standard method most forms use in simple scenarios.

mutlipart/form-data − This is used when you want to upload binary data in the form of files like image, word file etc.

Note − You can refer to Perl & CGI for a detail on how form data upload works.

HTML Form Controls
There are different types of form controls that you can use to collect data using HTML form −

Text Input Controls
Checkboxes Controls
Radio Box Controls
Select Box Controls
File Select boxes
Hidden Controls
Clickable Buttons
Submit and Reset Button
Text Input Controls
There are three types of text input used on forms −

Single-line text input controls − This control is used for items that require only one line of user input, such as search boxes or names. They are created using HTML <input> tag.

Password input controls − This is also a single-line text input but it masks the character as soon as a user enters it. They are also created using HTMl <input> tag.

Multi-line text input controls − This is used when the user is required to give details that may be longer than a single sentence. Multi-line input controls are created using HTML <textarea> tag.

Single-line text input controls
This control is used for items that require only one line of user input, such as search boxes or names. They are created using HTML <input> tag.

Lists
We use lists whenever we need to list items that are related somehow. A List can be used for cited works, numbered tutorial steps, navigation menus, and many, many other things. I'm sure you are familiar with bullet points from MS Word and other similar programs. There are 3 types of lists in HTML.

Unordered list
The first type is <ul>, which stands for Unordered List. Items in it are unindexed and are displayed as bullet points as default. Although the list is seen as unordered, the order of items is kept when displayed in a browser. <ul> is a paired tag that wraps list items.

List items
The <li> tag, stands for List Item, takes a single item in the list, and wraps its text. Aside from text, it also takes images or any other type of element.


JavaScript Events


The change in the state of an object is known as an Event. In html, there are various events which represents that some activity is performed by the user or by the browser. When javascript code is included in HTML, js react over these events and allow the execution. This process of reacting over the events is called Event Handling. Thus, js handles the HTML events via Event Handlers.