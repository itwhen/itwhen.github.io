---
title: Manager -
---
//[echo](../../index.md)/[tech.whence.echo.job.manager](../index.md)/[Manager](index.md)



# Manager  
 [jvm] 

管理器

interface [Manager](index.md) : [Namer](../../tech.whence.echo.definition/-namer/index.md)   


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [initialize](initialize.md)| [jvm]  <br>Brief description  <br><br><br>初始化<br><br>  <br>Content  <br>abstract fun [initialize](initialize.md)()  <br><br><br>
| [inspect](inspect.md)| [jvm]  <br>Brief description  <br><br><br>查看状态<br><br>  <br>Content  <br>abstract fun [inspect](inspect.md)(): [State](../../tech.whence.echo.job.manager.state/-state/index.md)  <br><br><br>
| [name](../../tech.whence.echo.definition/-namer/name.md)| [jvm]  <br>Brief description  <br><br><br>名称<br><br>  <br>Content  <br>abstract override fun [name](../../tech.whence.echo.definition/-namer/name.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [resume](resume.md)| [jvm]  <br>Brief description  <br><br><br>恢复<br><br>  <br>Content  <br>abstract suspend fun [resume](resume.md)()  <br><br><br>
| [start](start.md)| [jvm]  <br>Brief description  <br><br><br>启动<br><br>  <br>Content  <br>abstract suspend fun [start](start.md)()  <br><br><br>
| [stop](stop.md)| [jvm]  <br>Brief description  <br><br><br>停止<br><br>  <br>Content  <br>abstract suspend fun [stop](stop.md)()  <br><br><br>
| [suspend](suspend.md)| [jvm]  <br>Brief description  <br><br><br>挂起<br><br>  <br>Content  <br>abstract suspend fun [suspend](suspend.md)()  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Inheritors  
  
|  Name| 
|---|
| [AbstractManager](../-abstract-manager/index.md)
| [Provider](../../tech.whence.echo.job.stream.provider/-provider/index.md)
| [Work](../../tech.whence.echo.job.stream.work/-work/index.md)
| [Processor](../../tech.whence.echo.support.kafka.receiver.processor/-processor/index.md)

