﻿# Lab5设计文档
19302010015 许同樵
## 1、提取url

涉及知识点：字符串的查找和分割

解决方案：先将问号前的字符切除，然后找到"name="和最近的"&",提取name的值
## 2、计时倍增

涉及知识点：setTimeOut,时间计算，代码设计思路

解决方案：并非在运行时终止运行，因为那会导致阻塞；而是使用setTimeOut，在代码执行完毕后延迟数值改变的时间

## 3、查找最多出现的字符

涉及知识点：js中的key和value

解决方案：1、通过一个数组count来计每个字符出现的次数；2、查找count中最大的value。
## 4、截图

![page](./images/webPage.jpg)


![gitpage](./images/gitPage.jpg)