---
title: initialize -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity](../index.md)/[EntityAccessor](index.md)/[initialize](initialize.md)



# initialize  
[jvm]  
Brief description  


初始化实体字段属性 找到指定类型的为空字段并赋值为指定值



#### Return  


E



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| entity| <br><br>E 指定实体<br><br>
| type| <br><br>KClass<V> 指定字段类型<br><br>
| value| <br><br>V? 指定默认值<br><br>
  
  
Content  
fun <[E](initialize.md) : [Entity](../-entity/index.md), [V](initialize.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [initialize](initialize.md)(entity: [E](initialize.md), type: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[V](initialize.md)>, value: [V](initialize.md)?): [E](initialize.md)  



