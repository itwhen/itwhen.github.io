---
title: AbstractJob -
---
//[echo](../../index.md)/[tech.whence.echo.job](../index.md)/[AbstractJob](index.md)



# AbstractJob  
 [jvm] 

作业抽象

abstract class [AbstractJob](index.md)<[V](index.md)> : [Job](../-job/index.md), [Monitorable](../../tech.whence.echo.job.monitor/-monitorable/index.md)   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| V| <br><br>配置类<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [AbstractJob](-abstract-job.md)|  [jvm] <br><br>配置类<br><br>fun [AbstractJob](-abstract-job.md)()   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [configure](../../tech.whence.echo.job.monitor/-monitorable/configure.md)| [jvm]  <br>Brief description  <br><br><br>配置<br><br>  <br>Content  <br>abstract override fun [configure](../../tech.whence.echo.job.monitor/-monitorable/configure.md)(config: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md))  <br><br><br>
| [delegate](../-job/delegate.md)| [jvm]  <br>Brief description  <br><br><br>托管<br><br>  <br>Content  <br>abstract override fun [delegate](../-job/delegate.md)(): Service  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [name](../../tech.whence.echo.definition/-namer/name.md)| [jvm]  <br>Content  <br>abstract override fun [name](../../tech.whence.echo.definition/-namer/name.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [shutdown](../-job/shutdown.md)| [jvm]  <br>Brief description  <br><br><br>关闭<br><br>  <br>Content  <br>abstract override fun [shutdown](../-job/shutdown.md)()  <br><br><br>
| [startup](../-job/startup.md)| [jvm]  <br>Brief description  <br><br><br>开启<br><br>  <br>Content  <br>abstract override fun [startup](../-job/startup.md)()  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [monitor](index.md#tech.whence.echo.job/AbstractJob/monitor/#/PointingToDeclaration/)|  [jvm] <br><br>Monitor 监视器<br><br>open override val [monitor](index.md#tech.whence.echo.job/AbstractJob/monitor/#/PointingToDeclaration/): [Monitor](../../tech.whence.echo.job.monitor/-monitor/index.md)   <br>


## Inheritors  
  
|  Name| 
|---|
| [AbstractScheduledJob](../-abstract-scheduled-job/index.md)

