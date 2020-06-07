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
![Image]data:image/png;base64,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)

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
