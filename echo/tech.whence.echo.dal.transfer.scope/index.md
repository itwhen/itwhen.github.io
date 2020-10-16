---
title: tech.whence.echo.dal.transfer.scope -
---
//[echo](../index.md)/[tech.whence.echo.dal.transfer.scope](index.md)



# Package tech.whence.echo.dal.transfer.scope  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Batch](-batch/index.md)| [jvm]  <br>Brief description  <br><br><br>批次<br><br>  <br>Content  <br>data class [Batch](-batch/index.md)(**records**: [Records](../tech.whence.echo.dal.entity/index.md#tech.whence.echo.dal.entity/Records///PointingToDeclaration/), **min**: [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), **max**: [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html))  <br><br><br>
| [DateScope](-date-scope/index.md)| [jvm]  <br>Brief description  <br><br><br>日期时间范围<br><br>  <br>Content  <br>class [DateScope](-date-scope/index.md)(**min**: [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)?, **max**: [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)?, **key**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **range**: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html), **limit**: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)) : [Scope](-scope/index.md)<[LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)>   <br><br><br>
| [NumberScope](-number-scope/index.md)| [jvm]  <br>Brief description  <br><br><br>数值范围<br><br>  <br>Content  <br>class [NumberScope](-number-scope/index.md)(**min**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)?, **max**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)?, **key**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **range**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) : [Scope](-scope/index.md)<[Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)>   <br><br><br>
| [Querier](-querier/index.md)| [jvm]  <br>Brief description  <br><br><br>查询器<br><br>  <br>Content  <br>interface [Querier](-querier/index.md)  <br><br><br>
| [Scope](-scope/index.md)| [jvm]  <br>Brief description  <br><br><br>范围<br><br>  <br>Content  <br>interface [Scope](-scope/index.md)<[T](-scope/index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>  <br><br><br>

