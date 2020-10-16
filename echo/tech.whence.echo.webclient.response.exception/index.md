---
title: tech.whence.echo.webclient.response.exception -
---
//[echo](../index.md)/[tech.whence.echo.webclient.response.exception](index.md)



# Package tech.whence.echo.webclient.response.exception  


## Types  
  
|  Name|  Summary| 
|---|---|
| [ResponseEmptyException](-response-empty-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>空响应异常<br><br>  <br>Content  <br>class [ResponseEmptyException](-response-empty-exception/index.md) : [ResponseException](-response-exception/index.md)  <br><br><br>
| [ResponseException](-response-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>响应异常<br><br>  <br>Content  <br>open class [ResponseException](-response-exception/index.md)(**message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **cause**: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)?, **retryable**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) : [InvocationException](../tech.whence.echo.webclient/-invocation-exception/index.md)  <br><br><br>
| [ResponseFailedException](-response-failed-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>业务响应异常<br><br>  <br>Content  <br>class [ResponseFailedException](-response-failed-exception/index.md)(**code**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **retryable**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) : [ResponseException](-response-exception/index.md)  <br><br><br>
| [ResponseIllegalException](-response-illegal-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>非法响应异常<br><br>  <br>Content  <br>class [ResponseIllegalException](-response-illegal-exception/index.md)(**message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [ResponseException](-response-exception/index.md)  <br><br><br>
| [ResponseIncompleteException](-response-incomplete-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>响应未完毕异常<br><br>  <br>Content  <br>class [ResponseIncompleteException](-response-incomplete-exception/index.md)(**message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [ResponseException](-response-exception/index.md)  <br><br><br>
| [ResponseTimeoutException](-response-timeout-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>响应超时异常<br><br>  <br>Content  <br>class [ResponseTimeoutException](-response-timeout-exception/index.md)(**message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [ResponseException](-response-exception/index.md)  <br><br><br>
| [ResponseUnparsableException](-response-unparsable-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>响应无法解析异常<br><br>  <br>Content  <br>class [ResponseUnparsableException](-response-unparsable-exception/index.md)(**cause**: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html), **retryable**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **content**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) : [ResponseException](-response-exception/index.md)  <br><br><br>
| [ResponseUnrecognizedException](-response-unrecognized-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>响应无法识别异常<br><br>  <br>Content  <br>class [ResponseUnrecognizedException](-response-unrecognized-exception/index.md)(**status**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **content**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) : [ResponseException](-response-exception/index.md)  <br><br><br>

