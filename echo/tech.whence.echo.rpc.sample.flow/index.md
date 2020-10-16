---
title: tech.whence.echo.rpc.sample.flow -
---
//[echo](../index.md)/[tech.whence.echo.rpc.sample.flow](index.md)



# Package tech.whence.echo.rpc.sample.flow  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Flow](-flow/index.md)| [jvm]  <br>Brief description  <br><br><br>流程数据<br><br>  <br>Content  <br>interface [Flow](-flow/index.md) : [Resource](../tech.whence.echo.rpc.sample.resource/-resource/index.md)  <br><br><br>
| [FlowData](-flow-data/index.md)| [jvm]  <br>Brief description  <br><br><br>流程数据<br><br>  <br>Content  <br>interface [FlowData](-flow-data/index.md) : [ResourceData](../tech.whence.echo.rpc.sample.resource/-resource-data/index.md)  <br><br><br>
| [FlowFacade](-flow-facade/index.md)| [jvm]  <br>Brief description  <br><br><br>流程门面<br><br>  <br>Content  <br>interface [FlowFacade](-flow-facade/index.md)<[C](-flow-facade/index.md) : [Payload](../tech.whence.echo.rpc.payload/-payload/index.md), [U](-flow-facade/index.md) : [Payload](../tech.whence.echo.rpc.payload/-payload/index.md), [S](-flow-facade/index.md) : [FlowSearching](-flow-searching/index.md), [R](-flow-facade/index.md) : [FlowData](-flow-data/index.md)> : [ResourceFacade](../tech.whence.echo.rpc.sample.resource/-resource-facade/index.md)<[C](-flow-facade/index.md), [U](-flow-facade/index.md), [S](-flow-facade/index.md), [R](-flow-facade/index.md)>   <br><br><br>
| [FlowSearching](-flow-searching/index.md)| [jvm]  <br>Brief description  <br><br><br>流程搜索条件<br><br>  <br>Content  <br>interface [FlowSearching](-flow-searching/index.md) : [ResourceSearching](../tech.whence.echo.rpc.sample.resource/-resource-searching/index.md)  <br><br><br>
| [FlowService](-flow-service/index.md)| [jvm]  <br>Brief description  <br><br><br>流程服务抽象<br><br>  <br>Content  <br>abstract class [FlowService](-flow-service/index.md)<[T](-flow-service/index.md) : [FlowService](-flow-service/index.md)<[T](-flow-service/index.md), [C](-flow-service/index.md), [U](-flow-service/index.md), [S](-flow-service/index.md), [R](-flow-service/index.md), [N](-flow-service/index.md), [E](-flow-service/index.md), [D](-flow-service/index.md)>, [C](-flow-service/index.md) : [Payload](../tech.whence.echo.rpc.payload/-payload/index.md), [U](-flow-service/index.md) : [Payload](../tech.whence.echo.rpc.payload/-payload/index.md), [S](-flow-service/index.md) : [FlowSearching](-flow-searching/index.md), [R](-flow-service/index.md) : [FlowData](-flow-data/index.md), [N](-flow-service/index.md) : [IntConst](../tech.whence.echo.container.constant/-int-const/index.md), [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[N](-flow-service/index.md)>, [Trackable](-trackable/index.md), [E](-flow-service/index.md) : [Flow](-flow/index.md), [D](-flow-service/index.md) : [Dao](../tech.whence.echo.dal.dao/-dao/index.md)<[E](-flow-service/index.md), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), *>, [Queriable](../tech.whence.echo.dal.dao/-queriable/index.md)<[E](-flow-service/index.md), *, *, *, *, *, *, *, *, *>>(**source**: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[E](-flow-service/index.md)>, **flow**: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[N](-flow-service/index.md)>, **dao**: [D](-flow-service/index.md), **identifier**: [Identifier](../tech.whence.echo.dal.entity.id/-identifier/index.md)) : [ResourceService](../tech.whence.echo.rpc.sample.resource/-resource-service/index.md)<[T](-flow-service/index.md), [C](-flow-service/index.md), [U](-flow-service/index.md), [S](-flow-service/index.md), [R](-flow-service/index.md), [E](-flow-service/index.md), [D](-flow-service/index.md)> , [FlowFacade](-flow-facade/index.md)<[C](-flow-service/index.md), [U](-flow-service/index.md), [S](-flow-service/index.md), [R](-flow-service/index.md)>   <br><br><br>
| [Node](-node/index.md)| [jvm]  <br>Brief description  <br><br><br>流程节点<br><br>  <br>Content  <br>enum [Node](-node/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Node](-node/index.md)>   <br><br><br>
| [Operation](-operation/index.md)| [jvm]  <br>Brief description  <br><br><br>操作<br><br>  <br>Content  <br>enum [Operation](-operation/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Operation](-operation/index.md)>   <br><br><br>
| [Operations](-operations/index.md)| [jvm]  <br>Brief description  <br><br><br>流程操作的前后节点数据<br><br>  <br>Content  <br>class [Operations](-operations/index.md)  <br><br><br>
| [Trackable](-trackable/index.md)| [jvm]  <br>Brief description  <br><br><br>可跟踪的<br><br>  <br>Content  <br>interface [Trackable](-trackable/index.md)  <br><br><br>

