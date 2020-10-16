---
title: Pipeline -
---
//[echo](../../index.md)/[tech.whence.echo.job.shell](../index.md)/[Pipeline](index.md)



# Pipeline  
 [jvm] 

作业管道

class [Pipeline](index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Pipeline](-pipeline.md)|  [jvm] <br><br><br><br>fun [Pipeline](-pipeline.md)()   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [close](close.md)| [jvm]  <br>Brief description  <br><br><br>关闭<br><br>  <br>Content  <br>fun [close](close.md)()  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [into](into.md)| [jvm]  <br>Brief description  <br><br><br>将自身注入到会话中<br><br>  <br>Content  <br>fun [into](into.md)(session: Session)  <br><br><br>
| [prepare](prepare.md)| [jvm]  <br>Brief description  <br><br><br>作业准备<br><br>  <br>Content  <br>fun [prepare](prepare.md)(job: [Job](../../tech.whence.echo.job/-job/index.md))  <br><br><br>
| [process](process.md)| [jvm]  <br>Brief description  <br><br><br>执行批量管理命令<br><br>  <br>Content  <br>fun [process](process.md)(control: [Control](../-control/index.md)?): [Responder](../-responder/index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>执行指定作业控制<br><br>  <br>Content  <br>fun [process](process.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), operation: [Operation](../-operation/index.md)?, parameters: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)?): [Responder](../-responder/index.md)  <br><br><br>
| [ready](ready.md)| [jvm]  <br>Brief description  <br><br><br>预备 创建管理器<br><br>  <br>Content  <br>fun [ready](ready.md)()  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

