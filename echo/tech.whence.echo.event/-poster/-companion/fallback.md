---
title: fallback -
---
//[echo](../../../index.md)/[tech.whence.echo.event](../../index.md)/[Poster](../index.md)/[Companion](index.md)/[fallback](fallback.md)



# fallback  
[jvm]  
Brief description  


基于后备结果构造



#### Return  


Poster<R>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| exceptionally| <br><br>Consumer<Throwable> 异常处理<br><br>
| producer| <br><br>Producer<R> 后备结果生成<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun <[R](fallback.md)> [fallback](fallback.md)(producer: [Producer](../../../tech.whence.echo.function/-producer/index.md)<[R](fallback.md)>, exceptionally: [Consumer](../../../tech.whence.echo.function/-consumer/index.md)<[Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)>): [Poster](../index.md)<[R](fallback.md)>  



