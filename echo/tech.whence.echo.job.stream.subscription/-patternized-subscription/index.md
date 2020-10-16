---
title: PatternizedSubscription -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.subscription](../index.md)/[PatternizedSubscription](index.md)



# PatternizedSubscription  
 [jvm] 

正则型订阅

class [PatternizedSubscription](index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **pattern**: [Pattern](https://docs.oracle.com/javase/8/docs/api/java/util/regex/Pattern.html)) : [AbstractSubscription](../-abstract-subscription/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [PatternizedSubscription](-patternized-subscription.md)|  [jvm] <br><br><br><br>fun [PatternizedSubscription](-patternized-subscription.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), pattern: [Pattern](https://docs.oracle.com/javase/8/docs/api/java/util/regex/Pattern.html))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [configure](../-abstract-subscription/configure.md)| [jvm]  <br>Brief description  <br><br><br>配置<br><br>  <br>Content  <br>open override fun [configure](../-abstract-subscription/configure.md)(config: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md))  <br>open override fun [configure](../-abstract-subscription/configure.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [locate](../-abstract-subscription/locate.md)| [jvm]  <br>Brief description  <br><br><br>取消息管道定位<br><br>  <br>Content  <br>open override fun [locate](../-abstract-subscription/locate.md)(): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>  <br><br><br>
| [lookup](lookup.md)| [jvm]  <br>Brief description  <br><br><br>定位管道<br><br>  <br>Content  <br>open override fun [lookup](lookup.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), located: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Pipeline](../-pipeline/index.md)?  <br><br><br>
| [patternize](patternize.md)| [jvm]  <br>Brief description  <br><br><br>取订阅规则<br><br>  <br>Content  <br>open override fun [patternize](patternize.md)(): [Pattern](https://docs.oracle.com/javase/8/docs/api/java/util/regex/Pattern.html)  <br><br><br>
| [pipe](../-abstract-subscription/pipe.md)| [jvm]  <br>Brief description  <br><br><br>取消息管道名<br><br>  <br>Content  <br>open override fun [pipe](../-abstract-subscription/pipe.md)(): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>  <br><br><br>
| [repartition](repartition.md)| [jvm]  <br>Brief description  <br><br><br>重新分区<br><br>  <br>Content  <br>open override fun [repartition](repartition.md)(repartitioner: [Repartitioner](../-repartitioner/index.md))  <br><br><br>
| [represent](represent.md)| [jvm]  <br>Brief description  <br><br><br>设置代表分区<br><br>  <br>Content  <br>open override fun [represent](represent.md)(partitions: [Partitions](../-partitions/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [config](index.md#tech.whence.echo.job.stream.subscription/PatternizedSubscription/config/#/PointingToDeclaration/)|  [jvm] <br><br>Accessor 配置<br><br>open override val [config](index.md#tech.whence.echo.job.stream.subscription/PatternizedSubscription/config/#/PointingToDeclaration/): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)   <br>
| [name](index.md#tech.whence.echo.job.stream.subscription/PatternizedSubscription/name/#/PointingToDeclaration/)|  [jvm] <br><br>String 名称<br><br>open override var [name](index.md#tech.whence.echo.job.stream.subscription/PatternizedSubscription/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [represented](index.md#tech.whence.echo.job.stream.subscription/PatternizedSubscription/represented/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否是一类主题<br><br>open override val [represented](index.md#tech.whence.echo.job.stream.subscription/PatternizedSubscription/represented/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [specific](index.md#tech.whence.echo.job.stream.subscription/PatternizedSubscription/specific/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否是具体主题<br><br>open override val [specific](index.md#tech.whence.echo.job.stream.subscription/PatternizedSubscription/specific/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>

