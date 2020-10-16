---
title: fromMap -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity](../index.md)/[EntityMapper](index.md)/[fromMap](from-map.md)



# fromMap  
[jvm]  
Brief description  


将映射转换为实体



#### Return  


E?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>Map<String, Any?> 指定字段名称及数据<br><br>
| declarer| <br><br>KClass<E> 指定实体类型<br><br>
  
  
Content  
fun <[E](from-map.md) : [Entity](../-entity/index.md)> [fromMap](from-map.md)(data: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>, declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[E](from-map.md)>): [E](from-map.md)  



