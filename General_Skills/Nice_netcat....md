### Nice netcat...
Tags: ![](https://img.shields.io/badge/picoCTF_2021-blue) ![](https://img.shields.io/badge/General_Skills-red)

------------
Author: syreal<br>
**Description**<br>
There is a nice program that you can talk to by using this command in a shell: `$ nc mercury.picoctf.net 49039`, but it doesn't speak English...

------------

**Hints**<br>
1-You can practice using netcat with this picoGym problem: [what is a netcat?](http://https://play.picoctf.org/practice/challenge/34 "what is a netcat?")<br>
2-You can practice reading and writing ASCII with this picoGym problem: [Let's Warm Up](https://play.picoctf.org/practice/challenge/22")<br>

------------
# Solution
1-  run this in the Terminal `nc mercury.picoctf.net 49039`<br>
2- you will have this output:<br>
`112 
105 
99 
111 
67 
84 
70 
123 
103 
48 
48 
100 
95 
107 
49 
116 
116 
121 
33 
95 
110 
49 
99 
51 
95 
107 
49 
116 
116 
121 
33 
95 
51 
100 
56 
52 
101 
100 
99 
56 
125 
10`<br>
3- copy and take this output to a ASCII to Text converter like this one https://www.duplichecker.com/ascii-to-text.php<br>
4- the flag is `picoCTF{g00d_k1tty!_n1c3_k1tty!_3d84edc8}`<br>
# Screenshots
![](PicoCTF_Writeups/General_Skills/Screenshot 2023-12-14 at 02-38-19 ASCII to Text Convert you ASCII code into Text.png)
