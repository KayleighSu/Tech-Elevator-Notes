# Intro to JavaScript

In this Unit, you will study how to translate the algorithm design from a process diagram into program code for the computer. You'll write specific instructions for your computer, then ask the computer to follow - or execute - those instructions. This is computer programming.

Programmer > Creates Source Code > Compiler > Creates Binary > Computer Executes Binary Code

## Variables
In a process diagram, varibales are used to track the data in an algorithm. These variables have names and hold values that "vary" or change. In code, every program uses data in some way.

JavaScript takes the value that's on the right side of the assignment operator (=), and assigns it to the variable that's on the left side of the =.

---
*Example:*

let name = 'Sam';

let = Declarative statement

name = variable being assigne to

'Sam' = what the variable becomes

*Note:* The variable value is in single quotes. When you want to use words, or character data, you must enclose them in quotation marks. These are called **literal values** or **literals**

---

You can also change the value of a variable!

If changing the value, you don't use "let" again. You can only delcare a variable once!

When you define a variable without assigning a value, its value is equal to "undefined"

The declarations of constants are really similar to the declarations of variables with three key differences:
1. You declare constants with "const" not "let"
2. You **must** initialize it (set its value in the declaration)
3. By convention, you write names for constants in all uppercase with underscores separating the words, like: DAYS_PER_WEEK.

## Variable Naming
One of the golden rules in programming is to always give your variables and constants meaningful names.

Naming Rules:
- Names consist of letters A-Z, a-z, characters _, $, and digits 0-9.
- Names must start with a letter, _, or $.
- Names are case-sensitive
- Names may not be a JavaScript reserved keyword. (let/const)

## Naming Conventions:
Naming conventions are not enforced by a computer, but they are important for improving understanding and code readability.
- camelCase
- UPPER_SNAKE_CASE
- PascalCase
- lower_snake_case

*Note:* _ and $ are the only special characters allowed in names. JavaScript names cannot begin with a number.

## Data Types
Compilers store information in memory using only 0's and 1's. These numbers are binary digits, or **bits**. To interpret what those bits actually mean in a program, JavaScript must know what type of data the bits represent.

*Example:*

Suppose the variable refers to memory containing these bits: 01000001.
- In alphabetical data, this value is the letter "A".
- If the variable holds numeric data, then the value equates to the number 65.

*Note:* Although you can use either single or double quotes for string literals, single quotes are preferred. However, if the literal value includes an apostrophe or a single quote, you might find it easier to use double quotes.

*Example:*

'foo' "bar" '1234' 'Hello, Sam'

The end quotation marks must match the one used at the beginning.

*Note:*
It's best practice to name Boolean variables starting with is, has, does, or some other word that makes the variable read like a yes-or-no question.

---

*Object Example:*

let foo; // foo is underfined

foo = 42; // foo is a number

foo = 'Steve'; // foo is a string

foo = true; // foo is a Boolean

---

In programming, you often need to track complex entities, like a weather forcast, which incluides multiple characteristics. In JavaScript, you can bundle all of these properties into a single variable by using the **object** data type.

The curly braces contain a set of property names and their corresponding values, each name-value combination separated by a comma ",". Whithin each name-value combination, a colon ":" separates the property name from its value.

---

*Example:*

//Declare and assign the forecast object

let forecast = {

    description: 'Mostly Cloudy',
    
    currentTemperature: 36,

    highTemperature: 44,

    lowTemperature: 32,

    changeOfPrecipitation: 65,
};

// Change the description to a more optimistic viewpoint

forecast.description = 'Partly sunny';

// Print the forecast

console.log('Today it will be ' + forecast.description + 'with a ' forecast.changeOfPrecipitation + '% change of precipitation');

*Note:*
Notice each of the object's properties has a data type, like other variables:

forecast = object

forecast.description = string

forecast.currentTemperature = Number

---


