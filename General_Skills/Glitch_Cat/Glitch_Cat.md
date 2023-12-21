### Glitch Cat
Tags: ![](https://img.shields.io/badge/Beginner_picoCTF_2022-blue) ![](https://img.shields.io/badge/General_Skills-red)![](https://img.shields.io/badge/Python-black)![](https://img.shields.io/badge/nc-black)![](https://img.shields.io/badge/shell-black)

------------
Author: LT 'syreal' Jones<br>
**Description**<br>
Our flag printing service has started glitching! `$ nc saturn.picoctf.net 52682`
------------

**Hints**<br>
1-ASCII is one of the most common encodings used in programming<br>
2-We know that the glitch output is valid Python, somehow!<br>
3-Press Ctrl and c on your keyboard to close your connection and return to the command prompt.<br>

------------
# Solution
1-  create a simple Python script  <br>
Explanation :<br>
I know that 0x39 represents an hexadecimal character. And also, the chr function is Python 3 syntax. This function, simply “Return the string representing a character whose Unicode code point is the integer i” [source]( https://docs.python.org/3/library/functions.html#chr). In our case, we have 0x before the integer (indicating hexadecimal), therefore, it will convert from hexadecimal representation into the respective ASCII character.<br>
2- By using Python3 console we get our flag<br>
3- the output is:
`picoCTF{gl17ch_m3_n07_bda68f75}`<br>
# Screenshots
![](glitchcat.solved.png)
