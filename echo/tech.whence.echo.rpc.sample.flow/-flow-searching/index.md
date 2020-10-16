---
title: FlowSearching -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.sample.flow](../index.md)/[FlowSearching](index.md)



# FlowSearching  
 [jvm] 

流程搜索条件

interface [FlowSearching](index.md) : [ResourceSearching](../../tech.whence.echo.rpc.sample.resource/-resource-searching/index.md)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [auditedAt](index.md#tech.whence.echo.rpc.sample.flow/FlowSearching/auditedAt/#/PointingToDeclaration/)|  [jvm] <br><br>Criterion? 审核时间条件<br><br>abstract var [auditedAt](index.md#tech.whence.echo.rpc.sample.flow/FlowSearching/auditedAt/#/PointingToDeclaration/): [Criterion](../../tech.whence.echo.rpc.request.search.criterion/-criterion/index.md)?   <br>
| [createdAt](index.md#tech.whence.echo.rpc.sample.flow/FlowSearching/createdAt/#/PointingToDeclaration/)|  [jvm] <br><br>Criterion? 创建时间条件<br><br>abstract override var [createdAt](index.md#tech.whence.echo.rpc.sample.flow/FlowSearching/createdAt/#/PointingToDeclaration/): [Criterion](../../tech.whence.echo.rpc.request.search.criterion/-criterion/index.md)?   <br>
| [id](index.md#tech.whence.echo.rpc.sample.flow/FlowSearching/id/#/PointingToDeclaration/)|  [jvm] <br><br>Criterion? 编号条件<br><br>abstract override var [id](index.md#tech.whence.echo.rpc.sample.flow/FlowSearching/id/#/PointingToDeclaration/): [Criterion](../../tech.whence.echo.rpc.request.search.criterion/-criterion/index.md)?   <br>
| [submittedAt](index.md#tech.whence.echo.rpc.sample.flow/FlowSearching/submittedAt/#/PointingToDeclaration/)|  [jvm] <br><br>Criterion? 提交时间条件<br><br>abstract var [submittedAt](index.md#tech.whence.echo.rpc.sample.flow/FlowSearching/submittedAt/#/PointingToDeclaration/): [Criterion](../../tech.whence.echo.rpc.request.search.criterion/-criterion/index.md)?   <br>
| [updatedAt](index.md#tech.whence.echo.rpc.sample.flow/FlowSearching/updatedAt/#/PointingToDeclaration/)|  [jvm] <br><br>Criterion? 更新时间条件<br><br>abstract override var [updatedAt](index.md#tech.whence.echo.rpc.sample.flow/FlowSearching/updatedAt/#/PointingToDeclaration/): [Criterion](../../tech.whence.echo.rpc.request.search.criterion/-criterion/index.md)?   <br>


## Inheritors  
  
|  Name| 
|---|
| [OrderSearching](../../tech.whence.echo.rpc.sample.order/-order-searching/index.md)

