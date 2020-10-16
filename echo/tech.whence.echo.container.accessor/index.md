---
title: tech.whence.echo.container.accessor -
---
//[echo](../index.md)/[tech.whence.echo.container.accessor](index.md)



# Package tech.whence.echo.container.accessor  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Accessor](-accessor/index.md)| [jvm]  <br>Brief description  <br><br><br>数据访问器 用于封装 string -> any? 的访问 并提供 json-path 风格查询<br><br>  <br>Content  <br>class [Accessor](-accessor/index.md) : [Accessibility](../tech.whence.echo.container/-accessibility/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> , [Container](../tech.whence.echo.container/-container/index.md)  <br><br><br>
| [Adaptive](-adaptive/index.md)| [jvm]  <br>Brief description  <br><br><br>支持存放的<br><br>  <br>Content  <br>interface [Adaptive](-adaptive/index.md)  <br><br><br>
| [Entitifier](-entitifier/index.md)| [jvm]  <br>Brief description  <br><br><br>数据访问器实体转换器<br><br>  <br>Content  <br>class [Entitifier](-entitifier/index.md) : [AbstractAssembler](../tech.whence.echo.dal.entity.assembler/-abstract-assembler/index.md)<[Accessor](-accessor/index.md), [Accessor](-accessor/index.md), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>   <br><br><br>
| [Factory](-factory/index.md)| [jvm]  <br>Brief description  <br><br><br>表单生成器<br><br>  <br>Content  <br>interface [Factory](-factory/index.md)  <br><br><br>
| [Locate](-locate/index.md)| [jvm]  <br>Brief description  <br><br><br>转换到指定对象时定位其属性到当前访问器的某键<br><br>  <br>Content  <br>@[Target](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.annotation/-target/index.html)(allowedTargets = [[AnnotationTarget.PROPERTY](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.annotation/-annotation-target/-p-r-o-p-e-r-t-y/index.html)])  <br>  <br>annotation class [Locate](-locate/index.md)(**key**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))  <br><br><br>
| [Mode](-mode/index.md)| [jvm]  <br>Brief description  <br><br><br>解析模式<br><br>  <br>Content  <br>sealed class [Mode](-mode/index.md)  <br><br><br>
| [Modes](-modes/index.md)| [jvm]  <br>Brief description  <br><br><br>模式设置 用于存储多个模式值并提供简便操作方式<br><br>  <br>Content  <br>class [Modes](-modes/index.md)(**data**: [LinkedHashSet](https://docs.oracle.com/javase/8/docs/api/java/util/LinkedHashSet.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)  <br><br><br>
| [Property](-property/index.md)| [jvm]  <br>Brief description  <br><br><br>属性代理<br><br>  <br>Content  <br>class [Property](-property/index.md)<[V](-property/index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> : [ReadWriteProperty](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.properties/-read-write-property/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, [V](-property/index.md)?>   <br><br><br>
| [Readable](-readable/index.md)| [jvm]  <br>Brief description  <br><br><br>可转换为访问器<br><br>  <br>Content  <br>fun fun interface [Readable](-readable/index.md)  <br><br><br>
| [Reading](-reading/index.md)| [jvm]  <br>Brief description  <br><br><br>正在读取的键相关数据<br><br>  <br>Content  <br>class [Reading](-reading/index.md)  <br><br><br>
| [Validity](-validity/index.md)| [jvm]  <br>Brief description  <br><br><br>校验<br><br>  <br>Content  <br>interface [Validity](-validity/index.md)  <br><br><br>
| [Writable](-writable/index.md)| [jvm]  <br>Brief description  <br><br><br>可由访问器构造<br><br>  <br>Content  <br>@[Target](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.annotation/-target/index.html)(allowedTargets = [[AnnotationTarget.CLASS](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.annotation/-annotation-target/-c-l-a-s-s/index.html)])  <br>  <br>annotation class [Writable](-writable/index.md)  <br><br><br>

