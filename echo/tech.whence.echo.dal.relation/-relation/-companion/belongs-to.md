---
title: belongsTo -
---
//[echo](../../../index.md)/[tech.whence.echo.dal.relation](../../index.md)/[Relation](../index.md)/[Companion](index.md)/[belongsTo](belongs-to.md)



# belongsTo  
[jvm]  
Brief description  


归属于



#### Return  


BelongsTo<S, SK, T, TK>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| source| <br><br>Dao<S, SK, *><br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun <[S](belongs-to.md) : [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md), [SK](belongs-to.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), [T](belongs-to.md) : [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md), [TK](belongs-to.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)> [belongsTo](belongs-to.md)(source: [Dao](../../../tech.whence.echo.dal.dao/-dao/index.md)<[S](belongs-to.md), [SK](belongs-to.md), *>): [BelongsTo](../../-belongs-to/index.md)<[S](belongs-to.md), [SK](belongs-to.md), [T](belongs-to.md), [TK](belongs-to.md)>  



