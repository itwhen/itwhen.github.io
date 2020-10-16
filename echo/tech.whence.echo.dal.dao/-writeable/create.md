---
title: create -
---
//[echo](../../index.md)/[tech.whence.echo.dal.dao](../index.md)/[Writeable](index.md)/[create](create.md)



# create  
[jvm]  
Brief description  


写入



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| entity| <br><br>E 指定实体<br><br>
  
  
Content  
abstract suspend fun [create](create.md)(entity: [E](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  


[jvm]  
Brief description  


写入数据



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>Accessor 指定数据访问器<br><br>
  
  
Content  
abstract suspend fun [create](create.md)(data: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  


[jvm]  
Brief description  


写入多个



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| entities| <br><br>Collection<E> 指定实体<br><br>
  
  
Content  
abstract suspend fun [create](create.md)(entities: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[E](index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  



