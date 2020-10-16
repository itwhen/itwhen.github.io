---
title: tech.whence.echo.container.constant -
---
//[echo](../index.md)/[tech.whence.echo.container.constant](index.md)



# Package tech.whence.echo.container.constant  


## Types  
  
|  Name|  Summary| 
|---|---|
| [ClassConst](-class-const/index.md)| [jvm]  <br>Brief description  <br><br><br>类常量<br><br>  <br>Content  <br>interface [ClassConst](-class-const/index.md)<[T](-class-const/index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> : [Const](-const/index.md)<[KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [T](-class-const/index.md)>>   <br><br><br>
| [Const](-const/index.md)| [jvm]  <br>Brief description  <br><br><br>常量<br><br>  <br>Content  <br>interface [Const](-const/index.md)<[V](-const/index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> : [Adaptive](../tech.whence.echo.container.accessor/-adaptive/index.md)  <br><br><br>
| [Data](-data/index.md)| [jvm]  <br>Brief description  <br><br><br>常量的值与本身的映射<br><br>  <br>Content  <br>class [Data](-data/index.md)<[V](-data/index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [C](-data/index.md) : [Const](-const/index.md)<[V](-data/index.md)>>(**declarer**: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[C](-data/index.md)>) : [Container](../tech.whence.echo.container/-container/index.md)  <br><br><br>
| [Descriptor](-descriptor/index.md)| [jvm]  <br>Brief description  <br><br><br>常量描述符<br><br>  <br>Content  <br>data class [Descriptor](-descriptor/index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **title**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **items**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Descriptor.Item](-descriptor/-item/index.md)>) : [Payload](../tech.whence.echo.rpc.payload/-payload/index.md)  <br><br><br>
| [IntConst](-int-const/index.md)| [jvm]  <br>Brief description  <br><br><br>整型常量<br><br>  <br>Content  <br>interface [IntConst](-int-const/index.md) : [Const](-const/index.md)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>   <br><br><br>
| [StringConst](-string-const/index.md)| [jvm]  <br>Brief description  <br><br><br>字符串常量<br><br>  <br>Content  <br>interface [StringConst](-string-const/index.md) : [Const](-const/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>   <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [const](const.md)| [jvm]  <br>Brief description  <br><br><br>根据常量生成映射<br><br>  <br>Content  <br>inline fun <[C](const.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[C](const.md)>, [Const](-const/index.md)<[V](const.md)>, [V](const.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [const](const.md)(): [Data](-data/index.md)<[V](const.md), [C](const.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>根据常量类生成映射<br><br>  <br>Content  <br>fun <[C](const.md) : [Const](-const/index.md)<[V](const.md)>, [V](const.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [const](const.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[C](const.md)>): [Data](-data/index.md)<[V](const.md), [C](const.md)>?  <br><br><br>

