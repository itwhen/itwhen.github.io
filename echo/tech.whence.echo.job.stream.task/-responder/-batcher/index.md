---
title: Batcher -
---
//[echo](../../../index.md)/[tech.whence.echo.job.stream.task](../../index.md)/[Responder](../index.md)/[Batcher](index.md)



# Batcher  
 [jvm] 

批量处理器

class [Batcher](index.md)<[R](index.md) : [Traceable](../../../tech.whence.echo.job/-traceable/index.md)>(**tasks**: [Tasks](../../-tasks/index.md))   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| R| <br><br>: Traceable 数据类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Batcher](-batcher.md)|  [jvm] <br><br><br><br>fun [Batcher](-batcher.md)(tasks: [Tasks](../../-tasks/index.md))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [fail](fail.md)| [jvm]  <br>Brief description  <br><br><br>置为失败<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [fail](fail.md)(filter: [Predicate](../../../tech.whence.echo.function/-predicate/index.md)<[R](index.md)>?): [Responder.Batcher](index.md)<[R](index.md)>  <br><br><br>
| [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [ignore](ignore.md)| [jvm]  <br>Brief description  <br><br><br>忽略<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [ignore](ignore.md)(filter: [Predicate](../../../tech.whence.echo.function/-predicate/index.md)<[R](index.md)>?): [Responder.Batcher](index.md)<[R](index.md)>  <br><br><br>
| [peek](peek.md)| [jvm]  <br>Brief description  <br><br><br>遍历单个<br><br>  <br>Content  <br>fun [peek](peek.md)(callback: [Consumer](../../../tech.whence.echo.function/-consumer/index.md)<[R](index.md)>): [Responder.Batcher](index.md)<[R](index.md)>  <br><br><br>
| [reload](reload.md)| [jvm]  <br>Brief description  <br><br><br>重载<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [reload](reload.md)(filter: [Predicate](../../../tech.whence.echo.function/-predicate/index.md)<[R](index.md)>?): [Responder.Batcher](index.md)<[R](index.md)>  <br><br><br>
| [retry](retry.md)| [jvm]  <br>Brief description  <br><br><br>重试<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [retry](retry.md)(filter: [Predicate](../../../tech.whence.echo.function/-predicate/index.md)<[R](index.md)>?, retry: [Retry](../../../tech.whence.echo.retry/-retry/index.md)?): [Responder.Batcher](index.md)<[R](index.md)>  <br><br><br>
| [succeed](succeed.md)| [jvm]  <br>Brief description  <br><br><br>置为成功<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [succeed](succeed.md)(filter: [Predicate](../../../tech.whence.echo.function/-predicate/index.md)<[R](index.md)>?): [Responder.Batcher](index.md)<[R](index.md)>  <br><br><br>
| [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

