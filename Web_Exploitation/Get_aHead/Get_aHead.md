### Get_aHead
Tags: ![](https://img.shields.io/badge/Beginner_picoCTF_2021-blue) ![](https://img.shields.io/badge/Web_Exploitation-red)

------------
Author: madStacks<br>
**Description**<br>

Find the flag being held on this server to get ahead of the competition [http://mercury.picoctf.net:28916/](http://mercury.picoctf.net:28916/)

------------

**Hints**<br>
1-Maybe you have more than 2 choices<br>

2-Check out tools like Burpsuite to modify your requests and look at the responses<br>

------------
# Solution
1-upon opening the site we get to buttons "Choose Red" & "Choose Blue"

![](aHead.png)

2-The Ctf name gave a nice hint About a HEAD<br>

3-I opened up burpsuit, Intercepted the Request sent it to the Repeater

![](Repeater.png)

4-Changed the Request Method grom GET to HEAD and suprise suprise we got the flag

![](flag.png)

5-flag: `picoCTF{r3j3ct_th3_du4l1ty_70bc61c4}`
