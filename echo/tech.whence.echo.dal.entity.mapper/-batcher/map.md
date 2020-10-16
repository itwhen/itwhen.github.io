---
title: map -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity.mapper](../index.md)/[Batcher](index.md)/[map](map.md)



# map  
[jvm]  
Brief description  


按回调指定的键映射数据



#### Return  


Map<K, Map<String, Any?>>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| keymaker| <br><br>Transformer<E, K> 键生成<br><br>
  
  
Content  
fun <[K](map.md)> [map](map.md)(keymaker: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[E](index.md), [K](map.md)>): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[K](map.md), [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>>  



