---
title: retrieve -
---
//[echo](../../index.md)/[tech.whence.echo.dal.relation](../index.md)/[OneToOne](index.md)/[retrieve](retrieve.md)



# retrieve  
[jvm]  
Brief description  


根据源数据主键集合获取目标数据



#### Return  


Map<SK, T>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| batch| <br><br>Collection<SK> 指定源数据主键集合<br><br>
  
  
Content  
suspend fun [retrieve](retrieve.md)(batch: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[SK](index.md)>): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[SK](index.md), [T](index.md)>  


[jvm]  
Brief description  


根据源数据主键获取目标数据



#### Return  


T?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| id| <br><br>SK 指定源数据主键<br><br>
  
  
Content  
suspend fun [retrieve](retrieve.md)(id: [SK](index.md)): [T](index.md)?  



