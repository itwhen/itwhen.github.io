---
title: ResponseHandler -
---
//[echo](../../index.md)/[tech.whence.echo.webclient.response](../index.md)/[ResponseHandler](index.md)



# ResponseHandler  
 [jvm] 

响应处理器

fun fun interface [ResponseHandler](index.md)<[A](index.md) : [Actable](../../tech.whence.echo.webclient/-actable/index.md), [R](index.md)>   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| A| <br><br>: Action 行为<br><br>
| R| <br><br><br><br>
  


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [handle](handle.md)| [jvm]  <br>Brief description  <br><br><br>处理 根据指定请求/响应/默认结果生成结果<br><br>  <br>Content  <br>abstract fun [handle](handle.md)(request: [Request](../../tech.whence.echo.webclient.request/-request/index.md)<[A](index.md)>, response: [Response](../-response/index.md)): [R](index.md)?  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

