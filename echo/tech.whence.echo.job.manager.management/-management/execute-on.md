---
title: executeOn -
---
//[echo](../../index.md)/[tech.whence.echo.job.manager.management](../index.md)/[Management](index.md)/[executeOn](execute-on.md)



# executeOn  
[jvm]  
Brief description  


设置运行环境



#### Return  


Management



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| executor| <br><br>CoroutineContext 指定运行环境<br><br>
  
  
Content  
fun [executeOn](execute-on.md)(executor: [CoroutineContext](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.coroutines/-coroutine-context/index.html)): [Management](index.md)  


[jvm]  
Brief description  


设置运行环境 基于可用CPU处理器数大小的固定线程池 根据能力值ability扩展线程池大小



#### Return  


Management



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| ability| <br><br>UInt 能力值<br><br>
  
  
Content  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [executeOn](execute-on.md)(ability: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)): [Management](index.md)  



