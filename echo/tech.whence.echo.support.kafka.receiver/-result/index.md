---
title: Result -
---
//[echo](../../index.md)/[tech.whence.echo.support.kafka.receiver](../index.md)/[Result](index.md)



# Result  
 [jvm] 

结果

data class [Result](index.md)(**topic**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **partition**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **offset**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **date**: [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html), **key**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **value**: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md))   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Result](-result.md)|  [jvm] <br><br><br><br>fun [Result](-result.md)(topic: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), partition: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), offset: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), date: [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html), key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md))   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [component1](component1.md)| [jvm]  <br>Content  <br>operator fun [component1](component1.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [component2](component2.md)| [jvm]  <br>Content  <br>operator fun [component2](component2.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [component3](component3.md)| [jvm]  <br>Content  <br>operator fun [component3](component3.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)  <br><br><br>
| [component4](component4.md)| [jvm]  <br>Content  <br>operator fun [component4](component4.md)(): [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)  <br><br><br>
| [component5](component5.md)| [jvm]  <br>Content  <br>operator fun [component5](component5.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [component6](component6.md)| [jvm]  <br>Content  <br>operator fun [component6](component6.md)(): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)  <br><br><br>
| [copy](copy.md)| [jvm]  <br>Content  <br>fun [copy](copy.md)(topic: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), partition: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), offset: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), date: [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html), key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)): [Result](index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [date](index.md#tech.whence.echo.support.kafka.receiver/Result/date/#/PointingToDeclaration/)|  [jvm] <br><br>Instant 日期<br><br>val [date](index.md#tech.whence.echo.support.kafka.receiver/Result/date/#/PointingToDeclaration/): [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)   <br>
| [key](index.md#tech.whence.echo.support.kafka.receiver/Result/key/#/PointingToDeclaration/)|  [jvm] <br><br>String 键<br><br>val [key](index.md#tech.whence.echo.support.kafka.receiver/Result/key/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [offset](index.md#tech.whence.echo.support.kafka.receiver/Result/offset/#/PointingToDeclaration/)|  [jvm] <br><br>Long 偏移量<br><br>val [offset](index.md#tech.whence.echo.support.kafka.receiver/Result/offset/#/PointingToDeclaration/): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)   <br>
| [partition](index.md#tech.whence.echo.support.kafka.receiver/Result/partition/#/PointingToDeclaration/)|  [jvm] <br><br>Int 分区<br><br>val [partition](index.md#tech.whence.echo.support.kafka.receiver/Result/partition/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>
| [topic](index.md#tech.whence.echo.support.kafka.receiver/Result/topic/#/PointingToDeclaration/)|  [jvm] <br><br>String 主题<br><br>val [topic](index.md#tech.whence.echo.support.kafka.receiver/Result/topic/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [value](index.md#tech.whence.echo.support.kafka.receiver/Result/value/#/PointingToDeclaration/)|  [jvm] <br><br>Accessor 值<br><br>val [value](index.md#tech.whence.echo.support.kafka.receiver/Result/value/#/PointingToDeclaration/): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)   <br>

