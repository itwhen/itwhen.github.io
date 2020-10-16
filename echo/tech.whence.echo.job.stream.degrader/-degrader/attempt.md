---
title: attempt -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.degrader](../index.md)/[Degrader](index.md)/[attempt](attempt.md)



# attempt  
[jvm]  
Brief description  


尝试通过 1 若默认阶段允许 2 若在阻塞阶段不允许 3 否则根据权重决定最大尝试次数     在尝试次数内随机     若该随机数介乎于当前几率与控制器高水位之间则允许通过



#### Return  


Boolean 是否允许通过



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| weighting| <br><br>Int 当前权重<br><br>
  
  
Content  
fun [attempt](attempt.md)(weighting: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  



