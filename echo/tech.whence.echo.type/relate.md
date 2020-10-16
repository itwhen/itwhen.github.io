---
title: relate -
---
//[echo](../index.md)/[tech.whence.echo.type](index.md)/[relate](relate.md)



# relate  
[jvm]  
Brief description  


查找当前类及父类中与指定类关系最近的类



#### Return  


Set<KClass<T>>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| <receiver>| <br><br>KClass<*><br><br>
| declarer| <br><br>KClass<T> 指定类<br><br>
  
  
Content  
fun <[T](relate.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>.[relate](relate.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[T](relate.md)>): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[T](relate.md)>>  



