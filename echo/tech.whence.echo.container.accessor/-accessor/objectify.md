---
title: objectify -
---
//[echo](../../index.md)/[tech.whence.echo.container.accessor](../index.md)/[Accessor](index.md)/[objectify](objectify.md)



# objectify  
[jvm]  
Brief description  


转换为指定对象 若注解为 Writable 可写则寻找相应构造函数直接构造



#### Return  


T



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| declarer| <br><br>KClass<T><br><br>
  
  
Content  
fun <[T](objectify.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [objectify](objectify.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[T](objectify.md)>): [T](objectify.md)  


[jvm]  
Brief description  


转换为指定对象



#### Return  


T



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| declarer| <br><br>Class<T><br><br>
  
  
Content  
fun <[T](objectify.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [objectify](objectify.md)(declarer: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[T](objectify.md)>): [T](objectify.md)  


[jvm]  
Brief description  


转换为指定对象



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| declarer| <br><br>Type<br><br>
  
  
Content  
fun <[T](objectify.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [objectify](objectify.md)(declarer: [Type](https://docs.oracle.com/javase/8/docs/api/java/lang/reflect/Type.html)): [T](objectify.md)  


[jvm]  
Brief description  


转换为指定对象



#### Return  


T



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| declarer| <br><br>Reference<T><br><br>
  
  
Content  
fun <[T](objectify.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [objectify](objectify.md)(declarer: [Reference](../../tech.whence.echo.type/-reference/index.md)<[T](objectify.md)>): [T](objectify.md)  


[jvm]  
Brief description  


转换为指定对象



#### Return  


T



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| declarer| <br><br>KType<br><br>
  
  
Content  
fun <[T](objectify.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [objectify](objectify.md)(declarer: [KType](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-type/index.html)): [T](objectify.md)  


[jvm]  
Brief description  


转换为指定对象



#### Return  


T

  
Content  
inline fun <[T](objectify.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [objectify](objectify.md)(): [T](objectify.md)  



