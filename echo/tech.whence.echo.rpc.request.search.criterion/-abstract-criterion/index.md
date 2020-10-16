---
title: AbstractCriterion -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.request.search.criterion](../index.md)/[AbstractCriterion](index.md)



# AbstractCriterion  
 [jvm] 

搜索条件

abstract class [AbstractCriterion](index.md)<[T](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>(**operator**: [Operator](../../tech.whence.echo.dal.filter/-operator/index.md), **original**: [T](index.md), **value**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) : [Criterion](../-criterion/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [AbstractCriterion](-abstract-criterion.md)|  [jvm] <br><br><br><br>fun <[T](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [AbstractCriterion](-abstract-criterion.md)(operator: [Operator](../../tech.whence.echo.dal.filter/-operator/index.md), original: [T](index.md), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?)   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [encode](encode.md)| [jvm]  <br>Brief description  <br><br><br>编码为字符串<br><br>  <br>Content  <br>open override fun [encode](encode.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [operator](index.md#tech.whence.echo.rpc.request.search.criterion/AbstractCriterion/operator/#/PointingToDeclaration/)|  [jvm] <br><br>Operator 操作符<br><br>val [operator](index.md#tech.whence.echo.rpc.request.search.criterion/AbstractCriterion/operator/#/PointingToDeclaration/): [Operator](../../tech.whence.echo.dal.filter/-operator/index.md)   <br>
| [original](index.md#tech.whence.echo.rpc.request.search.criterion/AbstractCriterion/original/#/PointingToDeclaration/)|  [jvm] <br><br>T 初始值<br><br>open override val [original](index.md#tech.whence.echo.rpc.request.search.criterion/AbstractCriterion/original/#/PointingToDeclaration/): [T](index.md)   <br>
| [value](index.md#tech.whence.echo.rpc.request.search.criterion/AbstractCriterion/value/#/PointingToDeclaration/)|  [jvm] <br><br>Any? 指定值<br><br>val [value](index.md#tech.whence.echo.rpc.request.search.criterion/AbstractCriterion/value/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>


## Inheritors  
  
|  Name| 
|---|
| [Between](../-between/index.md)
| [EndWith](../-end-with/index.md)
| [Equal](../-equal/index.md)
| [GreaterThan](../-greater-than/index.md)
| [GreaterThanOrEqual](../-greater-than-or-equal/index.md)
| [In](../-in/index.md)
| [IsNotNull](../-is-not-null/index.md)
| [IsNull](../-is-null/index.md)
| [LessThan](../-less-than/index.md)
| [LessThanOrEqual](../-less-than-or-equal/index.md)
| [Like](../-like/index.md)
| [Match](../-match/index.md)
| [NotBetween](../-not-between/index.md)
| [NotEndWith](../-not-end-with/index.md)
| [NotEqual](../-not-equal/index.md)
| [NotIn](../-not-in/index.md)
| [NotLike](../-not-like/index.md)
| [NotMatch](../-not-match/index.md)
| [NotStartWith](../-not-start-with/index.md)
| [StartWith](../-start-with/index.md)

