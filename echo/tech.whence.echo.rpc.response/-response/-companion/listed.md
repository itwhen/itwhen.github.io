---
title: listed -
---
//[echo](../../../index.md)/[tech.whence.echo.rpc.response](../../index.md)/[Response](../index.md)/[Companion](index.md)/[listed](listed.md)



# listed  
[jvm]  
Brief description  


完成列表



#### Return  


Responsive



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>List<T> 数据<br><br>
| decorator| <br><br>Decorator<E, T>? 有效负载纠正<br><br>
  
  
Content  
inline fun <[E](listed.md) : [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md), [T](listed.md) : [Payload](../../../tech.whence.echo.rpc.payload/-payload/index.md)> [listed](listed.md)(data: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[E](listed.md)>, decorator: [Decorator](../../-decorator/index.md)<[T](listed.md), [E](listed.md)>?): [Response](../index.md)<[Listed](../../../tech.whence.echo.rpc.payload/-listed/index.md)<[T](listed.md)>>  


[jvm]  
Brief description  


完成列表



#### Return  


Response<Listed<T>>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>Entities<E> 数据<br><br>
| decorator| <br><br>Decorator<E, T>? 有效负载纠正<br><br>
  
  
Content  
inline fun <[E](listed.md) : [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md), [T](listed.md) : [Payload](../../../tech.whence.echo.rpc.payload/-payload/index.md)> [listed](listed.md)(data: [Entities](../../../tech.whence.echo.dal.entity/-entities/index.md)<[E](listed.md)>, decorator: [Decorator](../../-decorator/index.md)<[T](listed.md), [E](listed.md)>?): [Response](../index.md)<[Listed](../../../tech.whence.echo.rpc.payload/-listed/index.md)<[T](listed.md)>>  



