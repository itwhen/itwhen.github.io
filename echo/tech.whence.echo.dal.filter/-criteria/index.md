---
title: Criteria -
---
//[echo](../../index.md)/[tech.whence.echo.dal.filter](../index.md)/[Criteria](index.md)



# Criteria  
 [jvm] 

查询条件

class [Criteria](index.md)(**limit**: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), **page**: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), **data**: [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Key](../../tech.whence.echo.dal.schema.key/-key/index.md), [Criterion](../../tech.whence.echo.rpc.request.search.criterion/-criterion/index.md)>, **keys**: [Keys](../../tech.whence.echo.dal.schema.key/-keys/index.md))   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Criteria](-criteria.md)|  [jvm] <br><br><br><br>fun [Criteria](-criteria.md)(limit: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), page: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), data: [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Key](../../tech.whence.echo.dal.schema.key/-key/index.md), [Criterion](../../tech.whence.echo.rpc.request.search.criterion/-criterion/index.md)>, keys: [Keys](../../tech.whence.echo.dal.schema.key/-keys/index.md))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [add](add.md)| [jvm]  <br>Brief description  <br><br><br>添加条件<br><br>  <br>Content  <br>fun [add](add.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), criterion: [Criterion](../../tech.whence.echo.rpc.request.search.criterion/-criterion/index.md)): [Criteria](index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [into](into.md)| [jvm]  <br>Brief description  <br><br><br>将条件转换到查询器中<br><br>  <br>Content  <br>fun [into](into.md)(retriever: [Retriever](../../tech.whence.echo.dal.querier/-retriever/index.md)<*, *, *, *, *>)  <br>fun [into](into.md)(retriever: [Retriever](../../tech.whence.echo.dal.querier/-retriever/index.md)<*, *, *, *, *>, key: [Key](../../tech.whence.echo.dal.schema.key/-key/index.md), criterion: [Criterion](../../tech.whence.echo.rpc.request.search.criterion/-criterion/index.md))  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [limit](index.md#tech.whence.echo.dal.filter/Criteria/limit/#/PointingToDeclaration/)|  [jvm] <br><br>UInt 每页负载<br><br>var [limit](index.md#tech.whence.echo.dal.filter/Criteria/limit/#/PointingToDeclaration/): [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)   <br>
| [page](index.md#tech.whence.echo.dal.filter/Criteria/page/#/PointingToDeclaration/)|  [jvm] <br><br>UInt 指定页码<br><br>var [page](index.md#tech.whence.echo.dal.filter/Criteria/page/#/PointingToDeclaration/): [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)   <br>

