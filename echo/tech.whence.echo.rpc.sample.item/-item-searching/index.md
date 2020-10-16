---
title: ItemSearching -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.sample.item](../index.md)/[ItemSearching](index.md)



# ItemSearching  
 [jvm] 

物品搜索条件

interface [ItemSearching](index.md) : [ResourceSearching](../../tech.whence.echo.rpc.sample.resource/-resource-searching/index.md)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [code](index.md#tech.whence.echo.rpc.sample.item/ItemSearching/code/#/PointingToDeclaration/)|  [jvm] <br><br>Criteria? 编码条件<br><br>abstract var [code](index.md#tech.whence.echo.rpc.sample.item/ItemSearching/code/#/PointingToDeclaration/): [Criterion](../../tech.whence.echo.rpc.request.search.criterion/-criterion/index.md)?   <br>
| [createdAt](index.md#tech.whence.echo.rpc.sample.item/ItemSearching/createdAt/#/PointingToDeclaration/)|  [jvm] <br><br>Criterion? 创建时间条件<br><br>abstract override var [createdAt](index.md#tech.whence.echo.rpc.sample.item/ItemSearching/createdAt/#/PointingToDeclaration/): [Criterion](../../tech.whence.echo.rpc.request.search.criterion/-criterion/index.md)?   <br>
| [enabled](index.md#tech.whence.echo.rpc.sample.item/ItemSearching/enabled/#/PointingToDeclaration/)|  [jvm] <br><br>Criteria? 是否启用条件<br><br>abstract var [enabled](index.md#tech.whence.echo.rpc.sample.item/ItemSearching/enabled/#/PointingToDeclaration/): [Criterion](../../tech.whence.echo.rpc.request.search.criterion/-criterion/index.md)?   <br>
| [id](index.md#tech.whence.echo.rpc.sample.item/ItemSearching/id/#/PointingToDeclaration/)|  [jvm] <br><br>Criterion? 编号条件<br><br>abstract override var [id](index.md#tech.whence.echo.rpc.sample.item/ItemSearching/id/#/PointingToDeclaration/): [Criterion](../../tech.whence.echo.rpc.request.search.criterion/-criterion/index.md)?   <br>
| [name](index.md#tech.whence.echo.rpc.sample.item/ItemSearching/name/#/PointingToDeclaration/)|  [jvm] <br><br>Criteria? 名称条件<br><br>abstract var [name](index.md#tech.whence.echo.rpc.sample.item/ItemSearching/name/#/PointingToDeclaration/): [Criterion](../../tech.whence.echo.rpc.request.search.criterion/-criterion/index.md)?   <br>
| [updatedAt](index.md#tech.whence.echo.rpc.sample.item/ItemSearching/updatedAt/#/PointingToDeclaration/)|  [jvm] <br><br>Criterion? 更新时间条件<br><br>abstract override var [updatedAt](index.md#tech.whence.echo.rpc.sample.item/ItemSearching/updatedAt/#/PointingToDeclaration/): [Criterion](../../tech.whence.echo.rpc.request.search.criterion/-criterion/index.md)?   <br>

