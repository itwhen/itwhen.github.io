---
title: Limiter -
---
//[echo](../../index.md)/[tech.whence.echo.dal.querier.component](../index.md)/[Limiter](index.md)



# Limiter  
 [jvm] 

限制器

interface [Limiter](index.md)<[T](index.md)>   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| T| <br><br><br><br>
  


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [limit](limit.md)| [jvm]  <br>Brief description  <br><br><br>数量限制<br><br>  <br>Content  <br>abstract fun [limit](limit.md)(limit: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)): [T](index.md)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Inheritors  
  
|  Name| 
|---|
| [AbstractRetriever](../../tech.whence.echo.dal.querier/-abstract-retriever/index.md)
| [AbstractDelete](../../tech.whence.echo.support.jdbc.querier/-abstract-delete/index.md)
| [AbstractUpdate](../../tech.whence.echo.support.jdbc.querier/-abstract-update/index.md)
| [Where](../../tech.whence.echo.support.jdbc.querier.component/-where/index.md)
| [Select](../../tech.whence.echo.support.mongo.querier/-select/index.md)

