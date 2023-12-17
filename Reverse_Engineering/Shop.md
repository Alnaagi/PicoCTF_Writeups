### Shop
Tags: ![](https://img.shields.io/badge/Beginner_picoCTF_2021-blue) ![](https://img.shields.io/badge/Reverse_Engineering-red)

------------
Author: thelshellbr>
**Description**<br>
Best Stuff - Cheap Stuff, Buy Buy Buy... Store Instance: source. The shop is open for business at nc mercury.picoctf.net 24851.
------------

**Hints**<br>
1-Always check edge cases when programming<br>

------------
# Solution
1-after playing around i found out that you can buy in negative values<br>
2-buying option (0) for -12 i got 160 coins then buy option (2)<br>
3-the output 'Flag is:  [112 105 99 111 67 84 70 123 98 52 100 95 98 114 111 103 114 97 109 109 101 114 95 53 51 50 98 99 100 57 56 125]'
4-the numbers look like ascii encryption after converting the output we get this 'picoCTF{b4d_brogrammer_532bcd98}`
3- the flag is:
`picoCTF{b4d_brogrammer_532bcd98}`<br>
# Screenshots
![](shop.solved.png)
