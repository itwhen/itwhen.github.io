---
title: from -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity.mapper](../index.md)/[Mapper](index.md)/[from](from.md)



# from  
[jvm]  
Brief description  


将数据转换为实体



#### Return  


E



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>T 指定数据<br><br>
| declarer| <br><br>KClass<E> 指定实体类型<br><br>
  
  
Content  
abstract fun [from](from.md)(data: [T](index.md), declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[E](index.md)>): [E](index.md)  


[jvm]  
Brief description  


将映射转换到实体



#### Return  


E



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| creator| <br><br>Producer<E> 实体生成<br><br>
| data| <br><br>T 指定数据<br><br>
  
  
Content  
abstract fun [from](from.md)(data: [T](index.md), creator: [Producer](../../tech.whence.echo.function/-producer/index.md)<[E](index.md)>): [E](index.md)  


[jvm]  
Brief description  


转换到实体



#### Return  


E



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>T 指定数据<br><br>
| entity| <br><br>E 指定实体<br><br>
  
  
Content  
abstract fun [from](from.md)(data: [T](index.md), entity: [E](index.md)): [E](index.md)  



