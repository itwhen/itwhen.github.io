---
title: delete -
---
//[echo](../../../index.md)/[tech.whence.echo.rpc.request](../../index.md)/[Request](../index.md)/[Companion](index.md)/[delete](delete.md)



# delete  
[jvm]  
Brief description  


发起资源删除请求



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| batch| <br><br>Batch 指定批次<br><br>
| facade| <br><br>F 资源门面<br><br>
| handler| <br><br>Handler? 异常处理<br><br>
  
  
Content  
suspend fun <[F](delete.md) : [ResourceFacade](../../../tech.whence.echo.rpc.sample.resource/-resource-facade/index.md)<*, *, *, *>> [delete](delete.md)(facade: [F](delete.md), batch: [Batch](../../-batch/index.md), handler: [Failure.Handler](../../../tech.whence.echo.rpc.response/-failure/-handler/index.md)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  


[jvm]  
Brief description  


发起资源删除请求



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| facade| <br><br>F 资源门面<br><br>
| handler| <br><br>Handler? 异常处理<br><br>
| id| <br><br>Id 指定编号<br><br>
  
  
Content  
suspend fun <[F](delete.md) : [ResourceFacade](../../../tech.whence.echo.rpc.sample.resource/-resource-facade/index.md)<*, *, *, *>> [delete](delete.md)(facade: [F](delete.md), id: [Id](../../-id/index.md), handler: [Failure.Handler](../../../tech.whence.echo.rpc.response/-failure/-handler/index.md)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  


[jvm]  
Brief description  


发起资源删除请求



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| facade| <br><br>F 资源门面<br><br>
| handler| <br><br>Handler? 异常处理<br><br>
| id| <br><br>String 指定编号<br><br>
  
  
Content  
suspend fun <[F](delete.md) : [ResourceFacade](../../../tech.whence.echo.rpc.sample.resource/-resource-facade/index.md)<*, *, *, *>> [delete](delete.md)(facade: [F](delete.md), id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), handler: [Failure.Handler](../../../tech.whence.echo.rpc.response/-failure/-handler/index.md)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  



