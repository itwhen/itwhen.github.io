---
title: update -
---
//[echo](../../index.md)/[tech.whence.echo.dal.dao](../index.md)/[Queriable](index.md)/[update](update.md)



# update  
[jvm]  
Brief description  


更新



#### Return  


Long



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| updater| <br><br>QU 更新器<br><br>
  
  
Content  
abstract suspend fun [update](update.md)(updater: [QU](index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  


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
abstract suspend fun [update](update.md)(restriction: [QF](index.md), data: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  



