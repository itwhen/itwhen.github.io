---
title: tech.whence.echo.job.stream.work -
---
//[echo](../index.md)/[tech.whence.echo.job.stream.work](index.md)



# Package tech.whence.echo.job.stream.work  


## Types  
  
|  Name|  Summary| 
|---|---|
| [AbstractBuilder](-abstract-builder/index.md)| [jvm]  <br>Brief description  <br><br><br>构造器<br><br>  <br>Content  <br>abstract class [AbstractBuilder](-abstract-builder/index.md)<[A](-abstract-builder/index.md) : [AbstractBuilder](-abstract-builder/index.md)<[A](-abstract-builder/index.md), [W](-abstract-builder/index.md), [S](-abstract-builder/index.md), [B](-abstract-builder/index.md)>, [W](-abstract-builder/index.md) : [AbstractWork](-abstract-work/index.md)<[S](-abstract-builder/index.md), [B](-abstract-builder/index.md), *>, [S](-abstract-builder/index.md) : [AbstractWorkstage](../tech.whence.echo.job.stream.workstage/-abstract-workstage/index.md), [B](-abstract-builder/index.md) : [AbstractWorkstageBuilder](../tech.whence.echo.job.stream.workstage/-abstract-workstage-builder/index.md)<[B](-abstract-builder/index.md), *>>(**vertx**: Vertx, **work**: [W](-abstract-builder/index.md))  <br><br><br>
| [AbstractWork](-abstract-work/index.md)| [jvm]  <br>Brief description  <br><br><br>抽象工作<br><br>  <br>Content  <br>abstract class [AbstractWork](-abstract-work/index.md)<[W](-abstract-work/index.md) : [AbstractWorkstage](../tech.whence.echo.job.stream.workstage/-abstract-workstage/index.md), [WB](-abstract-work/index.md) : [AbstractWorkstageBuilder](../tech.whence.echo.job.stream.workstage/-abstract-workstage-builder/index.md)<[WB](-abstract-work/index.md), *>, [C](-abstract-work/index.md)>(**vertx**: Vertx, **workers**: [Workers](-workers/index.md), **multiplex**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) : [AbstractManager](../tech.whence.echo.job.manager/-abstract-manager/index.md), [Work](-work/index.md)<[W](-abstract-work/index.md)>   <br><br><br>
| [Assembler](-assembler/index.md)| [jvm]  <br>Brief description  <br><br><br>装配器<br><br>  <br>Content  <br>fun fun interface [Assembler](-assembler/index.md)  <br><br><br>
| [Conductor](-conductor/index.md)| [jvm]  <br>Brief description  <br><br><br>编排器<br><br>  <br>Content  <br>class [Conductor](-conductor/index.md)(**providable**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **originatedAt**: [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)?, **cycle**: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html))  <br><br><br>
| [Config](-config/index.md)| [jvm]  <br>Brief description  <br><br><br>配置<br><br>  <br>Content  <br>class [Config](-config/index.md)  <br><br><br>
| [Measurer](-measurer/index.md)| [jvm]  <br>Brief description  <br><br><br>测量器<br><br>  <br>Content  <br>class [Measurer](-measurer/index.md)  <br><br><br>
| [Namer](-namer/index.md)| [jvm]  <br>Brief description  <br><br><br>工人命名者<br><br>  <br>Content  <br>fun fun interface [Namer](-namer/index.md)  <br><br><br>
| [Scheduler](-scheduler/index.md)| [jvm]  <br>Brief description  <br><br><br>调度器<br><br>  <br>Content  <br>fun fun interface [Scheduler](-scheduler/index.md)  <br><br><br>
| [SequentialWork](-sequential-work/index.md)| [jvm]  <br>Brief description  <br><br><br>顺序工作<br><br>  <br>Content  <br>class [SequentialWork](-sequential-work/index.md)(**vertx**: Vertx, **name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **workers**: [Workers](-workers/index.md)?) : [AbstractWork](-abstract-work/index.md)<[SequentialWork.Workstage](-sequential-work/-workstage/index.md), [SequentialWork.WorkstageBuilder](-sequential-work/-workstage-builder/index.md), [CompletableFuture](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/CompletableFuture.html)<[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Task](../tech.whence.echo.job.stream.task/-task/index.md)>>>   <br><br><br>
| [Work](-work/index.md)| [jvm]  <br>Brief description  <br><br><br>工作<br><br>  <br>Content  <br>interface [Work](-work/index.md)<[S](-work/index.md) : [Workstage](../tech.whence.echo.job.stream.workstage/-workstage/index.md)> : [Manager](../tech.whence.echo.job.manager/-manager/index.md)  <br><br><br>
| [WorkBlockingException](-work-blocking-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>工作阻塞<br><br>  <br>Content  <br>class [WorkBlockingException](-work-blocking-exception/index.md) : [RuntimeException](https://docs.oracle.com/javase/8/docs/api/java/lang/RuntimeException.html)  <br><br><br>
| [Worker](-worker/index.md)| [jvm]  <br>Brief description  <br><br><br>工人<br><br>  <br>Content  <br>fun fun interface [Worker](-worker/index.md)  <br><br><br>
| [Workers](-workers/index.md)| [jvm]  <br>Brief description  <br><br><br>工人集合<br><br>  <br>Content  <br>class [Workers](-workers/index.md)  <br><br><br>
| [WorkExecutionException](-work-execution-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>工作执行异常<br><br>  <br>Content  <br>class [WorkExecutionException](-work-execution-exception/index.md)(**stage**: [Workstage](../tech.whence.echo.job.stream.workstage/-workstage/index.md), **worker**: [Thread](https://docs.oracle.com/javase/8/docs/api/java/lang/Thread.html)?, **throwable**: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)?) : [RuntimeException](https://docs.oracle.com/javase/8/docs/api/java/lang/RuntimeException.html)  <br><br><br>
| [WorkTimeoutException](-work-timeout-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>工作超时<br><br>  <br>Content  <br>class [WorkTimeoutException](-work-timeout-exception/index.md)(**life**: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)) : [RuntimeException](https://docs.oracle.com/javase/8/docs/api/java/lang/RuntimeException.html)  <br><br><br>

