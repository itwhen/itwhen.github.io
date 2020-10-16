---
title: Failure -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.response](../index.md)/[Failure](index.md)



# Failure  
 [jvm] 

失败

data class [Failure](index.md)(**code**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **errors**: [Errors](../../tech.whence.echo.validation/-errors/index.md)?) : [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html), [Readable](../../tech.whence.echo.container.accessor/-readable/index.md), [Responsive](../-responsive/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Failure](-failure.md)|  [jvm] <br><br><br><br>fun [Failure](-failure.md)(code: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), errors: [Errors](../../tech.whence.echo.validation/-errors/index.md)?)   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>
| [Handler](-handler/index.md)| [jvm]  <br>Brief description  <br><br><br>失败句柄<br><br>  <br>Content  <br>fun fun interface [Handler](-handler/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [access](access.md)| [jvm]  <br>Brief description  <br><br><br>转换<br><br>  <br>Content  <br>open override fun [access](access.md)(): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)  <br><br><br>
| [addSuppressed](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Throwable/addSuppressed/#kotlin.Throwable/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [addSuppressed](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Throwable/addSuppressed/#kotlin.Throwable/PointingToDeclaration/)(p0: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html))  <br><br><br>
| [component1](component1.md)| [jvm]  <br>Content  <br>operator fun [component1](component1.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [component2](component2.md)| [jvm]  <br>Content  <br>operator fun [component2](component2.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [component3](component3.md)| [jvm]  <br>Content  <br>operator fun [component3](component3.md)(): [Errors](../../tech.whence.echo.validation/-errors/index.md)?  <br><br><br>
| [copy](copy.md)| [jvm]  <br>Content  <br>fun [copy](copy.md)(code: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), errors: [Errors](../../tech.whence.echo.validation/-errors/index.md)?): [Failure](index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [fillInStackTrace](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Throwable/fillInStackTrace/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [fillInStackTrace](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Throwable/fillInStackTrace/#/PointingToDeclaration/)(): [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)  <br><br><br>
| [getLocalizedMessage](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Throwable/getLocalizedMessage/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [getLocalizedMessage](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Throwable/getLocalizedMessage/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [getStackTrace](get-stack-trace.md)| [jvm]  <br>Brief description  <br><br><br>隐藏当前跟踪堆栈<br><br>  <br>Content  <br>open override fun [getStackTrace](get-stack-trace.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[StackTraceElement](https://docs.oracle.com/javase/8/docs/api/java/lang/StackTraceElement.html)>  <br><br><br>
| [getSuppressed](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Throwable/getSuppressed/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [getSuppressed](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Throwable/getSuppressed/#/PointingToDeclaration/)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)>  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [initCause](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Throwable/initCause/#kotlin.Throwable/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [initCause](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Throwable/initCause/#kotlin.Throwable/PointingToDeclaration/)(p0: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)): [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)  <br><br><br>
| [into](../-responsive/into.md)| [jvm]  <br>Brief description  <br><br><br>传输到响应<br><br>  <br>Content  <br>open override fun <T : [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md)> [into](../-responsive/into.md)(responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<T>)  <br><br><br>
| [printStackTrace](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Throwable/printStackTrace/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [printStackTrace](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Throwable/printStackTrace/#/PointingToDeclaration/)()  <br>open override fun [printStackTrace](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Throwable/printStackTrace/#java.io.PrintStream/PointingToDeclaration/)(p0: [PrintStream](https://docs.oracle.com/javase/8/docs/api/java/io/PrintStream.html))  <br>open override fun [printStackTrace](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Throwable/printStackTrace/#java.io.PrintWriter/PointingToDeclaration/)(p0: [PrintWriter](https://docs.oracle.com/javase/8/docs/api/java/io/PrintWriter.html))  <br><br><br>
| [refine](refine.md)| [jvm]  <br>Brief description  <br><br><br>完善消息<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [refine](refine.md)(message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), override: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Failure](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>完善错误<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [refine](refine.md)(failure: [Failure](index.md), override: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Failure](index.md)  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [refine](refine.md)(code: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), override: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Failure](index.md)  <br><br><br>
| [setStackTrace](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Throwable/setStackTrace/#kotlin.Array[java.lang.StackTraceElement]/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [setStackTrace](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Throwable/setStackTrace/#kotlin.Array[java.lang.StackTraceElement]/PointingToDeclaration/)(p0: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[StackTraceElement](https://docs.oracle.com/javase/8/docs/api/java/lang/StackTraceElement.html)>)  <br><br><br>
| [simplify](simplify.md)| [jvm]  <br>Brief description  <br><br><br>简化版<br><br>  <br>Content  <br>fun [simplify](simplify.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [toString](to-string.md)| [jvm]  <br>Content  <br>open override fun [toString](to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [cause](index.md#tech.whence.echo.rpc.response/Failure/cause/#/PointingToDeclaration/)|  [jvm] open override val [cause](index.md#tech.whence.echo.rpc.response/Failure/cause/#/PointingToDeclaration/): [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)?   <br>
| [code](index.md#tech.whence.echo.rpc.response/Failure/code/#/PointingToDeclaration/)|  [jvm] <br><br>String 错误编码<br><br>val [code](index.md#tech.whence.echo.rpc.response/Failure/code/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [errors](index.md#tech.whence.echo.rpc.response/Failure/errors/#/PointingToDeclaration/)|  [jvm] <br><br>Errors? 校验错误<br><br>val [errors](index.md#tech.whence.echo.rpc.response/Failure/errors/#/PointingToDeclaration/): [Errors](../../tech.whence.echo.validation/-errors/index.md)?   <br>
| [message](index.md#tech.whence.echo.rpc.response/Failure/message/#/PointingToDeclaration/)|  [jvm] <br><br>String 错误消息<br><br>open override val [message](index.md#tech.whence.echo.rpc.response/Failure/message/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [reason](index.md#tech.whence.echo.rpc.response/Failure/reason/#/PointingToDeclaration/)|  [jvm] <br><br>Reason 原由<br><br>val [reason](index.md#tech.whence.echo.rpc.response/Failure/reason/#/PointingToDeclaration/): [Reason](../-reason/index.md)   <br>

