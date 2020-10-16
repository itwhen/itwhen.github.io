---
title: Filter -
---
//[echo](../../index.md)/[tech.whence.echo.dal.filter](../index.md)/[Filter](index.md)



# Filter  
 [jvm] 

过滤器

interface [Filter](index.md)<[T](index.md)>   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| T| <br><br>子类<br><br>
  


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [whereBetween](where-between.md)| [jvm]  <br>Brief description  <br><br><br>判断指定字段是否在指定值范围内<br><br>  <br>Content  <br>abstract fun <[V](where-between.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [whereBetween](where-between.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), range: [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[V](where-between.md), [V](where-between.md)>): [T](index.md)  <br>open fun <[V](where-between.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [whereBetween](where-between.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), minValue: [V](where-between.md), maxValue: [V](where-between.md)): [T](index.md)  <br><br><br>
| [whereEndWith](where-end-with.md)| [jvm]  <br>Brief description  <br><br><br>判断指定字段是否以指定值结束<br><br>  <br>Content  <br>abstract fun [whereEndWith](where-end-with.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [T](index.md)  <br><br><br>
| [whereEqual](where-equal.md)| [jvm]  <br>Brief description  <br><br><br>判断指定字段是否与指定值相等<br><br>  <br>Content  <br>abstract fun [whereEqual](where-equal.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [T](index.md)  <br><br><br>
| [whereGreaterThan](where-greater-than.md)| [jvm]  <br>Brief description  <br><br><br>判断指定字段是否大于指定值<br><br>  <br>Content  <br>abstract fun [whereGreaterThan](where-greater-than.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [T](index.md)  <br><br><br>
| [whereGreaterThanOrEqual](where-greater-than-or-equal.md)| [jvm]  <br>Brief description  <br><br><br>判断指定字段是否大于等于指定值<br><br>  <br>Content  <br>abstract fun [whereGreaterThanOrEqual](where-greater-than-or-equal.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [T](index.md)  <br><br><br>
| [whereIn](where-in.md)| [jvm]  <br>Brief description  <br><br><br>判断指定字段是否在指定值内<br><br>  <br>Content  <br>open fun <[V](where-in.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [whereIn](where-in.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), vararg values: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [V](where-in.md)>): [T](index.md)  <br>abstract fun <[V](where-in.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [whereIn](where-in.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), values: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[V](where-in.md)>): [T](index.md)  <br><br><br>
| [whereIsNotNull](where-is-not-null.md)| [jvm]  <br>Brief description  <br><br><br>判断指定字段是否不为空<br><br>  <br>Content  <br>abstract fun [whereIsNotNull](where-is-not-null.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [T](index.md)  <br><br><br>
| [whereIsNull](where-is-null.md)| [jvm]  <br>Brief description  <br><br><br>判断指定字段是否为空<br><br>  <br>Content  <br>abstract fun [whereIsNull](where-is-null.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [T](index.md)  <br><br><br>
| [whereLessThan](where-less-than.md)| [jvm]  <br>Brief description  <br><br><br>判断指定字段是否小于指定值<br><br>  <br>Content  <br>abstract fun [whereLessThan](where-less-than.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [T](index.md)  <br><br><br>
| [whereLessThanOrEqual](where-less-than-or-equal.md)| [jvm]  <br>Brief description  <br><br><br>判断指定字段是否小于等于指定值<br><br>  <br>Content  <br>abstract fun [whereLessThanOrEqual](where-less-than-or-equal.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [T](index.md)  <br><br><br>
| [whereLike](where-like.md)| [jvm]  <br>Brief description  <br><br><br>判断指定字段是否与指定值相似<br><br>  <br>Content  <br>abstract fun [whereLike](where-like.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [T](index.md)  <br><br><br>
| [whereMatch](where-match.md)| [jvm]  <br>Brief description  <br><br><br>判断指定字段是否与指定值匹配<br><br>  <br>Content  <br>abstract fun [whereMatch](where-match.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [T](index.md)  <br><br><br>
| [whereNotBetween](where-not-between.md)| [jvm]  <br>Brief description  <br><br><br>判断指定字段是否不在指定值范围内<br><br>  <br>Content  <br>abstract fun <[V](where-not-between.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [whereNotBetween](where-not-between.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), range: [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[V](where-not-between.md), [V](where-not-between.md)>): [T](index.md)  <br>open fun <[V](where-not-between.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [whereNotBetween](where-not-between.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), minValue: [V](where-not-between.md), maxValue: [V](where-not-between.md)): [T](index.md)  <br><br><br>
| [whereNotEndWith](where-not-end-with.md)| [jvm]  <br>Brief description  <br><br><br>判断指定字段是否不以指定值结束<br><br>  <br>Content  <br>abstract fun [whereNotEndWith](where-not-end-with.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [T](index.md)  <br><br><br>
| [whereNotEqual](where-not-equal.md)| [jvm]  <br>Brief description  <br><br><br>判断指定字段是否与指定值不相等<br><br>  <br>Content  <br>abstract fun [whereNotEqual](where-not-equal.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [T](index.md)  <br><br><br>
| [whereNotIn](where-not-in.md)| [jvm]  <br>Brief description  <br><br><br>判断指定字段是否不在指定值内<br><br>  <br>Content  <br>open fun <[V](where-not-in.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [whereNotIn](where-not-in.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), vararg values: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [V](where-not-in.md)>): [T](index.md)  <br>abstract fun <[V](where-not-in.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [whereNotIn](where-not-in.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), values: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[V](where-not-in.md)>): [T](index.md)  <br><br><br>
| [whereNotLike](where-not-like.md)| [jvm]  <br>Brief description  <br><br><br>判断指定字段是否不与指定值相似<br><br>  <br>Content  <br>abstract fun [whereNotLike](where-not-like.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [T](index.md)  <br><br><br>
| [whereNotMatch](where-not-match.md)| [jvm]  <br>Brief description  <br><br><br>判断指定字段是否与指定值匹配<br><br>  <br>Content  <br>abstract fun [whereNotMatch](where-not-match.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [T](index.md)  <br><br><br>
| [whereNotStartWith](where-not-start-with.md)| [jvm]  <br>Brief description  <br><br><br>判断指定字段是否不以指定值开始<br><br>  <br>Content  <br>abstract fun [whereNotStartWith](where-not-start-with.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [T](index.md)  <br><br><br>
| [whereStartWith](where-start-with.md)| [jvm]  <br>Brief description  <br><br><br>判断指定字段是否以指定值开始<br><br>  <br>Content  <br>abstract fun [whereStartWith](where-start-with.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [T](index.md)  <br><br><br>


## Inheritors  
  
|  Name| 
|---|
| [Criteria](../../tech.whence.echo.dal.querier.component/-criteria/index.md)

