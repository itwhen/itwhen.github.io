---
title: map -
---
//[echo](../../index.md)/[tech.whence.echo.container](../index.md)/[Paginator](index.md)/[map](map.md)



# map  
[jvm]  
Brief description  


降级输出



#### Return  


Paging<E>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| fixer| <br><br>Function2<E, T, Unit>? 负载有效时纠正<br><br>
  
  
Content  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun <[T](map.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [map](map.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[T](map.md)>, fixer: ([T](map.md), [E](index.md)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)?): [Paginator](index.md)<[T](map.md)>  



