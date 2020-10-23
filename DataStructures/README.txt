This code is for checking if the given expression is valid or not.
It uses stacks data structure for diong it. 
If it detects an open bracket than pushes it into the stack until it founds the closing bracket.
Once it gets the closing bracket it pops i.e. takes the top most element of the stack(which will be the opening bracket). 
And if it is the corressponding opening bracket than the flag changes to 0, which was declared 1 before.
so at the end if the top =-1 as well as the flag is 1, then the expression is valid and ivalid in all other cases.