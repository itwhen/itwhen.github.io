---
title: tech.whence.echo.codec -
---
//[echo](../index.md)/[tech.whence.echo.codec](index.md)



# Package tech.whence.echo.codec  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Codec](-codec/index.md)| [jvm]  <br>Brief description  <br><br><br>编解器 将数据源视作黑箱 取数据并解码出来呈现 编码封装数据存入数据源<br><br>  <br>Content  <br>interface [Codec](-codec/index.md) : [Namer](../tech.whence.echo.definition/-namer/index.md)  <br><br><br>
| [Codecs](-codecs/index.md)| [jvm]  <br>Brief description  <br><br><br>解编器容器<br><br>  <br>Content  <br>class [Codecs](-codecs/index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))  <br><br><br>
| [Context](-context/index.md)| [jvm]  <br>Brief description  <br><br><br>上下文 存储解编过程中的键值/解编器定义/解编方式 提供解编顺序支持 提供解编跟踪支持<br><br>  <br>Content  <br>class [Context](-context/index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **value**: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, **definition**: [Codec.Definition](-codec/-definition/index.md), **method**: [Codec.Method](-codec/-method/index.md), **traces**: [LinkedList](https://docs.oracle.com/javase/8/docs/api/java/util/LinkedList.html)<[Context.Trace](-context/-trace/index.md)>)  <br><br><br>
| [Converter](-converter/index.md)| [jvm]  <br>Brief description  <br><br><br>通用解码器<br><br>  <br>Content  <br>object [Converter](-converter/index.md)  <br><br><br>
| [Decoder](-decoder/index.md)| [jvm]  <br>Brief description  <br><br><br>解码器 提供转化任意值到指定类型的能力 能力不足时返回空值<br><br>  <br>Content  <br>interface [Decoder](-decoder/index.md)<[T](-decoder/index.md), out [P](-decoder/index.md)>  <br><br><br>
| [Handle](-handle/index.md)| [jvm]  <br>Brief description  <br><br><br>指定类型处理器角色注解<br><br>  <br>Content  <br>@[Target](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.annotation/-target/index.html)(allowedTargets = [[AnnotationTarget.CLASS](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.annotation/-annotation-target/-c-l-a-s-s/index.html)])  <br>  <br>annotation class [Handle](-handle/index.md)(**value**: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>>)  <br><br><br>
| [Transfer](-transfer/index.md)| [jvm]  <br>Brief description  <br><br><br>解编器角色注解<br><br>  <br>Content  <br>@[Target](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.annotation/-target/index.html)(allowedTargets = [[AnnotationTarget.CLASS](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.annotation/-annotation-target/-c-l-a-s-s/index.html)])  <br>  <br>annotation class [Transfer](-transfer/index.md)  <br><br><br>
| [UnconvertableException](-unconvertable-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>无法转换异常<br><br>  <br>Content  <br>class [UnconvertableException](-unconvertable-exception/index.md)(**definition**: [Codec.Definition](-codec/-definition/index.md), **method**: [Codec.Method](-codec/-method/index.md), **cause**: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)) : [RuntimeException](https://docs.oracle.com/javase/8/docs/api/java/lang/RuntimeException.html)  <br><br><br>

