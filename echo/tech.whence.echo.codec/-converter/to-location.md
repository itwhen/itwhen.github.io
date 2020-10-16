---
title: toLocation -
---
//[echo](../../index.md)/[tech.whence.echo.codec](../index.md)/[Converter](index.md)/[toLocation](to-location.md)



# toLocation  
[jvm]  
Brief description  


转换指定值指定路径的值为指定类型值 识别Json字符串/Xml字符串/Map/Accessor/JsonObject/JsonArray等 编译为Json后 根据指定路径查找



#### Return  


T?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| path| <br><br>String 指定 json-path 路径<br><br>
| value| <br><br>Any? 指定值<br><br>
  
  
Content  
fun <[T](to-location.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [toLocation](to-location.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, path: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [T](to-location.md)?  



