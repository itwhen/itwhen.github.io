---
title: Companion -
---
//[echo](../../../index.md)/[tech.whence.echo.job.shell](../../index.md)/[Responder](../index.md)/[Companion](index.md)



# Companion  
 [jvm] object [Companion](index.md)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [fail](fail.md)| [jvm]  <br>Brief description  <br><br><br>失败响应<br><br>  <br>Content  <br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  <br>  <br>fun [fail](fail.md)(message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [Responder](../index.md)  <br><br><br>
| [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [of](of.md)| [jvm]  <br>Brief description  <br><br><br>根据远程调用结果构造<br><br>  <br>Content  <br>fun [of](of.md)(response: [Response](../../../tech.whence.echo.rpc.response/-response/index.md)<*>): [Responder](../index.md)  <br><br><br>
| [success](success.md)| [jvm]  <br>Brief description  <br><br><br>空响应<br><br>  <br>Content  <br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  <br>  <br>fun [success](success.md)(): [Responder](../index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>响应<br><br>  <br>Content  <br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  <br>  <br>fun [success](success.md)(message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Responder](../index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>表格格式响应<br><br>  <br>Content  <br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  <br>  <br>fun [success](success.md)(message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), extra: Table<*, *, *>): [Responder](../index.md)  <br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  <br>  <br>fun [success](success.md)(message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), extra: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [Responder](../index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>列表格式响应<br><br>  <br>Content  <br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  <br>  <br>fun [success](success.md)(message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), extra: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<*>): [Responder](../index.md)  <br><br><br>
| [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [BANNER](index.md#tech.whence.echo.job.shell/Responder.Companion/BANNER/#/PointingToDeclaration/)|  [jvm] <br><br>BANNER<br><br>val [BANNER](index.md#tech.whence.echo.job.shell/Responder.Companion/BANNER/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [EOL](index.md#tech.whence.echo.job.shell/Responder.Companion/EOL/#/PointingToDeclaration/)|  [jvm] <br><br>默认换行符<br><br>const val [EOL](index.md#tech.whence.echo.job.shell/Responder.Companion/EOL/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [HTML](index.md#tech.whence.echo.job.shell/Responder.Companion/HTML/#/PointingToDeclaration/)|  [jvm] <br><br>WEB HTML<br><br>val [HTML](index.md#tech.whence.echo.job.shell/Responder.Companion/HTML/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [JS](index.md#tech.whence.echo.job.shell/Responder.Companion/JS/#/PointingToDeclaration/)|  [jvm] <br><br>WEB JS<br><br>val [JS](index.md#tech.whence.echo.job.shell/Responder.Companion/JS/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>

