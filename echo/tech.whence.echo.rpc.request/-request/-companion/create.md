---
title: create -
---
//[echo](../../../index.md)/[tech.whence.echo.rpc.request](../../index.md)/[Request](../index.md)/[Companion](index.md)/[create](create.md)



# create  
[jvm]  
Brief description  


发起资源创建请求



#### Return  


String



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| facade| <br><br>F 资源门面<br><br>
| handler| <br><br>Handler? 异常处理<br><br>
| request| <br><br>C 请求数据<br><br>
  
  
Content  
suspend fun <[F](create.md) : [ResourceFacade](../../../tech.whence.echo.rpc.sample.resource/-resource-facade/index.md)<[C](create.md), *, *, [Single](../../../tech.whence.echo.rpc.payload/-single/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>>, [C](create.md) : [Payload](../../../tech.whence.echo.rpc.payload/-payload/index.md)> [create](create.md)(facade: [F](create.md), request: [C](create.md), handler: [Failure.Handler](../../../tech.whence.echo.rpc.response/-failure/-handler/index.md)?): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  



