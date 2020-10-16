---
title: Response -
---
//[echo](../../index.md)/[tech.whence.echo.webclient.response](../index.md)/[Response](index.md)



# Response  
 [jvm] 

响应

class [Response](index.md)   


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>
| [Type](-type/index.md)| [jvm]  <br>Brief description  <br><br><br>响应类型<br><br>  <br>Content  <br>enum [Type](-type/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Response.Type](-type/index.md)>   <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [stringify](stringify.md)| [jvm]  <br>Brief description  <br><br><br>格式化<br><br>  <br>Content  <br>fun [stringify](stringify.md)(text: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?  <br><br><br>
| [toString](to-string.md)| [jvm]  <br>Content  <br>open override fun [toString](to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [code](index.md#tech.whence.echo.webclient.response/Response/code/#/PointingToDeclaration/)|  [jvm] <br><br>String? 业务错误编码<br><br>var [code](index.md#tech.whence.echo.webclient.response/Response/code/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [content](index.md#tech.whence.echo.webclient.response/Response/content/#/PointingToDeclaration/)|  [jvm] <br><br>String? 内容<br><br>val [content](index.md#tech.whence.echo.webclient.response/Response/content/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [exception](index.md#tech.whence.echo.webclient.response/Response/exception/#/PointingToDeclaration/)|  [jvm] <br><br>InvocationException? 异常<br><br>var [exception](index.md#tech.whence.echo.webclient.response/Response/exception/#/PointingToDeclaration/): [InvocationException](../../tech.whence.echo.webclient/-invocation-exception/index.md)?   <br>
| [exceptional](index.md#tech.whence.echo.webclient.response/Response/exceptional/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否异常<br><br>val [exceptional](index.md#tech.whence.echo.webclient.response/Response/exceptional/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [failed](index.md#tech.whence.echo.webclient.response/Response/failed/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否业务失败<br><br>val [failed](index.md#tech.whence.echo.webclient.response/Response/failed/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [headers](index.md#tech.whence.echo.webclient.response/Response/headers/#/PointingToDeclaration/)|  [jvm] <br><br>MultiMap? 响应头<br><br>val [headers](index.md#tech.whence.echo.webclient.response/Response/headers/#/PointingToDeclaration/): MultiMap?   <br>
| [id](index.md#tech.whence.echo.webclient.response/Response/id/#/PointingToDeclaration/)|  [jvm] <br><br>String?<br><br>var [id](index.md#tech.whence.echo.webclient.response/Response/id/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [message](index.md#tech.whence.echo.webclient.response/Response/message/#/PointingToDeclaration/)|  [jvm] <br><br>String? 业务错误消息<br><br>var [message](index.md#tech.whence.echo.webclient.response/Response/message/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [requestedAt](index.md#tech.whence.echo.webclient.response/Response/requestedAt/#/PointingToDeclaration/)|  [jvm] <br><br>Instant? 请求于<br><br>var [requestedAt](index.md#tech.whence.echo.webclient.response/Response/requestedAt/#/PointingToDeclaration/): [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)?   <br>
| [respondedAt](index.md#tech.whence.echo.webclient.response/Response/respondedAt/#/PointingToDeclaration/)|  [jvm] <br><br>Instant? 响应于<br><br>var [respondedAt](index.md#tech.whence.echo.webclient.response/Response/respondedAt/#/PointingToDeclaration/): [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)?   <br>
| [result](index.md#tech.whence.echo.webclient.response/Response/result/#/PointingToDeclaration/)|  [jvm] <br><br>Accessor? 解析结果<br><br>var [result](index.md#tech.whence.echo.webclient.response/Response/result/#/PointingToDeclaration/): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)?   <br>
| [retryable](index.md#tech.whence.echo.webclient.response/Response/retryable/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否可重试<br><br>var [retryable](index.md#tech.whence.echo.webclient.response/Response/retryable/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [status](index.md#tech.whence.echo.webclient.response/Response/status/#/PointingToDeclaration/)|  [jvm] <br><br>Int 状态码<br><br>val [status](index.md#tech.whence.echo.webclient.response/Response/status/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>
| [valid](index.md#tech.whence.echo.webclient.response/Response/valid/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否有效<br><br>val [valid](index.md#tech.whence.echo.webclient.response/Response/valid/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>

