---
title: OrderSearching -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.sample.order](../index.md)/[OrderSearching](index.md)



# OrderSearching  
 [jvm] 

单据搜索条件

interface [OrderSearching](index.md) : [FlowSearching](../../tech.whence.echo.rpc.sample.flow/-flow-searching/index.md)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [auditedAt](index.md#tech.whence.echo.rpc.sample.order/OrderSearching/auditedAt/#/PointingToDeclaration/)|  [jvm] <br><br>Criterion? 审核时间条件<br><br>abstract override var [auditedAt](index.md#tech.whence.echo.rpc.sample.order/OrderSearching/auditedAt/#/PointingToDeclaration/): [Criterion](../../tech.whence.echo.rpc.request.search.criterion/-criterion/index.md)?   <br>
| [createdAt](index.md#tech.whence.echo.rpc.sample.order/OrderSearching/createdAt/#/PointingToDeclaration/)|  [jvm] <br><br>Criterion? 创建时间条件<br><br>abstract override var [createdAt](index.md#tech.whence.echo.rpc.sample.order/OrderSearching/createdAt/#/PointingToDeclaration/): [Criterion](../../tech.whence.echo.rpc.request.search.criterion/-criterion/index.md)?   <br>
| [id](index.md#tech.whence.echo.rpc.sample.order/OrderSearching/id/#/PointingToDeclaration/)|  [jvm] <br><br>Criterion? 编号条件<br><br>abstract override var [id](index.md#tech.whence.echo.rpc.sample.order/OrderSearching/id/#/PointingToDeclaration/): [Criterion](../../tech.whence.echo.rpc.request.search.criterion/-criterion/index.md)?   <br>
| [number](index.md#tech.whence.echo.rpc.sample.order/OrderSearching/number/#/PointingToDeclaration/)|  [jvm] <br><br>Criterion? 单号条件<br><br>abstract var [number](index.md#tech.whence.echo.rpc.sample.order/OrderSearching/number/#/PointingToDeclaration/): [Criterion](../../tech.whence.echo.rpc.request.search.criterion/-criterion/index.md)?   <br>
| [sourceId](index.md#tech.whence.echo.rpc.sample.order/OrderSearching/sourceId/#/PointingToDeclaration/)|  [jvm] <br><br>Criterion? 来源单据编号条件<br><br>abstract var [sourceId](index.md#tech.whence.echo.rpc.sample.order/OrderSearching/sourceId/#/PointingToDeclaration/): [Criterion](../../tech.whence.echo.rpc.request.search.criterion/-criterion/index.md)?   <br>
| [sourceKind](index.md#tech.whence.echo.rpc.sample.order/OrderSearching/sourceKind/#/PointingToDeclaration/)|  [jvm] <br><br>Criterion? 来源单据类型条件<br><br>abstract var [sourceKind](index.md#tech.whence.echo.rpc.sample.order/OrderSearching/sourceKind/#/PointingToDeclaration/): [Criterion](../../tech.whence.echo.rpc.request.search.criterion/-criterion/index.md)?   <br>
| [submittedAt](index.md#tech.whence.echo.rpc.sample.order/OrderSearching/submittedAt/#/PointingToDeclaration/)|  [jvm] <br><br>Criterion? 提交时间条件<br><br>abstract override var [submittedAt](index.md#tech.whence.echo.rpc.sample.order/OrderSearching/submittedAt/#/PointingToDeclaration/): [Criterion](../../tech.whence.echo.rpc.request.search.criterion/-criterion/index.md)?   <br>
| [targetId](index.md#tech.whence.echo.rpc.sample.order/OrderSearching/targetId/#/PointingToDeclaration/)|  [jvm] <br><br>Criterion? 目标单据编号条件<br><br>abstract var [targetId](index.md#tech.whence.echo.rpc.sample.order/OrderSearching/targetId/#/PointingToDeclaration/): [Criterion](../../tech.whence.echo.rpc.request.search.criterion/-criterion/index.md)?   <br>
| [targetKind](index.md#tech.whence.echo.rpc.sample.order/OrderSearching/targetKind/#/PointingToDeclaration/)|  [jvm] <br><br>Criterion? 目标单据类型条件<br><br>abstract var [targetKind](index.md#tech.whence.echo.rpc.sample.order/OrderSearching/targetKind/#/PointingToDeclaration/): [Criterion](../../tech.whence.echo.rpc.request.search.criterion/-criterion/index.md)?   <br>
| [updatedAt](index.md#tech.whence.echo.rpc.sample.order/OrderSearching/updatedAt/#/PointingToDeclaration/)|  [jvm] <br><br>Criterion? 更新时间条件<br><br>abstract override var [updatedAt](index.md#tech.whence.echo.rpc.sample.order/OrderSearching/updatedAt/#/PointingToDeclaration/): [Criterion](../../tech.whence.echo.rpc.request.search.criterion/-criterion/index.md)?   <br>

