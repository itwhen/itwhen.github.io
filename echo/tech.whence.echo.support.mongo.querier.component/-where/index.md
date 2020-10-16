---
title: Where -
---
//[echo](../../index.md)/[tech.whence.echo.support.mongo.querier.component](../index.md)/[Where](index.md)



# Where  
 [jvm] 

查询条件

class [Where](index.md) : [Criteria](../-criteria/index.md)<[Where](index.md)> , [Restrictor](../../tech.whence.echo.dal.querier.component/-restrictor/index.md)<[Where](index.md), [Where](index.md), [Column](../-column/index.md), [Criterion](../-criterion/index.md)<*>> , [Container](../../tech.whence.echo.container/-container/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Where](-where.md)|  [jvm] fun [Where](-where.md)()   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [and](and.md)| [jvm]  <br>Brief description  <br><br><br>并且<br><br>  <br>Content  <br>open override fun [and](and.md)(callback: [Where](index.md).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [Where](index.md)  <br><br><br>
| [describe](describe.md)| [jvm]  <br>Brief description  <br><br><br>描述<br><br>  <br>Content  <br>fun [describe](describe.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [or](or.md)| [jvm]  <br>Brief description  <br><br><br>或者<br><br>  <br>Content  <br>open override fun [or](or.md)(callback: [Where](index.md).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [Where](index.md)  <br><br><br>
| [prepare](prepare.md)| [jvm]  <br>Brief description  <br><br><br>预备<br><br>  <br>Content  <br>fun [prepare](prepare.md)(): JsonObject  <br><br><br>
| [toString](to-string.md)| [jvm]  <br>Content  <br>open override fun [toString](to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [where](where.md)| [jvm]  <br>Brief description  <br><br><br>指定约束条件<br><br>  <br>Content  <br>open override fun [where](where.md)(criterion: [Criterion](../-criterion/index.md)<*>): [Where](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置子约束<br><br>  <br>Content  <br>open override fun [where](where.md)(sub: [Where](index.md)): [Where](index.md)  <br><br><br>[jvm]  <br>Content  <br>open override fun [where](../../tech.whence.echo.dal.querier.component/-criteria/where.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Where](index.md)  <br><br><br>
| [whereBetween](../-criteria/where-between.md)| [jvm]  <br>Content  <br>open override fun <V : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [whereBetween](../-criteria/where-between.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), range: [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<V, V>): [Where](index.md)  <br>open override fun <V : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [whereBetween](../../tech.whence.echo.dal.filter/-filter/where-between.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), minValue: V, maxValue: V): [Where](index.md)  <br><br><br>
| [whereEndWith](../-criteria/where-end-with.md)| [jvm]  <br>Content  <br>open override fun [whereEndWith](../-criteria/where-end-with.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Where](index.md)  <br><br><br>
| [whereEqual](../-criteria/where-equal.md)| [jvm]  <br>Content  <br>open override fun [whereEqual](../-criteria/where-equal.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Where](index.md)  <br><br><br>
| [whereGreaterThan](../-criteria/where-greater-than.md)| [jvm]  <br>Content  <br>open override fun [whereGreaterThan](../-criteria/where-greater-than.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Where](index.md)  <br><br><br>
| [whereGreaterThanOrEqual](../-criteria/where-greater-than-or-equal.md)| [jvm]  <br>Content  <br>open override fun [whereGreaterThanOrEqual](../-criteria/where-greater-than-or-equal.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Where](index.md)  <br><br><br>
| [whereIn](../../tech.whence.echo.dal.filter/-filter/where-in.md)| [jvm]  <br>Content  <br>open override fun <V : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [whereIn](../../tech.whence.echo.dal.filter/-filter/where-in.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), vararg values: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out V>): [Where](index.md)  <br>open override fun <V : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [whereIn](../-criteria/where-in.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), values: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<V>): [Where](index.md)  <br><br><br>
| [whereIsNotNull](../-criteria/where-is-not-null.md)| [jvm]  <br>Content  <br>open override fun [whereIsNotNull](../-criteria/where-is-not-null.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Where](index.md)  <br><br><br>
| [whereIsNull](../-criteria/where-is-null.md)| [jvm]  <br>Content  <br>open override fun [whereIsNull](../-criteria/where-is-null.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Where](index.md)  <br><br><br>
| [whereLessThan](../-criteria/where-less-than.md)| [jvm]  <br>Content  <br>open override fun [whereLessThan](../-criteria/where-less-than.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Where](index.md)  <br><br><br>
| [whereLessThanOrEqual](../-criteria/where-less-than-or-equal.md)| [jvm]  <br>Content  <br>open override fun [whereLessThanOrEqual](../-criteria/where-less-than-or-equal.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Where](index.md)  <br><br><br>
| [whereLike](../-criteria/where-like.md)| [jvm]  <br>Content  <br>open override fun [whereLike](../-criteria/where-like.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Where](index.md)  <br><br><br>
| [whereMatch](../-criteria/where-match.md)| [jvm]  <br>Content  <br>open override fun [whereMatch](../-criteria/where-match.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Where](index.md)  <br><br><br>
| [whereNotBetween](../-criteria/where-not-between.md)| [jvm]  <br>Content  <br>open override fun <V : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [whereNotBetween](../-criteria/where-not-between.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), range: [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<V, V>): [Where](index.md)  <br>open override fun <V : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [whereNotBetween](../../tech.whence.echo.dal.filter/-filter/where-not-between.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), minValue: V, maxValue: V): [Where](index.md)  <br><br><br>
| [whereNotEndWith](../-criteria/where-not-end-with.md)| [jvm]  <br>Content  <br>open override fun [whereNotEndWith](../-criteria/where-not-end-with.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Where](index.md)  <br><br><br>
| [whereNotEqual](../-criteria/where-not-equal.md)| [jvm]  <br>Content  <br>open override fun [whereNotEqual](../-criteria/where-not-equal.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Where](index.md)  <br><br><br>
| [whereNotIn](../../tech.whence.echo.dal.filter/-filter/where-not-in.md)| [jvm]  <br>Content  <br>open override fun <V : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [whereNotIn](../../tech.whence.echo.dal.filter/-filter/where-not-in.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), vararg values: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out V>): [Where](index.md)  <br>open override fun <V : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [whereNotIn](../-criteria/where-not-in.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), values: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<V>): [Where](index.md)  <br><br><br>
| [whereNotLike](../-criteria/where-not-like.md)| [jvm]  <br>Content  <br>open override fun [whereNotLike](../-criteria/where-not-like.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Where](index.md)  <br><br><br>
| [whereNotMatch](../-criteria/where-not-match.md)| [jvm]  <br>Content  <br>open override fun [whereNotMatch](../-criteria/where-not-match.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Where](index.md)  <br><br><br>
| [whereNotStartWith](../-criteria/where-not-start-with.md)| [jvm]  <br>Content  <br>open override fun [whereNotStartWith](../-criteria/where-not-start-with.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Where](index.md)  <br><br><br>
| [whereRaw](../-criteria/where-raw.md)| [jvm]  <br>Content  <br>open override fun [whereRaw](../-criteria/where-raw.md)(query: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Where](index.md)  <br><br><br>
| [whereStartWith](../-criteria/where-start-with.md)| [jvm]  <br>Content  <br>open override fun [whereStartWith](../-criteria/where-start-with.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Where](index.md)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [empty](index.md#tech.whence.echo.support.mongo.querier.component/Where/empty/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否为空<br><br>open override val [empty](index.md#tech.whence.echo.support.mongo.querier.component/Where/empty/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [size](index.md#tech.whence.echo.support.mongo.querier.component/Where/size/#/PointingToDeclaration/)|  [jvm] <br><br>UInt 当前容器总数据量<br><br>open override val [size](index.md#tech.whence.echo.support.mongo.querier.component/Where/size/#/PointingToDeclaration/): [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)   <br>

