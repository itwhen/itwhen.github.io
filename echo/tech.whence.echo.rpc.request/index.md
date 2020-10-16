---
title: tech.whence.echo.rpc.request -
---
//[echo](../index.md)/[tech.whence.echo.rpc.request](index.md)



# Package tech.whence.echo.rpc.request  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Batch](-batch/index.md)| [jvm]  <br>Brief description  <br><br><br>批次<br><br>  <br>Content  <br>class [Batch](-batch/index.md) : [Container](../tech.whence.echo.container/-container/index.md)  <br><br><br>
| [Id](-id/index.md)| [jvm]  <br>Brief description  <br><br><br>编码<br><br>  <br>Content  <br>class [Id](-id/index.md)  <br><br><br>
| [Request](-request/index.md)| [jvm]  <br>Brief description  <br><br><br>请求<br><br>  <br>Content  <br>class [Request](-request/index.md)<[T](-request/index.md) : [Payload](../tech.whence.echo.rpc.payload/-payload/index.md)>  <br><br><br>
| [Scope](-scope/index.md)| [jvm]  <br>Brief description  <br><br><br>所属范围<br><br>  <br>Content  <br>enum [Scope](-scope/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Scope](-scope/index.md)>   <br><br><br>
| [Token](-token/index.md)| [jvm]  <br>Brief description  <br><br><br>令牌信息<br><br>  <br>Content  <br>data class [Token](-token/index.md)(**id**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **expiration**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **expiredAt**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)  <br><br><br>
| [User](-user/index.md)| [jvm]  <br>Brief description  <br><br><br>用户信息<br><br>  <br>Content  <br>data class [User](-user/index.md)(**id**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **code**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **title**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **token**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [batch](batch.md)| [jvm]  <br>Brief description  <br><br><br>字符串转换为批次<br><br>  <br>Content  <br>fun [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html).[batch](batch.md)(): [Batch](-batch/index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>字符串集合转换为批次<br><br>  <br>Content  <br>fun [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>.[batch](batch.md)(): [Batch](-batch/index.md)  <br><br><br>
| [id](id.md)| [jvm]  <br>Brief description  <br><br><br>字符串转换为编号<br><br>  <br>Content  <br>fun [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html).[id](id.md)(): [Id](-id/index.md)  <br><br><br>

