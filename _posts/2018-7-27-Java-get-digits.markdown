---
layout:     post
title:      Java.get the digits of intger number
subtitle:   "Java笔记，得到整数的位数"
date:       2018-7-27 21:09:08
author:     "Zxq"
header-img: "img/post-bg-os-metro.jpg"
tags:
    - Java
    - 笔记
---


考虑纯数运算
math.log函数
><br>int x=12999;
<br>int n =(int) (Math.log(x)+1)/2;
<br>System.out.println(n);

发现缺点很多，弃用

使用最朴素的算法，将int转换为string，求length

><br>int x= 977123277;
<br>int y=(x+"").length();

over