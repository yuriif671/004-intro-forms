# Introduction to Forms

Reference: What the Youtube Video:  
https://www.youtube.com/watch?v=2O8pkybH6po

Sometimes you want to have webpage that does more than display information to the user.  You might want to create a web application, that allows the user to do something on the webpage. You might want to just use the webpage as interface to collect information from the user, and then send that information to some other website or API endpoint (like a website, but doesn't really behave as a webpage).  In both of these cases, you will want to create a Web Form interface to collect and send the user information

### Summary
A form is used to 
* create a user interface for collecting data from a user
* the data can be used on the page itself or sent to another place for processing

### The \<form> element

Originally, a form was its own container element, and all of the input fields you used had to be placed within the parent form element.  The form found in "formIntro.html" is a great example. The parent form element is defined on line 9 and closed on line 103.  Everything in between those lines is part of the form and will be collected up and can be send/submitted somewhere.

The form element is not striclty, necessary and a page can get by without a form element completely. Take a look at formApp.html for an example.

Do not worry about understanding how this program works, although it is simple enough that you might be able to decode what is going on. We will look at deconstructing  and creating our own javascript later on.

### Summary
* a \<form> tag is not needed to include form elements, but is helpful for grouping the form elements together

## Assignment
Create an html form that will have the user enter some data.  Your html form should include the following:
* a text input
* a checkbox
* radio boxes
* a select box
* a button for submitting data (can be a submit or button)
* each form element should have a _name_ and _id_
* each element should be appropriate for the data to be entered
* use css/styles to add decorative features or improve the layout of your form

