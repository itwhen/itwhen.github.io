---
title: Companion -
---
//[echo](../../../index.md)/[tech.whence.echo.webclient.response](../../index.md)/[Response](../index.md)/[Companion](index.md)



# Companion  
 [jvm] object [Companion](index.md)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [create](create.md)| [jvm]  <br>Brief description  <br><br><br>基于HttpResponse生产者构造<br><br>  <br>Content  <br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  <br>  <br>fun [create](create.md)(creator: [Producer](../../../tech.whence.echo.function/-producer/index.md)<HttpResponse<Buffer>>): [Response](../index.md)  <br><br><br>
| [empty](empty.md)| [jvm]  <br>Brief description  <br><br><br>空响应<br><br>  <br>Content  <br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  <br>  <br>fun [empty](empty.md)(): [Response](../index.md)  <br><br><br>
| [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [exceptionally](exceptionally.md)| [jvm]  <br>Brief description  <br><br><br>基于异常构造<br><br>  <br>Content  <br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  <br>  <br>fun [exceptionally](exceptionally.md)(exception: [RequestException](../../../tech.whence.echo.webclient.request.exception/-request-exception/index.md)): [Response](../index.md)  <br><br><br>
| [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [of](of.md)| [jvm]  <br>Brief description  <br><br><br>基于HttpResponse构造<br><br>  <br>Content  <br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  <br>  <br>fun [of](of.md)(response: HttpResponse<*>): [Response](../index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>构造<br><br>  <br>Content  <br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [of](of.md)(status: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), headers: MultiMap?, content: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, exception: [ResponseException](../../../tech.whence.echo.webclient.response.exception/-response-exception/index.md)?): [Response](../index.md)  <br><br><br>
| [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

