---
title: Relation -
---
//[echo](../../index.md)/[tech.whence.echo.dal.relation](../index.md)/[Relation](index.md)



# Relation  
 [jvm] 

关联

interface [Relation](index.md)<[S](index.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md), [SK](index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), [T](index.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md), [TK](index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| SK| <br><br>源主键类型<br><br>
| T| <br><br>目标数据类型<br><br>
| TK| <br><br>目标主键类型<br><br>
  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [source](index.md#tech.whence.echo.dal.relation/Relation/source/#/PointingToDeclaration/)|  [jvm] <br><br>Dao<S, SK, *> 源数据<br><br>abstract val [source](index.md#tech.whence.echo.dal.relation/Relation/source/#/PointingToDeclaration/): [Dao](../../tech.whence.echo.dal.dao/-dao/index.md)<[S](index.md), [SK](index.md), *>   <br>
| [target](index.md#tech.whence.echo.dal.relation/Relation/target/#/PointingToDeclaration/)|  [jvm] <br><br>Dao<T, TK, *> 目标数据<br><br>abstract val [target](index.md#tech.whence.echo.dal.relation/Relation/target/#/PointingToDeclaration/): [Dao](../../tech.whence.echo.dal.dao/-dao/index.md)<[T](index.md), [TK](index.md), *>   <br>


## Inheritors  
  
|  Name| 
|---|
| [ManyToMany](../-many-to-many/index.md)
| [OneToOne](../-one-to-one/index.md)

