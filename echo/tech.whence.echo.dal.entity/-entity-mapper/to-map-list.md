---
title: toMapList -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity](../index.md)/[EntityMapper](index.md)/[toMapList](to-map-list.md)



# toMapList  
[jvm]  
Brief description  


使用多个策略将实体集合转换为映射列表



#### Return  


List<Map<String, Any?>>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| entities| <br><br>Collection<E> 指定实体集合<br><br>
| strategist| <br><br>Strategist 转换策略<br><br>
  
  
Content  
fun <[E](to-map-list.md) : [Entity](../-entity/index.md)> [toMapList](to-map-list.md)(entities: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[E](to-map-list.md)>, strategist: [Strategist](../../tech.whence.echo.strategy/-strategist/index.md)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>>  



