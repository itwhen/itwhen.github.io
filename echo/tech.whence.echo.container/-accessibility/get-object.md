---
title: getObject -
---
//[echo](../../index.md)/[tech.whence.echo.container](../index.md)/[Accessibility](index.md)/[getObject](get-object.md)



# getObject  
[jvm]  
Brief description  


取指定对象



#### Return  


Result<T>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| declarer| <br><br>KClass<T> 指定类型<br><br>
| key| <br><br>K 指定键<br><br>
  
  
Content  
open fun <[T](get-object.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)> [getObject](get-object.md)(key: [K](index.md), declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[T](get-object.md)>): [Reply](../-reply/index.md)<[T](get-object.md)>  



