---
title: Context -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.provider](../index.md)/[Context](index.md)



# Context  
 [jvm] 

运行上下文

class [Context](index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Context](-context.md)|  [jvm] fun [Context](-context.md)()   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [conductBy](conduct-by.md)| [jvm]  <br>Brief description  <br><br><br>设置编排器<br><br>  <br>Content  <br>fun [conductBy](conduct-by.md)(conductor: [Conductor](../../tech.whence.echo.job.stream.work/-conductor/index.md)): [Context](index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [leadBy](lead-by.md)| [jvm]  <br>Brief description  <br><br><br>设置领导者<br><br>  <br>Content  <br>fun [leadBy](lead-by.md)(leader: [Leader](../../tech.whence.echo.job.manager.management/-leader/index.md), override: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Context](index.md)  <br><br><br>
| [logBy](log-by.md)| [jvm]  <br>Brief description  <br><br><br>设置日志管理器<br><br>  <br>Content  <br>fun [logBy](log-by.md)(logger: KLogger): [Context](index.md)  <br><br><br>
| [monitorBy](monitor-by.md)| [jvm]  <br>Brief description  <br><br><br>设置监控器<br><br>  <br>Content  <br>fun [monitorBy](monitor-by.md)(monitor: [Monitor](../../tech.whence.echo.job.stream.monitor/-monitor/index.md)): [Context](index.md)  <br><br><br>
| [name](name.md)| [jvm]  <br>Brief description  <br><br><br>设置名称<br><br>  <br>Content  <br>fun [name](name.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Context](index.md)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [conductor](index.md#tech.whence.echo.job.stream.provider/Context/conductor/#/PointingToDeclaration/)|  [jvm] <br><br>Conductor 编排器<br><br>lateinit var [conductor](index.md#tech.whence.echo.job.stream.provider/Context/conductor/#/PointingToDeclaration/): [Conductor](../../tech.whence.echo.job.stream.work/-conductor/index.md)   <br>
| [leader](index.md#tech.whence.echo.job.stream.provider/Context/leader/#/PointingToDeclaration/)|  [jvm] <br><br>Leader? 领导者<br><br>var [leader](index.md#tech.whence.echo.job.stream.provider/Context/leader/#/PointingToDeclaration/): [Leader](../../tech.whence.echo.job.manager.management/-leader/index.md)?   <br>
| [logger](index.md#tech.whence.echo.job.stream.provider/Context/logger/#/PointingToDeclaration/)|  [jvm] <br><br>KLogger? 日志<br><br>var [logger](index.md#tech.whence.echo.job.stream.provider/Context/logger/#/PointingToDeclaration/): KLogger?   <br>
| [monitor](index.md#tech.whence.echo.job.stream.provider/Context/monitor/#/PointingToDeclaration/)|  [jvm] <br><br>Monitor 监听器<br><br>lateinit var [monitor](index.md#tech.whence.echo.job.stream.provider/Context/monitor/#/PointingToDeclaration/): [Monitor](../../tech.whence.echo.job.stream.monitor/-monitor/index.md)   <br>
| [name](index.md#tech.whence.echo.job.stream.provider/Context/name/#/PointingToDeclaration/)|  [jvm] <br><br>String 名称<br><br>lateinit var [name](index.md#tech.whence.echo.job.stream.provider/Context/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>

