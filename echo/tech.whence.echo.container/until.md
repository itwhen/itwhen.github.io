---
title: until -
---
//[echo](../index.md)/[tech.whence.echo.container](index.md)/[until](until.md)



# until  
[jvm]  
Brief description  


遍历每个元素直到返回停止响应



#### Return  


R?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| <receiver>| <br><br>Sequence<T><br><br>
| breaker| <br><br>Breaker<T, R?>> 中断器<br><br>
| initial| <br><br>R? 初始值<br><br>
  
  
Content  
fun <[T](until.md), [R](until.md)> [Sequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.sequences/-sequence/index.html)<[T](until.md)>.[until](until.md)(initial: [R](until.md)?, breaker: [Breaker](../tech.whence.echo.function/-breaker/index.md)<[T](until.md), [R](until.md)?>): [R](until.md)?  



