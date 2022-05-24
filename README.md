[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=7618055&assignment_repo_type=AssignmentRepo)
# Project Instructions
Follow the instructions here: https://vuxcode.netlify.app/2022vt/pr1/lessons/major-project-brief/

REMEMBER TO "COMMIT" YOUR CHANGES REGULARLY TO SHOW HOW YOU HAVE BUILT THIS PROJECT! 

The final program is not the goal! The aim of the project is to show how you have developed your program, the steps you have taken and the problems you have solved!

# Project Notes

> You can use this section of the file to keep notes about your project as you work on it.

# Project Summary

I decided that my final project will relate to calculation and mathematical operations. From the first view, it seemed to be a simple program, but when I began writing it, I was about to quit. It appeared to be not so easy, as for me. But, anyway, here is it and it is different from what I draw in my plan. I lack necessary knowledge to make the calculator more realistic with even buttons and highlighted display.  
I made it simple without advanced functions and graphics. It can add two numbers, divide, multiply and subtract as well as to count in percentage. Firstly, I didn’t consider adding buttons M+ and M-, but as I had some time more, I tried and hope it works. Unfortunately, I couldn’t add calculations of decimals as I wanted in my plan. I faced a problem, when a dot wasn’t displayed on the screen, so I saved this question for later, but it’s still unresolved.
Everybody knows how to use a calculator, so I didn’t prepare some specific instruction to it. In case user presses a wrong number or sign, there is button “C”, that completely deletes all information from the display. I also tried to consider all mistakes, that can arise, when using the program. So, it won’t be possible to enter any math. operator until it is entered any number first as well as one more operator won’t be displayed after a second input number, but only a result after having pressed the button “=” or “%”. The same goes to the button “=”, that is impossible to click in another place, but only after input math. expression. The sign “%” allows us to do calculations in percentage, both to convert a single number and to use it in calculations. There is no need to press “=”, because after the sign “%” is pressed a result directly appears on the display. And buttons memory M+ and M-. As in usual calculator, M+ will save gotten result for to extract it later in calculations by using M-. 
Briefly about the code. It consists mostly of if/else statement because this method helped me to exclude mistakes and collapse in calculation functions. There are numbers of options to create a calculator, but I started using if/else, that includes many specific conditions, and continued by using the same principle.
In the beginning I added two global variables with empty arrays inputNumber1 and inputNumber2 for to save numbers. I used for it method push(). Then there are also two global variables joinNumber1 and joinNumber2 to store data from the arrays as numbers. For this purpose I used method join() and Number to convert the values to numbers. As well it was added empty variables sign (for math. operator), result and memory.
Function input. A number, that user enters, will be displayed on the screen. If there is no sign yet, it will be a first number, otherwise - a second. 
Function operator. If there is a result from previous calculations, that is equal to “ERROR!”, then by pressing any operator button nothing will happen. Moreover, the operator buttons will work only if there is not another earlier input operator. 
Function empty. I added this function to remove all data from the arrays and respective variables after getting a result, as by starting calculations from the beginning it’ll refer to earlier saved information there and break the program. 
Function equal. It’ll perform math. operation and get out a result, depending on input operator. The function will work only if user enters a second number of math. expression. By dividing by 0 user will see an error on the screen, otherwise it’ll be an ordinary numerical result.
Function percentage. As all functions above, this one also is restricted with conditions and works only after a single number, either first entered number or result, to convert it or if there is need to use percentage in calculations, then it will work according to the principle of function “equal”.
Function del. By pressing the button “C” all information from the screen as well as from arrays and respective variables will be cleared.
Function memoryEnt. It is pointless to save input numbers in memory so the function will work in case there is a result, that needs to be stored for further calculations.
Function memoryExt. If user hasn’t entered any first number yet, so by pressing the button M- it’ll be gotten previously saved result on the screen first. By having already any number and operator on the screen the function will output on the display previously saved result as a second number in the math. expression.
  


# User Guide

> Write a clear user guide for how someone should use your program.
