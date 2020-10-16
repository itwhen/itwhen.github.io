---
title: tech.whence.echo.job -
---
//[echo](../index.md)/[tech.whence.echo.job](index.md)



# Package tech.whence.echo.job  


## Types  
  
|  Name|  Summary| 
|---|---|
| [AbstractJob](-abstract-job/index.md)| [jvm]  <br>Brief description  <br><br><br>作业抽象<br><br>  <br>Content  <br>abstract class [AbstractJob](-abstract-job/index.md)<[V](-abstract-job/index.md)> : [Job](-job/index.md), [Monitorable](../tech.whence.echo.job.monitor/-monitorable/index.md)  <br><br><br>
| [AbstractScheduledJob](-abstract-scheduled-job/index.md)| [jvm]  <br>Brief description  <br><br><br>可调度作业抽象<br><br>  <br>Content  <br>abstract class [AbstractScheduledJob](-abstract-scheduled-job/index.md)<[V](-abstract-scheduled-job/index.md)>(**vertx**: Vertx) : [AbstractJob](-abstract-job/index.md)<[V](-abstract-scheduled-job/index.md)> , [ScheduledJob](-scheduled-job/index.md), [Leader](../tech.whence.echo.job.manager.management/-leader/index.md), [Authorizer](../tech.whence.echo.job.manager.management/-authorizer/index.md)  <br><br><br>
| [IdleJob](-idle-job/index.md)| [jvm]  <br>Brief description  <br><br><br>不中断作业<br><br>  <br>Content  <br>interface [IdleJob](-idle-job/index.md) : [Job](-job/index.md), [Monitorable](../tech.whence.echo.job.monitor/-monitorable/index.md)  <br><br><br>
| [IdleJobDelegator](-idle-job-delegator/index.md)| [jvm]  <br>Brief description  <br><br><br>不中断作业委托<br><br>  <br>Content  <br>class [IdleJobDelegator](-idle-job-delegator/index.md)(**delegator**: [IdleJob](-idle-job/index.md)) : AbstractIdleService, [Monitorable](../tech.whence.echo.job.monitor/-monitorable/index.md)  <br><br><br>
| [Job](-job/index.md)| [jvm]  <br>Brief description  <br><br><br>作业<br><br>  <br>Content  <br>interface [Job](-job/index.md) : [Namer](../tech.whence.echo.definition/-namer/index.md)  <br><br><br>
| [ScheduledJob](-scheduled-job/index.md)| [jvm]  <br>Brief description  <br><br><br>可调度作业<br><br>  <br>Content  <br>interface [ScheduledJob](-scheduled-job/index.md) : [IdleJob](-idle-job/index.md)  <br><br><br>
| [ScheduledJobDelegator](-scheduled-job-delegator/index.md)| [jvm]  <br>Brief description  <br><br><br>可调度作业委托<br><br>  <br>Content  <br>class [ScheduledJobDelegator](-scheduled-job-delegator/index.md)(**vertx**: Vertx, **principal**: [ScheduledJob](-scheduled-job/index.md)) : AbstractScheduledService, [Monitorable](../tech.whence.echo.job.monitor/-monitorable/index.md)  <br><br><br>
| [Traceable](-traceable/index.md)| [jvm]  <br>Brief description  <br><br><br>可跟踪数据<br><br>  <br>Content  <br>interface [Traceable](-traceable/index.md)  <br><br><br>

