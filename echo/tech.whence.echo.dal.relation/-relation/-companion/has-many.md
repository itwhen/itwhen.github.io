---
title: hasMany -
---
//[echo](../../../index.md)/[tech.whence.echo.dal.relation](../../index.md)/[Relation](../index.md)/[Companion](index.md)/[hasMany](has-many.md)



# hasMany  
[jvm]  
Brief description  


拥有多个



#### Return  


HasMany<S, SK, T, TK>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| source| <br><br>Dao<S, SK, *><br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun <[S](has-many.md) : [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md), [SK](has-many.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), [T](has-many.md) : [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md), [TK](has-many.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)> [hasMany](has-many.md)(source: [Dao](../../../tech.whence.echo.dal.dao/-dao/index.md)<[S](has-many.md), [SK](has-many.md), *>): [HasMany](../../-has-many/index.md)<[S](has-many.md), [SK](has-many.md), [T](has-many.md), [TK](has-many.md)>  



