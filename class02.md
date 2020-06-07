# Read: 02 - HTML Text, CSS Introduction, and Basic JavaScript Instructions
## Text 
When creating a web page, you add tags (known as markup) to the contents of the page. These tags provide extra meaning and allow browsers to show users the appropriate structure for the page.
1. Structural markup: the elements that you can use to describe both headings and paragraphs
- Headings
  ```<h1>This is a Main Heading</h1>
   <h2>This is a Level 2 Heading</h2> 
   <h3>This is a Level 3 Heading</h3> 
   <h4>This is a Level 4 Heading</h4> 
   <h5>This is a Level 5 Heading</h5> 
   <h6>This is a Level 6 Heading</h6> ```

 - paragraph : a browser will show each paragraph on a new line with some space between it and any subsequent paragraphs.
  - Bold 

```<p>This is how we make a word appear <b>bold.</b>  </p> <p>Inside a product description you might see some   <b>key features</b> in bold.</p>  ```
 - Italic 

 ``` <p>This is how we make a word appear <i>italic</i>.  </p> <p>It's a potato <i>Solanum teberosum</i>.</p> <p>Captain Cook sailed to Australia on the   <i>Endeavour</i>.</p>  ```
 - superscript and subscript 
 
 ``` <p>On the 4<sup>th</sup> of September you will learn   about E=MC<sup>2</sup>.</p> <p>The amount of CO<sub>2</sub> in the atmosphere   grew by 2ppm in 2009<sub>1</sub>.</p> ```
 - White space : Any white spaces areas in a normal p tag while collapse onitself and it will look normal like there is only one space .
 - line Breaks & HorizonTal rules : break br tag will end the line and start a new line the hr tag will draw a horzintal line .
 
1. Semantic markup:  which provides extra information; such as where emphasis is placed in a sentence, that something you have written is a quotation (and who said it), the meaning of acronyms, and so on.
- Strong and emphasis : strong will apear in bold and em element is for emphasis wil show in  italic
- Citation & defination : When you are referencing a piece of work such as a book, film or research paper, the  cite element can be used to indicate where the citation is from,The first time you explain some new terminology (perhaps an academic concept or some jargon) in a document, it is known as the defining instance of it.
- Quotations : blockquotes for longer quotes and q for smaller ones .
``` <blockquote cite="http://en.wikipedia.org/wiki/ Winnie-the-Pooh">  <p>Did you ever stop to think, and forget to start    again?</p> </blockquote> <p>As A.A. Milne said, <q>Some people talk to   animals. Not many listen though. That's the   problem.</q></p> ```
## Introducing CSS
CSS is used to give style for every html tags ,those styles include but not limitd to font size and color ,background color ,borders,padding and aligning text and images . You can ad style either inline or internally or you can link an extrnal css to the html .

## baisc javascript 

What is javascript , It is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement. Statements should end with a semicolon. You should write comments to explain what your code does. They help make your code easier to read and understand. This can help you and others who read your code. 

``` /* This script displays a greeting to the user based upon the current time. It is an example from JavaScript & jQuery book */ 
var today= new Date(); // Create a new date object  
var hour Now = today.getHours(); // It Find the current hour
 var greeting; 
  // Display the appropriate greeting based on the current time
 if (hourNow > 18) { greet ing = 'Good evening' ; 
 else if (hourNow > 12) { greeting = 'Good afternoon';
  else if (hourNow > 0) { greeting= 'Good morning';
   else { gr eeting = 'Welcome'; } 
   document.write(greeting) ; 
   ```

A script will have to temporarily store the bits of information it needs to do its job. It can store this data in variables dontaed by var .Arrays are assigned like you assign any other variable ,variables in array are treated like  numbered list items and numbering in the list starts at zero .
## Decisions and loops
Sometimes you need to deciede what line is going to be excuted next depending on inputs that why we use operators for evaluating condations by comparing them to what they might be and taking actions depending on the results 
```
var pass = 50; II Pass mark var score = 90; II Score 
II Check if the user has passed var hasPassed = score >= pass; 
II W rite the message into the page var el = document.getElementByld('answer '); e1  . textContent = 'Leve 1 passed: ' + has Passed;  
```
there is a special type of operators which are logical opertarts that work around boolean data and give true or false depending on the comparison of two or more  results of comparison operators 
```
var scorel = 8; II Round 1 score var score2 = 8; II Round 2 score var passl 6; II Round 1 pass mark var pass2 = 6; II Round 2 pass mark II Check whether user passed both rounds , store result in variable var passBoth = (scorel >= passl) && (score2 >= pass2); 
II Create message var msg = 'Both rounds passed: ' + passBoth; 
II Write the message into the page var el = document.getElementBy!d( 'answer') ; el.textContent = msg; 
```
