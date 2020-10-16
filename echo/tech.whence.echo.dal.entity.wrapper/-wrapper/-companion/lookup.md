---
title: lookup -
---
//[echo](../../../index.md)/[tech.whence.echo.dal.entity.wrapper](../../index.md)/[Wrapper](../index.md)/[Companion](index.md)/[lookup](lookup.md)



# lookup  
[jvm]  
Brief description  


寻找可服务指定实体的打包器



#### Return  


Wrapper



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| entity| <br><br>E 指定实体<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun <[E](lookup.md) : [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md)> [lookup](lookup.md)(entity: [E](lookup.md)): [Wrapper](../index.md)  


[jvm]  
Brief description  


寻找可服务指定实体类型的打包器



#### Return  


Wrapper



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| declarer| <br><br>KClass<out E> 指定实体类型<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun <[E](lookup.md) : [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md)> [lookup](lookup.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [E](lookup.md)>): [Wrapper](../index.md)  



