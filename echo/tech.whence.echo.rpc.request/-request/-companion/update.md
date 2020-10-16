---
title: update -
---
//[echo](../../../index.md)/[tech.whence.echo.rpc.request](../../index.md)/[Request](../index.md)/[Companion](index.md)/[update](update.md)



# update  
[jvm]  
Brief description  


发起资源更新请求



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| facade| <br><br>F 资源门面<br><br>
| handler| <br><br>Handler? 异常处理<br><br>
| id| <br><br>Id 指定编号<br><br>
| request| <br><br>Request<U>  请求数据<br><br>
  
  
Content  
suspend fun <[F](update.md) : [ResourceFacade](../../../tech.whence.echo.rpc.sample.resource/-resource-facade/index.md)<*, [U](update.md), *, *>, [U](update.md) : [Payload](../../../tech.whence.echo.rpc.payload/-payload/index.md)> [update](update.md)(facade: [F](update.md), id: [Id](../../-id/index.md), request: [U](update.md), handler: [Failure.Handler](../../../tech.whence.echo.rpc.response/-failure/-handler/index.md)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  


[jvm]  
Brief description  


发起资源更新请求



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| facade| <br><br>F 资源门面<br><br>
| handler| <br><br>Handler? 异常处理<br><br>
| id| <br><br>String 指定编号<br><br>
| request| <br><br>Request<U> 请求数据<br><br>
  
  
Content  
suspend fun <[F](update.md) : [ResourceFacade](../../../tech.whence.echo.rpc.sample.resource/-resource-facade/index.md)<*, [U](update.md), *, *>, [U](update.md) : [Payload](../../../tech.whence.echo.rpc.payload/-payload/index.md)> [update](update.md)(facade: [F](update.md), id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), request: [U](update.md), handler: [Failure.Handler](../../../tech.whence.echo.rpc.response/-failure/-handler/index.md)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  



