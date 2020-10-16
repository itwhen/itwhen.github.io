---
title: jsonful -
---
//[echo](../../../index.md)/[tech.whence.echo.container.accessor](../../index.md)/[Accessor](../index.md)/[Companion](index.md)/[jsonful](jsonful.md)



# jsonful  
[jvm]  
Brief description  


基于json字符串构造



#### Return  


Accessor



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>String? 指定字符串<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [jsonful](jsonful.md)(data: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [Accessor](../index.md)  


[jvm]  
Brief description  


基于JsonObject构造 将编码后再解码用以彻底转换为 Map对象



#### Return  


Accessor



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>JsonObject 指定对象<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [jsonful](jsonful.md)(data: JsonObject): [Accessor](../index.md)  



