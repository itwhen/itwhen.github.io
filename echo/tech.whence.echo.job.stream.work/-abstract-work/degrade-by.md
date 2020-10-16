---
title: degradeBy -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.work](../index.md)/[AbstractWork](index.md)/[degradeBy](degrade-by.md)



# degradeBy  
[jvm]  
Brief description  


设置降级配置



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| idler| <br><br>Retry? 重试<br><br>
| max| <br><br>Double 高水位<br><br>
| min| <br><br>Double 低水位<br><br>
| window| <br><br>Double 窗口值<br><br>
  
  
Content  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [degradeBy](degrade-by.md)(window: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), min: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), max: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), idler: [Retry](../../tech.whence.echo.retry/-retry/index.md)?)  



