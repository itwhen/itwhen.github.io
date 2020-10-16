---
title: Retry -
---
//[echo](../../index.md)/[tech.whence.echo.retry](../index.md)/[Retry](index.md)



# Retry  
 [jvm] 

重试

interface [Retry](index.md)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [allow](allow.md)| [jvm]  <br>Brief description  <br><br><br>是否允许下一步操作<br><br>  <br>Content  <br>abstract fun [allow](allow.md)(retrying: [Retrying](../-retrying/index.md), sleeper: [RetrySleeper](../-retry-sleeper/index.md)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br>open fun [allow](allow.md)(times: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), elapsed: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html), sleeper: [RetrySleeper](../-retry-sleeper/index.md)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [next](next.md)| [jvm]  <br>Brief description  <br><br><br>取下一个持续时间<br><br>  <br>Content  <br>abstract fun [next](next.md)(retrying: [Retrying](../-retrying/index.md)): [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)  <br><br><br>
| [sleep](sleep.md)| [jvm]  <br>Brief description  <br><br><br>休眠一个初始单元时间<br><br>  <br>Content  <br>abstract fun [sleep](sleep.md)(sleeper: [RetrySleeper](../-retry-sleeper/index.md))  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [util](util.md)| [jvm]  <br>Brief description  <br><br><br>执行回调直到拿到有效结果或重试终止<br><br>  <br>Content  <br>open fun <[T](util.md)> [util](util.md)(creator: [Producer](../../tech.whence.echo.function/-producer/index.md)<[T](util.md)?>): [T](util.md)?  <br><br><br>
| [validate](validate.md)| [jvm]  <br>Brief description  <br><br><br>判断指定重试设置是否可用<br><br>  <br>Content  <br>abstract fun [validate](validate.md)(retrying: [Retrying](../-retrying/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>


## Inheritors  
  
|  Name| 
|---|
| [AbstractRetry](../-abstract-retry/index.md)
| [ForeverRetry](../-forever-retry/index.md)

