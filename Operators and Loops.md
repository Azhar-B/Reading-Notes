# Operators and Loops

## Operators

### Comparison Operators: Evaluating Conditions

You can evaluate a situation by comparing one value in the script to what you expect it might be. The results will be Boolean: true or false.

== is equal to. This operator compares two values (numbers, strings, or Booleans) to see if they are the same. 

!= is not equal to. This operator compares two values (numbers, strings, or Booleans) to see if they are not the same.

Programmers refer to the testing or checking of a conditions as evaluating the condition. Conditions can be much more complex than those shown here, but they usually result in a value of true or false. 

There are a couple of notable exceptions: i) Every value can be treated as true or false even if it is not a Boolean true or false value. ii) In short-circuit evaluation, a condition might not need to run. 

> is greater than. This operator checks if the number on the left is great than the number on the right. 

< is less than. This operator checks if the number on the left is less than the number on the right. 

>= is greater than or equal to. This operator checks if the number on the left is greater or equal to the number on the right. 

<= is less than or equal to. This operator checks if the number is less than or equal to the number on the right.

### Structuring Comparison Operators

In any condition, there is usually one operator and two operands. The operands are placed on each side of the operator. They can be values or variables. You often see expressions enclosed in brackets.

### Using Expressions With Comparison Operators

The operand does not have to be a single value or variable name. An operand can be an expression (because each expression evaluates into a single value)

### Logical Operators

Comparison operators usually return single values of true or false. Logical operators allow you to compare the results of more than one comparison operator.

&& is Logical And. This operator tests more than one condition.

|| is Logical Or. This operator tests at least one condition. 

! is Logical Not. This operator takes a single Boolean value and inverts it. 

## Loops

Loops check a condition. If it returns true, a code block will run. Then the condition will be checked again and if it still returns true, the code block will run again. It repeats until the condition returns false. There are three common types of loops:
1. **For**
    * If you need to run code a specific number of times, use a **for** loop. In a **for** loop, the condition is usually a counter which is used to tell how many times the loop should run.
        * Initialization is creating a variable and set it to zero. This variable is commonly called i and it acts as the counter.
        * Condition: the loop should continue to run until the counter reaches a specific number.
        * Update: Every time the loop has run the statements in the curly braces, it adds one to the counter. 
2. **While**
    * If you do not know how many times the code should run, you can use a **while** loop. Here the condition can be something other than a counter, and the code will continue to loop for as long as the condition is true.
3. **Do While**
    * The **do while** loop is very similar to the **while** loop, but has one key difference: it will always run the statements inside the curly braces at least once, even if the condition evaluates to false.

