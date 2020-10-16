---
title: group -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity.mapper](../index.md)/[Batcher](index.md)/[group](group.md)



# group  
[jvm]  
Brief description  


按回调指定的键分组数据



#### Return  


Map<K, List<Map<String, Any?>>>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| grouper| <br><br>Transformer<E, K> 分组<br><br>
  
  
Content  
fun <[K](group.md)> [group](group.md)(grouper: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[E](index.md), [K](group.md)>): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[K](group.md), [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>>>  



