---
layout: post
title: js json 编辑
tags:  [json,edit]
categories: [android]
excerpt: "json 编辑"
---


<pre>

var data={"a":"safdsadfdsaf","b":12344};
console.log("data="+JSON.stringify(data));

//添加json项
data.c="hahahhah";
console.log("data="+JSON.stringify(data));

//删除json项
delete data.a
console.log("data="+JSON.stringify(data));

//输出结果
//data={"a":"safdsadfdsaf","b":12344}
//data={"a":"safdsadfdsaf","b":12344,"c":"hahahhah"}
//data={"b":12344,"c":"hahahhah"}

</pre>
