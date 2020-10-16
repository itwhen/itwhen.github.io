---
title: tech.whence.echo.job.shell.command -
---
//[echo](../index.md)/[tech.whence.echo.job.shell.command](index.md)



# Package tech.whence.echo.job.shell.command  


## Types  
  
|  Name|  Summary| 
|---|---|
| [AbstractCommand](-abstract-command/index.md)| [jvm]  <br>Brief description  <br><br><br>命令抽象<br><br>  <br>Content  <br>abstract class [AbstractCommand](-abstract-command/index.md)(**vertx**: Vertx, **name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **description**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [Command](-command/index.md)  <br><br><br>
| [AbstractPipingCommand](-abstract-piping-command/index.md)| [jvm]  <br>Brief description  <br><br><br>管道命令抽象<br><br>  <br>Content  <br>abstract class [AbstractPipingCommand](-abstract-piping-command/index.md)(**vertx**: Vertx, **name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **description**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [AbstractCommand](-abstract-command/index.md)  <br><br><br>
| [Command](-command/index.md)| [jvm]  <br>Brief description  <br><br><br>命令<br><br>  <br>Content  <br>interface [Command](-command/index.md) : Command  <br><br><br>
| [Controller](-controller/index.md)| [jvm]  <br>Brief description  <br><br><br>作业控制<br><br>  <br>Content  <br>class [Controller](-controller/index.md)(**vertx**: Vertx) : [AbstractPipingCommand](-abstract-piping-command/index.md)  <br><br><br>
| [Helper](-helper/index.md)| [jvm]  <br>Brief description  <br><br><br>助手<br><br>  <br>Content  <br>class [Helper](-helper/index.md)(**vertx**: Vertx) : [AbstractCommand](-abstract-command/index.md)  <br><br><br>
| [Operator](-operator/index.md)| [jvm]  <br>Brief description  <br><br><br>作业控制器<br><br>  <br>Content  <br>class [Operator](-operator/index.md)(**vertx**: Vertx) : [AbstractPipingCommand](-abstract-piping-command/index.md)  <br><br><br>
| [Verticle](-verticle/index.md)| [jvm]  <br>Brief description  <br><br><br>Verticle管理<br><br>  <br>Content  <br>class [Verticle](-verticle/index.md)(**vertx**: Vertx) : [AbstractCommand](-abstract-command/index.md)  <br><br><br>

