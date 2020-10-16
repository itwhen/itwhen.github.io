---
title: retrieves -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.association](../index.md)/[Association](index.md)/[retrieves](retrieves.md)



# retrieves  
[jvm]  
Brief description  


根据实体内关联编号搜索



#### Return  


Map<String, FR>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| entities| <br><br>Paginator<E><br><br>
  
  
Content  
suspend fun [retrieves](retrieves.md)(entities: [Paginator](../../tech.whence.echo.container/-paginator/index.md)<[E](index.md)>): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [FR](index.md)>  
suspend fun [retrieves](retrieves.md)(entities: [Entities](../../tech.whence.echo.dal.entity/-entities/index.md)<[E](index.md)>): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [FR](index.md)>  



