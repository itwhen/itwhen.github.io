---
title: retrieve -
---
//[echo](../../../index.md)/[tech.whence.echo.rpc.request](../../index.md)/[Request](../index.md)/[Companion](index.md)/[retrieve](retrieve.md)



# retrieve  
[jvm]  
Brief description  


发起资源获取请求



#### Return  


R?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| facade| <br><br>F 资源门面<br><br>
| handler| <br><br>Handler? 异常处理<br><br>
| id| <br><br>Id 指定编号<br><br>
  
  
Content  
suspend fun <[F](retrieve.md) : [ResourceFacade](../../../tech.whence.echo.rpc.sample.resource/-resource-facade/index.md)<*, *, *, [R](retrieve.md)>, [R](retrieve.md) : [Payload](../../../tech.whence.echo.rpc.payload/-payload/index.md)> [retrieve](retrieve.md)(facade: [F](retrieve.md), id: [Id](../../-id/index.md), handler: [Failure.Handler](../../../tech.whence.echo.rpc.response/-failure/-handler/index.md)?): [R](retrieve.md)?  


[jvm]  
Brief description  


发起资源获取请求



#### Return  


R?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| facade| <br><br>F 资源门面<br><br>
| handler| <br><br>Handler? 异常处理<br><br>
| id| <br><br>String 指定编号<br><br>
  
  
Content  
suspend fun <[F](retrieve.md) : [ResourceFacade](../../../tech.whence.echo.rpc.sample.resource/-resource-facade/index.md)<*, *, *, [R](retrieve.md)>, [R](retrieve.md) : [Payload](../../../tech.whence.echo.rpc.payload/-payload/index.md)> [retrieve](retrieve.md)(facade: [F](retrieve.md), id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), handler: [Failure.Handler](../../../tech.whence.echo.rpc.response/-failure/-handler/index.md)?): [R](retrieve.md)?  



