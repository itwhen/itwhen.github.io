---
title: Response -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.response](../index.md)/[Response](index.md)



# Response  
 [jvm] 

响应

class [Response](index.md)<[T](index.md) : [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md)> : [Responsive](../-responsive/index.md)   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| T| <br><br>: Payload 负载类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Response](-response.md)|  [jvm] fun [Response](-response.md)()   <br>
| [Response](-response.md)|  [jvm] fun [Response](-response.md)(response: JsonObject)   <br>
| [Response](-response.md)|  [jvm] fun [Response](-response.md)(response: OperationResponse)   <br>
| [Response](-response.md)|  [jvm] fun [Response](-response.md)(headers: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md), data: Buffer?)   <br>
| [Response](-response.md)|  [jvm] fun <[T](index.md) : [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md)> [Response](-response.md)(payload: [T](index.md), type: [KType](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-type/index.html))   <br>
| [Response](-response.md)|  [jvm] fun <[T](index.md) : [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md)> [Response](-response.md)(payload: [T](index.md), type: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[T](index.md)>)   <br>
| [Response](-response.md)|  [jvm] fun <[T](index.md) : [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md)> [Response](-response.md)(payload: [T](index.md), type: [Type](https://docs.oracle.com/javase/8/docs/api/java/lang/reflect/Type.html))   <br>
| [Response](-response.md)|  [jvm] fun [Response](-response.md)(failure: [Failure](../-failure/index.md))   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [exceptionally](exceptionally.md)| [jvm]  <br>Brief description  <br><br><br>若失败时<br><br>  <br>Content  <br>fun [exceptionally](exceptionally.md)(handler: [Failure.Handler](../-failure/-handler/index.md)): [Response](index.md)<[T](index.md)>  <br><br><br>
| [get](get.md)| [jvm]  <br>Brief description  <br><br><br>获取负载数据<br><br>  <br>Content  <br>fun [get](get.md)(): [T](index.md)?  <br>fun <[V](get.md)> [get](get.md)(block: [T](index.md).() -> [V](get.md)): [V](get.md)?  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [into](into.md)| [jvm]  <br>Brief description  <br><br><br>若成功时<br><br>  <br>Content  <br>fun [into](into.md)(block: ([T](index.md)?) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))  <br><br><br>[jvm]  <br>Brief description  <br><br><br>传输到响应<br><br>  <br>Content  <br>open override fun <T : [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md)> [into](../-responsive/into.md)(responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<T>)  <br><br><br>
| [map](map.md)| [jvm]  <br>Brief description  <br><br><br>转换为指定对象<br><br>  <br>Content  <br>fun <[R](map.md)> [map](map.md)(transformer: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[Response](index.md)<[T](index.md)>, [R](map.md)>): [R](map.md)  <br><br><br>
| [toJson](to-json.md)| [jvm]  <br>Brief description  <br><br><br>转换<br><br>  <br>Content  <br>fun [toJson](to-json.md)(): JsonObject  <br><br><br>
| [toOperation](to-operation.md)| [jvm]  <br>Brief description  <br><br><br>转换<br><br>  <br>Content  <br>fun [toOperation](to-operation.md)(accessible: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): OperationResponse  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [declarer](index.md#tech.whence.echo.rpc.response/Response/declarer/#/PointingToDeclaration/)|  [jvm] <br><br>KType? 负载类<br><br>var [declarer](index.md#tech.whence.echo.rpc.response/Response/declarer/#/PointingToDeclaration/): JavaType?   <br>
| [extra](index.md#tech.whence.echo.rpc.response/Response/extra/#/PointingToDeclaration/)|  [jvm] <br><br>Accessor? 额外数据<br><br>var [extra](index.md#tech.whence.echo.rpc.response/Response/extra/#/PointingToDeclaration/): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)?   <br>
| [failure](index.md#tech.whence.echo.rpc.response/Response/failure/#/PointingToDeclaration/)|  [jvm] <br><br>Failure? 业务错误<br><br>var [failure](index.md#tech.whence.echo.rpc.response/Response/failure/#/PointingToDeclaration/): [Failure](../-failure/index.md)?   <br>
| [payload](index.md#tech.whence.echo.rpc.response/Response/payload/#/PointingToDeclaration/)|  [jvm] <br><br>T? 负载数据<br><br>var [payload](index.md#tech.whence.echo.rpc.response/Response/payload/#/PointingToDeclaration/): [T](index.md)?   <br>
| [valid](index.md#tech.whence.echo.rpc.response/Response/valid/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否正常<br><br>val [valid](index.md#tech.whence.echo.rpc.response/Response/valid/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>

