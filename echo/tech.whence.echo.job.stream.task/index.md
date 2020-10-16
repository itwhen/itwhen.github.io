---
title: tech.whence.echo.job.stream.task -
---
//[echo](../index.md)/[tech.whence.echo.job.stream.task](index.md)



# Package tech.whence.echo.job.stream.task  


## Types  
  
|  Name|  Summary| 
|---|---|
| [AbstractTask](-abstract-task/index.md)| [jvm]  <br>Brief description  <br><br><br>抽象任务<br><br>  <br>Content  <br>abstract class [AbstractTask](-abstract-task/index.md)<[T](-abstract-task/index.md) : [Message](../tech.whence.echo.job.stream.message/-message/index.md)>(**id**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **key**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **value**: [Accessor](../tech.whence.echo.container.accessor/-accessor/index.md), **source**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **createdAt**: [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)) : [AbstractMessage](../tech.whence.echo.job.stream.message/-abstract-message/index.md), [Task](-task/index.md)  <br><br><br>
| [Builder](-builder/index.md)| [jvm]  <br>Brief description  <br><br><br>构造器<br><br>  <br>Content  <br>fun fun interface [Builder](-builder/index.md)<[V](-builder/index.md)>  <br><br><br>
| [Converter](-converter/index.md)| [jvm]  <br>Brief description  <br><br><br>批量处理器<br><br>  <br>Content  <br>fun fun interface [Converter](-converter/index.md)<[V](-converter/index.md), [R](-converter/index.md)>  <br><br><br>
| [Responder](-responder/index.md)| [jvm]  <br>Brief description  <br><br><br>响应器<br><br>  <br>Content  <br>class [Responder](-responder/index.md)(**tasks**: [Tasks](-tasks/index.md))  <br><br><br>
| [ResponsiveTask](-responsive-task/index.md)| [jvm]  <br>Brief description  <br><br><br>响应式任务<br><br>  <br>Content  <br>class [ResponsiveTask](-responsive-task/index.md)<[T](-responsive-task/index.md) : [Task](-task/index.md)>(**proxy**: [T](-responsive-task/index.md), **marker**: ([T](-responsive-task/index.md), [Measurer.Action](../tech.whence.echo.job.stream.work/-measurer/-action/index.md)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) : [AbstractTask](-abstract-task/index.md)<[T](-responsive-task/index.md)>   <br><br><br>
| [Task](-task/index.md)| [jvm]  <br>Brief description  <br><br><br>任务<br><br>  <br>Content  <br>interface [Task](-task/index.md) : [Message](../tech.whence.echo.job.stream.message/-message/index.md)  <br><br><br>
| [Tasks](-tasks/index.md)| [jvm]  <br>Brief description  <br><br><br>任务集合<br><br>  <br>Content  <br>class [Tasks](-tasks/index.md)(**data**: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[Task](-task/index.md)>, **measurer**: [Measurer](../tech.whence.echo.job.stream.work/-measurer/index.md), **markable**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) : [Iterable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)<[Task](-task/index.md)> , [Container](../tech.whence.echo.container/-container/index.md)  <br><br><br>

