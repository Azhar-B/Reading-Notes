# How Javascript Makes Web Pages More Interactive

1. Access Content
    * You can use JavaScript to select any element, attribute, or text from an HTML page. For example: 
        * Select the text inside all of the <hl> elements on a page 
       * Select any elements that have a class attribute with a value of note 
        * Find out what was entered into a text input whose id attribute has a value of email.
2. Modify Content
    * You can use JavaScript to add elements, attributes, and text to the page, or remove them For example: 
        * Add a paragraph of text after the first <hl> element 
        * Change the value of c 1 ass attributes to trigger new CSS rules for those elements 
        * Change the size or position of an <img> element
3. Program Rules
    * You can specify a set of steps for the browser to follow (like a recipe), which allows it to access or change the content of a page. For example: 
        * A gallery script could check which image a user clicked on and display a larger version of that image. 
        * A mortgage calculator could collect values from a form, perform a calculation, and display repayments. 
        * An animation could check the dimensions of the browser window and move an image to the bottom of the viewable area (also known as the viewport)

# Chapter One: ABC of Programming

## Script

A script is a series of instructions that a computer can follow to achieve a goal.

To write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it.

1. Define the goal
    * First, you need to define the task you want to achieve. You can think of this as a puzzle for the computer to solve.
2. Design the script
    * To design a script you split the goal out into a series of tasks that are going to be involved in solving this puzzle. This can be represented using a flowchart. You can then write down individual steps that the computer needs to perform in order to complete each individual task (and any information it needs to perform the task), rather like writing a recipe that it can follow.
3. Code each step
    * Each of the steps needs to be written in a programming language that the compu ter understands. In our case, this is JavaScript. As tempting as it can be to start coding straight away, it pays to spend time designing your script before you start writing it. 


## Expressions

An expression evaluates into (results in) a single value. Broadly speaking there are two types of expressions. 
1. Expressions that just assign a value to a variable. 
2. Expressions that use two or more values to return a single value.

### Operators

Expressions rely on things called operators; they allow programmers to create a single value from one or more values.
1. Types of Operators:
    * Assignment Operators assign a value to a variable.
        * Several arithmetic operations can be performed in one expression, but it is important to understand how the result will be calculated. Multiplication and division are performed before addition or subtraction.
        * To change the order in which operations are performed, place the calculation you want done first inside parentheses
    * Arithmetic Operators preform basic math.
    * String Operators combine two strings.
        * There is just one string operator: the + symbol. It is used to join the strings on either side of it. 
        * There are many occasions where you may need to join two or more strings to create a single value. Programmers call the process of joining together two or more strings to create one new string concatenation.
            * When you place quotes around a number, it is a string (not a numeric data type), and you cannot perform addition operations on strings.
            * f you try to add a numeric data type to a string, then the number becomes part of the string, e.g., adding a house number to a street name:
            * f you try to use any of the other arithmetic operators on a string, then the value that results is usually a value called NaN. This means "not a number." 
    * Comparison Operators compare two values and return true or false.
    * Logical Operators combine expressions and return true or false.

## Function

Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements).

To create a function, you give it a name and then write the statements needed to achieve its task inside the curly braces. This is known as a function declaration.

If asking the function to preform its task later, you need to give your function a name. That name should describe the task it is performing. When you ask it to perform its task, it is known as calling the function.

Some functions need to be provided with information in order to achieve a given task. Pieces of information passed to a function are known as parameters. 

When you write a function and you expect it to provide you with an answer, the response is known as a return value. 

When you call a function that has parameters, you specify the values it should use in the parentheses that follow its name. The values are called arguments, and they can be provided as values or as variables.

Some function return information to the code that called them.