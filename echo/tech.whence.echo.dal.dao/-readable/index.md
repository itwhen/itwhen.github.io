---
title: Readable -
---
//[echo](../../index.md)/[tech.whence.echo.dal.dao](../index.md)/[Readable](index.md)



# Readable  
 [jvm] 

可读

interface [Readable](index.md)<[E](index.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md), [PK](index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| E| <br><br>: Entity 实体类型<br><br>
  


## Functions  
  
|  Name|  Summary| 
|---|---|
| [count](count.md)| [jvm]  <br>Brief description  <br><br><br>统计<br><br>  <br>Content  <br>abstract suspend fun [count](count.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [dirty](dirty.md)| [jvm]  <br>Brief description  <br><br><br>检查实体是否变化<br><br>  <br>Content  <br>abstract fun [dirty](dirty.md)(entity: [E](index.md))  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [filter](filter.md)| [jvm]  <br>Brief description  <br><br><br>过滤字段<br><br>  <br>Content  <br>open suspend fun [filter](filter.md)(column: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), limit: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), page: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)): [Paginator](../../tech.whence.echo.container/-paginator/index.md)<[E](index.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>过滤字段 效率考虑指定字段必须有身份 [tech.whence.echo.dal.schema.key.Identity](../../tech.whence.echo.dal.schema.key/-identity/index.md)<br><br>  <br>Content  <br>abstract suspend fun [filter](filter.md)(column: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), values: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>, limit: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), page: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)): [Paginator](../../tech.whence.echo.container/-paginator/index.md)<[E](index.md)>  <br><br><br>
| [find](find.md)| [jvm]  <br>Brief description  <br><br><br>查找<br><br>  <br>Content  <br>abstract suspend fun [find](find.md)(): [Entities](../../tech.whence.echo.dal.entity/-entities/index.md)<[E](index.md)>  <br><br><br>
| [has](has.md)| [jvm]  <br>Brief description  <br><br><br>判断是否存在<br><br>  <br>Content  <br>abstract suspend fun [has](has.md)(id: [PK](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>判断实体是否存在<br><br>  <br>Content  <br>abstract suspend fun [has](has.md)(entity: [E](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [retrieve](retrieve.md)| [jvm]  <br>Brief description  <br><br><br>查找<br><br>  <br>Content  <br>abstract suspend fun [retrieve](retrieve.md)(id: [PK](index.md)): [E](index.md)?  <br><br><br>[jvm]  <br>Brief description  <br><br><br>查找多个<br><br>  <br>Content  <br>open suspend fun [retrieve](retrieve.md)(vararg batch: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [PK](index.md)>): [Entities](../../tech.whence.echo.dal.entity/-entities/index.md)<[E](index.md)>  <br>abstract suspend fun [retrieve](retrieve.md)(batch: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[PK](index.md)>): [Entities](../../tech.whence.echo.dal.entity/-entities/index.md)<[E](index.md)>  <br><br><br>
| [singularize](singularize.md)| [jvm]  <br>Brief description  <br><br><br>检查实体字段值的唯一性 通过注解 [Unique](../../tech.whence.echo.dal.schema.key.strategy/-unique/index.md) 检查 合并注解 [In](../-operation/-s-i-n-g-u-l-a-r-i-z-e/index.md) 内的字段及其值<br><br>  <br>Content  <br>abstract suspend fun [singularize](singularize.md)(entity: [E](index.md))  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Inheritors  
  
|  Name| 
|---|
| [Accessible](../-accessible/index.md)

