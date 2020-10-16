---
title: tech.whence.echo.rpc.exception -
---
//[echo](../index.md)/[tech.whence.echo.rpc.exception](index.md)



# Package tech.whence.echo.rpc.exception  


## Types  
  
|  Name|  Summary| 
|---|---|
| [ConflictedException](-conflicted-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>数据重复<br><br>  <br>Content  <br>class [ConflictedException](-conflicted-exception/index.md)(**message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) : [ResponseException](-response-exception/index.md)  <br><br><br>
| [InvalidatedException](-invalidated-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>校验失败<br><br>  <br>Content  <br>class [InvalidatedException](-invalidated-exception/index.md)(**errors**: [Errors](../tech.whence.echo.validation/-errors/index.md)) : [ResponseException](-response-exception/index.md)  <br><br><br>
| [MissingException](-missing-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>找不到指定记录<br><br>  <br>Content  <br>class [MissingException](-missing-exception/index.md)(**message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) : [ResponseException](-response-exception/index.md)  <br><br><br>
| [ResponseException](-response-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>响应异常<br><br>  <br>Content  <br>open class [ResponseException](-response-exception/index.md)(**message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **type**: ReplyFailure) : ReplyException  <br><br><br>
| [TodoException](-todo-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>开发中<br><br>  <br>Content  <br>class [TodoException](-todo-exception/index.md)(**message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) : [ResponseException](-response-exception/index.md)  <br><br><br>
| [UnauthorizedException](-unauthorized-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>未授权<br><br>  <br>Content  <br>class [UnauthorizedException](-unauthorized-exception/index.md) : [ResponseException](-response-exception/index.md)  <br><br><br>
| [UnavailableException](-unavailable-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>不可用<br><br>  <br>Content  <br>class [UnavailableException](-unavailable-exception/index.md)(**message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) : [ResponseException](-response-exception/index.md)  <br><br><br>
| [UnrecognizedException](-unrecognized-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>无法识别<br><br>  <br>Content  <br>class [UnrecognizedException](-unrecognized-exception/index.md)(**message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) : [ResponseException](-response-exception/index.md)  <br><br><br>

