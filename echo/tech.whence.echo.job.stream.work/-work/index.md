---
title: Work -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.work](../index.md)/[Work](index.md)



# Work  
 [jvm] 

工作

interface [Work](index.md)<[S](index.md) : [Workstage](../../tech.whence.echo.job.stream.workstage/-workstage/index.md)> : [Manager](../../tech.whence.echo.job.manager/-manager/index.md)   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| S| <br><br>: Workstage 工作阶段类型<br><br>
  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [dispatch](dispatch.md)| [jvm]  <br>Brief description  <br><br><br>调度<br><br>  <br>Content  <br>abstract fun [dispatch](dispatch.md)(): [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [initialize](../../tech.whence.echo.job.manager/-manager/initialize.md)| [jvm]  <br>Brief description  <br><br><br>初始化<br><br>  <br>Content  <br>abstract override fun [initialize](../../tech.whence.echo.job.manager/-manager/initialize.md)()  <br><br><br>
| [inspect](../../tech.whence.echo.job.manager/-manager/inspect.md)| [jvm]  <br>Brief description  <br><br><br>查看状态<br><br>  <br>Content  <br>abstract override fun [inspect](../../tech.whence.echo.job.manager/-manager/inspect.md)(): [State](../../tech.whence.echo.job.manager.state/-state/index.md)  <br><br><br>
| [name](../../tech.whence.echo.definition/-namer/name.md)| [jvm]  <br>Brief description  <br><br><br>名称<br><br>  <br>Content  <br>abstract override fun [name](../../tech.whence.echo.definition/-namer/name.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [resume](../../tech.whence.echo.job.manager/-manager/resume.md)| [jvm]  <br>Brief description  <br><br><br>恢复<br><br>  <br>Content  <br>abstract suspend override fun [resume](../../tech.whence.echo.job.manager/-manager/resume.md)()  <br><br><br>
| [stage](stage.md)| [jvm]  <br>Brief description  <br><br><br>设置阶段<br><br>  <br>Content  <br>abstract fun [stage](stage.md)(workstage: [S](index.md))  <br><br><br>
| [start](../../tech.whence.echo.job.manager/-manager/start.md)| [jvm]  <br>Brief description  <br><br><br>启动<br><br>  <br>Content  <br>abstract suspend override fun [start](../../tech.whence.echo.job.manager/-manager/start.md)()  <br><br><br>
| [stop](../../tech.whence.echo.job.manager/-manager/stop.md)| [jvm]  <br>Brief description  <br><br><br>停止<br><br>  <br>Content  <br>abstract suspend override fun [stop](../../tech.whence.echo.job.manager/-manager/stop.md)()  <br><br><br>
| [suspend](../../tech.whence.echo.job.manager/-manager/suspend.md)| [jvm]  <br>Brief description  <br><br><br>挂起<br><br>  <br>Content  <br>abstract suspend override fun [suspend](../../tech.whence.echo.job.manager/-manager/suspend.md)()  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Inheritors  
  
|  Name| 
|---|
| [AbstractWork](../-abstract-work/index.md)

