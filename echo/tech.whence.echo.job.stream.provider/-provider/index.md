---
title: Provider -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.provider](../index.md)/[Provider](index.md)



# Provider  
 [jvm] 

数据提供者

interface [Provider](index.md) : [Manager](../../tech.whence.echo.job.manager/-manager/index.md), [Container](../../tech.whence.echo.container/-container/index.md)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [close](close.md)| [jvm]  <br>Brief description  <br><br><br>关闭<br><br>  <br>Content  <br>abstract fun [close](close.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Task](../../tech.whence.echo.job.stream.task/-task/index.md)>?  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [initialize](../../tech.whence.echo.job.manager/-manager/initialize.md)| [jvm]  <br>Brief description  <br><br><br>初始化<br><br>  <br>Content  <br>abstract override fun [initialize](../../tech.whence.echo.job.manager/-manager/initialize.md)()  <br><br><br>
| [inspect](../../tech.whence.echo.job.manager/-manager/inspect.md)| [jvm]  <br>Brief description  <br><br><br>查看状态<br><br>  <br>Content  <br>abstract override fun [inspect](../../tech.whence.echo.job.manager/-manager/inspect.md)(): [State](../../tech.whence.echo.job.manager.state/-state/index.md)  <br><br><br>
| [name](../../tech.whence.echo.definition/-namer/name.md)| [jvm]  <br>Brief description  <br><br><br>名称<br><br>  <br>Content  <br>abstract override fun [name](../../tech.whence.echo.definition/-namer/name.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [ready](ready.md)| [jvm]  <br>Brief description  <br><br><br>准备<br><br>  <br>Content  <br>abstract fun [ready](ready.md)()  <br><br><br>
| [respond](respond.md)| [jvm]  <br>Brief description  <br><br><br>响应<br><br>  <br>Content  <br>abstract fun [respond](respond.md)()  <br><br><br>
| [resume](../../tech.whence.echo.job.manager/-manager/resume.md)| [jvm]  <br>Brief description  <br><br><br>恢复<br><br>  <br>Content  <br>abstract suspend override fun [resume](../../tech.whence.echo.job.manager/-manager/resume.md)()  <br><br><br>
| [start](../../tech.whence.echo.job.manager/-manager/start.md)| [jvm]  <br>Brief description  <br><br><br>启动<br><br>  <br>Content  <br>abstract suspend override fun [start](../../tech.whence.echo.job.manager/-manager/start.md)()  <br><br><br>
| [stop](../../tech.whence.echo.job.manager/-manager/stop.md)| [jvm]  <br>Brief description  <br><br><br>停止<br><br>  <br>Content  <br>abstract suspend override fun [stop](../../tech.whence.echo.job.manager/-manager/stop.md)()  <br><br><br>
| [suspend](../../tech.whence.echo.job.manager/-manager/suspend.md)| [jvm]  <br>Brief description  <br><br><br>挂起<br><br>  <br>Content  <br>abstract suspend override fun [suspend](../../tech.whence.echo.job.manager/-manager/suspend.md)()  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [empty](index.md#tech.whence.echo.job.stream.provider/Provider/empty/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 当前容器是否为空<br><br>abstract override val [empty](index.md#tech.whence.echo.job.stream.provider/Provider/empty/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [size](index.md#tech.whence.echo.job.stream.provider/Provider/size/#/PointingToDeclaration/)|  [jvm] <br><br>UInt 当前容器总数据量<br><br>abstract override val [size](index.md#tech.whence.echo.job.stream.provider/Provider/size/#/PointingToDeclaration/): [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)   <br>


## Inheritors  
  
|  Name| 
|---|
| [AbstractProvider](../-abstract-provider/index.md)
| [MessagingProvider](../-messaging-provider/index.md)
| [RetryingProvider](../-retrying-provider/index.md)
| [SupplyingProvider](../-supplying-provider/index.md)

