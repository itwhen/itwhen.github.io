---
title: HasManyVia -
---
//[echo](../../index.md)/[tech.whence.echo.dal.relation](../index.md)/[HasManyVia](index.md)



# HasManyVia  
 [jvm] 

通过中间数据拥有多个

class [HasManyVia](index.md)<[S](index.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md), [SK](index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), [V](index.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md), [T](index.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md), [TK](index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)> : [ManyToMany](../-many-to-many/index.md)<[HasManyVia](index.md)<[S](index.md), [SK](index.md), [V](index.md), [T](index.md), [TK](index.md)>, [S](index.md), [SK](index.md), [V](index.md), [T](index.md), [TK](index.md)>    


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| S| <br><br>源数据类型<br><br>
| SK| <br><br>源数据主键类型<br><br>
| T| <br><br>目标数据类型<br><br>
| TK| <br><br>目标数据主键类型<br><br>
| V| <br><br>途经数据类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [HasManyVia](-has-many-via.md)|  [jvm] <br><br>源数据类型<br><br>fun [HasManyVia](-has-many-via.md)()   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [expand](../-many-to-many/expand.md)| [jvm]  <br>Brief description  <br><br><br>中间数据膨胀系数<br><br>  <br>Content  <br>override fun [expand](../-many-to-many/expand.md)(factor: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)): [HasManyVia](index.md)<[S](index.md), [SK](index.md), [V](index.md), [T](index.md), [TK](index.md)>  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [link](../-many-to-many/link.md)| [jvm]  <br>Brief description  <br><br><br>生成源及目标途经数据<br><br>  <br>Content  <br>suspend override fun [link](../-many-to-many/link.md)(sources: [Entities](../../tech.whence.echo.dal.entity/-entities/index.md)<[S](index.md)>, targets: [Entities](../../tech.whence.echo.dal.entity/-entities/index.md)<[T](index.md)>, creator: ([S](index.md), [T](index.md)) -> [V](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [retrieve](../-many-to-many/retrieve.md)| [jvm]  <br>Brief description  <br><br><br>根据源数据主键获取目标数据<br><br>  <br>Content  <br>suspend override fun [retrieve](../-many-to-many/retrieve.md)(id: [SK](index.md)): [Entities](../../tech.whence.echo.dal.entity/-entities/index.md)<[T](index.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>根据源数据主键集合获取目标数据<br><br>  <br>Content  <br>suspend override fun [retrieve](../-many-to-many/retrieve.md)(batch: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[SK](index.md)>): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[SK](index.md), [Entities](../../tech.whence.echo.dal.entity/-entities/index.md)<[T](index.md)>>  <br><br><br>
| [source](../-many-to-many/source.md)| [jvm]  <br>Brief description  <br><br><br>设置来源<br><br>  <br>Content  <br>override fun [source](../-many-to-many/source.md)(source: [Dao](../../tech.whence.echo.dal.dao/-dao/index.md)<[S](index.md), [SK](index.md), *>): [HasManyVia](index.md)<[S](index.md), [SK](index.md), [V](index.md), [T](index.md), [TK](index.md)>  <br><br><br>
| [target](../-many-to-many/target.md)| [jvm]  <br>Brief description  <br><br><br>目标<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>override fun [target](../-many-to-many/target.md)(target: [Dao](../../tech.whence.echo.dal.dao/-dao/index.md)<[T](index.md), [TK](index.md), *>, reference: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, local: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [HasManyVia](index.md)<[S](index.md), [SK](index.md), [V](index.md), [T](index.md), [TK](index.md)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [unlink](../-many-to-many/unlink.md)| [jvm]  <br>Brief description  <br><br><br>取消与目标数据关联<br><br>  <br>Content  <br>suspend override fun [unlink](../-many-to-many/unlink.md)(id: [SK](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br>suspend override fun [unlink](../-many-to-many/unlink.md)(batch: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[SK](index.md)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [via](../-many-to-many/via.md)| [jvm]  <br>Brief description  <br><br><br>途经<br><br>  <br>Content  <br>override fun [via](../-many-to-many/via.md)(via: [Dao](../../tech.whence.echo.dal.dao/-dao/index.md)<[V](index.md), out [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), *>, reference: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [HasManyVia](index.md)<[S](index.md), [SK](index.md), [V](index.md), [T](index.md), [TK](index.md)>  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [source](index.md#tech.whence.echo.dal.relation/HasManyVia/source/#/PointingToDeclaration/)|  [jvm] <br><br>Dao<S, SK, *> 源数据<br><br>open lateinit override var [source](index.md#tech.whence.echo.dal.relation/HasManyVia/source/#/PointingToDeclaration/): [Dao](../../tech.whence.echo.dal.dao/-dao/index.md)<[S](index.md), [SK](index.md), *>   <br>
| [target](index.md#tech.whence.echo.dal.relation/HasManyVia/target/#/PointingToDeclaration/)|  [jvm] <br><br>Dao<T, TK, *> 目标数据<br><br>open lateinit override var [target](index.md#tech.whence.echo.dal.relation/HasManyVia/target/#/PointingToDeclaration/): [Dao](../../tech.whence.echo.dal.dao/-dao/index.md)<[T](index.md), [TK](index.md), *>   <br>

