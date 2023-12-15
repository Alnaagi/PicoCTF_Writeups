### fixme2.py
Tags: ![](https://img.shields.io/badge/Beginner_picoCTF_2022-blue) ![](https://img.shields.io/badge/General_Skills-red)![](https://img.shields.io/badge/Python-black)

------------
Author: LT 'syreal' Jones<br>
**Description**<br>
Fix the syntax error in this Python script to print the flag. [Download Python script](https://artifacts.picoctf.net/c/4/fixme2.py)
------------

**Hints**<br>
1-Are equality and assignment the same symbol?<br>
2-To view the file in the webshell, do: $ nano fixme2.py<br>
3-To exit nano, press Ctrl and x and follow the on-screen prompts.<br>
4-The str_xor function does not need to be reverse engineered for this challenge.<br>

------------
# Solution
1-  Fix the SyntaxError: invalid syntax on line 22 <br>
Explanation :<br>
it is important to understand the concept of different Python operators, including “=” for value assignment, “==” for equality comparison, and other arithmetic, logical, and bitwise [operators]( https://docs.python.org/3/library/operator.html).<br>
2- By Adding =  to the = in the code to make it == and it will work normally<br>
3- the output is:
`That is correct! Here's your flag: picoCTF{3qu4l1ty_n0t_4551gnm3nt_e8814d03}`<br>
# Screenshots
![](fixme2.py.png)<br>
![](fixme2.py.solved.png)
