---
title: Responder -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.task](../index.md)/[Responder](index.md)



# Responder  
 [jvm] 

响应器

class [Responder](index.md)(**tasks**: [Tasks](../-tasks/index.md))   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Responder](-responder.md)|  [jvm] <br><br><br><br>fun [Responder](-responder.md)(tasks: [Tasks](../-tasks/index.md))   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Batcher](-batcher/index.md)| [jvm]  <br>Brief description  <br><br><br>批量处理器<br><br>  <br>Content  <br>class [Batcher](-batcher/index.md)<[R](-batcher/index.md) : [Traceable](../../tech.whence.echo.job/-traceable/index.md)>(**tasks**: [Tasks](../-tasks/index.md))  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [fail](fail.md)| [jvm]  <br>Brief description  <br><br><br>置为失败<br><br>  <br>Content  <br>fun [fail](fail.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))  <br>fun [fail](fail.md)(result: [Traceable](../../tech.whence.echo.job/-traceable/index.md))  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [ignore](ignore.md)| [jvm]  <br>Brief description  <br><br><br>忽略<br><br>  <br>Content  <br>fun [ignore](ignore.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))  <br>fun [ignore](ignore.md)(result: [Traceable](../../tech.whence.echo.job/-traceable/index.md))  <br><br><br>
| [retry](retry.md)| [jvm]  <br>Brief description  <br><br><br>重试<br><br>  <br>Content  <br>fun [retry](retry.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))  <br>fun [retry](retry.md)(result: [Traceable](../../tech.whence.echo.job/-traceable/index.md))  <br>fun [retry](retry.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), retry: [Retry](../../tech.whence.echo.retry/-retry/index.md)?)  <br>fun [retry](retry.md)(result: [Traceable](../../tech.whence.echo.job/-traceable/index.md), retry: [Retry](../../tech.whence.echo.retry/-retry/index.md)?)  <br><br><br>
| [succeed](succeed.md)| [jvm]  <br>Brief description  <br><br><br>置为成功<br><br>  <br>Content  <br>fun [succeed](succeed.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))  <br>fun [succeed](succeed.md)(result: [Traceable](../../tech.whence.echo.job/-traceable/index.md))  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

