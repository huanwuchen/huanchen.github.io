---
layout: post
title: data 原生用法 jquery 用法
tags:  [jquery,javascript,data]
categories: [js,javascript]
author: huanchen
excerpt: "data 原生用法 jquery 用法"
---


//原生js：
 
document.getElementById("obj").dataset.bid = "1";//赋值
var bid = document.getElementById("obj").dataset.bid;//取值
 
document.getElementById("obj").setAttribute("data-bid", "1");//赋值
var bid = document.getElementById("obj").getAttribute("data-bid");//取值
 
 
//jquery用法：
 
$('#obj').data('bid', '1');//赋值
 
var bid = $('#obj').data('bid');//取值
 
 
$('#obj').attr('data-bid', '1');//赋值
 
var bid = $('#obj').attr('data-bid');//取值