---
title: AbstractCommand -
---
//[echo](../../index.md)/[tech.whence.echo.job.shell.command](../index.md)/[AbstractCommand](index.md)



# AbstractCommand  
 [jvm] 

命令抽象

abstract class [AbstractCommand](index.md)(**vertx**: Vertx, **name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **description**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [Command](../-command/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [AbstractCommand](-abstract-command.md)|  [jvm] fun [AbstractCommand](-abstract-command.md)(vertx: Vertx, name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [cli](cli.md)| [jvm]  <br>Brief description  <br><br><br>命令行界面<br><br>  <br>Content  <br>open override fun [cli](cli.md)(): CLI  <br><br><br>
| [complete](complete.md)| [jvm]  <br>Brief description  <br><br><br>结束<br><br>  <br>Content  <br>open override fun [complete](complete.md)(completion: Completion)  <br><br><br>
| [createProcess](../-verticle/index.md#io.vertx.ext.shell.command/Command/createProcess/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [createProcess](../-verticle/index.md#io.vertx.ext.shell.command/Command/createProcess/#/PointingToDeclaration/)(): Process  <br><br><br>[jvm]  <br>Brief description  <br><br><br>新建进程<br><br>  <br>Content  <br>open override fun [createProcess](create-process.md)(args: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<CliToken>): Process  <br><br><br>
| [describe](describe.md)| [jvm]  <br>Brief description  <br><br><br>描述<br><br>  <br>Content  <br>open override fun [describe](describe.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [name](name.md)| [jvm]  <br>Brief description  <br><br><br>名称<br><br>  <br>Content  <br>open override fun [name](name.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Inheritors  
  
|  Name| 
|---|
| [AbstractPipingCommand](../-abstract-piping-command/index.md)
| [Helper](../-helper/index.md)
| [Verticle](../-verticle/index.md)

