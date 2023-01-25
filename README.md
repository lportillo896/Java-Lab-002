# Java-Lab-002

## Variables, Types and Operators

Be able to explain what variables are. Understand variable types, allowed names, and valid values.
Know how to create and use string, integer, floating-point, and boolean variables.

### Part 1 - PricelessScript.java - [MasterCard YouTube Ad](https://www.youtube.com/watch?v=Q_6stXKGuHo)

The lab template contains a program that prints the following:
```
2 tickets: $28.00
2 hotdogs, 2 popcorn, 2 sodas: $18.00
1 autographed baseball $45.00
real conversation with 11 year old son: priceless
true
```

Ignore the code that you don't fully recognize and concentrate on changing the variables to alter the MasterCard *Priceless* script to say:
```
3 tickets: $42.00
3 hotdogs, 3 popcorn, 3 sodas: $27.00
2 autographed baseball $90.00
watching the Giants win: priceless
false
```

### Part 2 - Interpretation
Take note of the various variables and their data types. Write a brief summary in this section of the README.md file listing the:
* Variable name
* Its data type
* and example values you can assign them.

Next give TWO example variable names and TWO example variable assignments that are *WRONG* and explain why.
* Hint: your IDE can help you discover these!

### Part 3 - Bonus: Play around with Java String Format Specifiers.

Pick several of the Java format specifiers below and define variables of the correct type utilize *sout* and *String.format* to view the resulting formats.

![Format Specifiers](JavaStringFormatSpecifiers.png)

### Part 4 - Submission
* Just as you did last week (Reference the Lab video in your Week 1 module), create a Spring2023 feature branch of your code
* Commit your working code to your local copy
* Push it to your Remote/origin branch (i.e. GitHub: Spring2023 -> origin/Spring2023)
* Then issue a Pull request to my instructor branch
    * Make sure to save the Pull request URL and submit it for the lab.

### Interpretation of Variables

* The Integer variable has a data type "int". Values you can assign include 156 or 2 or 4862.
* The Boolean variable has a data type "boolean" Values you can assign include true or false.
* The Double Precision Floating Point variable has a data type "double". Values you can assign include 46.0 or 157.55 or Math.PI
* The 32 Bit Floating Point variable has a data type "float". Values you can assign include 25.0f or 257.5f
* The String variable has a data type "String".  Values you can assign include "Hello world!" or "123".

### Examples of Wrong Variables

1. int dogs = two;

This is incorrect because the Integer variable type "int" can only accept whole numbers such as 1 or 10.  It can't accept characters or strings of characters.

2. boolean trueOrfalse = yes

This is incorrect because the Boolean variable type "boolean" can only store "true" or "false".  It won't accept other characters or integers such as 1 or "no".