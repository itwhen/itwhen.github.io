---
title: Request -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.request](../index.md)/[Request](index.md)



# Request  
 [jvm] 

请求

class [Request](index.md)<[T](index.md) : [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md)>   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| T| <br><br>: Any 负载类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Request](-request.md)|  [jvm] @[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun <[T](index.md) : [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md)> [Request](-request.md)(payload: [T](index.md), user: [User](../-user/index.md)?, extra: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)?)   <br>
| [Request](-request.md)|  [jvm] fun [Request](-request.md)(request: JsonObject)   <br>
| [Request](-request.md)|  [jvm] fun [Request](-request.md)(request: OperationRequest, declarer: [KType](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-type/index.html)?, original: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))   <br>
| [Request](-request.md)|  [jvm] fun [Request](-request.md)(request: OperationRequest, accession: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md), declarer: [KType](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-type/index.html)?)   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toJson](to-json.md)| [jvm]  <br>Brief description  <br><br><br>转换<br><br>  <br>Content  <br>fun [toJson](to-json.md)(): JsonObject  <br><br><br>
| [toOperation](to-operation.md)| [jvm]  <br>Brief description  <br><br><br>转换<br><br>  <br>Content  <br>fun [toOperation](to-operation.md)(): OperationRequest  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [validate](validate.md)| [jvm]  <br>Brief description  <br><br><br>校验<br><br>  <br>Content  <br>fun [validate](validate.md)(): [Errors](../../tech.whence.echo.validation/-errors/index.md)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [accession](index.md#tech.whence.echo.rpc.request/Request/accession/#/PointingToDeclaration/)|  [jvm] <br><br>Accessor 初始数据<br><br>val [accession](index.md#tech.whence.echo.rpc.request/Request/accession/#/PointingToDeclaration/): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)   <br>
| [declarer](index.md#tech.whence.echo.rpc.request/Request/declarer/#/PointingToDeclaration/)|  [jvm] <br><br>KClass<out T>? 负载类<br><br>var [declarer](index.md#tech.whence.echo.rpc.request/Request/declarer/#/PointingToDeclaration/): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [T](index.md)>?   <br>
| [extra](index.md#tech.whence.echo.rpc.request/Request/extra/#/PointingToDeclaration/)|  [jvm] <br><br>Accessor 附加数据<br><br>val [extra](index.md#tech.whence.echo.rpc.request/Request/extra/#/PointingToDeclaration/): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)   <br>
| [payload](index.md#tech.whence.echo.rpc.request/Request/payload/#/PointingToDeclaration/)|  [jvm] <br><br>T? 负载数据<br><br>val [payload](index.md#tech.whence.echo.rpc.request/Request/payload/#/PointingToDeclaration/): [T](index.md)?   <br>
| [user](index.md#tech.whence.echo.rpc.request/Request/user/#/PointingToDeclaration/)|  [jvm] <br><br>User 当前用户<br><br>val [user](index.md#tech.whence.echo.rpc.request/Request/user/#/PointingToDeclaration/): [User](../-user/index.md)   <br>

