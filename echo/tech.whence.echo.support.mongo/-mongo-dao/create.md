---
title: create -
---
//[echo](../../index.md)/[tech.whence.echo.support.mongo](../index.md)/[MongoDao](index.md)/[create](create.md)



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
open suspend override fun [create](create.md)(entity: [E](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  


[jvm]  
Brief description  


写入



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| creator| <br><br>QC 创建器<br><br>
  
  
Content  
open suspend override fun [create](create.md)(creator: [Insert](../../tech.whence.echo.support.mongo.querier/-insert/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  


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
open suspend override fun [create](create.md)(entities: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[E](index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  



