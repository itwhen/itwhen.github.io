---
title: MongoSource -
---
//[echo](../../index.md)/[tech.whence.echo.support.mongo.transfer](../index.md)/[MongoSource](index.md)



# MongoSource  
 [jvm] 

Mongo数据源

interface [MongoSource](index.md)<[T](index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)> : [Source](../../tech.whence.echo.dal.transfer.source/-source/index.md)<[MongoDao](../../tech.whence.echo.support.mongo/-mongo-dao/index.md)<[Record](../../tech.whence.echo.dal.entity/-record/index.md), [T](index.md)>, [T](index.md)>    


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| T| <br><br>: Serializable 主键类型<br><br>
  


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Inheritors  
  
|  Name| 
|---|
| [MongoBranchNode](../-mongo-branch-node/index.md)
| [MongoLeafNode](../-mongo-leaf-node/index.md)
| [MongoRoot](../-mongo-root/index.md)

