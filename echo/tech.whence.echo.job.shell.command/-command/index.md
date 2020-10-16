---
title: Command -
---
//[echo](../../index.md)/[tech.whence.echo.job.shell.command](../index.md)/[Command](index.md)



# Command  
 [jvm] 

命令

interface [Command](index.md) : Command   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [cli](index.md#io.vertx.ext.shell.command/Command/cli/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [cli](index.md#io.vertx.ext.shell.command/Command/cli/#/PointingToDeclaration/)(): CLI  <br><br><br>
| [complete](index.md#io.vertx.ext.shell.command/Command/complete/#io.vertx.ext.shell.cli.Completion/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [complete](index.md#io.vertx.ext.shell.command/Command/complete/#io.vertx.ext.shell.cli.Completion/PointingToDeclaration/)(p0: Completion)  <br><br><br>
| [createProcess](../-verticle/index.md#io.vertx.ext.shell.command/Command/createProcess/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [createProcess](../-verticle/index.md#io.vertx.ext.shell.command/Command/createProcess/#/PointingToDeclaration/)(): Process  <br>abstract override fun [createProcess](index.md#io.vertx.ext.shell.command/Command/createProcess/#kotlin.collections.MutableList[io.vertx.ext.shell.cli.CliToken]/PointingToDeclaration/)(p0: [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<CliToken>): Process  <br><br><br>
| [describe](describe.md)| [jvm]  <br>Brief description  <br><br><br>描述<br><br>  <br>Content  <br>abstract fun [describe](describe.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [name](index.md#io.vertx.ext.shell.command/Command/name/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [name](index.md#io.vertx.ext.shell.command/Command/name/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Inheritors  
  
|  Name| 
|---|
| [AbstractCommand](../-abstract-command/index.md)

