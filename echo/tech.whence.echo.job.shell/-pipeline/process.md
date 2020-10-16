---
title: process -
---
//[echo](../../index.md)/[tech.whence.echo.job.shell](../index.md)/[Pipeline](index.md)/[process](process.md)



# process  
[jvm]  
Brief description  


执行批量管理命令



#### Return  


Responder



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| control| <br><br>Control? 指定命令<br><br>
  
  
Content  
fun [process](process.md)(control: [Control](../-control/index.md)?): [Responder](../-responder/index.md)  


[jvm]  
Brief description  


执行指定作业控制



#### Return  


Responder



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| name| <br><br>String 指定作业名<br><br>
| operation| <br><br>Control? 指定控制<br><br>
| parameters| <br><br>Accessor? 指定参数<br><br>
  
  
Content  
fun [process](process.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), operation: [Operation](../-operation/index.md)?, parameters: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)?): [Responder](../-responder/index.md)  



