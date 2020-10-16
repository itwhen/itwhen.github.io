---
title: of -
---
//[echo](../../../index.md)/[tech.whence.echo.job.stream.work](../../index.md)/[Work](../index.md)/[Companion](index.md)/[of](of.md)



# of  
[jvm]  
Brief description  


构造



#### Return  


SequentialWork.Builder



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| name| <br><br>String 名称<br><br>
| vertx| <br><br>Vertx<br><br>
| worker| <br><br>Worker 工人<br><br>
| workers| <br><br>Int 人数<br><br>
| workload| <br><br>Int 负载<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [of](of.md)(vertx: Vertx, name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), workers: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), workload: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), worker: [Worker](../../-worker/index.md)): [SequentialWork.Builder](../../-sequential-work/-builder/index.md)  


[jvm]  
Brief description  


构造



#### Return  


SequentialWork.Builder



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| vertx| <br><br>Vertx<br><br>
| worker| <br><br>Worker 工人<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [of](of.md)(vertx: Vertx, worker: [Worker](../../-worker/index.md)): [SequentialWork.Builder](../../-sequential-work/-builder/index.md)  



