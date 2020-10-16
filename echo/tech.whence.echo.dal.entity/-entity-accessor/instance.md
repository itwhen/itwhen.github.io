---
title: instance -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity](../index.md)/[EntityAccessor](index.md)/[instance](instance.md)



# instance  
[jvm]  
Brief description  


取指定实体类型实例 若有无参数构造时直接构造 否则假定开启了no-arg插件尝试用java方式构造



#### Return  


E



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| declarer| <br><br>KClass<E> 指定实体类型<br><br>
  
  
Content  
fun <[E](instance.md) : [Entity](../-entity/index.md)> [instance](instance.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[E](instance.md)>): [E](instance.md)  



