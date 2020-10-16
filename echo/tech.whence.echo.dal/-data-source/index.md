---
title: DataSource -
---
//[echo](../../index.md)/[tech.whence.echo.dal](../index.md)/[DataSource](index.md)



# DataSource  
 [jvm] 

数据源

interface [DataSource](index.md)   


## Types  
  
|  Name|  Summary| 
|---|---|
| [Attribute](-attribute/index.md)| [jvm]  <br>Brief description  <br><br><br>数据源属性<br><br>  <br>Content  <br>enum [Attribute](-attribute/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[DataSource.Attribute](-attribute/index.md)> , [Validity](../../tech.whence.echo.container.accessor/-validity/index.md)  <br><br><br>
| [Define](-define/index.md)| [jvm]  <br>Brief description  <br><br><br>将对象属性定义为数据源属性<br><br>  <br>Content  <br>@[Target](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.annotation/-target/index.html)(allowedTargets = [[AnnotationTarget.PROPERTY](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.annotation/-annotation-target/-p-r-o-p-e-r-t-y/index.html), [AnnotationTarget.FIELD](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.annotation/-annotation-target/-f-i-e-l-d/index.html)])  <br>  <br>annotation class [Define](-define/index.md)(**attribute**: [DataSource.Attribute](-attribute/index.md))  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [build](build.md)| [jvm]  <br>Brief description  <br><br><br>构建连接字符串<br><br>  <br>Content  <br>abstract fun [build](build.md)(): [ConnectionString](../../tech.whence.echo.dal.connection/-connection-string/index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Inheritors  
  
|  Name| 
|---|
| [JdbcDataSource](../../tech.whence.echo.support.jdbc.driver.general/-jdbc-data-source/index.md)
| [MysqlDataSource](../../tech.whence.echo.support.jdbc.driver.mysql/-mysql-data-source/index.md)
| [MongoDataSource](../../tech.whence.echo.support.mongo/-mongo-data-source/index.md)
| [RedisDataSource](../../tech.whence.echo.support.redis/-redis-data-source/index.md)

