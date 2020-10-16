---
title: Batcher -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity.mapper](../index.md)/[Batcher](index.md)



# Batcher  
 [jvm] 

实体批量转换器 缓存实体及其数据做中间用途

class [Batcher](index.md)<[E](index.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)>(**entities**: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[E](index.md)>, **strategist**: [Strategist](../../tech.whence.echo.strategy/-strategist/index.md))   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| E| <br><br>: Entity 实体类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Batcher](-batcher.md)|  [jvm] <br><br><br><br>fun <[E](index.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [Batcher](-batcher.md)(entities: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[E](index.md)>, strategist: [Strategist](../../tech.whence.echo.strategy/-strategist/index.md))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [each](each.md)| [jvm]  <br>Brief description  <br><br><br>循环执行回调<br><br>  <br>Content  <br>fun [each](each.md)(consumer: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<[Map.Entry](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/-entry/index.html)<[E](index.md), [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>>>)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [fix](fix.md)| [jvm]  <br>Brief description  <br><br><br>纠正指定实体转换数据<br><br>  <br>Content  <br>fun [fix](fix.md)(entity: [E](index.md), data: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>): [Batcher](index.md)<[E](index.md)>  <br><br><br>
| [group](group.md)| [jvm]  <br>Brief description  <br><br><br>按回调指定的键分组数据<br><br>  <br>Content  <br>fun <[K](group.md)> [group](group.md)(grouper: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[E](index.md), [K](group.md)>): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[K](group.md), [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>>>  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [list](list.md)| [jvm]  <br>Brief description  <br><br><br>取转换后数据列表<br><br>  <br>Content  <br>fun [list](list.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>>  <br><br><br>
| [map](map.md)| [jvm]  <br>Brief description  <br><br><br>按回调指定的键映射数据<br><br>  <br>Content  <br>fun <[K](map.md)> [map](map.md)(keymaker: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[E](index.md), [K](map.md)>): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[K](map.md), [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>>  <br><br><br>
| [sequence](sequence.md)| [jvm]  <br>Brief description  <br><br><br>序列化<br><br>  <br>Content  <br>fun [sequence](sequence.md)(): [Sequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.sequences/-sequence/index.html)<[Map.Entry](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/-entry/index.html)<[E](index.md), [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>>>  <br><br><br>
| [settle](settle.md)| [jvm]  <br>Brief description  <br><br><br>找到相关策略进行结算<br><br>  <br>Content  <br>fun [settle](settle.md)(): [Batcher](index.md)<[E](index.md)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

