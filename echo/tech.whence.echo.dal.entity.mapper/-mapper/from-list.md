---
title: fromList -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity.mapper](../index.md)/[Mapper](index.md)/[fromList](from-list.md)



# fromList  
[jvm]  
Brief description  


将列表转换为实体列表 提供一个回调用来纠正实体 若在此时返回空则从列表中移除之



#### Return  


List<E>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>List<T> 指定数据列表<br><br>
| declarer| <br><br>KClass<E> 目标实体类型<br><br>
| fixer| <br><br>Fixer<E>? 纠正<br><br>
  
  
Content  
abstract fun [fromList](from-list.md)(data: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](index.md)>, declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[E](index.md)>, fixer: [Fixer](../../tech.whence.echo.function/-fixer/index.md)<[E](index.md)>?): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[E](index.md)>  



