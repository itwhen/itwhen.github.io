---
title: ofGrouped -
---
//[echo](../../../index.md)/[tech.whence.echo.dal.entity.mapper.strategy](../../index.md)/[BatchSettlingStrategy](../index.md)/[Companion](index.md)/[ofGrouped](of-grouped.md)



# ofGrouped  
[jvm]  
Brief description  


分组



#### Return  


BatchSettlingStrategy<E, K, List<Map<String, Any?>>>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| finder| <br><br>Transformer<Set<K>, List<T>> 查数据<br><br>
| fixAt| <br><br>String? 纠正点<br><br>
| keymaker| <br><br>Transformer<E, K> 取字段<br><br>
| organizer| <br><br>Transformer<T, K> 分组<br><br>
  
  
Content  
fun <[E](of-grouped.md) : [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md), [T](of-grouped.md) : [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md), [K](of-grouped.md)> [ofGrouped](of-grouped.md)(keymaker: [Transformer](../../../tech.whence.echo.function/-transformer/index.md)<[E](of-grouped.md), [K](of-grouped.md)>, finder: [Transformer](../../../tech.whence.echo.function/-transformer/index.md)<[Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[K](of-grouped.md)>, [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](of-grouped.md)>>, organizer: [Transformer](../../../tech.whence.echo.function/-transformer/index.md)<[T](of-grouped.md), [K](of-grouped.md)>, fixAt: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [BatchSettlingStrategy](../index.md)<[E](of-grouped.md), [K](of-grouped.md), [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>>>  



