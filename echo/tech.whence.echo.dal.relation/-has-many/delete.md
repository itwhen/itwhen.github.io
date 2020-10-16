---
title: delete -
---
//[echo](../../index.md)/[tech.whence.echo.dal.relation](../index.md)/[HasMany](index.md)/[delete](delete.md)



# delete  
[jvm]  
Brief description  


删除目标数据中相应数据



#### Return  


Int



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| batch| <br><br>Collection<SK> 指定源数据主键集合<br><br>
  
  
Content  
suspend fun [delete](delete.md)(batch: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[SK](index.md)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  


[jvm]  
Brief description  


删除目标数据中相应数据



#### Return  


Int



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| id| <br><br>SK 指定源数据主键<br><br>
  
  
Content  
suspend fun [delete](delete.md)(id: [SK](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  



