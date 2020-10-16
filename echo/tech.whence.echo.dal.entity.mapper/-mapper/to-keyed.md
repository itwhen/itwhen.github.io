---
title: toKeyed -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity.mapper](../index.md)/[Mapper](index.md)/[toKeyed](to-keyed.md)



# toKeyed  
[jvm]  
Brief description  


使用策略将实体集合转换 实体指定属性做键 实体转换的映射做值



#### Return  


Map<K, T>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>Collection<E> 指定实体集合<br><br>
| keyBy| <br><br>Transformer<E, K> 取键方法<br><br>
| strategist| <br><br>Strategist 转换策略<br><br>
  
  
Content  
abstract fun <[K](to-keyed.md)> [toKeyed](to-keyed.md)(data: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[E](index.md)>, strategist: [Strategist](../../tech.whence.echo.strategy/-strategist/index.md)?, keyBy: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[E](index.md), [K](to-keyed.md)>): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[K](to-keyed.md), [T](index.md)>  



