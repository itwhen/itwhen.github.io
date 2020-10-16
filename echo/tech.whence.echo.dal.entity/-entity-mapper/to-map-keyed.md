---
title: toMapKeyed -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity](../index.md)/[EntityMapper](index.md)/[toMapKeyed](to-map-keyed.md)



# toMapKeyed  
[jvm]  
Brief description  


使用多个策略将实体集合转换为映射 实体指定属性做键 实体转换的映射做值



#### Return  


Map<K, Map<String, Any?>>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| entities| <br><br>Collection<E> 指定实体集合<br><br>
| keyBy| <br><br>Transformer<E, K> 取键方法<br><br>
| strategist| <br><br>Strategist 转换策略<br><br>
  
  
Content  
fun <[K](to-map-keyed.md), [E](to-map-keyed.md) : [Entity](../-entity/index.md)> [toMapKeyed](to-map-keyed.md)(entities: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[E](to-map-keyed.md)>, strategist: [Strategist](../../tech.whence.echo.strategy/-strategist/index.md), keyBy: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[E](to-map-keyed.md), [K](to-map-keyed.md)>): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[K](to-map-keyed.md), [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>>  



