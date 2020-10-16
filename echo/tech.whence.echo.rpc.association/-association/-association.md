---
title: Association -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.association](../index.md)/[Association](index.md)/[Association](-association.md)



# Association  
[jvm]  
Brief description  


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| E| <br><br>当前数据<br><br>
| ER| <br><br>当前响应<br><br>
| F| <br><br>来源门面<br><br>
| FR| <br><br>来源门面响应<br><br>
  
  
Content  
fun <[F](index.md) : [ItemFacade](../../tech.whence.echo.rpc.sample.item/-item-facade/index.md)<*, *, *, [FR](index.md)>, [FR](index.md) : [ItemData](../../tech.whence.echo.rpc.sample.item/-item-data/index.md), [E](index.md) : [Resource](../../tech.whence.echo.rpc.sample.resource/-resource/index.md), [ER](index.md) : [ResourceData](../../tech.whence.echo.rpc.sample.resource/-resource-data/index.md)> [Association](-association.md)(associate: [Associate](../-associate/index.md)<[F](index.md), [FR](index.md)>, inhere: ([E](index.md)) -> [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, externalize: ([ER](index.md), [FR](index.md)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))  



