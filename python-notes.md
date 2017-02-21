# Python notes on udacity
## Introductions
### What should I know? 
*If and else statements*

An **else** statement can be combined with an **if** statement. An **else** statement contains the block of vode that executes if the conditional expression in the if statement resolves to 0 or a FALSE value. 
The **else** statement is an optional statement and there could be at most only one 'else' statement following **if.**

if <test expression>:
  <statement>
else:
  statement (s)
  
  
Block is the code that will run when the test expression is true. If it doesn't evaluate to true, the block doesn't execute. 

i = 21

def absolute (x):

if x<0:

  x = -x
  
return x


Quiz: define bigger. 

def bigger(x, y): 
  if x>y:
    return x
  return y
  

*Function definitions*
Procedure is something that takes input in, does some work on those inputs, and produces outputs. Allows a small amount of code to do a bunch of different things. 


inputs are just a list of names followed by commas. () no input. (page) one input. (a, b, c, d) 4 inputs. 

block is the body of the procedure. indented inside the definition. (4 spaces is the convention in python)

def <name> (parameters):
  
  <block>
  
  everything indented is in the block. 
  
  ###What will we learn? 
  -Functions, for ex. print "Hello World"
  -new Ideas (lessons 2 and 3). Classes and object oriented programming. 
  
