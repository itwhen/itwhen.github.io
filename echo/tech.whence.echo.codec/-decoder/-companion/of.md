---
title: of -
---
//[echo](../../../index.md)/[tech.whence.echo.codec](../../index.md)/[Decoder](../index.md)/[Companion](index.md)/[of](of.md)



# of  
[jvm]  
Brief description  


基于可解析类型的构造



#### Return  


Conversion<T, Array<out T>>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| declarer| <br><br>KClass<T> 指定类型<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
inline fun <[T](of.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [of](of.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[T](of.md)>): [Decoder](../index.md)<[T](of.md), [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [T](of.md)>>  



