# Bug List

> Make a list of the things that don't work as expected. Keep a list of things that you have fixed and try to document how you solved them.

1. P.: How to save in the input line of calculator three or more input symbols in a row (not to change one for another), like this 3+5 or 4*7-3? S.: Store an empty array above the function, use an array function push(symbol) and join(array name) inside the function for to save all the input symbols in one line. 

2. P.: When using mathematical operators, I found that the solution above wouldn't work, as it's not possible to use a specific index to point on input numbers 1 and 2, as input number can consist of several digits. S.: To make the calculator work correctly it needs to be created separate arrays for each input number and then, as method join doesn't change the initial array, I added another variables to store joined arrays. 

3. P.: After gotten calculation result it's not possible to enter new numbers to do new calculation from the beginning, as it continues to fill existing arrays from previous calculations.  S.: To solve this problem, in the function operator I set array's length for both input numbers to zero as well as var sign with operator. Such way it'll empty all previous arrays that will give a possibility to enter new numbers.  


4. P.: If to press any operator (+, -, * or /) first it'll display this sign in the beginning or if to press it when the second number has been entered it breaks the very expression.   S.: For the operator sign is displayed properly I added some conditions, using if statement, that will prevent user from the entering the sign twice or in a wrong place. 

5. P.: If to enter numbers for calculation from the beginning, there is no problem at all, but, if to continue counting by just adding an operator sign to result, gotten from previous calculation, the calculator begins to work incorrectly.   S.: I decided to create one more variable to store result of math. operations, then added a condition, that, if exactly this result takes part in further calculation, then it'll be saved as joinNumber1 firstly, thereby allowing other functionsto work properly.

 
