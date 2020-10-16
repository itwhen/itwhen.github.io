---
title: toPaginator -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity](../index.md)/[EntityMapper](index.md)/[toPaginator](to-paginator.md)



# toPaginator  
[jvm]  
Brief description  


使用多个策略将实体分页器转换为映射分页器



#### Return  


Paginator<Map<String, Any?>>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| entities| <br><br>Paginator<E> 指定实体分页器<br><br>
| strategist| <br><br>Strategist 转换策略<br><br>
  
  
Content  
fun <[E](to-paginator.md) : [Entity](../-entity/index.md)> [toPaginator](to-paginator.md)(entities: [Paginator](../../tech.whence.echo.container/-paginator/index.md)<[E](to-paginator.md)>, strategist: [Strategist](../../tech.whence.echo.strategy/-strategist/index.md)): [Paginator](../../tech.whence.echo.container/-paginator/index.md)<[Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>>  


[jvm]  
Brief description  


将实体分页组件转换为映射分页组件 并在转换过程中纠正数据



#### Return  


Paginator<Map<String, Any?>>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| entities| <br><br>Paginator<E> 指定实体分页器<br><br>
| fixer| <br><br>Consumer<MutableMap<K, Map<String, Any?>>>? 纠正<br><br>
| keyBy| <br><br>Transformer<E, K> 取键方法<br><br>
  
  
Content  
fun <[K](to-paginator.md), [E](to-paginator.md) : [Entity](../-entity/index.md)> [toPaginator](to-paginator.md)(entities: [Paginator](../../tech.whence.echo.container/-paginator/index.md)<[E](to-paginator.md)>, keyBy: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[E](to-paginator.md), [K](to-paginator.md)>, fixer: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<[MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>>?): [Paginator](../../tech.whence.echo.container/-paginator/index.md)<[Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>>  



