---
title: set -
---
//[echo](../../index.md)/[tech.whence.echo.dal.schema.key](../index.md)/[Keys](index.md)/[set](set.md)



# set  
[jvm]  
Brief description  


设置指定字段并返回是否成功 若已加载返回假 虚拟键不受限 否则添加到数据中并返回真 重复字段将合并注解(实现接口时)



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| key| <br><br>Key 指定字段<br><br>
| renew| <br><br>Boolean 是否需要刷新当前字段<br><br>
  
  
Content  
fun [set](set.md)(key: [Key](../-key/index.md), renew: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  



