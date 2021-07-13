**Programming with Javascript**

Introduction-
- Learning to program with JavaScript involves:
    1. Understanding basic programming concepts and terms used to describe JS codes.
    2. Learning the language itself and its vocabulary, and structuring of sentences or lines.
    3. Becoming familiar with how it is applied by looking at examples of how JS is commonly used in websites today.

- JS makes a webpage more interactive by accessing and modifying the content while the web page is live and being viewed.
- you can use JS to select any element, attribute, or text from an HTML page. This way, you can provide a single script to multiple elements or attributes 
that are similar.
- You can also specify a set of steps or rules for the browser to follow, which allows it to access or change the contents of a page.
- JS can make the webpage feel interactive by responding to what the user does.
- HTML is the base language that shows the raw data on your website,
CSS is used to style your website and give structure to how it looks, and /Javascript/ gives functionality to your website.
- HTML provides content to a page to describe it's structure just like on a wireframe. An element of HTML consists of the opening and closing tags.
- Some tags like images don't have an opening and closing tag, they have one self-closing tag.
Example:  p class="fruit">peach< p enclosed in <>. The first part is the attribute name "p class", and the second part is the attribute value "fruit". It opens with 'p' and closes with 'p' as well.
- CSS uses rules to indicate how the contents of one or more elements should be displayed in the browser. Each rule has a selector and a declaration block.
- The CSS selector indicates which elements the rule applies to. The delacaration block contains rules that indicate how those elements should appear.
Example: .fruit {color: pink;}
- ABC of programming: A-What is a script and how do I create one? B-How do computers fir in with the world around them. C-How do I write a script for a web page?
    Once you have learned the basics, you can easily learn how to use JS to tell browsers what you want them to do.
- What is a script? A script is a series of instructions that a computer can follow to achieve a goal. You could compare scripts to recipes, handbooks, or manuals. Scripts are made up of step-by-step instructions that the computer can follow. To write a script, you first need to state your goal and then list the tasks needed to be completed in order to reach that goal. Define the goal>Design the script>Code each step. A script is built similar to a step-by-step flow-chart. 

Expressions-
- An expression evaluates into (results in) a single value. Broadly speaking, there are two types of expressions.
- Expression examples: var color = 'beige'; assign a value to a variable, which would be color beige.
- Expression examples: var area = * 2;. Uses two or more values to return a single value, which would be 6 in this case. The variable name is "area".
- Expressions rely on operators; they allow programmers to create a single value from one or more values. The operator in the examples above is "=".
- String Operator: There is only one string operator, it is the "+" sign; it is used to string together multiple value into one.

Functions-
- Functions consist of a series of statments that have been grouped together because they perform a specific task.
- If different parts of a script repleat the same task, you can reuse the function (rather than repeating the same set of statements).
- The steps that the function needs to perform in order to perform its tasks are packaged up in a code block. A code block consists of one or more statements contained within curly braces. (You do not write a semicolon after the closing curly brace - unlike a statement).
- When you write a function and you expect it to provide you with an answer, the response is known as a return value.
- The statements in a function are not always executed when a page loads, so functions also offer a way to store the steps needed to acieve a task.
- If you are going to ask the function to perform its taks later, you need to give it a name. That name should describe the task it is performing. When you ask it to perform its taks, this is known as calling the function.
- Function Example: var msg = 'Sign up to receive our newsletter for 10% off!';
                    function updateMessage() {
                        var el = document.getElementById('message');
                        el.textContent = msg;
                    }
                    updateMessage();
Declaring a function-
Example: function sayHello() {
           document.write('Hello!');
         }
"function" is the keyword while "sayHello" is the function name that you had named before. The code block is in curly braces.

Calling a function-
After you have declared your function, you can call (use) it where you want. In this case, calling it would be sayHello();
