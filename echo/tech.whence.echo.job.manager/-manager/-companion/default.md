---
title: default -
---
//[echo](../../../index.md)/[tech.whence.echo.job.manager](../../index.md)/[Manager](../index.md)/[Companion](index.md)/[default](default.md)



# default  
[jvm]  
Brief description  


构造



#### Return  


DefaultManager



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| callback| <br><br>Consumer<Management><br><br>
| vertx| <br><br>Vertx<br><br>
  
  
Content  
fun [default](default.md)(vertx: Vertx, callback: [Consumer](../../../tech.whence.echo.function/-consumer/index.md)<[Management](../../../tech.whence.echo.job.manager.management/-management/index.md)>): [DefaultManager](../../-default-manager/index.md)  


[jvm]  
Brief description  


构造



#### Return  


DefaultManager



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| dispatch| <br><br>Actor? 调度<br><br>
| manager| <br><br>Manager 管理器<br><br>
| vertx| <br><br>Vertx<br><br>
  
  
Content  
fun [default](default.md)(vertx: Vertx, manager: [Manager](../index.md), dispatch: [Actor](../../../tech.whence.echo.job.manager.management/-actor/index.md)?): [DefaultManager](../../-default-manager/index.md)  


[jvm]  
Brief description  


构造



#### Return  


DefaultManager



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| dispatch| <br><br>Runner? 调度<br><br>
| resume| <br><br>Runner? 恢复<br><br>
| start| <br><br>Runner? 启动<br><br>
| stop| <br><br>Runner? 停止<br><br>
| suspend| <br><br>Runner? 挂起<br><br>
| vertx| <br><br>Vertx<br><br>
  
  
Content  
fun [default](default.md)(vertx: Vertx, start: [Actor](../../../tech.whence.echo.job.manager.management/-actor/index.md)?, suspend: [Actor](../../../tech.whence.echo.job.manager.management/-actor/index.md)?, resume: [Actor](../../../tech.whence.echo.job.manager.management/-actor/index.md)?, stop: [Actor](../../../tech.whence.echo.job.manager.management/-actor/index.md)?, dispatch: [Actor](../../../tech.whence.echo.job.manager.management/-actor/index.md)?): [DefaultManager](../../-default-manager/index.md)  



