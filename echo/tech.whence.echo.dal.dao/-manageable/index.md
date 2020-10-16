---
title: Manageable -
---
//[echo](../../index.md)/[tech.whence.echo.dal.dao](../index.md)/[Manageable](index.md)



# Manageable  
 [jvm] 

可管理

interface [Manageable](index.md)<[E](index.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md), [C](index.md) : [Client](../-client/index.md)<*, *>>   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| C| <br><br>: Client 客户端类型<br><br>
| E| <br><br>: Entity 实体类型<br><br>
  


## Functions  
  
|  Name|  Summary| 
|---|---|
| [disconnect](disconnect.md)| [jvm]  <br>Brief description  <br><br><br>释放数据库连接<br><br>  <br>Content  <br>abstract suspend fun [disconnect](disconnect.md)()  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [preconnect](preconnect.md)| [jvm]  <br>Brief description  <br><br><br>设置数据库连接<br><br>  <br>Content  <br>abstract fun [preconnect](preconnect.md)(vertx: Vertx, connection: [ConnectionString](../../tech.whence.echo.dal.connection/-connection-string/index.md))  <br><br><br>
| [ready](ready.md)| [jvm]  <br>Brief description  <br><br><br>使用数据库连接执行回调<br><br>  <br>Content  <br>abstract suspend fun <[R](ready.md)> [ready](ready.md)(block: [SuspendFunction1](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.coroutines/-suspend-function1/index.html)<[C](index.md), [R](ready.md)>): [R](ready.md)  <br><br><br>
| [redefine](redefine.md)| [jvm]  <br>Brief description  <br><br><br>重新从数据源加载表结构<br><br>  <br>Content  <br>abstract suspend fun [redefine](redefine.md)(force: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [schema](index.md#tech.whence.echo.dal.dao/Manageable/schema/#/PointingToDeclaration/)|  [jvm] <br><br>Schema<E> 表定义<br><br>abstract val [schema](index.md#tech.whence.echo.dal.dao/Manageable/schema/#/PointingToDeclaration/): [Schema](../../tech.whence.echo.dal.schema/-schema/index.md)<[E](index.md)>   <br>


## Inheritors  
  
|  Name| 
|---|
| [Dao](../-dao/index.md)

