---
title: Client -
---
//[echo](../../index.md)/[tech.whence.echo.dal.dao](../index.md)/[Client](index.md)



# Client  
 [jvm] 

数据源客户端

interface [Client](index.md)<[T](index.md), [C](index.md)>   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [close](close.md)| [jvm]  <br>Brief description  <br><br><br>关闭连接池<br><br>  <br>Content  <br>abstract suspend fun [close](close.md)()  <br><br><br>
| [connect](connect.md)| [jvm]  <br>Brief description  <br><br><br>获取一个连接<br><br>  <br>Content  <br>abstract suspend fun [connect](connect.md)(): [C](index.md)  <br><br><br>
| [describe](describe.md)| [jvm]  <br>Brief description  <br><br><br>描述表结构<br><br>  <br>Content  <br>abstract suspend fun [describe](describe.md)(schema: [Schema](../../tech.whence.echo.dal.schema/-schema/index.md)<out [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)>): [Keys](../../tech.whence.echo.dal.schema.key/-keys/index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [transact](transact.md)| [jvm]  <br>Brief description  <br><br><br>在事务中执行指定回调<br><br>  <br>Content  <br>abstract suspend fun <[R](transact.md)> [transact](transact.md)(block: [SuspendFunction1](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.coroutines/-suspend-function1/index.html)<[C](index.md), [R](transact.md)>): [R](transact.md)  <br><br><br>


## Inheritors  
  
|  Name| 
|---|
| [JdbcClient](../../tech.whence.echo.support.jdbc.driver.general/-jdbc-client/index.md)
| [MysqlClient](../../tech.whence.echo.support.jdbc.driver.mysql/-mysql-client/index.md)
| [MongoClient](../../tech.whence.echo.support.mongo/-mongo-client/index.md)
| [RedisClient](../../tech.whence.echo.support.redis/-redis-client/index.md)

