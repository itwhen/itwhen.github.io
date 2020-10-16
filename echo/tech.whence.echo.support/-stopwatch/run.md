---
title: run -
---
//[echo](../../index.md)/[tech.whence.echo.support](../index.md)/[Stopwatch](index.md)/[run](run.md)



# run  
[jvm]  
Brief description  


执行子回调模块



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| name| <br><br>String 名称<br><br>
| runner| <br><br>Runner 回调<br><br>
  
  
Content  
fun [run](run.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), runner: [Runner](../../tech.whence.echo.function/-runner/index.md))  


[jvm]  
Brief description  


执行子回调模块并返回其结果



#### Return  


T



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| name| <br><br>String 名称<br><br>
| producer| <br><br>Producer<T> 回调<br><br>
  
  
Content  
fun <[T](run.md)> [run](run.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), producer: [Producer](../../tech.whence.echo.function/-producer/index.md)<[T](run.md)>): [T](run.md)  



