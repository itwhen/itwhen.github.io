---
title: AbstractBuilder -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.work](../index.md)/[AbstractBuilder](index.md)



# AbstractBuilder  
 [jvm] 

构造器

abstract class [AbstractBuilder](index.md)<[A](index.md) : [AbstractBuilder](index.md)<[A](index.md), [W](index.md), [S](index.md), [B](index.md)>, [W](index.md) : [AbstractWork](../-abstract-work/index.md)<[S](index.md), [B](index.md), *>, [S](index.md) : [AbstractWorkstage](../../tech.whence.echo.job.stream.workstage/-abstract-workstage/index.md), [B](index.md) : [AbstractWorkstageBuilder](../../tech.whence.echo.job.stream.workstage/-abstract-workstage-builder/index.md)<[B](index.md), *>>(**vertx**: Vertx, **work**: [W](index.md))   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| A| <br><br>: Builder<A, W, S, B> 子类<br><br>
| B| <br><br>: AbstractWorkstageBuilder<B, *> 工作阶段构造器类型<br><br>
| S| <br><br>: AbstractWorkstage 工作阶段类型<br><br>
| W| <br><br>: AbstractWork<S, B, *> 工作类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [AbstractBuilder](-abstract-builder.md)|  [jvm] <br><br><br><br>fun <[W](index.md) : [AbstractWork](../-abstract-work/index.md)<[S](index.md), [B](index.md), *>> [AbstractBuilder](-abstract-builder.md)(vertx: Vertx, work: [W](index.md))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [automatize](automatize.md)| [jvm]  <br>Brief description  <br><br><br>设置自动执行间隔<br><br>  <br>Content  <br>fun [automatize](automatize.md)(interval: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)): [A](index.md)  <br><br><br>
| [build](build.md)| [jvm]  <br>Brief description  <br><br><br>构造<br><br>  <br>Content  <br>fun [build](build.md)(leader: [Leader](../../tech.whence.echo.job.manager.management/-leader/index.md)): [W](index.md)  <br><br><br>
| [configure](configure.md)| [jvm]  <br>Brief description  <br><br><br>设置配置<br><br>  <br>Content  <br>fun [configure](configure.md)(config: [Config](../-config/index.md)): [A](index.md)  <br><br><br>
| [degrade](degrade.md)| [jvm]  <br>Brief description  <br><br><br>设置降级配置<br><br>  <br>Content  <br>fun [degrade](degrade.md)(window: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), min: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), max: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), idler: [Retry](../../tech.whence.echo.retry/-retry/index.md)?): [A](index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [log](log.md)| [jvm]  <br>Brief description  <br><br><br>设置日志记录器<br><br>  <br>Content  <br>fun [log](log.md)(logger: KLogger): [A](index.md)  <br><br><br>
| [manage](manage.md)| [jvm]  <br>Brief description  <br><br><br>默认管理构造<br><br>  <br>Content  <br>fun [manage](manage.md)(vertx: Vertx): [Manager](../../tech.whence.echo.job.manager/-manager/index.md)  <br><br><br>
| [message](message.md)| [jvm]  <br>Brief description  <br><br><br>设置普通任务提供者<br><br>  <br>Content  <br>fun [message](message.md)(provider: [MessagingProvider](../../tech.whence.echo.job.stream.provider/-messaging-provider/index.md)): [A](index.md)  <br>fun [message](message.md)(messager: [MessagingProvider.Messager](../../tech.whence.echo.job.stream.provider/-messaging-provider/-messager/index.md), stamp: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [A](index.md)  <br>fun [message](message.md)(messager: [MessagingProvider.Messager](../../tech.whence.echo.job.stream.provider/-messaging-provider/-messager/index.md), stamp: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, suppliers: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), responseAt: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[ResponseTiming](../../tech.whence.echo.job.stream.message/-response-timing/index.md)>): [A](index.md)  <br><br><br>
| [monitor](monitor.md)| [jvm]  <br>Brief description  <br><br><br>设置监听器<br><br>  <br>Content  <br>fun [monitor](monitor.md)(monitor: [Monitor](../../tech.whence.echo.job.stream.monitor/-monitor/index.md)): [A](index.md)  <br><br><br>
| [name](name.md)| [jvm]  <br>Brief description  <br><br><br>名称<br><br>  <br>Content  <br>fun [name](name.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置工人命名器<br><br>  <br>Content  <br>fun [name](name.md)(namer: [Namer](../-namer/index.md)): [A](index.md)  <br><br><br>
| [reclaim](reclaim.md)| [jvm]  <br>Brief description  <br><br><br>设置回收工人<br><br>  <br>Content  <br>fun [reclaim](reclaim.md)(reclaimer: [Worker](../-worker/index.md)): [A](index.md)  <br><br><br>
| [retry](retry.md)| [jvm]  <br>Brief description  <br><br><br>设置重试任务提供者<br><br>  <br>Content  <br>fun [retry](retry.md)(provider: [RetryingProvider](../../tech.whence.echo.job.stream.provider/-retrying-provider/index.md)?): [A](index.md)  <br>fun [retry](retry.md)(retry: [Retry](../../tech.whence.echo.retry/-retry/index.md)): [A](index.md)  <br><br><br>
| [schedule](schedule.md)| [jvm]  <br>Brief description  <br><br><br>设置调度器<br><br>  <br>Content  <br>fun [schedule](schedule.md)(scheduler: [Scheduler](../-scheduler/index.md)): [A](index.md)  <br><br><br>
| [stage](stage.md)| [jvm]  <br>Brief description  <br><br><br>设置阶段<br><br>  <br>Content  <br>fun [stage](stage.md)(stage: [S](index.md)): [A](index.md)  <br>fun [stage](stage.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), builder: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<[B](index.md)>): [A](index.md)  <br>fun [stage](stage.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), workers: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), workload: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), worker: [Worker](../-worker/index.md)?, extender: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<[B](index.md)>?): [A](index.md)  <br><br><br>
| [supply](supply.md)| [jvm]  <br>Brief description  <br><br><br>设置指定任务提供者<br><br>  <br>Content  <br>fun [supply](supply.md)(provider: [SupplyingProvider](../../tech.whence.echo.job.stream.provider/-supplying-provider/index.md)): [A](index.md)  <br>fun [supply](supply.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), producer: [Producer](../../tech.whence.echo.function/-producer/index.md)<[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Message](../../tech.whence.echo.job.stream.message/-message/index.md)>>): [A](index.md)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [trustee](trustee.md)| [jvm]  <br>Brief description  <br><br><br>托管构造<br><br>  <br>Content  <br>fun <[T](trustee.md) : [Leader](../../tech.whence.echo.job.manager.management/-leader/index.md), [Authorizer](../../tech.whence.echo.job.manager.management/-authorizer/index.md)> [trustee](trustee.md)(trustee: [T](trustee.md))  <br><br><br>


## Inheritors  
  
|  Name| 
|---|
| [SequentialWork](../-sequential-work/-builder/index.md)

