---
title: 初学python一
date: 2017-09-03 22:04:48
tags:
---
<font size=4>学习版本：python2.7</font>
***    
*    python2中数字0在首位表示八进制，python3禁止这样的写法。在python2中，0x在首位表示八进制。    
*    x=input("x="):给x赋值    
*    pow(2,3)==2**3
*    round函数会把浮点数四舍五入
*    python2中两个整数使用"/"是进行下取整，要想进行正常的除法使用*from \__future__ import division*。当然在python2中“//”仍表示执行整除。    
```           
>>>from __furture__ import division    
>>>1/2  
0.5        
>>>1//2    
0    
```