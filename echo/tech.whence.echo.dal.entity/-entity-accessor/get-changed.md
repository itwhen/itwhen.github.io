---
title: getChanged -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity](../index.md)/[EntityAccessor](index.md)/[getChanged](get-changed.md)



# getChanged  
[jvm]  
Brief description  


取实体中变化的值



#### Return  


Set<I>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| assembler| <br><br>Assembler<F, T, I> 装配器<br><br>
| entity| <br><br>Entity 指定实体<br><br>
| strategist| <br><br>Strategist? 指定过滤策略 若未设置则返回所有字段<br><br>
  
  
Content  
fun <[F](get-changed.md), [T](get-changed.md), [I](get-changed.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [getChanged](get-changed.md)(entity: [Entity](../-entity/index.md), strategist: [Strategist](../../tech.whence.echo.strategy/-strategist/index.md)?, assembler: [Assembler](../../tech.whence.echo.dal.entity.assembler/-assembler/index.md)<[F](get-changed.md), [T](get-changed.md), [I](get-changed.md)>): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[I](get-changed.md)>  


[jvm]  
Brief description  


取实体中变化的值 若当前实体未被包裹因无法获取原始数据故所有字段都被认为已改变 取指定实体中原始值并判断是否在制作中 取出字段集合中可更新的字段 再使用键值处理器过滤 最后过滤掉未变更的部分



#### Return  


Map<Key, Pair<Any?, V?>>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| entity| <br><br>Entity 指定实体<br><br>
| handler| <br><br>KeyValueHandler<V> 键值处理器<br><br>
  
  
Content  
fun <[V](get-changed.md)> [getChanged](get-changed.md)(entity: [Entity](../-entity/index.md), handler: [EntityAccessor.KeyValueHandler](-key-value-handler/index.md)<[V](get-changed.md)>): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[Key](../../tech.whence.echo.dal.schema.key/-key/index.md), [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, [V](get-changed.md)?>>  


[jvm]  
Brief description  


取实体指定字段数据变化



#### Return  


EntityChanging<V>?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| creating| <br><br>Boolean 是否制作中<br><br>
| entity| <br><br>Entity 指定实体<br><br>
| handler| <br><br>KeyValueHandler<V> 键值处理器<br><br>
| key| <br><br>Key 指定字段<br><br>
| original| <br><br>Accessor 原始数据访问器<br><br>
  
  
Content  
fun <[V](get-changed.md)> [getChanged](get-changed.md)(entity: [Entity](../-entity/index.md), key: [Key](../../tech.whence.echo.dal.schema.key/-key/index.md), creating: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), original: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md), handler: [EntityAccessor.KeyValueHandler](-key-value-handler/index.md)<[V](get-changed.md)>): [EntityAccessor.Change](-change/index.md)<[V](get-changed.md)>?  



