---
title: const -
---
//[echo](../index.md)/[tech.whence.echo.container.constant](index.md)/[const](const.md)



# const  
[jvm]  
Brief description  


根据常量生成映射



#### Return  


Data<V, C>

  
Content  
inline fun <[C](const.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[C](const.md)>, [Const](-const/index.md)<[V](const.md)>, [V](const.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [const](const.md)(): [Data](-data/index.md)<[V](const.md), [C](const.md)>  


[jvm]  
Brief description  


根据常量类生成映射



#### Return  


Data<V, C>?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| declarer| <br><br>KClass<C> 指定类<br><br>
  
  
Content  
fun <[C](const.md) : [Const](-const/index.md)<[V](const.md)>, [V](const.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [const](const.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[C](const.md)>): [Data](-data/index.md)<[V](const.md), [C](const.md)>?  



