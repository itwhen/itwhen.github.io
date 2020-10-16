---
title: delete -
---
//[echo](../../index.md)/[tech.whence.echo.dal.dao](../index.md)/[AbstractDao](index.md)/[delete](delete.md)



# delete  
[jvm]  
Brief description  


删除



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| id| <br><br>Serializable 指定主键<br><br>
  
  
Content  
open suspend override fun [delete](delete.md)(id: [PK](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  


[jvm]  
Brief description  


删除



#### Return  


Long



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| batch| <br><br>Collection<Serializable> 指定主键值<br><br>
  
  
Content  
open suspend override fun [delete](delete.md)(batch: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[PK](index.md)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  


[jvm]  
Brief description  


删除指定实体



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| entity| <br><br>实体<br><br>
  
  
Content  
open suspend override fun [delete](delete.md)(entity: [E](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  


[jvm]  
Brief description  


按字段删除



#### Return  


Int



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| column| <br><br>String 指定字段<br><br>
| values| <br><br>Collection<Serializable> 指定值<br><br>
  
  
Content  
open suspend override fun [delete](delete.md)(column: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), values: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  



