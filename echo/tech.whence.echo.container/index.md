---
title: tech.whence.echo.container -
---
//[echo](../index.md)/[tech.whence.echo.container](index.md)



# Package tech.whence.echo.container  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Accessibility](-accessibility/index.md)| [jvm]  <br>Brief description  <br><br><br>数据可访问性<br><br>  <br>Content  <br>interface [Accessibility](-accessibility/index.md)<[K](-accessibility/index.md), [V](-accessibility/index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>  <br><br><br>
| [Container](-container/index.md)| [jvm]  <br>Brief description  <br><br><br>容器<br><br>  <br>Content  <br>interface [Container](-container/index.md)  <br><br><br>
| [Holder](-holder/index.md)| [jvm]  <br>Brief description  <br><br><br>延迟加载器<br><br>  <br>Content  <br>class [Holder](-holder/index.md)<[T](-holder/index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **factory**: [Transformer](../tech.whence.echo.function/-transformer/index.md)<[T](-holder/index.md)?, [T](-holder/index.md)>)  <br><br><br>
| [Paginator](-paginator/index.md)| [jvm]  <br>Brief description  <br><br><br>数据分页器<br><br>  <br>Content  <br>class [Paginator](-paginator/index.md)<[E](-paginator/index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>(**limit**: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), **page**: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)) : [Reference](../tech.whence.echo.type/-reference/index.md)<[E](-paginator/index.md)> , [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), [Container](-container/index.md)  <br><br><br>
| [Properties](-properties/index.md)| [jvm]  <br>Brief description  <br><br><br>属性管理器<br><br>  <br>Content  <br>object [Properties](-properties/index.md)  <br><br><br>
| [Reply](-reply/index.md)| [jvm]  <br>Brief description  <br><br><br>响应<br><br>  <br>Content  <br>class [Reply](-reply/index.md)<[V](-reply/index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [array](array.md)| [jvm]  <br>Brief description  <br><br><br>将一个对象转换为数组形式<br><br>  <br>Content  <br>inline fun <[R](array.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html).[array](array.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[R](array.md)>  <br>inline fun <[R](array.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html).[array](array.md)(noinline convert: ([Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?) -> [R](array.md)?): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[R](array.md)>  <br><br><br>
| [extract](extract.md)| [jvm]  <br>Brief description  <br><br><br>将一个列表子项里的某项抽取出来<br><br>  <br>Content  <br>inline fun <[K](extract.md), [V](extract.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [R](extract.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[K](extract.md), [V](extract.md)?>>.[extract](extract.md)(key: [K](extract.md), noinline cast: ([V](extract.md)) -> [R](extract.md)??): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[R](extract.md)>  <br><br><br>
| [filterValuesNotNull](filter-values-not-null.md)| [jvm]  <br>Brief description  <br><br><br>过滤非空值<br><br>  <br>Content  <br>fun <[K](filter-values-not-null.md), [V](filter-values-not-null.md)> [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<out [K](filter-values-not-null.md), [V](filter-values-not-null.md)?>.[filterValuesNotNull](filter-values-not-null.md)(): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[K](filter-values-not-null.md), [V](filter-values-not-null.md)>  <br><br><br>
| [jsonify](jsonify.md)| [jvm]  <br>Brief description  <br><br><br>转为 JsonObject 对象<br><br>  <br>Content  <br>fun [jsonify](jsonify.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): JsonObject  <br><br><br>
| [matchFirst](match-first.md)| [jvm]  <br>Brief description  <br><br><br>找到第一个元素 该值经由转换后不为空<br><br>  <br>Content  <br>inline fun <[T](match-first.md), [R](match-first.md)> [Sequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.sequences/-sequence/index.html)<[T](match-first.md)>.[matchFirst](match-first.md)(convert: ([T](match-first.md)) -> [R](match-first.md)?): [R](match-first.md)?  <br><br><br>
| [until](until.md)| [jvm]  <br>Brief description  <br><br><br>遍历每个元素直到返回停止响应<br><br>  <br>Content  <br>fun <[T](until.md), [R](until.md)> [Sequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.sequences/-sequence/index.html)<[T](until.md)>.[until](until.md)(initial: [R](until.md)?, breaker: [Breaker](../tech.whence.echo.function/-breaker/index.md)<[T](until.md), [R](until.md)?>): [R](until.md)?  <br><br><br>

