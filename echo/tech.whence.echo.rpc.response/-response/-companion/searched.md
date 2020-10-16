---
title: searched -
---
//[echo](../../../index.md)/[tech.whence.echo.rpc.response](../../index.md)/[Response](../index.md)/[Companion](index.md)/[searched](searched.md)



# searched  
[jvm]  
Brief description  


完成搜索



#### Return  


Response<Paged<T>>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>Paginator<E> 分页数据<br><br>
| decorator| <br><br>Decorator<E, T>? 有效负载纠正<br><br>
  
  
Content  
inline fun <[E](searched.md) : [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md), [T](searched.md) : [Payload](../../../tech.whence.echo.rpc.payload/-payload/index.md)> [searched](searched.md)(data: [Paginator](../../../tech.whence.echo.container/-paginator/index.md)<[E](searched.md)>, decorator: [Decorator](../../-decorator/index.md)<[T](searched.md), [E](searched.md)>?): [Response](../index.md)<[Paged](../../../tech.whence.echo.rpc.payload/-paged/index.md)<[T](searched.md)>>  



