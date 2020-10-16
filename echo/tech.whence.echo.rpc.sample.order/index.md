---
title: tech.whence.echo.rpc.sample.order -
---
//[echo](../index.md)/[tech.whence.echo.rpc.sample.order](index.md)



# Package tech.whence.echo.rpc.sample.order  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Order](-order/index.md)| [jvm]  <br>Brief description  <br><br><br>单据数据<br><br>  <br>Content  <br>interface [Order](-order/index.md) : [Flow](../tech.whence.echo.rpc.sample.flow/-flow/index.md)  <br><br><br>
| [OrderData](-order-data/index.md)| [jvm]  <br>Brief description  <br><br><br>单据数据<br><br>  <br>Content  <br>interface [OrderData](-order-data/index.md) : [FlowData](../tech.whence.echo.rpc.sample.flow/-flow-data/index.md)  <br><br><br>
| [OrderFacade](-order-facade/index.md)| [jvm]  <br>Brief description  <br><br><br>单据门面<br><br>  <br>Content  <br>interface [OrderFacade](-order-facade/index.md)<[C](-order-facade/index.md) : [Payload](../tech.whence.echo.rpc.payload/-payload/index.md), [U](-order-facade/index.md) : [Payload](../tech.whence.echo.rpc.payload/-payload/index.md), [S](-order-facade/index.md) : [OrderSearching](-order-searching/index.md), [R](-order-facade/index.md) : [OrderData](-order-data/index.md)> : [FlowFacade](../tech.whence.echo.rpc.sample.flow/-flow-facade/index.md)<[C](-order-facade/index.md), [U](-order-facade/index.md), [S](-order-facade/index.md), [R](-order-facade/index.md)>   <br><br><br>
| [OrderSearching](-order-searching/index.md)| [jvm]  <br>Brief description  <br><br><br>单据搜索条件<br><br>  <br>Content  <br>interface [OrderSearching](-order-searching/index.md) : [FlowSearching](../tech.whence.echo.rpc.sample.flow/-flow-searching/index.md)  <br><br><br>
| [OrderService](-order-service/index.md)| [jvm]  <br>Brief description  <br><br><br>订单服务抽象<br><br>  <br>Content  <br>abstract class [OrderService](-order-service/index.md)<[T](-order-service/index.md) : [OrderService](-order-service/index.md)<[T](-order-service/index.md), [C](-order-service/index.md), [U](-order-service/index.md), [S](-order-service/index.md), [R](-order-service/index.md), [N](-order-service/index.md), [E](-order-service/index.md), [D](-order-service/index.md)>, [C](-order-service/index.md) : [Payload](../tech.whence.echo.rpc.payload/-payload/index.md), [U](-order-service/index.md) : [Payload](../tech.whence.echo.rpc.payload/-payload/index.md), [S](-order-service/index.md) : [OrderSearching](-order-searching/index.md), [R](-order-service/index.md) : [OrderData](-order-data/index.md), [N](-order-service/index.md) : [IntConst](../tech.whence.echo.container.constant/-int-const/index.md), [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[N](-order-service/index.md)>, [Trackable](../tech.whence.echo.rpc.sample.flow/-trackable/index.md), [E](-order-service/index.md) : [Order](-order/index.md), [D](-order-service/index.md) : [Dao](../tech.whence.echo.dal.dao/-dao/index.md)<[E](-order-service/index.md), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), *>, [Queriable](../tech.whence.echo.dal.dao/-queriable/index.md)<[E](-order-service/index.md), *, *, *, *, *, *, *, *, *>>(**source**: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[E](-order-service/index.md)>, **flow**: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[N](-order-service/index.md)>, **dao**: [D](-order-service/index.md), **identifier**: [Identifier](../tech.whence.echo.dal.entity.id/-identifier/index.md)) : [FlowService](../tech.whence.echo.rpc.sample.flow/-flow-service/index.md)<[T](-order-service/index.md), [C](-order-service/index.md), [U](-order-service/index.md), [S](-order-service/index.md), [R](-order-service/index.md), [N](-order-service/index.md), [E](-order-service/index.md), [D](-order-service/index.md)> , [OrderFacade](-order-facade/index.md)<[C](-order-service/index.md), [U](-order-service/index.md), [S](-order-service/index.md), [R](-order-service/index.md)>   <br><br><br>

