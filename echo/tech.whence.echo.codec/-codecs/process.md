---
title: process -
---
//[echo](../../index.md)/[tech.whence.echo.codec](../index.md)/[Codecs](index.md)/[process](process.md)



# process  
[jvm]  
Brief description  


设置指定类型处理器 若为内置时不允许设置 若存在指定类型时将覆盖之



#### Return  


Codecs



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| processor| <br><br>Codec 处理器<br><br>
| target| <br><br>KClass<*> 指定类型<br><br>
  
  
Content  
fun [process](process.md)(target: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>, processor: [Codec](../-codec/index.md)): [Codecs](index.md)  



