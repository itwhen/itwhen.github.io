---
title: MongoClient -
---
//[echo](../../index.md)/[tech.whence.echo.support.mongo](../index.md)/[MongoClient](index.md)



# MongoClient  
 [jvm] 

Mongo客户端

class [MongoClient](index.md)(**producer**: [Producer](../../tech.whence.echo.function/-producer/index.md)<MongoClient>) : [Client](../../tech.whence.echo.dal.dao/-client/index.md)<[MongoClient](index.md), MongoClient>    


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [MongoClient](-mongo-client.md)|  [jvm] <br><br><br><br>fun [MongoClient](-mongo-client.md)(producer: [Producer](../../tech.whence.echo.function/-producer/index.md)<MongoClient>)   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [close](close.md)| [jvm]  <br>Brief description  <br><br><br>关闭连接池<br><br>  <br>Content  <br>open suspend override fun [close](close.md)()  <br><br><br>
| [connect](connect.md)| [jvm]  <br>Brief description  <br><br><br>获取一个连接<br><br>  <br>Content  <br>open suspend override fun [connect](connect.md)(): MongoClient  <br><br><br>
| [describe](describe.md)| [jvm]  <br>Brief description  <br><br><br>描述表结构<br><br>  <br>Content  <br>open suspend override fun [describe](describe.md)(schema: [Schema](../../tech.whence.echo.dal.schema/-schema/index.md)<out [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)>): [Keys](../../tech.whence.echo.dal.schema.key/-keys/index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [transact](transact.md)| [jvm]  <br>Brief description  <br><br><br>在事务中执行指定回调<br><br>  <br>Content  <br>open suspend override fun <[R](transact.md)> [transact](transact.md)(block: [SuspendFunction1](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.coroutines/-suspend-function1/index.html)<MongoClient, [R](transact.md)>): [R](transact.md)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [pool](index.md#tech.whence.echo.support.mongo/MongoClient/pool/#/PointingToDeclaration/)|  [jvm] <br><br>Holder<MongoClient><br><br>val [pool](index.md#tech.whence.echo.support.mongo/MongoClient/pool/#/PointingToDeclaration/): [Holder](../../tech.whence.echo.container/-holder/index.md)<MongoClient>   <br>

