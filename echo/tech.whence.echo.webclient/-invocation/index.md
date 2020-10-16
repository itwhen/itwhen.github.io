---
title: Invocation -
---
//[echo](../../index.md)/[tech.whence.echo.webclient](../index.md)/[Invocation](index.md)



# Invocation  
 [jvm] 

调用

data class [Invocation](index.md)<[A](index.md) : [Actable](../-actable/index.md), [R](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>(**request**: [Request](../../tech.whence.echo.webclient.request/-request/index.md)<[A](index.md)>, **response**: [Response](../../tech.whence.echo.webclient.response/-response/index.md), **result**: [R](index.md)?)   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| A| <br><br>: Action 行为<br><br>
| R| <br><br>结果<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Invocation](-invocation.md)|  [jvm] <br><br><br><br>fun <[A](index.md) : [Actable](../-actable/index.md), [R](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [Invocation](-invocation.md)(request: [Request](../../tech.whence.echo.webclient.request/-request/index.md)<[A](index.md)>, response: [Response](../../tech.whence.echo.webclient.response/-response/index.md), result: [R](index.md)?)   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [component1](component1.md)| [jvm]  <br>Content  <br>operator fun [component1](component1.md)(): [Request](../../tech.whence.echo.webclient.request/-request/index.md)<[A](index.md)>  <br><br><br>
| [component2](component2.md)| [jvm]  <br>Content  <br>operator fun [component2](component2.md)(): [Response](../../tech.whence.echo.webclient.response/-response/index.md)  <br><br><br>
| [component3](component3.md)| [jvm]  <br>Content  <br>operator fun [component3](component3.md)(): [R](index.md)?  <br><br><br>
| [copy](copy.md)| [jvm]  <br>Content  <br>fun [copy](copy.md)(request: [Request](../../tech.whence.echo.webclient.request/-request/index.md)<[A](index.md)>, response: [Response](../../tech.whence.echo.webclient.response/-response/index.md), result: [R](index.md)?): [Invocation](index.md)<[A](index.md), [R](index.md)>  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [reply](reply.md)| [jvm]  <br>Brief description  <br><br><br>转换为 Reply 对象<br><br>  <br>Content  <br>fun [reply](reply.md)(default: [Producer](../../tech.whence.echo.function/-producer/index.md)<[R](index.md)>?): [Reply](../../tech.whence.echo.container/-reply/index.md)<[R](index.md)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [request](index.md#tech.whence.echo.webclient/Invocation/request/#/PointingToDeclaration/)|  [jvm] <br><br>Request<A> 请求<br><br>val [request](index.md#tech.whence.echo.webclient/Invocation/request/#/PointingToDeclaration/): [Request](../../tech.whence.echo.webclient.request/-request/index.md)<[A](index.md)>   <br>
| [response](index.md#tech.whence.echo.webclient/Invocation/response/#/PointingToDeclaration/)|  [jvm] <br><br>Response 响应<br><br>val [response](index.md#tech.whence.echo.webclient/Invocation/response/#/PointingToDeclaration/): [Response](../../tech.whence.echo.webclient.response/-response/index.md)   <br>
| [result](index.md#tech.whence.echo.webclient/Invocation/result/#/PointingToDeclaration/)|  [jvm] <br><br>R? 结果<br><br>val [result](index.md#tech.whence.echo.webclient/Invocation/result/#/PointingToDeclaration/): [R](index.md)?   <br>

