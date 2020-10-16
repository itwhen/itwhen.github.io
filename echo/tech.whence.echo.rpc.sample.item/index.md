---
title: tech.whence.echo.rpc.sample.item -
---
//[echo](../index.md)/[tech.whence.echo.rpc.sample.item](index.md)



# Package tech.whence.echo.rpc.sample.item  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Item](-item/index.md)| [jvm]  <br>Brief description  <br><br><br>物品数据<br><br>  <br>Content  <br>interface [Item](-item/index.md) : [Resource](../tech.whence.echo.rpc.sample.resource/-resource/index.md)  <br><br><br>
| [ItemData](-item-data/index.md)| [jvm]  <br>Brief description  <br><br><br>物品数据<br><br>  <br>Content  <br>interface [ItemData](-item-data/index.md) : [ResourceData](../tech.whence.echo.rpc.sample.resource/-resource-data/index.md)  <br><br><br>
| [ItemFacade](-item-facade/index.md)| [jvm]  <br>Brief description  <br><br><br>物品门面<br><br>  <br>Content  <br>interface [ItemFacade](-item-facade/index.md)<[C](-item-facade/index.md) : [Payload](../tech.whence.echo.rpc.payload/-payload/index.md), [U](-item-facade/index.md) : [Payload](../tech.whence.echo.rpc.payload/-payload/index.md), [S](-item-facade/index.md) : [ItemSearching](-item-searching/index.md), [R](-item-facade/index.md) : [ItemData](-item-data/index.md)> : [ResourceFacade](../tech.whence.echo.rpc.sample.resource/-resource-facade/index.md)<[C](-item-facade/index.md), [U](-item-facade/index.md), [S](-item-facade/index.md), [R](-item-facade/index.md)>   <br><br><br>
| [ItemSearching](-item-searching/index.md)| [jvm]  <br>Brief description  <br><br><br>物品搜索条件<br><br>  <br>Content  <br>interface [ItemSearching](-item-searching/index.md) : [ResourceSearching](../tech.whence.echo.rpc.sample.resource/-resource-searching/index.md)  <br><br><br>
| [ItemService](-item-service/index.md)| [jvm]  <br>Brief description  <br><br><br>物品服务抽象<br><br>  <br>Content  <br>abstract class [ItemService](-item-service/index.md)<[T](-item-service/index.md) : [ItemService](-item-service/index.md)<[T](-item-service/index.md), [C](-item-service/index.md), [U](-item-service/index.md), [S](-item-service/index.md), [R](-item-service/index.md), [E](-item-service/index.md), [D](-item-service/index.md)>, [C](-item-service/index.md) : [Payload](../tech.whence.echo.rpc.payload/-payload/index.md), [U](-item-service/index.md) : [Payload](../tech.whence.echo.rpc.payload/-payload/index.md), [S](-item-service/index.md) : [ItemSearching](-item-searching/index.md), [R](-item-service/index.md) : [ItemData](-item-data/index.md), [E](-item-service/index.md) : [Item](-item/index.md), [D](-item-service/index.md) : [Dao](../tech.whence.echo.dal.dao/-dao/index.md)<[E](-item-service/index.md), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), *>, [Queriable](../tech.whence.echo.dal.dao/-queriable/index.md)<[E](-item-service/index.md), *, *, *, *, *, *, *, *, *>>(**source**: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[E](-item-service/index.md)>, **dao**: [D](-item-service/index.md), **identifier**: [Identifier](../tech.whence.echo.dal.entity.id/-identifier/index.md)) : [ResourceService](../tech.whence.echo.rpc.sample.resource/-resource-service/index.md)<[T](-item-service/index.md), [C](-item-service/index.md), [U](-item-service/index.md), [S](-item-service/index.md), [R](-item-service/index.md), [E](-item-service/index.md), [D](-item-service/index.md)> , [ItemFacade](-item-facade/index.md)<[C](-item-service/index.md), [U](-item-service/index.md), [S](-item-service/index.md), [R](-item-service/index.md)>   <br><br><br>

