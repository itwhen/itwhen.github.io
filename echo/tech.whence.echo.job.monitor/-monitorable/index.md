---
title: Monitorable -
---
//[echo](../../index.md)/[tech.whence.echo.job.monitor](../index.md)/[Monitorable](index.md)



# Monitorable  
 [jvm] 

可监控的

interface [Monitorable](index.md) : [Namer](../../tech.whence.echo.definition/-namer/index.md)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [configure](configure.md)| [jvm]  <br>Brief description  <br><br><br>配置<br><br>  <br>Content  <br>abstract fun [configure](configure.md)(config: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md))  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [name](../../tech.whence.echo.definition/-namer/name.md)| [jvm]  <br>Brief description  <br><br><br>名称<br><br>  <br>Content  <br>abstract override fun [name](../../tech.whence.echo.definition/-namer/name.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [monitor](index.md#tech.whence.echo.job.monitor/Monitorable/monitor/#/PointingToDeclaration/)|  [jvm] <br><br>Monitor 监控器<br><br>abstract val [monitor](index.md#tech.whence.echo.job.monitor/Monitorable/monitor/#/PointingToDeclaration/): [Monitor](../-monitor/index.md)   <br>


## Inheritors  
  
|  Name| 
|---|
| [AbstractJob](../../tech.whence.echo.job/-abstract-job/index.md)
| [IdleJob](../../tech.whence.echo.job/-idle-job/index.md)
| [IdleJobDelegator](../../tech.whence.echo.job/-idle-job-delegator/index.md)
| [ScheduledJobDelegator](../../tech.whence.echo.job/-scheduled-job-delegator/index.md)

