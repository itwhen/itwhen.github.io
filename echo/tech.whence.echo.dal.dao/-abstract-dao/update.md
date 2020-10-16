---
title: update -
---
//[echo](../../index.md)/[tech.whence.echo.dal.dao](../index.md)/[AbstractDao](index.md)/[update](update.md)



# update  
[jvm]  
Brief description  


更新



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| entity| <br><br>E 指定实体<br><br>
  
  
Content  
open suspend override fun [update](update.md)(entity: [E](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  


[jvm]  
Brief description  


按条件更新



#### Return  


Long



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>Map<String, Serializable?> 数据<br><br>
| restriction| <br><br>QF 约束<br><br>
  
  
Content  
open suspend override fun [update](update.md)(restriction: [QF](index.md), data: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  


[jvm]  
Brief description  


按照指定主键更新多个字段



#### Return  


Int



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| batch| <br><br>Collection<PK> 指定主键值<br><br>
| data| <br><br>Map<String, Serializable> 指定数据<br><br>
  
  
Content  
open suspend override fun [update](update.md)(batch: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[PK](index.md)>, data: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  


[jvm]  
Brief description  


按字段更新



#### Return  


Int



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| batch| <br><br>Collection<PK> 指定主键值<br><br>
| column| <br><br>String 指定字段<br><br>
| from| <br><br>Collection<T> 来源值<br><br>
| to| <br><br>T 目标值<br><br>
  
  
Content  
open suspend override fun <[T](update.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)> [update](update.md)(batch: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[PK](index.md)>, column: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), from: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[T](update.md)>, to: [T](update.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  


[jvm]  
Brief description  


按字段更新



#### Return  


Long



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| batch| <br><br>Collection<PK> 指定主键值<br><br>
| column| <br><br>String 指定字段<br><br>
| to| <br><br>Serializable 目标值<br><br>
| unassigned| <br><br>Boolean 指定字段是否未赋值<br><br>
  
  
Content  
open suspend override fun [update](update.md)(batch: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[PK](index.md)>, column: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), to: [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), unassigned: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  



