---
layout: post
title: android 跳转
tags:  [android,跳转]
categories: [android]
excerpt: "android 跳转"
---


<pre>
//普通跳转
//新建一个显式意图，第一个参数为当前Activity类对象，第二个参数为你要打开的Activity类
Intent intent =new Intent(MainActivity.this,MainActivity2.class);
startActivity(intent);

//带参数跳转
Intent intent = new Intent(Main.this, MainActivity.class);
// 用Bundle携带数据
Bundle bundle = new Bundle();
// 传递name参数为tinyphp
bundle.putString("name", "tinyphp");
intent.putExtras(bundle);

startActivity(intent);

//接收activity：

// 新页面接收数据
Bundle bundle = this.getIntent().getExtras();
// 接收name值
String name = bundle.getString("name");
