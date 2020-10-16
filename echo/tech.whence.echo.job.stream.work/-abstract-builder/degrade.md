---
title: degrade -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.work](../index.md)/[AbstractBuilder](index.md)/[degrade](degrade.md)



# degrade  
[jvm]  
Brief description  


设置降级配置



#### Return  


A



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| idler| <br><br>Retry? 重试<br><br>
| max| <br><br>Double 最高值<br><br>
| min| <br><br>Double 最低值<br><br>
| window| <br><br>Double 窗口<br><br>
  
  
Content  
fun [degrade](degrade.md)(window: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), min: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), max: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), idler: [Retry](../../tech.whence.echo.retry/-retry/index.md)?): [A](index.md)  



