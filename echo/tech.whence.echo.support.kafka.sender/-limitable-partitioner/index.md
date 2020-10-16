---
title: LimitablePartitioner -
---
//[echo](../../index.md)/[tech.whence.echo.support.kafka.sender](../index.md)/[LimitablePartitioner](index.md)



# LimitablePartitioner  
 [jvm] 

可限制分区器

class [LimitablePartitioner](index.md) : Partitioner   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [LimitablePartitioner](-limitable-partitioner.md)|  [jvm] fun [LimitablePartitioner](-limitable-partitioner.md)()   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Limiter](-limiter/index.md)| [jvm]  <br>Brief description  <br><br><br>限制器<br><br>  <br>Content  <br>fun fun interface [Limiter](-limiter/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [close](close.md)| [jvm]  <br>Brief description  <br><br><br>关闭<br><br>  <br>Content  <br>open override fun [close](close.md)()  <br><br><br>
| [configure](configure.md)| [jvm]  <br>Brief description  <br><br><br>配置<br><br>  <br>Content  <br>open override fun [configure](configure.md)(configs: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), *>)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [onNewBatch](index.md#org.apache.kafka.clients.producer/Partitioner/onNewBatch/#kotlin.String#org.apache.kafka.common.Cluster#kotlin.Int/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [onNewBatch](index.md#org.apache.kafka.clients.producer/Partitioner/onNewBatch/#kotlin.String#org.apache.kafka.common.Cluster#kotlin.Int/PointingToDeclaration/)(p0: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), p1: Cluster, p2: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))  <br><br><br>
| [partition](partition.md)| [jvm]  <br>Brief description  <br><br><br>指定分区<br><br>  <br>Content  <br>open override fun [partition](partition.md)(pipeline: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), key: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, keyBytes: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)?, value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, valueBytes: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)?, cluster: Cluster): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

