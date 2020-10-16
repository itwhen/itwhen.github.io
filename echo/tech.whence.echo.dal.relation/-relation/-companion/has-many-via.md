---
title: hasManyVia -
---
//[echo](../../../index.md)/[tech.whence.echo.dal.relation](../../index.md)/[Relation](../index.md)/[Companion](index.md)/[hasManyVia](has-many-via.md)



# hasManyVia  
[jvm]  
Brief description  


通过中间数据拥有多个



#### Return  


HasManyVia<S, SK, V, T, TK>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| source| <br><br>Dao<S, SK, *><br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun <[S](has-many-via.md) : [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md), [SK](has-many-via.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), [V](has-many-via.md) : [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md), [T](has-many-via.md) : [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md), [TK](has-many-via.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)> [hasManyVia](has-many-via.md)(source: [Dao](../../../tech.whence.echo.dal.dao/-dao/index.md)<[S](has-many-via.md), [SK](has-many-via.md), *>): [HasManyVia](../../-has-many-via/index.md)<[S](has-many-via.md), [SK](has-many-via.md), [V](has-many-via.md), [T](has-many-via.md), [TK](has-many-via.md)>  



