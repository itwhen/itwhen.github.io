---
title: tech.whence.echo.job.manager.state -
---
//[echo](../index.md)/[tech.whence.echo.job.manager.state](index.md)



# Package tech.whence.echo.job.manager.state  


## Types  
  
|  Name|  Summary| 
|---|---|
| [State](-state/index.md)| [jvm]  <br>Brief description  <br><br><br>作业状态<br><br>  <br>Content  <br>enum [State](-state/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[State](-state/index.md)>   <br><br><br>
| [StateInvalidException](-state-invalid-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>状态异常<br><br>  <br>Content  <br>class [StateInvalidException](-state-invalid-exception/index.md)(**sources**: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[State](-state/index.md)>, **target**: [State](-state/index.md), **current**: [State](-state/index.md)) : [RuntimeException](https://docs.oracle.com/javase/8/docs/api/java/lang/RuntimeException.html)  <br><br><br>
| [StateUntransferableException](-state-untransferable-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>状态无法转换<br><br>  <br>Content  <br>class [StateUntransferableException](-state-untransferable-exception/index.md)(**operation**: [Operation](../tech.whence.echo.job.manager/-operation/index.md), **cause**: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)) : [RuntimeException](https://docs.oracle.com/javase/8/docs/api/java/lang/RuntimeException.html)  <br><br><br>

