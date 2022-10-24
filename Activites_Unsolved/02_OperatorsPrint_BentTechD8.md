# Quick Reference Guide - Lesson 02 - Let's go!

## Hot Topics:

## Operators
 
Arithmetic | Operators| Example  |
| -------- |:-----------:|  -----------| 
| Addition | | + | | 2 + 2 |
| Subtraction | | - | | 8 - 4 |
| Multiplication | | \* | | 4 \* 4|
| Divison | | / | | 12 / 3 |
| Modulus | | % | | 13 % 3 |
| Exponentiation | |\*\* | | 2\*\*4| 
| Floor | | // | | 13 // 3|


 ## More on print

You will see many cool and wild things following the print function. Some refer to methods used prior 3.6 formatting within print

-  **Example - print with end**: 
 
	` print("This is a test", end="!!")`

-  **Example - print with sep**:  

	`print("This is a sep test","More sep Test", sep="!!")`

-  **Example print with end and sep**: 

	`print("This is a test","More test", sep="!!",end="$$$")`


### Printing with variables (sort of legacy...but still used often)

Since you know what variables are, you might as well use them everywhere you can!

-  **Example - print with variable**: 
 
	` var1 = "test"`

	`print("this is a %s" % var1)`

-  **Example - print with multiple variables:**

	`var2 = 3`
	
	`print("this is a %s %d" % (var1,var2))`

-  **Example print with end and sep**:
 
	`print("This is a test","More test", sep="!!",end="$$$")`

### Printing with variables by calling directly (used often)

You can indeed call on variables, with minor formatting.

-  **Example - print with variable**: 
 
	` var1 = "test"`

	` print("this is var1:", var1, "--followed by more text")`

-  **Example - print with multiple variables:**

	`var2 = 3`
	
	`print("this is var1:",var1,"and this is var2:",var2`

### Python 3.6 introduces f-strings, very clean and readable

Here are some examples of f-strings.

-  **Example - print f-string with variable**: 
 
	` var1 = "test"`

	` print(f"This is a {var1}")`

-  **Example - print f-string with multiple variables:**

	`var2 = 3`
	
	`print(f"This is a {var1} and now {var2}")`

# ===================================
    
-------

## Copyright

BentTechD8 is a proud partener of Hardbit Solutions LLC © 2022. All Rights Reserved.
