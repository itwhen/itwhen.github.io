---
title: unsuccessfully -
---
//[echo](../../index.md)/[tech.whence.echo.webclient](../index.md)/[ConfigBuilder](index.md)/[unsuccessfully](unsuccessfully.md)



# unsuccessfully  
[jvm]  
Brief description  


指定业务失败时的可重试设置



#### Return  


ConfigBuilder<C, A, R>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| retries| <br><br>Array<out ResponseRetry> 指定重试<br><br>
  
  
Content  
fun [unsuccessfully](unsuccessfully.md)(vararg retries: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [ResponseRetry](../../tech.whence.echo.webclient.response/-response-retry/index.md)>): [ConfigBuilder](index.md)<[C](index.md), [A](index.md), [R](index.md)>  



