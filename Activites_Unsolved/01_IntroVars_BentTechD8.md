# Quick Reference Guide - Lesson 01 - Let's go!

## Hot Topics:

**Python** is a high-level, general purpose programming language used for a variety of applications. Python `modules`, refered to as `files` have the format and extention of `filename.py` 
 - **Example**:  
 
	`GatherUserData.py`

A **Program** is a series of **instructions** to perform specific tasks
-  **Example**: 
	```
	# Script to print to screen:
	print(f"hello world")
	``` 

A **Comment** should state the **why** of the code below the comment.  Comments start with the `#` character, known as a  `hashtag`  or  `octothorpe`.

-  **Example**:  
```bash 
    # Wayne does NOT think this line belongs here, ask him why
```

**Variable**, data stored/assigned in a named memory location which can be referenced/called/altered.

-  **Example**: In this example `fname` is a **variable** used to store the value`Wayne`.
```bash 
    fname = "Wayne"
``` 

### Variable Types

- **String Variable**: A string variable is any collection of characters surrounded by a single or double quotation mark. 
					   Strings can contain integers/numbers within them but these are seen as characters without any numeric value, just a symbol.
	-  **Example**:   **Wayne** is a **string** variable.

	```bash 
		# String variable Example
		name = "Wayne"
	```

- **Integer Variable**: An integer variable stores a whole number (0, 1, 10, -100). Integers can be positive or negative and any length.

	- **Example**:  In this example we assign the value **101** to  `age`.

	```bash 
	# Variable Assignment Integer
	age = 10
	```

- **Float Variable**: A float is an integer with a decimal point. They are different from integers in that integers have to be whole numbers while floats can contain decimals within them.

	- **Example**:  Here we assign the value **6.25** to `grams`.

	```bash 
	# Floats, not a rootbeer float
	grams = 6.25
	```

- **Boolean Variables**: Boolean variables have the value of `True` or `False`.

  - **Example**:  In this example we assign the value **True** to `replay`.

	```bash 
	# Booleans
	replay = True
	```

- **More Complex Variable Types to Come!**


### Python Functions        

#### help() - Best help is self help! 
  - **Example**:
	```bash 
	help(ENTER FUNCTION NAME HERE)
    help(print)
	```

#### type() - Since python leverages OOP, knowing what type of oject you are dealing with helps 
  - **Example**:
	```bash 
	type("ThisIsAString")
    type(print)
	```
#### print() - Print lines to the standard output / console
  - **Example**:
	```bash 
    print(f"hello world")
	```

#### input() - Prompt for user input to store in a variable
  - **Example**:
	```bash 
    fname = input ("What is your first name? ")
    print("Hello" + fname)
	print(f"Hello {fname}")
	```

#### str() String conversion
  - **Example**:
	```bash
    age = 41
    start = "My age is "
    sentence = start + str(age)
	print(sentence)
	```
-------

## Copyright

BentTechD8 is a proud partener of Hardbit Solutions LLC © 2022. All Rights Reserved.
