---
title: AbstractDeleter -
---
//[echo](../../index.md)/[tech.whence.echo.dal.querier](../index.md)/[AbstractDeleter](index.md)



# AbstractDeleter  
 [jvm] 

抽象删除器

abstract class [AbstractDeleter](index.md)<[T](index.md) : [AbstractDeleter](index.md)<[T](index.md), [R](index.md), [A](index.md), [C](index.md), [D](index.md)>, [R](index.md) : [Restrictor](../../tech.whence.echo.dal.querier.component/-restrictor/index.md)<[R](index.md), [R](index.md), [A](index.md), [C](index.md)>, [A](index.md) : [Assignment](../../tech.whence.echo.dal.querier.component/-assignment/index.md), [C](index.md) : [Criterion](../../tech.whence.echo.dal.querier.component/-criterion/index.md)<*, [A](index.md), *>, [D](index.md) : [Definition](../../tech.whence.echo.dal.querier.component/-definition/index.md)<*, *>> : [AbstractRestrictor](../../tech.whence.echo.dal.querier.component/-abstract-restrictor/index.md)<[T](index.md), [R](index.md), [A](index.md), [C](index.md)> , [Deleter](../-deleter/index.md)<[T](index.md), [R](index.md), [A](index.md), [C](index.md), [D](index.md)>    


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| C| <br><br>操作<br><br>
| D| <br><br>定义<br><br>
| R| <br><br>约束<br><br>
| T| <br><br>子类<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [AbstractDeleter](-abstract-deleter.md)|  [jvm] <br><br><br><br>fun [AbstractDeleter](-abstract-deleter.md)()   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [and](../../tech.whence.echo.dal.querier.component/-abstract-restrictor/and.md)| [jvm]  <br>Content  <br>open override fun [and](../../tech.whence.echo.dal.querier.component/-abstract-restrictor/and.md)(callback: [R](index.md).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [T](index.md)  <br><br><br>
| [define](../../tech.whence.echo.dal.querier.component/-definer/define.md)| [jvm]  <br>Brief description  <br><br><br>生成定义<br><br>  <br>Content  <br>abstract override fun [define](../../tech.whence.echo.dal.querier.component/-definer/define.md)(): [D](index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [from](from.md)| [jvm]  <br>Brief description  <br><br><br>指定删除来源<br><br>  <br>Content  <br>open override fun [from](from.md)(schema: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [T](index.md)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [or](../../tech.whence.echo.dal.querier.component/-abstract-restrictor/or.md)| [jvm]  <br>Content  <br>open override fun [or](../../tech.whence.echo.dal.querier.component/-abstract-restrictor/or.md)(callback: [R](index.md).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [T](index.md)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [where](../../tech.whence.echo.dal.querier.component/-abstract-restrictor/where.md)| [jvm]  <br>Content  <br>open override fun [where](../../tech.whence.echo.dal.querier.component/-abstract-restrictor/where.md)(criterion: [C](index.md)): [T](index.md)  <br>open override fun [where](../../tech.whence.echo.dal.querier.component/-abstract-restrictor/where.md)(sub: [R](index.md)): [T](index.md)  <br>open override fun [where](../../tech.whence.echo.dal.querier.component/-criteria/where.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [T](index.md)  <br><br><br>
| [whereBetween](../../tech.whence.echo.dal.filter/-filter/where-between.md)| [jvm]  <br>Content  <br>abstract override fun <V : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [whereBetween](../../tech.whence.echo.dal.filter/-filter/where-between.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), range: [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<V, V>): [T](index.md)  <br>open override fun <V : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [whereBetween](../../tech.whence.echo.dal.filter/-filter/where-between.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), minValue: V, maxValue: V): [T](index.md)  <br><br><br>
| [whereEndWith](../../tech.whence.echo.dal.filter/-filter/where-end-with.md)| [jvm]  <br>Content  <br>abstract override fun [whereEndWith](../../tech.whence.echo.dal.filter/-filter/where-end-with.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [T](index.md)  <br><br><br>
| [whereEqual](../../tech.whence.echo.dal.filter/-filter/where-equal.md)| [jvm]  <br>Content  <br>abstract override fun [whereEqual](../../tech.whence.echo.dal.filter/-filter/where-equal.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [T](index.md)  <br><br><br>
| [whereGreaterThan](../../tech.whence.echo.dal.filter/-filter/where-greater-than.md)| [jvm]  <br>Content  <br>abstract override fun [whereGreaterThan](../../tech.whence.echo.dal.filter/-filter/where-greater-than.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [T](index.md)  <br><br><br>
| [whereGreaterThanOrEqual](../../tech.whence.echo.dal.filter/-filter/where-greater-than-or-equal.md)| [jvm]  <br>Content  <br>abstract override fun [whereGreaterThanOrEqual](../../tech.whence.echo.dal.filter/-filter/where-greater-than-or-equal.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [T](index.md)  <br><br><br>
| [whereIn](../../tech.whence.echo.dal.filter/-filter/where-in.md)| [jvm]  <br>Content  <br>open override fun <V : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [whereIn](../../tech.whence.echo.dal.filter/-filter/where-in.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), vararg values: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out V>): [T](index.md)  <br>abstract override fun <V : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [whereIn](../../tech.whence.echo.dal.filter/-filter/where-in.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), values: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<V>): [T](index.md)  <br><br><br>
| [whereIsNotNull](../../tech.whence.echo.dal.filter/-filter/where-is-not-null.md)| [jvm]  <br>Content  <br>abstract override fun [whereIsNotNull](../../tech.whence.echo.dal.filter/-filter/where-is-not-null.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [T](index.md)  <br><br><br>
| [whereIsNull](../../tech.whence.echo.dal.filter/-filter/where-is-null.md)| [jvm]  <br>Content  <br>abstract override fun [whereIsNull](../../tech.whence.echo.dal.filter/-filter/where-is-null.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [T](index.md)  <br><br><br>
| [whereLessThan](../../tech.whence.echo.dal.filter/-filter/where-less-than.md)| [jvm]  <br>Content  <br>abstract override fun [whereLessThan](../../tech.whence.echo.dal.filter/-filter/where-less-than.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [T](index.md)  <br><br><br>
| [whereLessThanOrEqual](../../tech.whence.echo.dal.filter/-filter/where-less-than-or-equal.md)| [jvm]  <br>Content  <br>abstract override fun [whereLessThanOrEqual](../../tech.whence.echo.dal.filter/-filter/where-less-than-or-equal.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [T](index.md)  <br><br><br>
| [whereLike](../../tech.whence.echo.dal.filter/-filter/where-like.md)| [jvm]  <br>Content  <br>abstract override fun [whereLike](../../tech.whence.echo.dal.filter/-filter/where-like.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [T](index.md)  <br><br><br>
| [whereMatch](../../tech.whence.echo.dal.filter/-filter/where-match.md)| [jvm]  <br>Content  <br>abstract override fun [whereMatch](../../tech.whence.echo.dal.filter/-filter/where-match.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [T](index.md)  <br><br><br>
| [whereNotBetween](../../tech.whence.echo.dal.filter/-filter/where-not-between.md)| [jvm]  <br>Content  <br>abstract override fun <V : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [whereNotBetween](../../tech.whence.echo.dal.filter/-filter/where-not-between.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), range: [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<V, V>): [T](index.md)  <br>open override fun <V : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [whereNotBetween](../../tech.whence.echo.dal.filter/-filter/where-not-between.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), minValue: V, maxValue: V): [T](index.md)  <br><br><br>
| [whereNotEndWith](../../tech.whence.echo.dal.filter/-filter/where-not-end-with.md)| [jvm]  <br>Content  <br>abstract override fun [whereNotEndWith](../../tech.whence.echo.dal.filter/-filter/where-not-end-with.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [T](index.md)  <br><br><br>
| [whereNotEqual](../../tech.whence.echo.dal.filter/-filter/where-not-equal.md)| [jvm]  <br>Content  <br>abstract override fun [whereNotEqual](../../tech.whence.echo.dal.filter/-filter/where-not-equal.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [T](index.md)  <br><br><br>
| [whereNotIn](../../tech.whence.echo.dal.filter/-filter/where-not-in.md)| [jvm]  <br>Content  <br>open override fun <V : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [whereNotIn](../../tech.whence.echo.dal.filter/-filter/where-not-in.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), vararg values: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out V>): [T](index.md)  <br>abstract override fun <V : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [whereNotIn](../../tech.whence.echo.dal.filter/-filter/where-not-in.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), values: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<V>): [T](index.md)  <br><br><br>
| [whereNotLike](../../tech.whence.echo.dal.filter/-filter/where-not-like.md)| [jvm]  <br>Content  <br>abstract override fun [whereNotLike](../../tech.whence.echo.dal.filter/-filter/where-not-like.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [T](index.md)  <br><br><br>
| [whereNotMatch](../../tech.whence.echo.dal.filter/-filter/where-not-match.md)| [jvm]  <br>Content  <br>abstract override fun [whereNotMatch](../../tech.whence.echo.dal.filter/-filter/where-not-match.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [T](index.md)  <br><br><br>
| [whereNotStartWith](../../tech.whence.echo.dal.filter/-filter/where-not-start-with.md)| [jvm]  <br>Content  <br>abstract override fun [whereNotStartWith](../../tech.whence.echo.dal.filter/-filter/where-not-start-with.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [T](index.md)  <br><br><br>
| [whereRaw](../../tech.whence.echo.dal.querier.component/-criteria/where-raw.md)| [jvm]  <br>Content  <br>abstract override fun [whereRaw](../../tech.whence.echo.dal.querier.component/-criteria/where-raw.md)(query: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [T](index.md)  <br><br><br>
| [whereStartWith](../../tech.whence.echo.dal.filter/-filter/where-start-with.md)| [jvm]  <br>Content  <br>abstract override fun [whereStartWith](../../tech.whence.echo.dal.filter/-filter/where-start-with.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [T](index.md)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [description](index.md#tech.whence.echo.dal.querier/AbstractDeleter/description/#/PointingToDeclaration/)|  [jvm] <br><br>String? 描述<br><br>open override val [description](index.md#tech.whence.echo.dal.querier/AbstractDeleter/description/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [renamer](index.md#tech.whence.echo.dal.querier/AbstractDeleter/renamer/#/PointingToDeclaration/)|  [jvm] override var [renamer](index.md#tech.whence.echo.dal.querier/AbstractDeleter/renamer/#/PointingToDeclaration/): [Fixer](../../tech.whence.echo.function/-fixer/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>   <br>
| [valid](index.md#tech.whence.echo.dal.querier/AbstractDeleter/valid/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否有效<br><br>open override val [valid](index.md#tech.whence.echo.dal.querier/AbstractDeleter/valid/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>


## Inheritors  
  
|  Name| 
|---|
| [AbstractDelete](../../tech.whence.echo.support.jdbc.querier/-abstract-delete/index.md)
| [Delete](../../tech.whence.echo.support.mongo.querier/-delete/index.md)

