# Bug List

> Make a list of the things that don't work as expected. Keep a list of things that you have fixed and try to document how you solved them.

1. P.: How to save in the input line of calculator three or more input symbols in a row (not to change one for another), like this 3+5 or 4*7-3? S.: Store an empty array above the function, use an array function push(symbol) and join(array name) inside the function for to save all the input symbols in one line. 

2. P.: When using mathematical operators, I found that the solution above wouldn't work, as it's not possible to use a specific index to point on input numbers 1 and 2, as input number can consist of several digits. S.: To make the calculator work correctly it needs to be created separate arrays for each input number and then, as method join doesn't change the initial array, I added another variables to store joined arrays. 
