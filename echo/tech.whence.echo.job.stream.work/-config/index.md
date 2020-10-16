---
title: Config -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.work](../index.md)/[Config](index.md)



# Config  
 [jvm] 

配置

class [Config](index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Config](-config.md)|  [jvm] fun [Config](-config.md)()   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [collectable](index.md#tech.whence.echo.job.stream.work/Config/collectable/#/PointingToDeclaration/)|  [jvm] <br><br>Int 需收集量<br><br>var [collectable](index.md#tech.whence.echo.job.stream.work/Config/collectable/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>
| [cycle](index.md#tech.whence.echo.job.stream.work/Config/cycle/#/PointingToDeclaration/)|  [jvm] <br><br>Duration 工作周期<br><br>var [cycle](index.md#tech.whence.echo.job.stream.work/Config/cycle/#/PointingToDeclaration/): [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)   <br>
| [degradationIdler](index.md#tech.whence.echo.job.stream.work/Config/degradationIdler/#/PointingToDeclaration/)|  [jvm] <br><br>Retry 生产降级时等待<br><br>var [degradationIdler](index.md#tech.whence.echo.job.stream.work/Config/degradationIdler/#/PointingToDeclaration/): [Retry](../../tech.whence.echo.retry/-retry/index.md)   <br>
| [duration](index.md#tech.whence.echo.job.stream.work/Config/duration/#/PointingToDeclaration/)|  [jvm] <br><br>Duration 工作时长<br><br>var [duration](index.md#tech.whence.echo.job.stream.work/Config/duration/#/PointingToDeclaration/): [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)   <br>
| [name](index.md#tech.whence.echo.job.stream.work/Config/name/#/PointingToDeclaration/)|  [jvm] <br><br>String 名称<br><br>lateinit var [name](index.md#tech.whence.echo.job.stream.work/Config/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [providable](index.md#tech.whence.echo.job.stream.work/Config/providable/#/PointingToDeclaration/)|  [jvm] <br><br><br><br>最大提供数量 提供者存放消息的最大量<br><br><ol><li>数量 Integer.MIN, 1 时调度器采用SynchronousQueue实现</li><li>数量 (1, Integer.MAX] 时调度器采用LinkedBlockingQueue实现</li></ol><br><br>var [providable](index.md#tech.whence.echo.job.stream.work/Config/providable/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>
| [providerCycle](index.md#tech.whence.echo.job.stream.work/Config/providerCycle/#/PointingToDeclaration/)|  [jvm] <br><br>Duration 生产周期<br><br>var [providerCycle](index.md#tech.whence.echo.job.stream.work/Config/providerCycle/#/PointingToDeclaration/): [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)   <br>
| [providerIdler](index.md#tech.whence.echo.job.stream.work/Config/providerIdler/#/PointingToDeclaration/)|  [jvm] <br><br>Retry 生产时空闲等待<br><br>var [providerIdler](index.md#tech.whence.echo.job.stream.work/Config/providerIdler/#/PointingToDeclaration/): [Retry](../../tech.whence.echo.retry/-retry/index.md)   <br>
| [providerOriginatedAt](index.md#tech.whence.echo.job.stream.work/Config/providerOriginatedAt/#/PointingToDeclaration/)|  [jvm] <br><br>LocalDateTime? 数据起始时间<br><br>var [providerOriginatedAt](index.md#tech.whence.echo.job.stream.work/Config/providerOriginatedAt/#/PointingToDeclaration/): [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)?   <br>
| [providerScheduling](index.md#tech.whence.echo.job.stream.work/Config/providerScheduling/#/PointingToDeclaration/)|  [jvm] <br><br>Duration 生产调度周期<br><br>var [providerScheduling](index.md#tech.whence.echo.job.stream.work/Config/providerScheduling/#/PointingToDeclaration/): [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)   <br>
| [reporterScheduling](index.md#tech.whence.echo.job.stream.work/Config/reporterScheduling/#/PointingToDeclaration/)|  [jvm] <br><br>Duration 度量调度周期<br><br>var [reporterScheduling](index.md#tech.whence.echo.job.stream.work/Config/reporterScheduling/#/PointingToDeclaration/): [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)   <br>

