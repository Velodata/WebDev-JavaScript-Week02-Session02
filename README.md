# Week 02 - Data Types & Operators

Welcome to Week 02, Wednesday Session 02!

Thanks to a public Holiday, we didn't get to do Monday's session.

Hence we'll be covering a fair bit tonight.

In JavaScript, we has several different data types. If you're a student, you must understand them before you can become good at the language. Let's
go through each data type, especially the concept of the Boolean (true or false) arguement.

## 📌 JavaScript Strings

-   A string (or a text string) is a series of characters like `John Doe`
-   Strings are written with quotes. You can use single or double quotes:
-   For example:

    ```js
    // Using double quotes:
    let carName1 = "Volvo XC60";

    // Using single quotes:
    let carName2 = "Volvo XC60";
    ```

-   You can use quotes inside a string, as long as they don't match the quotes surrounding the string:

-   For Example: You can double quotes insides single quotes, or single quotes inside double quotes:

    ```js
    // Single quote inside double quotes:
    let answer1 = "It's alright";

    // Single quotes inside double quotes:
    let answer2 = "He is called 'Johnny'";

    // Double quotes inside single quotes:
    let answer3 = 'He is called "Johnny"';
    ```

## 📌 JavaScript Numbers

-   All JavaScript numbers are stored as decimal numbers (floating point).
-   Numbers can be written with, or without decimals:
-   For example: The following statements are equivalent in JavaScript:

    ```js
    // With decimals:
    let x1 = 34.0;

    // Without decimals:
    let x2 = 34;
    ```

    ### Exponential Notation

    Extra large or extra small numbers can be written with scientific (exponential) notation:

    A good practice is to put spaces around operators ( = + - \* / ):

    For example:

    ```js
    let y = 123e5; // 12300000
    let z = 123e-5; // 0.00123
    ```

    ### the JavaScript Big Integer

    By default, all JavaScript numbers are stored in a 64-bit floating-point format.

    However, a new datatype (ES2020) was recently introduced which can be used to store integer values that are
    too big to be represented by a normal JavaScript Number.

    For example:

    ```js
    let x = BigInt("123456789012345678901234567890");
    ```

## 📌 JavaScript Booleans

-   Booleans can only have two values: true or false.
-   Booleans are super important to understand in the logic of passing an argument. For example, is a password entered true or false? In the example of tasks an incomplete task is considered false and a complete task is considered true.

    For example:

    ```js
    let x = 5;
    let y = 5;
    let z = 6;
    if (x == y) {
    	return true;
    }
    if (x == z) {
    	return true;
    } else {
    	return false;
    }
    ```

## 📌 JavaScript Arrays

-   Without exception, JavaScript arrays are ALWAYS written with square brackets.
-   Array items are separated by commas
-   The following code declares (creates) an array called cars, containing three items (car names):

    ```js
    const cars = ["Saab", "Volvo", "BMW"];
    ```

## 📌 JavaScript Objects

-   JavaScript objects are written with curly braces {}.
-   Object properties are written as name:value pairs, separated by commas

    For example: The object (person) in the example below has 4 properties: firstName, lastName, age, and eyeColor.

    ```js
    const person = {
    	firstName: "John",
    	lastName: "Doe",
    	age: 50,
    	eyeColor: "blue",
    };
    ```

## 📌 The typeof Operator

-   You can use the JavaScript typeof operator to find the type of a JavaScript variable.

    For example:

    ```js
    typeof ""; // Returns "string"
    typeof "John"; // Returns "string"
    typeof "John Doe"; // Returns "string"
    ```

## 📌 Undefined

-   In JavaScript, a variable without a value, has the value `undefined`. The type is also `undefined`.

    ```js
    let car; // Value is undefined, type is undefined
    console.log("typeof(car) === ", typeof car);
    ```

# Week 02 - Part 2: Symbols and operators

In JavaScript we use certain symbols and operators as commands that perform functions. Students need to understand the concept of what an `=` means (single equals) as well as what `==` means (double equals )means. Explaining the symbols and operators is important to understand assigning and command values.

## 📌 JavaScript Assignment

-   The Assignment Operator (=) assigns a value to a variable:

    For example:

    ```js
    let x = 10;     

    let x = 5;       // Assign the value 5 to x

    let y = 2;       // Assign the value 2 to y

    let z = x + y;   // Assign the value x + y to z:
    ```


## 📌 JavaScript Addition

-   The Addition Operator (+) adds numbers:

    For example:

    ```js
    
    let x = 5;
    let y = 2;
    let z = x + y;
    ```

## 📌 JavaScript Multiplication

-   The Multiplication Operator (*) multiplies numbers:

    For example:

    ```js
    
    let x = 5;
    let y = 2;
    let z = x * y;
    ```

## 📌 Types of JavaScript Operators

-   There are different types of JavaScript operators:

    • Arithmetic Operators

    • Assignment Operators

    • Comparison Operators

    • String Operators

    • Logical Operators

    • Bitwise Operators

    • Ternary Operators

    • Type Operators



## 📌 JavaScript Arithmetic Operators

-   Arithmetic Operators are used to perform arithmetic on numbers:

    For example:

    ```js
    
    let a = 3;
    let x = (100 + 50) * a;
    ```

    +       Addition
    -       Subtraction
    *       Multiplication
    **      Exponentiation (ES2016)
    /       Division
    %       Modulus (Division Remainder)
    ++      Increment
    --      Decrement

## 📌 JavaScript Assignment Operators

Assignment operators assign values to JavaScript variables.

The Addition Assignment Operator (+=) adds a value to a variable.

    For example:

    ```js
    
    let x = 10;    // first we let x equal 10
    x += 5;        // and then we add another 5 to the vaue of x
    ```




## 📌 JavaScript Comparison Operators

**Operator    Description**
==          equal to
===         equal value and equal type
!=          not equal
!==         not equal value or not equal type
>           greater than
<           less than
>=          greater than or equal to
<=          less than or equal to
?           ternary operator



## 📌 JavaScript String Comparison

All the comparison operators above can also be used on strings:

    For example:

    ```js
    let text1 = "A";
    let text2 = "B";
    let result = text1 < text2;
    ```

## 📌 JavaScript String Addition

## 📌 Adding Strings and Numbers

## 📌 JavaScript Logical Operators

## 📌 JavaScript Type Operators

## 📌 JavaScript Bitwise Operators

## 📌 JavaScript Logical Operators

## 📌 JavaScript Logical Operators

| Keyword  | Description                                                       |
| -------- | ----------------------------------------------------------------- |
| Jvar     | Declares a variable                                               |
| let      | Declares a block variable                                         |
| const    | Declares a block constant                                         |
| if       | Marks a block of statements to be executed if a condition is true |
| switch   | Marks a block of statements to be executed in different cases     |
| for      | Marks a block of statements to be executed in a loop              |
| function | Declares a function                                               |
| return   | Exits a function                                                  |
| try      | Implements error handling to a block of statements                |
