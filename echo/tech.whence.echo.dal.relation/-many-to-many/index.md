---
title: ManyToMany -
---
//[echo](../../index.md)/[tech.whence.echo.dal.relation](../index.md)/[ManyToMany](index.md)



# ManyToMany  
 [jvm] 

多对多

abstract class [ManyToMany](index.md)<[A](index.md) : [ManyToMany](index.md)<[A](index.md), [S](index.md), [SK](index.md), [V](index.md), [T](index.md), [TK](index.md)>, [S](index.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md), [SK](index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), [V](index.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md), [T](index.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md), [TK](index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)> : [Relation](../-relation/index.md)<[S](index.md), [SK](index.md), [T](index.md), [TK](index.md)>    


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| A| <br><br>子类型<br><br>
| S| <br><br>源数据类型<br><br>
| SK| <br><br>源数据主键类型<br><br>
| T| <br><br>目标数据类型<br><br>
| TK| <br><br>目标数据主键类型<br><br>
| V| <br><br>途经数据类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [ManyToMany](-many-to-many.md)|  [jvm] <br><br>子类型<br><br>fun [ManyToMany](-many-to-many.md)()   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [expand](expand.md)| [jvm]  <br>Brief description  <br><br><br>中间数据膨胀系数<br><br>  <br>Content  <br>fun [expand](expand.md)(factor: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)): [A](index.md)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [link](link.md)| [jvm]  <br>Brief description  <br><br><br>生成源及目标途经数据<br><br>  <br>Content  <br>suspend fun [link](link.md)(sources: [Entities](../../tech.whence.echo.dal.entity/-entities/index.md)<[S](index.md)>, targets: [Entities](../../tech.whence.echo.dal.entity/-entities/index.md)<[T](index.md)>, creator: ([S](index.md), [T](index.md)) -> [V](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [retrieve](retrieve.md)| [jvm]  <br>Brief description  <br><br><br>根据源数据主键获取目标数据<br><br>  <br>Content  <br>suspend fun [retrieve](retrieve.md)(id: [SK](index.md)): [Entities](../../tech.whence.echo.dal.entity/-entities/index.md)<[T](index.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>根据源数据主键集合获取目标数据<br><br>  <br>Content  <br>suspend fun [retrieve](retrieve.md)(batch: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[SK](index.md)>): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[SK](index.md), [Entities](../../tech.whence.echo.dal.entity/-entities/index.md)<[T](index.md)>>  <br><br><br>
| [source](source.md)| [jvm]  <br>Brief description  <br><br><br>设置来源<br><br>  <br>Content  <br>fun [source](source.md)(source: [Dao](../../tech.whence.echo.dal.dao/-dao/index.md)<[S](index.md), [SK](index.md), *>): [A](index.md)  <br><br><br>
| [target](target.md)| [jvm]  <br>Brief description  <br><br><br>目标<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [target](target.md)(target: [Dao](../../tech.whence.echo.dal.dao/-dao/index.md)<[T](index.md), [TK](index.md), *>, reference: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, local: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [A](index.md)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [unlink](unlink.md)| [jvm]  <br>Brief description  <br><br><br>取消与目标数据关联<br><br>  <br>Content  <br>suspend fun [unlink](unlink.md)(id: [SK](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br>suspend fun [unlink](unlink.md)(batch: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[SK](index.md)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [via](via.md)| [jvm]  <br>Brief description  <br><br><br>途经<br><br>  <br>Content  <br>fun [via](via.md)(via: [Dao](../../tech.whence.echo.dal.dao/-dao/index.md)<[V](index.md), out [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), *>, reference: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [A](index.md)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [source](index.md#tech.whence.echo.dal.relation/ManyToMany/source/#/PointingToDeclaration/)|  [jvm] <br><br>Dao<S, SK, *> 源数据<br><br>open lateinit override var [source](index.md#tech.whence.echo.dal.relation/ManyToMany/source/#/PointingToDeclaration/): [Dao](../../tech.whence.echo.dal.dao/-dao/index.md)<[S](index.md), [SK](index.md), *>   <br>
| [target](index.md#tech.whence.echo.dal.relation/ManyToMany/target/#/PointingToDeclaration/)|  [jvm] <br><br>Dao<T, TK, *> 目标数据<br><br>open lateinit override var [target](index.md#tech.whence.echo.dal.relation/ManyToMany/target/#/PointingToDeclaration/): [Dao](../../tech.whence.echo.dal.dao/-dao/index.md)<[T](index.md), [TK](index.md), *>   <br>


## Inheritors  
  
|  Name| 
|---|
| [BelongsToVia](../-belongs-to-via/index.md)
| [HasManyVia](../-has-many-via/index.md)

