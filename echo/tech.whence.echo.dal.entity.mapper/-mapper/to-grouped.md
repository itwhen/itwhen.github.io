---
title: toGrouped -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity.mapper](../index.md)/[Mapper](index.md)/[toGrouped](to-grouped.md)



# toGrouped  
[jvm]  
Brief description  


使用策略将实体集合转换 实体指定属性做分组键 实体转换的映射列表做值



#### Return  


Map<K, List<T>>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>Collection<E> 指定实体集合<br><br>
| groupBy| <br><br>Transformer<E, K> 取分组键方法<br><br>
| strategist| <br><br>Strategist 转换策略<br><br>
  
  
Content  
abstract fun <[K](to-grouped.md)> [toGrouped](to-grouped.md)(data: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[E](index.md)>, strategist: [Strategist](../../tech.whence.echo.strategy/-strategist/index.md)?, groupBy: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[E](index.md), [K](to-grouped.md)>): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[K](to-grouped.md), [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](index.md)>>  



