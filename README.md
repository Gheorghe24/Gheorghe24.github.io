# My Personal Calculator
HTML/CSS & bit of Javascript
--------------------------------
Javascript Functions:
--------------------

Constructor : 
-----------
I save my previous and current operands

Clear : 
----------
I free my operands

Delete : 
------
Delete the last character(operand)

AppendNumber : 
--------------
Add to my current operand the input 

Choose operation : 
-----------------
Call my compute function and update my current,previous operands

Compute : 
-----------
I have 4 cases(4 operation) and for this I use a switch:
- "+"
- "-"
- "*"
- "/" 

I am also parsing to float my operands before computation

GetDisplayNumber : 
---------------------
In this function I am parsing my operands(integer digit and decimal digit)
And finally concatenate them and return as a result

UpdateDisplay : 
------------------
I just display the operands (with or without decimal digits) and the operation

