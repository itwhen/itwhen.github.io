---
title: xmlful -
---
//[echo](../../../index.md)/[tech.whence.echo.container.accessor](../../index.md)/[Accessor](../index.md)/[Companion](index.md)/[xmlful](xmlful.md)



# xmlful  
[jvm]  
Brief description  


基于xml字符串构造 若转换后数据为空返回空 若未指定根名称则用整个数据构造 若指定根在数据中存在且是一个Map则取相应值转换 否则返回空



#### Return  


Accessor



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>String? 指定字符串<br><br>
| root| <br><br>String? 指定根名称<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [xmlful](xmlful.md)(data: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, root: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [Accessor](../index.md)  



