---
title: stage -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.work](../index.md)/[AbstractBuilder](index.md)/[stage](stage.md)



# stage  
[jvm]  
Brief description  


设置阶段



#### Return  


A



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| stage| <br><br>S 指定阶段<br><br>
  
  
Content  
fun [stage](stage.md)(stage: [S](index.md)): [A](index.md)  


[jvm]  
Brief description  


设置阶段



#### Return  


A



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| builder| <br><br>Consumer<B> 构造<br><br>
| name| <br><br>String 名称<br><br>
  
  
Content  
fun [stage](stage.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), builder: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<[B](index.md)>): [A](index.md)  


[jvm]  
Brief description  


设置阶段



#### Return  


A



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| extender| <br><br>Consumer<B>? 扩展<br><br>
| name| <br><br>String 名称<br><br>
| worker| <br><br>Worker? 工人<br><br>
| workers| <br><br>Int 工人数<br><br>
| workload| <br><br>Int 负载<br><br>
  
  
Content  
fun [stage](stage.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), workers: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), workload: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), worker: [Worker](../-worker/index.md)?, extender: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<[B](index.md)>?): [A](index.md)  



