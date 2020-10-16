---
title: ResponseUnrecognizedException -
---
//[echo](../../index.md)/[tech.whence.echo.webclient.response.exception](../index.md)/[ResponseUnrecognizedException](index.md)



# ResponseUnrecognizedException  
 [jvm] 

响应无法识别异常

class [ResponseUnrecognizedException](index.md)(**status**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **content**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) : [ResponseException](../-response-exception/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [ResponseUnrecognizedException](-response-unrecognized-exception.md)|  [jvm] <br><br><br><br>fun [ResponseUnrecognizedException](-response-unrecognized-exception.md)(status: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), content: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?)   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [addSuppressed](index.md#kotlin/Throwable/addSuppressed/#kotlin.Throwable/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [addSuppressed](index.md#kotlin/Throwable/addSuppressed/#kotlin.Throwable/PointingToDeclaration/)(p0: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html))  <br><br><br>
| [equals](index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [fillInStackTrace](index.md#kotlin/Throwable/fillInStackTrace/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [fillInStackTrace](index.md#kotlin/Throwable/fillInStackTrace/#/PointingToDeclaration/)(): [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)  <br><br><br>
| [getLocalizedMessage](index.md#kotlin/Throwable/getLocalizedMessage/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [getLocalizedMessage](index.md#kotlin/Throwable/getLocalizedMessage/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [getStackTrace](index.md#kotlin/Throwable/getStackTrace/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [getStackTrace](index.md#kotlin/Throwable/getStackTrace/#/PointingToDeclaration/)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[StackTraceElement](https://docs.oracle.com/javase/8/docs/api/java/lang/StackTraceElement.html)>  <br><br><br>
| [getSuppressed](index.md#kotlin/Throwable/getSuppressed/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [getSuppressed](index.md#kotlin/Throwable/getSuppressed/#/PointingToDeclaration/)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)>  <br><br><br>
| [hashCode](index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [initCause](index.md#kotlin/Throwable/initCause/#kotlin.Throwable/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [initCause](index.md#kotlin/Throwable/initCause/#kotlin.Throwable/PointingToDeclaration/)(p0: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)): [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)  <br><br><br>
| [printStackTrace](index.md#kotlin/Throwable/printStackTrace/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [printStackTrace](index.md#kotlin/Throwable/printStackTrace/#/PointingToDeclaration/)()  <br>open override fun [printStackTrace](index.md#kotlin/Throwable/printStackTrace/#java.io.PrintStream/PointingToDeclaration/)(p0: [PrintStream](https://docs.oracle.com/javase/8/docs/api/java/io/PrintStream.html))  <br>open override fun [printStackTrace](index.md#kotlin/Throwable/printStackTrace/#java.io.PrintWriter/PointingToDeclaration/)(p0: [PrintWriter](https://docs.oracle.com/javase/8/docs/api/java/io/PrintWriter.html))  <br><br><br>
| [setStackTrace](index.md#kotlin/Throwable/setStackTrace/#kotlin.Array[java.lang.StackTraceElement]/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [setStackTrace](index.md#kotlin/Throwable/setStackTrace/#kotlin.Array[java.lang.StackTraceElement]/PointingToDeclaration/)(p0: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[StackTraceElement](https://docs.oracle.com/javase/8/docs/api/java/lang/StackTraceElement.html)>)  <br><br><br>
| [toString](index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [cause](index.md#tech.whence.echo.webclient.response.exception/ResponseUnrecognizedException/cause/#/PointingToDeclaration/)|  [jvm] open override val [cause](index.md#tech.whence.echo.webclient.response.exception/ResponseUnrecognizedException/cause/#/PointingToDeclaration/): [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)?   <br>
| [message](index.md#tech.whence.echo.webclient.response.exception/ResponseUnrecognizedException/message/#/PointingToDeclaration/)|  [jvm] open override val [message](index.md#tech.whence.echo.webclient.response.exception/ResponseUnrecognizedException/message/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [retryable](index.md#tech.whence.echo.webclient.response.exception/ResponseUnrecognizedException/retryable/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否可重试<br><br>override val [retryable](index.md#tech.whence.echo.webclient.response.exception/ResponseUnrecognizedException/retryable/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [status](index.md#tech.whence.echo.webclient.response.exception/ResponseUnrecognizedException/status/#/PointingToDeclaration/)|  [jvm] <br><br>Int http状态<br><br>val [status](index.md#tech.whence.echo.webclient.response.exception/ResponseUnrecognizedException/status/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>

