---
title: Companion -
---
//[echo](../../../index.md)/[tech.whence.echo.support.jdbc.driver.general](../../index.md)/[JdbcDao](../index.md)/[Companion](index.md)



# Companion  
 [jvm] object [Companion](index.md)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [customize](customize.md)| [jvm]  <br>Brief description  <br><br><br>根据指定结构静态构造<br><br>  <br>Content  <br>fun <[PK](customize.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)> [customize](customize.md)(schema: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), keys: [Keys](../../../tech.whence.echo.dal.schema.key/-keys/index.md), consumer: [Consumer](../../../tech.whence.echo.function/-consumer/index.md)<[Builder](../../../tech.whence.echo.dal.schema/-builder/index.md)<[Record](../../../tech.whence.echo.dal.entity/-record/index.md)>>): [JdbcDao](../index.md)<[Record](../../../tech.whence.echo.dal.entity/-record/index.md), [PK](customize.md)>  <br><br><br>
| [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [extend](extend.md)| [jvm]  <br>Brief description  <br><br><br>根据扩展静态构造<br><br>  <br>Content  <br>fun <[D](extend.md) : [JdbcDao](../index.md)<out [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md), [PK](extend.md)>, [PK](extend.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)> [extend](extend.md)(client: [JdbcClient](../../-jdbc-client/index.md), producer: [Producer](../../../tech.whence.echo.function/-producer/index.md)<[D](extend.md)>): [D](extend.md)  <br><br><br>
| [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [locate](locate.md)| [jvm]  <br>Brief description  <br><br><br>根据实体构造<br><br>  <br>Content  <br>inline fun <[E](locate.md) : [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md), [PK](locate.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)> [locate](locate.md)(schema: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), consumer: [Consumer](../../../tech.whence.echo.function/-consumer/index.md)<[Builder](../../../tech.whence.echo.dal.schema/-builder/index.md)<[E](locate.md)>>): [JdbcDao](../index.md)<[E](locate.md), [PK](locate.md)>  <br><br><br>
| [sourcing](sourcing.md)| [jvm]  <br>Brief description  <br><br><br>根据数据源结构静态构造<br><br>  <br>Content  <br>fun <[PK](sourcing.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)> [sourcing](sourcing.md)(schema: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), consumer: [Consumer](../../../tech.whence.echo.function/-consumer/index.md)<[Builder](../../../tech.whence.echo.dal.schema/-builder/index.md)<[Record](../../../tech.whence.echo.dal.entity/-record/index.md)>>): [JdbcDao](../index.md)<[Record](../../../tech.whence.echo.dal.entity/-record/index.md), [PK](sourcing.md)>  <br><br><br>
| [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

