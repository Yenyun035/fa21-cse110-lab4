Q1: values added:  20

Q2: final result:  20

Q3: values added:  20

Q4: Nothing printed. ReferenceError: result is not defined. This is 
because a variable declared using 'let' is only visible inside its 
code block ({...}). In this case result is only visible inside the if statement.

Q5 & Q6: Nothing printed. TypeError: Assignment to constant variable. 
This is because a constant variable cannot be reassigned since it's 
considered 'unchanging' variable. Hence it raised an error since the 
program tried to assign the sum of num1 and num2 into it.
