---
title: lead -
---
//[echo](../../index.md)/[tech.whence.echo.codec](../index.md)/[Context](index.md)/[lead](lead.md)



# lead  
[jvm]  
Brief description  


前置处理 若值为空不处理 若解码时遍历所有解编器解码指定值 若有编码器将指定值处理为空则返回假 若编码时仅判断是否可处理指定值 其他返回真



#### Return  


Boolean 是否可继续处理



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| transfers| <br><br>List<Codec> 解编器<br><br>
  
  
Content  
fun [lead](lead.md)(transfers: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Codec](../-codec/index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  



