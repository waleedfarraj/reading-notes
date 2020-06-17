# Forms and JS Events
## forms 
when you want to apply for something you are handed 
some forms to fill in , html move that idea to the 
virtual realm , There are several types of form controls that
you can use to collect information from visitors
to your site.
ADDING TEXT:
Making Choices:
Submitting Forms: Uploading Files:
Password input
Like a single line text box but it
masks the characters entered.
Text input (single-line)
Used for a single line of text such
as email addresses and names.
Text area (multi-line)
For longer areas of text, such as
messages and comments.
How Forms Work
1. A user fills in a form and then presses a button
to submit the information to the server.
1. The name of each form
control is sent to the
server along with the
value the user enters or
selects.
1. The server processes
the information using a
programming language
such as PHP, C#, VB.net,
or Java. It may also store
the information in a
database.
1. The server creates a new
page to send back to the
browser based on the
information received.
- Form Structure consist of a form tag that 
we add an action inside and a method it may 
contain and id as well .
-for text input we add input tag then specify
type of data and a name attribute that reflects
the data entred you can add size and max length
password is as same as text but we add the type 
to be password.
## lists
List markers can be given different appearances
using the list-style-type and list-style image
properties.
Table cells can have different borders and spacing in
different browsers, but there are properties you can
use to control them and make them more consistent. 
here is some table proprties :
-width : to set the width of the table
-padding to set the space between the border of each table cell and its content
-text-transform to convert the content of the table headers to uppercase
-letter-spacing, font-size to add additional styling to the content of the table headers
-border-top, border-bottom to set borders above and below the table headers
-text-align to align the writing to the left of some table cells and to the right of the others
-background-color to change the background color of the alternating table rows
-:hover to highlight a table row when a user's mouse goes over it.
## Events
When you browse the web, your browser registers different
types of events. It's the browser's way of saying, "Hey, this
just happened." Your script can then respond to these events. 
When the user interacts with the HTML on a web page, there are three
steps involved in getting it to trigger some JavaScript code.
Together these steps are known as event handling. 
1. Select t he element
node(s) you want the
script to respond to.
For example, if you want to
trigger a function when a user
clicks on a specific link, you need
to get the DOM node for that
link element. You do this using a
DOM query 
2. Indicate which event on
the selected node(s) will
trigger the response.
Programmers call this binding an
event to a DOM node.
The previous two pages showed
a selection of the popular events
that you can monitor for. 
3. State the code you want
to run when the event
occurs.
W hen the event occurs, on a
specified element, it will trigger
a function. This may be a named
or an anonymous function. 
Event listeners are a more recent approach to handling events.
They can deal with more than one function at a time
but they are not supported in older browsers. 
