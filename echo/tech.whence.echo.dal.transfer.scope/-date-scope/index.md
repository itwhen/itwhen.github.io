---
title: DateScope -
---
//[echo](../../index.md)/[tech.whence.echo.dal.transfer.scope](../index.md)/[DateScope](index.md)



# DateScope  
 [jvm] 

日期时间范围

class [DateScope](index.md)(**min**: [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)?, **max**: [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)?, **key**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **range**: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html), **limit**: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)) : [Scope](../-scope/index.md)<[LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)>    


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [DateScope](-date-scope.md)|  [jvm] <br><br><br><br>fun [DateScope](-date-scope.md)(min: [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)?, max: [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)?, key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), range: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html), limit: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [split](split.md)| [jvm]  <br>Brief description  <br><br><br>切分<br><br>  <br>Content  <br>open override fun [split](split.md)(root: [Root](../../tech.whence.echo.dal.transfer.node/-root/index.md)<*, *>, direction: [Direction](../../tech.whence.echo.dal.transfer.node/-direction/index.md), size: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Querier](../-querier/index.md)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [max](index.md#tech.whence.echo.dal.transfer.scope/DateScope/max/#/PointingToDeclaration/)|  [jvm] <br><br>LocalDateTime 最大时间<br><br>open override var [max](index.md#tech.whence.echo.dal.transfer.scope/DateScope/max/#/PointingToDeclaration/): [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)?   <br>
| [min](index.md#tech.whence.echo.dal.transfer.scope/DateScope/min/#/PointingToDeclaration/)|  [jvm] <br><br>LocalDateTime 最小时间<br><br>open override var [min](index.md#tech.whence.echo.dal.transfer.scope/DateScope/min/#/PointingToDeclaration/): [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)?   <br>

