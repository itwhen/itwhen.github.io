---
title: Retrying -
---
//[echo](../../index.md)/[tech.whence.echo.retry](../index.md)/[Retrying](index.md)



# Retrying  
 [jvm] 

重试设置

class [Retrying](index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Retrying](-retrying.md)|  [jvm] fun [Retrying](-retrying.md)()   <br>
| [Retrying](-retrying.md)|  [jvm] fun [Retrying](-retrying.md)(times: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), elapsed: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [forward](forward.md)| [jvm]  <br>Brief description  <br><br><br>标记为下一步 记录次数及延续时间<br><br>  <br>Content  <br>fun [forward](forward.md)(): [Retrying](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>标记为下一步 并记录期待终止时间<br><br>  <br>Content  <br>fun [forward](forward.md)(retry: [Retry](../-retry/index.md)): [Retrying](index.md)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [reset](reset.md)| [jvm]  <br>Brief description  <br><br><br>重置<br><br>  <br>Content  <br>fun [reset](reset.md)(): [Retrying](index.md)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [delay](index.md#tech.whence.echo.retry/Retrying/delay/#/PointingToDeclaration/)|  [jvm] <br><br>Duration 延后<br><br>val [delay](index.md#tech.whence.echo.retry/Retrying/delay/#/PointingToDeclaration/): [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)   <br>
| [elapsed](index.md#tech.whence.echo.retry/Retrying/elapsed/#/PointingToDeclaration/)|  [jvm] <br><br>Long 持续时间<br><br>var [elapsed](index.md#tech.whence.echo.retry/Retrying/elapsed/#/PointingToDeclaration/): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)   <br>
| [expectAt](index.md#tech.whence.echo.retry/Retrying/expectAt/#/PointingToDeclaration/)|  [jvm] <br><br>Long 期待终止时间<br><br>var [expectAt](index.md#tech.whence.echo.retry/Retrying/expectAt/#/PointingToDeclaration/): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)   <br>
| [startAt](index.md#tech.whence.echo.retry/Retrying/startAt/#/PointingToDeclaration/)|  [jvm] <br><br>Long 开始时间<br><br>var [startAt](index.md#tech.whence.echo.retry/Retrying/startAt/#/PointingToDeclaration/): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)   <br>
| [times](index.md#tech.whence.echo.retry/Retrying/times/#/PointingToDeclaration/)|  [jvm] <br><br>Int 可重试次数<br><br>var [times](index.md#tech.whence.echo.retry/Retrying/times/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>

