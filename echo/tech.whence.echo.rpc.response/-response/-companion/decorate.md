---
title: decorate -
---
//[echo](../../../index.md)/[tech.whence.echo.rpc.response](../../index.md)/[Response](../index.md)/[Companion](index.md)/[decorate](decorate.md)



# decorate  
[jvm]  
Brief description  


转换实体并修饰



#### Return  


T



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>E 实体<br><br>
| decorator| <br><br>Decorator<T, E>? 修饰器<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
inline fun <[E](decorate.md) : [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md), [T](decorate.md) : [Payload](../../../tech.whence.echo.rpc.payload/-payload/index.md)> [decorate](decorate.md)(data: [E](decorate.md), decorator: [Decorator](../../-decorator/index.md)<[T](decorate.md), [E](decorate.md)>?): [T](decorate.md)  



