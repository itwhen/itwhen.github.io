---
title: HasMany -
---
//[echo](../../index.md)/[tech.whence.echo.dal.relation](../index.md)/[HasMany](index.md)



# HasMany  
 [jvm] 

拥有多个

class [HasMany](index.md)<[S](index.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md), [SK](index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), [T](index.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md), [TK](index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| SK| <br><br>源数据主键类型<br><br>
| T| <br><br>目标数据类型<br><br>
| TK| <br><br>目标数据主键类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [HasMany](-has-many.md)|  [jvm] <br><br>源数据主键类型<br><br>fun [HasMany](-has-many.md)()   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [delete](delete.md)| [jvm]  <br>Brief description  <br><br><br>删除目标数据中相应数据<br><br>  <br>Content  <br>suspend fun [delete](delete.md)(id: [SK](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br>suspend fun [delete](delete.md)(batch: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[SK](index.md)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [expand](expand.md)| [jvm]  <br>Brief description  <br><br><br>中间数据膨胀系数<br><br>  <br>Content  <br>fun [expand](expand.md)(factor: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)): [HasMany](index.md)<[S](index.md), [SK](index.md), [T](index.md), [TK](index.md)>  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [retrieve](retrieve.md)| [jvm]  <br>Brief description  <br><br><br>根据源数据主键获取目标数据<br><br>  <br>Content  <br>suspend fun [retrieve](retrieve.md)(id: [SK](index.md)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](index.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>根据源数据主键集合获取目标数据<br><br>  <br>Content  <br>suspend fun [retrieve](retrieve.md)(batch: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[SK](index.md)>): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[SK](index.md), [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](index.md)>>  <br><br><br>
| [source](source.md)| [jvm]  <br>Brief description  <br><br><br>设置来源<br><br>  <br>Content  <br>fun [source](source.md)(source: [Dao](../../tech.whence.echo.dal.dao/-dao/index.md)<[S](index.md), [SK](index.md), *>): [HasMany](index.md)<[S](index.md), [SK](index.md), [T](index.md), [TK](index.md)>  <br><br><br>
| [target](target.md)| [jvm]  <br>Brief description  <br><br><br>目标<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [target](target.md)(target: [Dao](../../tech.whence.echo.dal.dao/-dao/index.md)<[T](index.md), [TK](index.md), *>, reference: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [HasMany](index.md)<[S](index.md), [SK](index.md), [T](index.md), [TK](index.md)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

