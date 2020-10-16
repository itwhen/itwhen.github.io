---
title: Mapper -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity.mapper](../index.md)/[Mapper](index.md)



# Mapper  
 [jvm] 

实体转换接口

interface [Mapper](index.md)<[E](index.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md), [T](index.md)>   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| E| <br><br>: Entity<br><br>
| T| <br><br><br><br>
  


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [from](from.md)| [jvm]  <br>Brief description  <br><br><br>转换到实体<br><br>  <br>Content  <br>abstract fun [from](from.md)(data: [T](index.md), entity: [E](index.md)): [E](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>将数据转换为实体<br><br>  <br>Content  <br>abstract fun [from](from.md)(data: [T](index.md), declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[E](index.md)>): [E](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>将映射转换到实体<br><br>  <br>Content  <br>abstract fun [from](from.md)(data: [T](index.md), creator: [Producer](../../tech.whence.echo.function/-producer/index.md)<[E](index.md)>): [E](index.md)  <br><br><br>
| [fromGrouped](from-grouped.md)| [jvm]  <br>Brief description  <br><br><br>将列表转换为实体列表 提供一个回调用来纠正实体 若在此时返回空则从列表中移除之<br><br>  <br>Content  <br>abstract fun [fromGrouped](from-grouped.md)(data: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](index.md)>>, declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[E](index.md)>, fixer: [Fixer](../../tech.whence.echo.function/-fixer/index.md)<[E](index.md)>?): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[E](index.md)>>  <br><br><br>
| [fromKeyed](from-keyed.md)| [jvm]  <br>Brief description  <br><br><br>将列表转换为实体列表 提供一个回调用来纠正实体 若在此时返回空则从列表中移除之<br><br>  <br>Content  <br>abstract fun [fromKeyed](from-keyed.md)(data: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [T](index.md)>, declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[E](index.md)>, fixer: [Fixer](../../tech.whence.echo.function/-fixer/index.md)<[E](index.md)>?): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [E](index.md)>  <br><br><br>
| [fromList](from-list.md)| [jvm]  <br>Brief description  <br><br><br>将列表转换为实体列表 提供一个回调用来纠正实体 若在此时返回空则从列表中移除之<br><br>  <br>Content  <br>abstract fun [fromList](from-list.md)(data: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](index.md)>, declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[E](index.md)>, fixer: [Fixer](../../tech.whence.echo.function/-fixer/index.md)<[E](index.md)>?): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[E](index.md)>  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [to](to.md)| [jvm]  <br>Brief description  <br><br><br>使用策略将实体转换 获取实体中实际字段数据及附加数据 再针对字段值的不同类型分别处理 再应用策略处理<br><br>  <br>Content  <br>abstract fun [to](to.md)(entity: [E](index.md), strategist: [Strategist](../../tech.whence.echo.strategy/-strategist/index.md)?): [T](index.md)  <br><br><br>
| [toGrouped](to-grouped.md)| [jvm]  <br>Brief description  <br><br><br>使用策略将实体集合转换 实体指定属性做分组键 实体转换的映射列表做值<br><br>  <br>Content  <br>abstract fun <[K](to-grouped.md)> [toGrouped](to-grouped.md)(data: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[E](index.md)>, strategist: [Strategist](../../tech.whence.echo.strategy/-strategist/index.md)?, groupBy: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[E](index.md), [K](to-grouped.md)>): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[K](to-grouped.md), [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](index.md)>>  <br><br><br>
| [toKeyed](to-keyed.md)| [jvm]  <br>Brief description  <br><br><br>使用策略将实体集合转换 实体指定属性做键 实体转换的映射做值<br><br>  <br>Content  <br>abstract fun <[K](to-keyed.md)> [toKeyed](to-keyed.md)(data: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[E](index.md)>, strategist: [Strategist](../../tech.whence.echo.strategy/-strategist/index.md)?, keyBy: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[E](index.md), [K](to-keyed.md)>): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[K](to-keyed.md), [T](index.md)>  <br><br><br>
| [toList](to-list.md)| [jvm]  <br>Brief description  <br><br><br>使用策略将实体集合转换为列表<br><br>  <br>Content  <br>abstract fun [toList](to-list.md)(data: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[E](index.md)>, strategist: [Strategist](../../tech.whence.echo.strategy/-strategist/index.md)?): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](index.md)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

