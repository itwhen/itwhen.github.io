---
title: tech.whence.echo.webclient.request.exception -
---
//[echo](../index.md)/[tech.whence.echo.webclient.request.exception](index.md)



# Package tech.whence.echo.webclient.request.exception  


## Types  
  
|  Name|  Summary| 
|---|---|
| [RequestAuthorizationExpiredException](-request-authorization-expired-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>授权过期异常<br><br>  <br>Content  <br>class [RequestAuthorizationExpiredException](-request-authorization-expired-exception/index.md)(**message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [RequestException](-request-exception/index.md)  <br><br><br>
| [RequestAuthorizationFailedException](-request-authorization-failed-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>授权失败异常<br><br>  <br>Content  <br>class [RequestAuthorizationFailedException](-request-authorization-failed-exception/index.md)(**message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [RequestException](-request-exception/index.md)  <br><br><br>
| [RequestAuthorizationUnprovidedException](-request-authorization-unprovided-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>未授权异常<br><br>  <br>Content  <br>class [RequestAuthorizationUnprovidedException](-request-authorization-unprovided-exception/index.md)(**environment**: [Environment](../tech.whence.echo.support/-environment/index.md)) : [RequestException](-request-exception/index.md)  <br><br><br>
| [RequestException](-request-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>请求异常<br><br>  <br>Content  <br>open class [RequestException](-request-exception/index.md)(**message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **cause**: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)?, **retryable**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) : [InvocationException](../tech.whence.echo.webclient/-invocation-exception/index.md)  <br><br><br>
| [RequestFailedException](-request-failed-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>请求失败异常<br><br>  <br>Content  <br>class [RequestFailedException](-request-failed-exception/index.md)(**request**: [Request](../tech.whence.echo.webclient.request/-request/index.md)<*>, **cause**: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)?) : [RequestException](-request-exception/index.md)  <br><br><br>
| [RequestParameterInvalidException](-request-parameter-invalid-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>请求参数非法异常<br><br>  <br>Content  <br>class [RequestParameterInvalidException](-request-parameter-invalid-exception/index.md)(**message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **cause**: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)?) : [RequestException](-request-exception/index.md)  <br><br><br>
| [RequestRedoableException](-request-redoable-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>需重试异常<br><br>  <br>Content  <br>class [RequestRedoableException](-request-redoable-exception/index.md)(**message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **fallback**: [Producer](../tech.whence.echo.function/-producer/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>) : [RequestException](-request-exception/index.md)  <br><br><br>
| [RequestRestrictedException](-request-restricted-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>请求受限异常<br><br>  <br>Content  <br>class [RequestRestrictedException](-request-restricted-exception/index.md)(**message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **retryable**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) : [RequestException](-request-exception/index.md)  <br><br><br>
| [RequestThrottledException](-request-throttled-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>请求频率受限异常<br><br>  <br>Content  <br>class [RequestThrottledException](-request-throttled-exception/index.md)(**message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [RequestException](-request-exception/index.md)  <br><br><br>

