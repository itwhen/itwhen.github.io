---
title: to -
---
//[echo](../../index.md)/[tech.whence.echo.codec](../index.md)/[Converter](index.md)/[to](to.md)



# to  
[jvm]  
Brief description  


转换指定值为指定类型 若指定值为空返回空 若指定值已经是指定类型则直接返回 否则使用指定解编器容器转换 此时将value视作数据源故调用codecs的解码方法



#### Return  


T?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| codecs| <br><br>Codecs 默认使用内置解编器容器<br><br>
| declarer| <br><br>KClass<T> 指定类型<br><br>
| value| <br><br>Any? 指定值<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun <[T](to.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [to](to.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[T](to.md)>, codecs: [Codecs](../-codecs/index.md)): [T](to.md)?  



