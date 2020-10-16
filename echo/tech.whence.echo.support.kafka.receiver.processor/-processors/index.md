---
title: Processors -
---
//[echo](../../index.md)/[tech.whence.echo.support.kafka.receiver.processor](../index.md)/[Processors](index.md)



# Processors  
 [jvm] 

处理器集合

class [Processors](index.md)(**factory**: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [Processor](../-processor/index.md)>) : [Processor](../-processor/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Processors](-processors.md)|  [jvm] <br><br><br><br>fun [Processors](-processors.md)(factory: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [Processor](../-processor/index.md)>)   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [initialize](../-processor/initialize.md)| [jvm]  <br>Brief description  <br><br><br>初始化<br><br>  <br>Content  <br>open override fun [initialize](../-processor/initialize.md)()  <br><br><br>
| [inspect](../-processor/inspect.md)| [jvm]  <br>Brief description  <br><br><br>查看状态<br><br>  <br>Content  <br>open override fun [inspect](../-processor/inspect.md)(): [State](../../tech.whence.echo.job.manager.state/-state/index.md)  <br><br><br>
| [name](name.md)| [jvm]  <br>Brief description  <br><br><br>名称<br><br>  <br>Content  <br>open override fun [name](name.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [produce](produce.md)| [jvm]  <br>Brief description  <br><br><br>生成处理器 填充到指定数量<br><br>  <br>Content  <br>fun [produce](produce.md)(count: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))  <br><br><br>
| [resume](../-processor/resume.md)| [jvm]  <br>Brief description  <br><br><br>恢复<br><br>  <br>Content  <br>open suspend override fun [resume](../-processor/resume.md)()  <br><br><br>
| [start](start.md)| [jvm]  <br>Brief description  <br><br><br>启动<br><br>  <br>Content  <br>open suspend override fun [start](start.md)()  <br><br><br>
| [stop](stop.md)| [jvm]  <br>Brief description  <br><br><br>停止<br><br>  <br>Content  <br>open suspend override fun [stop](stop.md)()  <br><br><br>
| [suspend](../-processor/suspend.md)| [jvm]  <br>Brief description  <br><br><br>挂起<br><br>  <br>Content  <br>open suspend override fun [suspend](../-processor/suspend.md)()  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

