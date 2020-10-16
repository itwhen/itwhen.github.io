---
title: BelongsTo -
---
//[echo](../../index.md)/[tech.whence.echo.dal.relation](../index.md)/[BelongsTo](index.md)



# BelongsTo  
 [jvm] 

归属于

class [BelongsTo](index.md)<[S](index.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md), [SK](index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), [T](index.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md), [TK](index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)> : [OneToOne](../-one-to-one/index.md)<[BelongsTo](index.md)<[S](index.md), [SK](index.md), [T](index.md), [TK](index.md)>, [S](index.md), [SK](index.md), [T](index.md), [TK](index.md)>    


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| SK| <br><br>源主键类型<br><br>
| T| <br><br>目标数据类型<br><br>
| TK| <br><br>目标主键类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [BelongsTo](-belongs-to.md)|  [jvm] <br><br>源主键类型<br><br>fun [BelongsTo](-belongs-to.md)()   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [retrieve](../-one-to-one/retrieve.md)| [jvm]  <br>Brief description  <br><br><br>根据源数据主键获取目标数据<br><br>  <br>Content  <br>suspend override fun [retrieve](../-one-to-one/retrieve.md)(id: [SK](index.md)): [T](index.md)?  <br><br><br>[jvm]  <br>Brief description  <br><br><br>根据源数据主键集合获取目标数据<br><br>  <br>Content  <br>suspend override fun [retrieve](../-one-to-one/retrieve.md)(batch: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[SK](index.md)>): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[SK](index.md), [T](index.md)>  <br><br><br>
| [source](../-one-to-one/source.md)| [jvm]  <br>Brief description  <br><br><br>设置来源<br><br>  <br>Content  <br>override fun [source](../-one-to-one/source.md)(source: [Dao](../../tech.whence.echo.dal.dao/-dao/index.md)<[S](index.md), [SK](index.md), *>): [BelongsTo](index.md)<[S](index.md), [SK](index.md), [T](index.md), [TK](index.md)>  <br><br><br>
| [target](../-one-to-one/target.md)| [jvm]  <br>Brief description  <br><br><br>设置目标<br><br>  <br>Content  <br>override fun [target](../-one-to-one/target.md)(target: [Dao](../../tech.whence.echo.dal.dao/-dao/index.md)<[T](index.md), [TK](index.md), *>, reference: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [BelongsTo](index.md)<[S](index.md), [SK](index.md), [T](index.md), [TK](index.md)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [source](index.md#tech.whence.echo.dal.relation/BelongsTo/source/#/PointingToDeclaration/)|  [jvm] <br><br>Dao<S, SK, *> 源数据<br><br>open lateinit override var [source](index.md#tech.whence.echo.dal.relation/BelongsTo/source/#/PointingToDeclaration/): [Dao](../../tech.whence.echo.dal.dao/-dao/index.md)<[S](index.md), [SK](index.md), *>   <br>
| [target](index.md#tech.whence.echo.dal.relation/BelongsTo/target/#/PointingToDeclaration/)|  [jvm] <br><br>Dao<T, TK, *> 目标数据<br><br>open lateinit override var [target](index.md#tech.whence.echo.dal.relation/BelongsTo/target/#/PointingToDeclaration/): [Dao](../../tech.whence.echo.dal.dao/-dao/index.md)<[T](index.md), [TK](index.md), *>   <br>

