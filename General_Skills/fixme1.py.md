### fixme1.py
Tags: ![](https://img.shields.io/badge/picoCTF_2022-blue) ![](https://img.shields.io/badge/General_Skills-red)![](https://img.shields.io/badge/Python-black)

------------
Author: LT 'syreal' Jones<br>
**Description**<br>
Fix the syntax error in this Python script to print the flag. [Download Python script](https://artifacts.picoctf.net/c/27/fixme1.py)
------------

**Hints**<br>
1-Indentation is very meaningful in Python<br>
2-To view the file in the webshell, do: $ nano fixme1.py<br>
3-To exit nano, press Ctrl and x and follow the on-screen prompts.<br>
4-The str_xor function does not need to be reverse engineered for this challenge.<br>

------------
# Solution
1-  Fix the Unexpected indent (or TabError) on line 20 <br>
Explanation :<br>
Python uses spacing at the start of the line to determine when code blocks start and end. Errors you can get are:<br>
Unexpected indent. This line of code has more spaces at the start than the one before, but the one before is not the start of a subblock (e.g., the if, while, and for statements). All lines of code in a block must start with exactly the same string of whitespace.<br>
2- By Deleting 2 spaces before the print function the code will work normally<br>
3- the output is:
`That is correct! Here's your flag: picoCTF{1nd3nt1ty_cr1515_182342f7}`<br>
# Screenshots
![](fixme1.py.png)
