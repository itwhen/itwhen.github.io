---
title: Subscription -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.subscription](../index.md)/[Subscription](index.md)



# Subscription  
 [jvm] 

消息订阅

interface [Subscription](index.md)   


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [configure](configure.md)| [jvm]  <br>Brief description  <br><br><br>配置<br><br>  <br>Content  <br>abstract fun [configure](configure.md)(config: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md))  <br>abstract fun [configure](configure.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [locate](locate.md)| [jvm]  <br>Brief description  <br><br><br>取消息管道定位<br><br>  <br>Content  <br>abstract fun [locate](locate.md)(): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>  <br><br><br>
| [lookup](lookup.md)| [jvm]  <br>Brief description  <br><br><br>定位管道<br><br>  <br>Content  <br>abstract fun [lookup](lookup.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), located: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Pipeline](../-pipeline/index.md)?  <br><br><br>
| [patternize](patternize.md)| [jvm]  <br>Brief description  <br><br><br>取订阅规则<br><br>  <br>Content  <br>abstract fun [patternize](patternize.md)(): [Pattern](https://docs.oracle.com/javase/8/docs/api/java/util/regex/Pattern.html)  <br><br><br>
| [pipe](pipe.md)| [jvm]  <br>Brief description  <br><br><br>取消息管道名<br><br>  <br>Content  <br>abstract fun [pipe](pipe.md)(): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>  <br><br><br>
| [repartition](repartition.md)| [jvm]  <br>Brief description  <br><br><br>重新分区<br><br>  <br>Content  <br>abstract fun [repartition](repartition.md)(repartitioner: [Repartitioner](../-repartitioner/index.md))  <br><br><br>
| [represent](represent.md)| [jvm]  <br>Brief description  <br><br><br>设置代表分区<br><br>  <br>Content  <br>abstract fun [represent](represent.md)(partitions: [Partitions](../-partitions/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [config](index.md#tech.whence.echo.job.stream.subscription/Subscription/config/#/PointingToDeclaration/)|  [jvm] <br><br>Accessor 相关配置<br><br>abstract val [config](index.md#tech.whence.echo.job.stream.subscription/Subscription/config/#/PointingToDeclaration/): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)   <br>
| [name](index.md#tech.whence.echo.job.stream.subscription/Subscription/name/#/PointingToDeclaration/)|  [jvm] <br><br>String 名称<br><br>abstract val [name](index.md#tech.whence.echo.job.stream.subscription/Subscription/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [represented](index.md#tech.whence.echo.job.stream.subscription/Subscription/represented/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否是一类主题<br><br>abstract val [represented](index.md#tech.whence.echo.job.stream.subscription/Subscription/represented/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [specific](index.md#tech.whence.echo.job.stream.subscription/Subscription/specific/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否是具体主题<br><br>abstract val [specific](index.md#tech.whence.echo.job.stream.subscription/Subscription/specific/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>


## Inheritors  
  
|  Name| 
|---|
| [AbstractSubscription](../-abstract-subscription/index.md)

