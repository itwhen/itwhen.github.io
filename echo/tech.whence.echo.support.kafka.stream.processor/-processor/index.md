---
title: Processor -
---
//[echo](../../index.md)/[tech.whence.echo.support.kafka.stream.processor](../index.md)/[Processor](index.md)



# Processor  
 [jvm] 

处理器

interface [Processor](index.md)<[V](index.md)> : Processor<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [V](index.md)>    


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| V| <br><br>值类型<br><br>
  


## Functions  
  
|  Name|  Summary| 
|---|---|
| [close](index.md#org.apache.kafka.streams.processor/Processor/close/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>abstract override fun [close](index.md#org.apache.kafka.streams.processor/Processor/close/#/PointingToDeclaration/)()  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [init](index.md#org.apache.kafka.streams.processor/Processor/init/#org.apache.kafka.streams.processor.ProcessorContext/PointingToDeclaration/)| [jvm]  <br>Content  <br>abstract override fun [init](index.md#org.apache.kafka.streams.processor/Processor/init/#org.apache.kafka.streams.processor.ProcessorContext/PointingToDeclaration/)(p0: ProcessorContext)  <br><br><br>
| [process](index.md#org.apache.kafka.streams.processor/Processor/process/#kotlin.String#TypeParam(bounds=[kotlin.Any?])/PointingToDeclaration/)| [jvm]  <br>Content  <br>abstract override fun [process](index.md#org.apache.kafka.streams.processor/Processor/process/#kotlin.String#TypeParam(bounds=[kotlin.Any?])/PointingToDeclaration/)(p0: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), p1: [V](index.md))  <br><br><br>
| [punctuate](punctuate.md)| [jvm]  <br>Brief description  <br><br><br>标记时间<br><br>  <br>Content  <br>abstract fun [punctuate](punctuate.md)(timestamp: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))  <br><br><br>
| [reprocess](reprocess.md)| [jvm]  <br>Brief description  <br><br><br>重新处理消息<br><br>  <br>Content  <br>abstract fun [reprocess](reprocess.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Inheritors  
  
|  Name| 
|---|
| [AbstractProcessor](../-abstract-processor/index.md)

