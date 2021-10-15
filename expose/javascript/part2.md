Q1: It printed '3' since here i was declared using 'var', so i can stilled be referred outside the for loop.

Q2: It printed '150' since the last iteration of for loop
was processing the discountedPrice of 300, and discountedPrice was declared using 'var' so can be referred outside the for loop. Hence the value of discountedPrice was 300 * 0.5 = 150 and was printed.

Q3: It printed '150' since it was lastly updated in the last iteration of the for loop which was processing '300'. Also finalPrices was declared using 'var', so it can be
referred outside the for loop and thus '150' was printed.

Q4: The function returned an array [ 50, 100, 150 ]. In the function, these values were stored in the array 'discounted'. Each discounted values were pushed into discounted in each interation of for loop. There were
three iterations and so discounted has three corresponding
discounted value of the orginal input values.

Q5: There was a Reference error since i in this case was declared using 'let', so it was only visible inside the for loop and cannot be referred outside the loop.

Q6: There was a Reference error since discountedPrice in this case was declared using 'let', so it was only visible inside the for loop and cannot be referred outside the for loop.

Q7: It printed '150' since finalPrice was declared and referred in the same scope, so there was no reference error here.

Q8: It also returned an array [ 50, 100, 150 ]. Though the array discounted was declared using 'let', it was updated in the for loop and the value of the updated version was directly returned by the function.

Q9: There was a Reference error since i in this case was declared using 'let', so it was only visible inside the for loop and cannot be referred outside the loop.

Q10: It printed '3'. In this case the declaration of the constant variable length was in the same scope as the line printing this variable, so there was no reference error. Also, since length was never reassigned, there was no erro due to reassignments.

Q11: It also returnd an array [ 50, 100, 150 ]. Though the array discounted was declared with 'const' here, it is allowed to update the array since the restriction to constant variables is that it cannot be reassigned. Therefore, the function returned the final version of the array discounted which was updated through the for loop.

Q12A: student.name
Q12B: student["Grad Year"]
Q12C: student.greeting()
Q12D: student["Favorite Teacher"].name
Q12E: student.courseLoad[0]

Q13A: '32'. Since integer 2 would be mapped to its correpsonding string representation and concatenated with the string '3'.
Q13B: 1. '3' in this case was converted from string to integer, and then applied arithmetic operation on it and 2 so the answer was integer 1.
Q13C: 3. Since null was converted to integer 0, the calculation became 3 + 0 which is 3.
Q13D: '3null'. In this case the string 3 was concatenated with 'null' which was converted from null.
Q13E: 4. Since true was converted to integer 1, 3 + 1 is 4.
Q13F: 0. In this case it did arithmatic on false and null, where both of them were converted to integer 0, so the answer was 0.
Q13G: '3undefined'. Similar to null, undefined was directly converted to its corresponding string and concatenated with 3.
Q13H: NaN. '3' was converted to integer 3 but undefined was NaN based on numeric conversion rules so subtracting 3 with NaN gave NaN.

Q14A: True. '2' was converted to integer 2, and as 2 is definitely greater than 1, it returned true.
Q14B: False. '2' < '12'. Since both are strings, it did string comparison instead of numeric comparison. In this case '2' as string is greater than '1' (based on ascii code), so the result was false. 
Q14C: True. '2' was converted to integer 2, so they're the same, thus evaluating to true.
Q14D: False. This statement was evaluated without converting '2' to integer 2, so since they have different types, it evaluated to false.
Q14E: False. In this case true was converted to integer 1 and since 1 is not equal to 2 so outputing false.
Q14F: True. According to boolean conversion rules, values other than "empty" values are converted to true, so Boolean(2) is true and thus the statement was evaluated to true.

Q15: == compares two vlaues and applied type conversion if necessary, while === compares two values without applyting type conversion.

Q17: [2, 4, 6]. After going into modifyArray(), a new array newArr was created. Then in each iteration of the for loop, the function callback, which in this case is doSomething(), was called. Each element of array then
was passed into doSomething() and the value of a double of the element passed was returned. The returned values were stored in newArr and finally the function returned newArr. Therefore, the returned array was an array with each of its value is the double of the corresponding value in [1, 2, 3].

Q19: Output is
                1
                4
                3
                2