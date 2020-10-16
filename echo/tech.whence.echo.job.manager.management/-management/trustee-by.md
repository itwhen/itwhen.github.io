---
title: trusteeBy -
---
//[echo](../../index.md)/[tech.whence.echo.job.manager.management](../index.md)/[Management](index.md)/[trusteeBy](trustee-by.md)



# trusteeBy  
[jvm]  
Brief description  


设置委托人



#### Return  


Management



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| trustor| <br><br>Manager 指定委托人<br><br>
  
  
Content  
fun [trusteeBy](trustee-by.md)(trustor: [Manager](../../tech.whence.echo.job.manager/-manager/index.md)): [Management](index.md)  


[jvm]  
Brief description  


设置委托方法



#### Return  


Management



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| resume| <br><br>Actor? 恢复<br><br>
| start| <br><br>Actor? 启动<br><br>
| stop| <br><br>Actor? 停止<br><br>
| suspend| <br><br>Actor? 挂起<br><br>
  
  
Content  
fun [trusteeBy](trustee-by.md)(start: [Actor](../-actor/index.md)?, suspend: [Actor](../-actor/index.md)?, resume: [Actor](../-actor/index.md)?, stop: [Actor](../-actor/index.md)?): [Management](index.md)  



