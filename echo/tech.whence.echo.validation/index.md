---
title: tech.whence.echo.validation -
---
//[echo](../index.md)/[tech.whence.echo.validation](index.md)



# Package tech.whence.echo.validation  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Annotator](-annotator/index.md)| [jvm]  <br>Brief description  <br><br><br>注解器<br><br>  <br>Content  <br>class [Annotator](-annotator/index.md)(**ruler**: [Ruler](-ruler/index.md))  <br><br><br>
| [Context](-context/index.md)| [jvm]  <br>Brief description  <br><br><br>上下文<br><br>  <br>Content  <br>class [Context](-context/index.md)(**validator**: [Validator](-validator/index.md), **data**: [Accessor](../tech.whence.echo.container.accessor/-accessor/index.md))  <br><br><br>
| [Errors](-errors/index.md)| [jvm]  <br>Brief description  <br><br><br>错误消息<br><br>  <br>Content  <br>class [Errors](-errors/index.md) : [Container](../tech.whence.echo.container/-container/index.md), [Readable](../tech.whence.echo.container.accessor/-readable/index.md)  <br><br><br>
| [InvalidatedException](-invalidated-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>校验失败<br><br>  <br>Content  <br>class [InvalidatedException](-invalidated-exception/index.md)(**errors**: [Errors](-errors/index.md)) : [RuntimeException](https://docs.oracle.com/javase/8/docs/api/java/lang/RuntimeException.html)  <br><br><br>
| [Ruler](-ruler/index.md)| [jvm]  <br>Brief description  <br><br><br>规则<br><br>  <br>Content  <br>class [Ruler](-ruler/index.md)(**key**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **validator**: [Validator](-validator/index.md))  <br><br><br>
| [Validated](-validated/index.md)| [jvm]  <br>Brief description  <br><br><br>校验结果<br><br>  <br>Content  <br>sealed class [Validated](-validated/index.md)  <br><br><br>
| [Validation](-validation/index.md)| [jvm]  <br>Brief description  <br><br><br>校验器<br><br>  <br>Content  <br>object [Validation](-validation/index.md)  <br><br><br>
| [Validator](-validator/index.md)| [jvm]  <br>Brief description  <br><br><br>校验器<br><br>  <br>Content  <br>class [Validator](-validator/index.md)  <br><br><br>

