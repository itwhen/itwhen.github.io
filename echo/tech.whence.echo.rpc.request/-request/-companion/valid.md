---
title: valid -
---
//[echo](../../../index.md)/[tech.whence.echo.rpc.request](../../index.md)/[Request](../index.md)/[Companion](index.md)/[valid](valid.md)



# valid  
[jvm]  
Brief description  


检查指定资源是否有效 是否存在或启用



#### Return  


R



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| facade| <br><br>F 资源门面<br><br>
| handler| <br><br>Handler? 异常处理<br><br>
| id| <br><br>Id 指定编号<br><br>
  
  
Content  
suspend fun <[F](valid.md) : [ResourceFacade](../../../tech.whence.echo.rpc.sample.resource/-resource-facade/index.md)<*, *, *, [R](valid.md)>, [R](valid.md) : [ItemData](../../../tech.whence.echo.rpc.sample.item/-item-data/index.md)> [valid](valid.md)(facade: [F](valid.md), id: [Id](../../-id/index.md), handler: [Failure.Handler](../../../tech.whence.echo.rpc.response/-failure/-handler/index.md)?): [R](valid.md)  


[jvm]  
Brief description  


检查指定资源是否有效 是否存在或启用



#### Return  


R



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| facade| <br><br>F 资源门面<br><br>
| handler| <br><br>Handler? 异常处理<br><br>
| id| <br><br>String 指定编号<br><br>
  
  
Content  
suspend fun <[F](valid.md) : [ResourceFacade](../../../tech.whence.echo.rpc.sample.resource/-resource-facade/index.md)<*, *, *, [R](valid.md)>, [R](valid.md) : [ItemData](../../../tech.whence.echo.rpc.sample.item/-item-data/index.md)> [valid](valid.md)(facade: [F](valid.md), id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), handler: [Failure.Handler](../../../tech.whence.echo.rpc.response/-failure/-handler/index.md)?): [R](valid.md)  


[jvm]  
Brief description  


检查指定资源是否有效 是否存在或启用



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| batch| <br><br>Batch 编号批次<br><br>
| facade| <br><br>F 资源门面<br><br>
| handler| <br><br>Handler? 异常处理<br><br>
  
  
Content  
inline suspend fun <[F](valid.md) : [ResourceFacade](../../../tech.whence.echo.rpc.sample.resource/-resource-facade/index.md)<*, *, *, [R](valid.md)>, [R](valid.md) : [ItemData](../../../tech.whence.echo.rpc.sample.item/-item-data/index.md)> [valid](valid.md)(facade: [F](valid.md), batch: [Batch](../../-batch/index.md), handler: [Failure.Handler](../../../tech.whence.echo.rpc.response/-failure/-handler/index.md)?)  


[jvm]  
Brief description  


检查指定资源是否有效 是否存在或启用



#### Return  


Unit



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| batch| <br><br>Collection<String> 编号批次<br><br>
| facade| <br><br>F 资源门面<br><br>
| handler| <br><br>Handler? 异常处理<br><br>
  
  
Content  
inline suspend fun <[F](valid.md) : [ResourceFacade](../../../tech.whence.echo.rpc.sample.resource/-resource-facade/index.md)<*, *, *, [R](valid.md)>, [R](valid.md) : [ItemData](../../../tech.whence.echo.rpc.sample.item/-item-data/index.md)> [valid](valid.md)(facade: [F](valid.md), batch: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>, handler: [Failure.Handler](../../../tech.whence.echo.rpc.response/-failure/-handler/index.md)?)  



