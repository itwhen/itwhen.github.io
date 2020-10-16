---
title: fix -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity](../index.md)/[EntityAccessor](index.md)/[fix](fix.md)



# fix  
[jvm]  
Brief description  


根据期望值将指定实体相应字段值修正 寻找到跟指定类型一致的字段 若当前值为空且期望值也为空或者两者相等则将该字段赋值为指定值



#### Return  


E



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| entity| <br><br>E 指定实体<br><br>
| fixer| <br><br>Fixer<V?> 纠正<br><br>
| type| <br><br>KClass<V> 指定字段类型<br><br>
  
  
Content  
fun <[E](fix.md) : [Entity](../-entity/index.md), [V](fix.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [fix](fix.md)(entity: [E](fix.md), type: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[V](fix.md)>, fixer: [Fixer](../../tech.whence.echo.function/-fixer/index.md)<[V](fix.md)?>): [E](fix.md)  



