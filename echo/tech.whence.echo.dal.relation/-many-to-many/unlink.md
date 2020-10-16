---
title: unlink -
---
//[echo](../../index.md)/[tech.whence.echo.dal.relation](../index.md)/[ManyToMany](index.md)/[unlink](unlink.md)



# unlink  
[jvm]  
Brief description  


取消与目标数据关联



#### Return  


Int



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| batch| <br><br>Collection<SK> 指定源主键<br><br>
  
  
Content  
suspend fun [unlink](unlink.md)(batch: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[SK](index.md)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  


[jvm]  
Brief description  


取消与目标数据关联



#### Return  


Int



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| id| <br><br>SK 指定源主键<br><br>
  
  
Content  
suspend fun [unlink](unlink.md)(id: [SK](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  



