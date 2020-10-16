---
title: Companion -
---
//[echo](../../../index.md)/[tech.whence.echo.dal.schema](../../index.md)/[Schema](../index.md)/[Companion](index.md)



# Companion  
 [jvm] object [Companion](index.md)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [customize](customize.md)| [jvm]  <br>Brief description  <br><br><br>基于自定义结构构造<br><br>  <br>Content  <br>fun [customize](customize.md)(schema: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), keys: [Keys](../../../tech.whence.echo.dal.schema.key/-keys/index.md)): [Builder](../../-builder/index.md)<[Record](../../../tech.whence.echo.dal.entity/-record/index.md)>  <br><br><br>
| [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [locate](locate.md)| [jvm]  <br>Brief description  <br><br><br>基于实体类型构造<br><br>  <br>Content  <br>inline fun <[T](locate.md) : [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md)> [locate](locate.md)(schema: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [Builder](../../-builder/index.md)<[T](locate.md)>  <br>fun <[T](locate.md) : [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md)> [locate](locate.md)(declarer: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[T](locate.md)>, schema: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [Builder](../../-builder/index.md)<[T](locate.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>基于实体类型构造 若指定表名为空将以指定实体类型名称为准<br><br>  <br>Content  <br>fun <[T](locate.md) : [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md)> [locate](locate.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[T](locate.md)>, schema: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [Builder](../../-builder/index.md)<[T](locate.md)>  <br><br><br>
| [sourcing](sourcing.md)| [jvm]  <br>Brief description  <br><br><br>基于数据源结构构造 将在数据访问前去数据源加载字段数据<br><br>  <br>Content  <br>fun [sourcing](sourcing.md)(schema: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Builder](../../-builder/index.md)<[Record](../../../tech.whence.echo.dal.entity/-record/index.md)>  <br><br><br>
| [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

