---
title: Verticle -
---
//[echo](../../index.md)/[tech.whence.echo.job.shell.command](../index.md)/[Verticle](index.md)



# Verticle  
 [jvm] 

Verticle管理

class [Verticle](index.md)(**vertx**: Vertx) : [AbstractCommand](../-abstract-command/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Verticle](-verticle.md)|  [jvm] <br><br><br><br>fun [Verticle](-verticle.md)(vertx: Vertx)   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [cli](../-abstract-command/cli.md)| [jvm]  <br>Brief description  <br><br><br>命令行界面<br><br>  <br>Content  <br>open override fun [cli](../-abstract-command/cli.md)(): CLI  <br><br><br>
| [complete](../-abstract-command/complete.md)| [jvm]  <br>Brief description  <br><br><br>结束<br><br>  <br>Content  <br>open override fun [complete](../-abstract-command/complete.md)(completion: Completion)  <br><br><br>
| [createProcess](index.md#io.vertx.ext.shell.command/Command/createProcess/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [createProcess](index.md#io.vertx.ext.shell.command/Command/createProcess/#/PointingToDeclaration/)(): Process  <br><br><br>[jvm]  <br>Brief description  <br><br><br>新建进程<br><br>  <br>Content  <br>open override fun [createProcess](../-abstract-command/create-process.md)(args: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<CliToken>): Process  <br><br><br>
| [describe](../-abstract-command/describe.md)| [jvm]  <br>Brief description  <br><br><br>描述<br><br>  <br>Content  <br>open override fun [describe](../-abstract-command/describe.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [name](../-abstract-command/name.md)| [jvm]  <br>Brief description  <br><br><br>名称<br><br>  <br>Content  <br>open override fun [name](../-abstract-command/name.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

