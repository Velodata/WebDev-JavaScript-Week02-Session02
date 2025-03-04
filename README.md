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

-   For Example: You can double quotes insides single quotes,  or single quotes inside double quotes:

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

    By default,  all JavaScript numbers are stored in a 64-bit floating-point format.

    However, a new datatype (ES2020) was recently introduced which can be used to store integer values that are
    too big to be represented by a normal JavaScript Number.

    For example:

    ```js
    let x = BigInt("123456789012345678901234567890");
    ```
    





## 📌 JavaScript Line Length and Line Breaks

-   For best readability, programmers often like to avoid code lines longer than 80 characters. Although with large modern screens nowadays the need to do this is less common.
-   If a JavaScript statement does not fit on one line, the best place to break it is after an operator:

    For example:

    ```js
    document.getElementById("demo").innerHTML = "Hello Dolly!";
    ```

## 📌 JavaScript Code Blocks

-   JavaScript statements can be grouped together in code blocks, inside curly brackets {...}.
-   The purpose of code blocks is to define statements to be executed together.
-   One place you will find statements grouped together in blocks, is in JavaScript functions:
    For example

    ```js
    function myFunction() {
    	document.getElementById("demo1").innerHTML = "Hello Dolly!";
    	document.getElementById("demo2").innerHTML = "How are you?";
    }
    ```

## 📌 JavaScript Code Blocks

-   It's quite common for JavaScript statements to start with a keyword which identifies the JavaScript action to be performed.

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

## 📌 JavaScript Comments

-   Not all JavaScript statements are "executed".
-   Code after double slashes // or between /_ and _/ is treated as a comment.
-   Comments are ignored, and will not be executed:

    For example:

    ```js
    let x = 5; // I will be executed

    // x = 6; I will NOT be executed
    ```

## 📌 Multi-line Comments

-   Multi-line comments start with /_ and end with _/.
-   Multi-line comments happen when we comment out multiple lines of JavaScript.
-   Any text between /_ and _/ will be ignored by JavaScript.
-   This example uses a multi-line comment (a comment block) to explain the code:

    ```js
    /*
    The code below will change
    the heading with id = "myH"
    and the paragraph with id = "myP"
    in my web page:
    */
    document.getElementById("myH").innerHTML = "My First Page";
    document.getElementById("myP").innerHTML = "My first paragraph.";
    ```

## 📌 JavaScript Identifiers

-   Identifiers are JavaScript names.
-   Identifiers are used to name variables and keywords, and functions.
-   The rules for legal names are the same in most programming languages.
-   A JavaScript name must begin with:

    -   A letter (A-Z or a-z)
    -   • A dollar sign ($)
    -   • Or an underscore (\_)

-   Subsequent characters may be letters, digits, underscores, or dollar signs

    ### Special Note

    Numbers are not allowed as the first character in names.

    This way JavaScript can easily distinguish identifiers from numbers.

## 📌 JavaScript is ALWAYS Case Sensitive

-   All JavaScript identifiers are case sensitive.
-   For example: The variables `lastName` and `lastname`, are two different variables:

    ```js
    let lastname, lastName;
    lastName = "Doe";
    lastname = "Peterson";
    ```

## 📌 JavaScript and Camel Case

-   Historically, programmers have used different ways of joining multiple words into one variable name:

    ### Hypens - NOT ALLOWED

    first-name, last-name, master-card, inter-city

-   Hyphens are not allowed in JavaScript. They are reserved for subtractions.

    ### Underscore (allowed)

    first_name, last_name, master_card, inter_city.

    ### Upper Camel Case - aka Pascal Case (allowed)

    FirstName, LastName, MasterCard, InterCity

    ### Lower Camel Case

    firstName, lastName, masterCard, interCity

-   JavaScript programmers tend to use lower camel case that starts with a lowercase letter:

## 📌 JavaScript Character Set

-   JavaScript uses the Unicode character set.

-   Unicode covers (almost) all the characters, punctuations, and symbols in the world.

-   For a closer look, please study our Complete Unicode Reference.

## 📌 JavaScript Expressions

-   An expression is a combination of values, variables, and operators, which computes to a value.
-   The computation is called an evaluation.
-   For example, 5 _ 10 evaluates to 50:
    5 _ 10
-   Expressions can also contain variable values:
    x \* 10
-   The values can be of various types, such as numbers and strings.
    For example, "John" + " " + "Doe", evaluates to "John Doe":
    "John" + " " + "Doe"
