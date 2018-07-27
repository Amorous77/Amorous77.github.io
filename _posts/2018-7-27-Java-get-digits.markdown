---
layout:     post
title:      Java.get the digits of intger number
subtitle:   "Java笔记，得到整数的位数"
date:       2018-7-27 21:09:08
author:     "Zxq"
header-img: "img/amorous77.jpg"
tags:
    - Java
    - 笔记
---


考虑纯数运算
>math.log
>int x=12999;
<br>int n =(int) (Math.log(x)+1)/2;
>System.out.println(n);

发现缺点很多，弃用

使用最朴素的算法，将int转换为string，求length

>int x= 977123277;
>int y=(x+"").length();

over