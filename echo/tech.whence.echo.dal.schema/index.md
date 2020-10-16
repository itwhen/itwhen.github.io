---
title: tech.whence.echo.dal.schema -
---
//[echo](../index.md)/[tech.whence.echo.dal.schema](index.md)



# Package tech.whence.echo.dal.schema  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Annotator](-annotator/index.md)| [jvm]  <br>Brief description  <br><br><br>注解器<br><br>  <br>Content  <br>class [Annotator](-annotator/index.md)<[T](-annotator/index.md) : [Entity](../tech.whence.echo.dal.entity/-entity/index.md)>(**builder**: [Builder](-builder/index.md)<[T](-annotator/index.md)>)  <br><br><br>
| [Builder](-builder/index.md)| [jvm]  <br>Brief description  <br><br><br>数据表构造器<br><br>  <br>Content  <br>class [Builder](-builder/index.md)<[T](-builder/index.md) : [Entity](../tech.whence.echo.dal.entity/-entity/index.md)>  <br><br><br>
| [Describer](-describer/index.md)| [jvm]  <br>Brief description  <br><br><br>数据表描述器<br><br>  <br>Content  <br>interface [Describer](-describer/index.md)  <br><br><br>
| [Schema](-schema/index.md)| [jvm]  <br>Brief description  <br><br><br>数据表<br><br>  <br>Content  <br>class [Schema](-schema/index.md)<[T](-schema/index.md) : [Entity](../tech.whence.echo.dal.entity/-entity/index.md)>  <br><br><br>
| [Table](-table/index.md)| [jvm]  <br>Brief description  <br><br><br>定义表名<br><br>  <br>Content  <br>@[Target](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.annotation/-target/index.html)(allowedTargets = [[AnnotationTarget.CLASS](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.annotation/-annotation-target/-c-l-a-s-s/index.html)])  <br>  <br>annotation class [Table](-table/index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))  <br><br><br>
| [UnannotatableException](-unannotatable-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>注解无法识别<br><br>  <br>Content  <br>class [UnannotatableException](-unannotatable-exception/index.md)(**key**: [Key](../tech.whence.echo.dal.schema.key/-key/index.md), **annotation**: [Annotation](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-annotation/index.html)) : [IllegalStateException](https://docs.oracle.com/javase/8/docs/api/java/lang/IllegalStateException.html)  <br><br><br>
| [UndetectableException](-undetectable-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>数据表无法检测<br><br>  <br>Content  <br>class [UndetectableException](-undetectable-exception/index.md) : [DataAccessException](../tech.whence.echo.dal/-data-access-exception/index.md)  <br><br><br>
| [Verifier](-verifier/index.md)| [jvm]  <br>Brief description  <br><br><br>构建检查<br><br>  <br>Content  <br>fun fun interface [Verifier](-verifier/index.md)  <br><br><br>

