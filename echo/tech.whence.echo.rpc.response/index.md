---
title: tech.whence.echo.rpc.response -
---
//[echo](../index.md)/[tech.whence.echo.rpc.response](index.md)



# Package tech.whence.echo.rpc.response  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Decorator](-decorator/index.md)| [jvm]  <br>Brief description  <br><br><br>响应负载修饰器<br><br>  <br>Content  <br>fun fun interface [Decorator](-decorator/index.md)<[P](-decorator/index.md) : [Payload](../tech.whence.echo.rpc.payload/-payload/index.md), [D](-decorator/index.md) : [Entity](../tech.whence.echo.dal.entity/-entity/index.md)>  <br><br><br>
| [Describe](-describe/index.md)| [jvm]  <br>Brief description  <br><br><br>序列化负载时给常量字段扩展其描述字段<br><br>  <br>Content  <br>@[Target](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.annotation/-target/index.html)(allowedTargets = [[AnnotationTarget.PROPERTY](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.annotation/-annotation-target/-p-r-o-p-e-r-t-y/index.html), [AnnotationTarget.FIELD](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.annotation/-annotation-target/-f-i-e-l-d/index.html), [AnnotationTarget.VALUE_PARAMETER](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.annotation/-annotation-target/-v-a-l-u-e_-p-a-r-a-m-e-t-e-r/index.html), [AnnotationTarget.PROPERTY_GETTER](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.annotation/-annotation-target/-p-r-o-p-e-r-t-y_-g-e-t-t-e-r/index.html)])  <br>  <br>annotation class [Describe](-describe/index.md)  <br><br><br>
| [Failure](-failure/index.md)| [jvm]  <br>Brief description  <br><br><br>失败<br><br>  <br>Content  <br>data class [Failure](-failure/index.md)(**code**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **errors**: [Errors](../tech.whence.echo.validation/-errors/index.md)?) : [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html), [Readable](../tech.whence.echo.container.accessor/-readable/index.md), [Responsive](-responsive/index.md)  <br><br><br>
| [Layout](-layout/index.md)| [jvm]  <br>Brief description  <br><br><br>响应格式<br><br>  <br>Content  <br>enum [Layout](-layout/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Layout](-layout/index.md)>   <br><br><br>
| [Reason](-reason/index.md)| [jvm]  <br>Brief description  <br><br><br>错误原因<br><br>  <br>Content  <br>enum [Reason](-reason/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Reason](-reason/index.md)> , [StringConst](../tech.whence.echo.container.constant/-string-const/index.md)  <br><br><br>
| [Response](-response/index.md)| [jvm]  <br>Brief description  <br><br><br>响应<br><br>  <br>Content  <br>class [Response](-response/index.md)<[T](-response/index.md) : [Payload](../tech.whence.echo.rpc.payload/-payload/index.md)> : [Responsive](-responsive/index.md)  <br><br><br>
| [Responsive](-responsive/index.md)| [jvm]  <br>Brief description  <br><br><br>可响应标记<br><br>  <br>Content  <br>interface [Responsive](-responsive/index.md)  <br><br><br>

