---
title: Invocation -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.api](../index.md)/[Invocation](index.md)



# Invocation  
 [jvm] 

调用

class [Invocation](index.md)(**id**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **path**: [Fixer](../../tech.whence.echo.function/-fixer/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>, **method**: PathItem.HttpMethod, **secure**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Invocation](-invocation.md)|  [jvm] <br><br><br><br>fun [Invocation](-invocation.md)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), path: [Fixer](../../tech.whence.echo.function/-fixer/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>, method: PathItem.HttpMethod, secure: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [id](index.md#tech.whence.echo.rpc.api/Invocation/id/#/PointingToDeclaration/)|  [jvm] <br><br>String 编号<br><br>val [id](index.md#tech.whence.echo.rpc.api/Invocation/id/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [method](index.md#tech.whence.echo.rpc.api/Invocation/method/#/PointingToDeclaration/)|  [jvm] <br><br>HttpMethod 请求方法<br><br>val [method](index.md#tech.whence.echo.rpc.api/Invocation/method/#/PointingToDeclaration/): PathItem.HttpMethod   <br>
| [name](index.md#tech.whence.echo.rpc.api/Invocation/name/#/PointingToDeclaration/)|  [jvm] <br><br>String 名称<br><br>val [name](index.md#tech.whence.echo.rpc.api/Invocation/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [parameters](index.md#tech.whence.echo.rpc.api/Invocation/parameters/#/PointingToDeclaration/)|  [jvm] <br><br>List<Parameter> 请求参数<br><br>var [parameters](index.md#tech.whence.echo.rpc.api/Invocation/parameters/#/PointingToDeclaration/): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<Parameter>   <br>
| [path](index.md#tech.whence.echo.rpc.api/Invocation/path/#/PointingToDeclaration/)|  [jvm] <br><br>Fixer<String> 路径<br><br>val [path](index.md#tech.whence.echo.rpc.api/Invocation/path/#/PointingToDeclaration/): [Fixer](../../tech.whence.echo.function/-fixer/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>   <br>
| [request](index.md#tech.whence.echo.rpc.api/Invocation/request/#/PointingToDeclaration/)|  [jvm] <br><br>RequestBody? 请求内容<br><br>var [request](index.md#tech.whence.echo.rpc.api/Invocation/request/#/PointingToDeclaration/): RequestBody?   <br>
| [responses](index.md#tech.whence.echo.rpc.api/Invocation/responses/#/PointingToDeclaration/)|  [jvm] <br><br>Map<HttpResponseStatus, ApiResponse> 响应<br><br>var [responses](index.md#tech.whence.echo.rpc.api/Invocation/responses/#/PointingToDeclaration/): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<HttpResponseStatus, ApiResponse>   <br>
| [secure](index.md#tech.whence.echo.rpc.api/Invocation/secure/#/PointingToDeclaration/)|  [jvm] val [secure](index.md#tech.whence.echo.rpc.api/Invocation/secure/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [security](index.md#tech.whence.echo.rpc.api/Invocation/security/#/PointingToDeclaration/)|  [jvm] <br><br>SecurityRequirement? 安全需求<br><br>var [security](index.md#tech.whence.echo.rpc.api/Invocation/security/#/PointingToDeclaration/): SecurityRequirement?   <br>

