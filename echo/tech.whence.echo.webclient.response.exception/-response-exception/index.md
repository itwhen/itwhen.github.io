---
title: ResponseException -
---
//[echo](../../index.md)/[tech.whence.echo.webclient.response.exception](../index.md)/[ResponseException](index.md)



# ResponseException  
 [jvm] 

响应异常

open class [ResponseException](index.md)(**message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **cause**: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)?, **retryable**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) : [InvocationException](../../tech.whence.echo.webclient/-invocation-exception/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [ResponseException](-response-exception.md)|  [jvm] fun [ResponseException](-response-exception.md)(message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, cause: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)?, retryable: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [addSuppressed](../-response-unrecognized-exception/index.md#kotlin/Throwable/addSuppressed/#kotlin.Throwable/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [addSuppressed](../-response-unrecognized-exception/index.md#kotlin/Throwable/addSuppressed/#kotlin.Throwable/PointingToDeclaration/)(p0: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html))  <br><br><br>
| [equals](../-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [fillInStackTrace](../-response-unrecognized-exception/index.md#kotlin/Throwable/fillInStackTrace/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [fillInStackTrace](../-response-unrecognized-exception/index.md#kotlin/Throwable/fillInStackTrace/#/PointingToDeclaration/)(): [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)  <br><br><br>
| [getLocalizedMessage](../-response-unrecognized-exception/index.md#kotlin/Throwable/getLocalizedMessage/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [getLocalizedMessage](../-response-unrecognized-exception/index.md#kotlin/Throwable/getLocalizedMessage/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [getStackTrace](../-response-unrecognized-exception/index.md#kotlin/Throwable/getStackTrace/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [getStackTrace](../-response-unrecognized-exception/index.md#kotlin/Throwable/getStackTrace/#/PointingToDeclaration/)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[StackTraceElement](https://docs.oracle.com/javase/8/docs/api/java/lang/StackTraceElement.html)>  <br><br><br>
| [getSuppressed](../-response-unrecognized-exception/index.md#kotlin/Throwable/getSuppressed/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [getSuppressed](../-response-unrecognized-exception/index.md#kotlin/Throwable/getSuppressed/#/PointingToDeclaration/)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)>  <br><br><br>
| [hashCode](../-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [initCause](../-response-unrecognized-exception/index.md#kotlin/Throwable/initCause/#kotlin.Throwable/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [initCause](../-response-unrecognized-exception/index.md#kotlin/Throwable/initCause/#kotlin.Throwable/PointingToDeclaration/)(p0: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)): [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)  <br><br><br>
| [printStackTrace](../-response-unrecognized-exception/index.md#kotlin/Throwable/printStackTrace/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [printStackTrace](../-response-unrecognized-exception/index.md#kotlin/Throwable/printStackTrace/#/PointingToDeclaration/)()  <br>open override fun [printStackTrace](../-response-unrecognized-exception/index.md#kotlin/Throwable/printStackTrace/#java.io.PrintStream/PointingToDeclaration/)(p0: [PrintStream](https://docs.oracle.com/javase/8/docs/api/java/io/PrintStream.html))  <br>open override fun [printStackTrace](../-response-unrecognized-exception/index.md#kotlin/Throwable/printStackTrace/#java.io.PrintWriter/PointingToDeclaration/)(p0: [PrintWriter](https://docs.oracle.com/javase/8/docs/api/java/io/PrintWriter.html))  <br><br><br>
| [setStackTrace](../-response-unrecognized-exception/index.md#kotlin/Throwable/setStackTrace/#kotlin.Array[java.lang.StackTraceElement]/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [setStackTrace](../-response-unrecognized-exception/index.md#kotlin/Throwable/setStackTrace/#kotlin.Array[java.lang.StackTraceElement]/PointingToDeclaration/)(p0: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[StackTraceElement](https://docs.oracle.com/javase/8/docs/api/java/lang/StackTraceElement.html)>)  <br><br><br>
| [toString](../-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [cause](index.md#tech.whence.echo.webclient.response.exception/ResponseException/cause/#/PointingToDeclaration/)|  [jvm] open override val [cause](index.md#tech.whence.echo.webclient.response.exception/ResponseException/cause/#/PointingToDeclaration/): [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)?   <br>
| [message](index.md#tech.whence.echo.webclient.response.exception/ResponseException/message/#/PointingToDeclaration/)|  [jvm] open override val [message](index.md#tech.whence.echo.webclient.response.exception/ResponseException/message/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [retryable](index.md#tech.whence.echo.webclient.response.exception/ResponseException/retryable/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否可重试<br><br>override val [retryable](index.md#tech.whence.echo.webclient.response.exception/ResponseException/retryable/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>


## Inheritors  
  
|  Name| 
|---|
| [ResponseEmptyException](../-response-empty-exception/index.md)
| [ResponseFailedException](../-response-failed-exception/index.md)
| [ResponseIllegalException](../-response-illegal-exception/index.md)
| [ResponseIncompleteException](../-response-incomplete-exception/index.md)
| [ResponseTimeoutException](../-response-timeout-exception/index.md)
| [ResponseUnparsableException](../-response-unparsable-exception/index.md)
| [ResponseUnrecognizedException](../-response-unrecognized-exception/index.md)

