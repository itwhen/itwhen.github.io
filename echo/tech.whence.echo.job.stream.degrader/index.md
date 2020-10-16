---
title: tech.whence.echo.job.stream.degrader -
---
//[echo](../index.md)/[tech.whence.echo.job.stream.degrader](index.md)



# Package tech.whence.echo.job.stream.degrader  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Controller](-controller/index.md)| [jvm]  <br>Brief description  <br><br><br>降级控制器<br><br>  <br>Content  <br>interface [Controller](-controller/index.md)  <br><br><br>
| [Degrader](-degrader/index.md)| [jvm]  <br>Brief description  <br><br><br>降级器<br><br>  <br>Content  <br>class [Degrader](-degrader/index.md)(**controller**: [Controller](-controller/index.md), **window**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **measurer**: [Measurer](../tech.whence.echo.job.stream.work/-measurer/index.md), **idler**: [Retry](../tech.whence.echo.retry/-retry/index.md)?)  <br><br><br>
| [Stage](-stage/index.md)| [jvm]  <br>Brief description  <br><br><br>降级器阶段<br><br>  <br>Content  <br>enum [Stage](-stage/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Stage](-stage/index.md)>   <br><br><br>
| [WarmUpController](-warm-up-controller/index.md)| [jvm]  <br>Brief description  <br><br><br>预热式控制器<br><br>  <br>Content  <br>class [WarmUpController](-warm-up-controller/index.md) : [Controller](-controller/index.md)  <br><br><br>

