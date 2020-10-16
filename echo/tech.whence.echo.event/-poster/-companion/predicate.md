---
title: predicate -
---
//[echo](../../../index.md)/[tech.whence.echo.event](../../index.md)/[Poster](../index.md)/[Companion](index.md)/[predicate](predicate.md)



# predicate  
[jvm]  
Brief description  


基于断言结果构造



#### Return  


Poster<Boolean>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| exceptionally| <br><br>Consumer<Throwable> 异常处理<br><br>
| producer| <br><br>Producer<Boolean> 结果生成<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [predicate](predicate.md)(producer: [Producer](../../../tech.whence.echo.function/-producer/index.md)<[Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)>, exceptionally: [Consumer](../../../tech.whence.echo.function/-consumer/index.md)<[Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)>): [Poster](../index.md)<[Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)>  



