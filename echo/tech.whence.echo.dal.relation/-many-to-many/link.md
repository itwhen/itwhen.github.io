---
title: link -
---
//[echo](../../index.md)/[tech.whence.echo.dal.relation](../index.md)/[ManyToMany](index.md)/[link](link.md)



# link  
[jvm]  
Brief description  


生成源及目标途经数据



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| creator| <br><br>Function2<S, T, V> 途经数据生成<br><br>
| sources| <br><br>Set<S> 源数据<br><br>
| targets| <br><br>Set<T> 目标数据<br><br>
  
  
Content  
suspend fun [link](link.md)(sources: [Entities](../../tech.whence.echo.dal.entity/-entities/index.md)<[S](index.md)>, targets: [Entities](../../tech.whence.echo.dal.entity/-entities/index.md)<[T](index.md)>, creator: ([S](index.md), [T](index.md)) -> [V](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  



