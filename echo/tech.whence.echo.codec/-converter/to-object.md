---
title: toObject -
---
//[echo](../../index.md)/[tech.whence.echo.codec](../index.md)/[Converter](index.md)/[toObject](to-object.md)



# toObject  
[jvm]  
Brief description  


转换指定值为指定类型



#### Return  


T?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| value| <br><br>Any? 指定值<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
inline fun <[T](to-object.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)> [toObject](to-object.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [T](to-object.md)?  


[jvm]  
Brief description  


转换指定值为指定类型



#### Return  


T?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| declarer| <br><br>KClass<T> 指定类型<br><br>
| value| <br><br>Any? 指定值<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun <[T](to-object.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)> [toObject](to-object.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[T](to-object.md)>): [T](to-object.md)?  



