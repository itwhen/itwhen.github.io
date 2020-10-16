---
title: toMapGrouped -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity](../index.md)/[EntityMapper](index.md)/[toMapGrouped](to-map-grouped.md)



# toMapGrouped  
[jvm]  
Brief description  


使用多个策略将实体集合转换为映射 实体指定属性做分组键 实体转换的映射列表做值



#### Return  


Map<K, List<Map<String, Any?>>>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| entities| <br><br>Collection<E> 指定实体集合<br><br>
| groupBy| <br><br>Transformer<E, K> 取分组键方法<br><br>
| strategist| <br><br>Strategist 转换策略<br><br>
  
  
Content  
fun <[K](to-map-grouped.md), [E](to-map-grouped.md) : [Entity](../-entity/index.md)> [toMapGrouped](to-map-grouped.md)(entities: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[E](to-map-grouped.md)>, strategist: [Strategist](../../tech.whence.echo.strategy/-strategist/index.md), groupBy: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[E](to-map-grouped.md), [K](to-map-grouped.md)>): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[K](to-map-grouped.md), [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>>>  



