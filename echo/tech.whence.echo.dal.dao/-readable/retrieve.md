---
title: retrieve -
---
//[echo](../../index.md)/[tech.whence.echo.dal.dao](../index.md)/[Readable](index.md)/[retrieve](retrieve.md)



# retrieve  
[jvm]  
Brief description  


查找



#### Return  


E



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| id| <br><br>Serializable 指定主键值<br><br>
  
  
Content  
abstract suspend fun [retrieve](retrieve.md)(id: [PK](index.md)): [E](index.md)?  


[jvm]  
Brief description  


查找多个



#### Return  


Entities<E>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| batch| <br><br>Collection<Serializable> 指定主键值<br><br>
  
  
Content  
abstract suspend fun [retrieve](retrieve.md)(batch: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[PK](index.md)>): [Entities](../../tech.whence.echo.dal.entity/-entities/index.md)<[E](index.md)>  


[jvm]  
Brief description  


查找多个



#### Return  


List<E>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| batch| <br><br>Array<out Serializable> 指定主键值<br><br>
  
  
Content  
open suspend fun [retrieve](retrieve.md)(vararg batch: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [PK](index.md)>): [Entities](../../tech.whence.echo.dal.entity/-entities/index.md)<[E](index.md)>  



