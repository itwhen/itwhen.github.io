---
title: tech.whence.echo.rpc.sample.resource -
---
//[echo](../index.md)/[tech.whence.echo.rpc.sample.resource](index.md)



# Package tech.whence.echo.rpc.sample.resource  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Resource](-resource/index.md)| [jvm]  <br>Brief description  <br><br><br>资源数据<br><br>  <br>Content  <br>interface [Resource](-resource/index.md) : [Entity](../tech.whence.echo.dal.entity/-entity/index.md)  <br><br><br>
| [ResourceData](-resource-data/index.md)| [jvm]  <br>Brief description  <br><br><br>资源数据<br><br>  <br>Content  <br>interface [ResourceData](-resource-data/index.md) : [Payload](../tech.whence.echo.rpc.payload/-payload/index.md)  <br><br><br>
| [ResourceFacade](-resource-facade/index.md)| [jvm]  <br>Brief description  <br><br><br>资源门面<br><br>  <br>Content  <br>interface [ResourceFacade](-resource-facade/index.md)<[C](-resource-facade/index.md) : [Payload](../tech.whence.echo.rpc.payload/-payload/index.md), [U](-resource-facade/index.md) : [Payload](../tech.whence.echo.rpc.payload/-payload/index.md), [S](-resource-facade/index.md) : [ResourceSearching](-resource-searching/index.md), [R](-resource-facade/index.md) : [ResourceData](-resource-data/index.md)> : [Facade](../tech.whence.echo.rpc/-facade/index.md)  <br><br><br>
| [ResourceSearching](-resource-searching/index.md)| [jvm]  <br>Brief description  <br><br><br>资源搜索条件<br><br>  <br>Content  <br>interface [ResourceSearching](-resource-searching/index.md) : [Payload](../tech.whence.echo.rpc.payload/-payload/index.md)  <br><br><br>
| [ResourceService](-resource-service/index.md)| [jvm]  <br>Brief description  <br><br><br>资源服务抽象<br><br>  <br>Content  <br>abstract class [ResourceService](-resource-service/index.md)<[T](-resource-service/index.md) : [ResourceService](-resource-service/index.md)<[T](-resource-service/index.md), [C](-resource-service/index.md), [U](-resource-service/index.md), [S](-resource-service/index.md), [R](-resource-service/index.md), [E](-resource-service/index.md), [D](-resource-service/index.md)>, [C](-resource-service/index.md) : [Payload](../tech.whence.echo.rpc.payload/-payload/index.md), [U](-resource-service/index.md) : [Payload](../tech.whence.echo.rpc.payload/-payload/index.md), [S](-resource-service/index.md) : [ResourceSearching](-resource-searching/index.md), [R](-resource-service/index.md) : [ResourceData](-resource-data/index.md), [E](-resource-service/index.md) : [Resource](-resource/index.md), [D](-resource-service/index.md) : [Dao](../tech.whence.echo.dal.dao/-dao/index.md)<[E](-resource-service/index.md), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), *>, [Queriable](../tech.whence.echo.dal.dao/-queriable/index.md)<[E](-resource-service/index.md), *, *, *, *, *, *, *, *, *>>(**source**: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[E](-resource-service/index.md)>, **dao**: [D](-resource-service/index.md), **identifier**: [Identifier](../tech.whence.echo.dal.entity.id/-identifier/index.md)) : [AbstractService](../tech.whence.echo.rpc/-abstract-service/index.md)<[T](-resource-service/index.md)> , [ResourceFacade](-resource-facade/index.md)<[C](-resource-service/index.md), [U](-resource-service/index.md), [S](-resource-service/index.md), [R](-resource-service/index.md)>   <br><br><br>

