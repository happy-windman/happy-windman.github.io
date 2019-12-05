---
layout: post
title:  "字符串与数组操作方法整理"
date:   2018-05-17 14:05:21 +0800
tags:  Html,Javascript
color: rgb(255,90,90)
cover: '../assets/test.png'
subtitle: '字符串'
---

  字符串：
   substring(start,end) 截取。   第一个参数表示开始位置，第二个代表结束位置（不包括结束位置） 
会自动调整两个参数的顺序，但是不能是负数，可以只写一个参数，第一个参数是起始位置，结束位置是默认到结束。
   slice 截取。 第一个参数表示开始位置，第二个代表结束位置（不包括结束位置）。
起始位置一定小于结束位置，支持负数，从字符串末尾向前截取，-1表示最后一位。
   substr（start，end）截取。   第一个参数表示开始位置，第二个代表结束位置（不包括结束位置）


   indexOf：从左向右进行查找，第一个满足条件的，第二个参数：查找的起始位置，默认就是从0位置查找，找不到返回-1
   lastIndexOf：从右向左进行查找 , 第二个参数，指定字符串的起始位置。
   includes（）判断当前指定字符串在已有字符串中有没有出现过，有出现true。否则false。ES6
 
   charAt(index):返回指定索引处的字符串
   charCodeAt(index):返回指定索引处的字符的Unicode的值

   
   concat(str1,str2,…):连接多个字符串，返回连接后的字符串的副本，不改变str1，str2等字符；
   split() 字符串的方法，把字符串切分成一个数组集合  以某个字符来分割

   toLowerCase()：将字符串转换为小写
   toUpperCase()：将字符串转换为大写
   
  match(regex):搜索字符串，并返回正则表达式的所有匹配
  replace(str1,str2):str1也可以为正则表达式或字符串，用str2替换str1
     字符替换变量：
     string.replace(key,"b");替换一个
     string.replace(new RegExp(key,'g'),"b");替换全局

  search(regex):基于正则表达式搜索字符串，并返回第一个匹配的位置
  valueOf()：返回原始字符串值

