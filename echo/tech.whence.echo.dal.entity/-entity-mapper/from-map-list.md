---
title: fromMapList -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity](../index.md)/[EntityMapper](index.md)/[fromMapList](from-map-list.md)



# fromMapList  
[jvm]  
Brief description  


将映射列表转换为实体列表 提供一个回调用来纠正实体 若在此时返回空则从列表中移除之



#### Return  


List<E>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>List<Map<String, Any?>> 指定键值列表<br><br>
| declarer| <br><br>KClass<E> 目标实体类型<br><br>
| fixer| <br><br>Fixer<E>? 纠正<br><br>
  
  
Content  
fun <[E](from-map-list.md) : [Entity](../-entity/index.md)> [fromMapList](from-map-list.md)(data: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>>, declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[E](from-map-list.md)>, fixer: [Fixer](../../tech.whence.echo.function/-fixer/index.md)<[E](from-map-list.md)>?): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[E](from-map-list.md)>  



