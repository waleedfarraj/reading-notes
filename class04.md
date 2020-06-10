# Read: 04 - HTML Links, CSS Layout, JS Functions
## links
Links are the defining feature of the web because they allow 
you to move from one web page to another — enabling the
very idea of browsing or surfing. Links are created using the `<a>` element.
Users can click on anything between the opening `<a>` tag and the
 closing `</a>` tag. You specify which page you want to link to using
 the href attribute.
You can links to another website by linking the website link, you 
can add add Relative URLs  when linking to pages within your own
website. They provide a shorthand way of telling the browser where to
find your files.
To create a link that starts up the user's email program and
addresses an email to a specifie  email address, you use the `<a>`
element. However, this time the value of the href attribute starts
with mailto: and is followed by the email address you want the
email to be sent to.
You can use the id attribute to target elements within
a page that can be linked to. and target to let the link open in a new tab .
## Layouts
CSS treats each HTML element as if it is in its
own box. This box will either be a block-level
box or an inline box. If one block-level element sits inside another
block-level element then the outer box is
known as the containing or **parent element**.

CSS has the following positioning schemes that allow you to control
the layout of a page: normal flow, relative positioning, and absolute
positioning. You specify the positioning scheme using the position
property in CSS. You can also float elements using the float property.

1. Normal flow
Every block-level element
appears on a new line, causing
each item to appear lower down
the page than the previous one.
Even if you specify the width
of the boxes and there is space
for two elements to sit side-byside, they will not appear next
to each other. This is the default
behavior (unless you tell the
browser to do something else).

2. Relative Positioning
This moves an element from the
position it would be in normal
flow, shifting it to the top, right,
bottom, or left of where it
would have been placed. This
does not affect the position of
surrounding elements; they stay
in the position they would be in
in normal flow.
3. Absolute positioning
This positions the element
in relation to its containing
element. It is taken out of
normal flow, meaning that it
does not affect the position
of any surrounding elements
(as they simply ignore the
space it would have taken up).
Absolutely positioned elements
move as users scroll up and
down the page.

When u work in the layouts you need to keep in mind 
that people are viewing the webite on diffrent size screen devices
with diffrent resolution system .

### liquid layouts and fixed width layouts 
liquid layout from it is name is more fluid and responsive to diffrent sreen sizes and diffrent setting that the user might have on his end  and fixed width layouts are static ,both have some advantages and disadvantages .


![liquid](/images/liquid.PNG)
![fixed](/images/fixed.PNG)

## Functions
Browsers require very detailed instructions about what
we want them to do. Therefore, complex scripts can run
to hundreds (even thousands) of lines. Programmers use
functions, methods, and objects to organize their code
where going to disccus one of those today.
### FUNctions 
They may look scary at first but they are your friend we use them to assign them a set of code that we want to run more than once through the code and that will save us alot of time in the long run .
first of you need to declare a function  by giving it a name  about what it does and entering the lines of code it contains, the seconed step is calling it "use it " in the place you want it to run . some function need inserted values to run some don't .

## Pair programming 


Iterative loops. Code reviews. Fast feedback. Error checking and linting. These are software engineering practices that have proven to dramatically improve the quality of code developers produce.pair programming is the practice of two developers sharing a single workstation to interactively tackle a coding task together.
Pair programming consist of two people as the name implies a driver who does the coding and version control and the navigator who aids him by thinking about the bigger piture and how an algorithm might be converted in to code, while scanning for typos or bugs .
While learning to code, developers likely study several programming languages. Similar to a foreign language class, there are four fundamental skills that help anyone learn a new language: Listening: hearing and interpreting the vocabulary Speaking: using the correct words to communicate an idea Reading: understanding what written language intends to convey Writing: producing from scratch a meaningful.
