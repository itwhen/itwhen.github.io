---
title: fromAccessors -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity](../index.md)/[EntityMapper](index.md)/[fromAccessors](from-accessors.md)



# fromAccessors  
[jvm]  
Brief description  


将Form列表转换为实体列表 提供一个回调用来纠正实体 若在此时返回空则从列表中移除之



#### Return  


List<E>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>Collection<Accessor> 指定数据访问器集合<br><br>
| declarer| <br><br>KClass<E> 目标实体类型<br><br>
| fixer| <br><br>Fixer<E>? 纠正<br><br>
  
  
Content  
fun <[E](from-accessors.md) : [Entity](../-entity/index.md)> [fromAccessors](from-accessors.md)(data: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)>, declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[E](from-accessors.md)>, fixer: [Fixer](../../tech.whence.echo.function/-fixer/index.md)<[E](from-accessors.md)>?): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[E](from-accessors.md)>  



