---
title: tech.whence.echo.rpc.payload -
---
//[echo](../index.md)/[tech.whence.echo.rpc.payload](index.md)



# Package tech.whence.echo.rpc.payload  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Buffered](-buffered/index.md)| [jvm]  <br>Brief description  <br><br><br>缓冲型负载<br><br>  <br>Content  <br>data class [Buffered](-buffered/index.md)(**data**: Buffer) : [Payload](-payload/index.md)  <br><br><br>
| [Empty](-empty/index.md)| [jvm]  <br>Brief description  <br><br><br>空负载<br><br>  <br>Content  <br>class [Empty](-empty/index.md) : [Payload](-payload/index.md)  <br><br><br>
| [Listed](-listed/index.md)| [jvm]  <br>Brief description  <br><br><br>列表<br><br>  <br>Content  <br>data class [Listed](-listed/index.md)<[T](-listed/index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>(**data**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](-listed/index.md)>) : [Payload](-payload/index.md)  <br><br><br>
| [Mapped](-mapped/index.md)| [jvm]  <br>Brief description  <br><br><br>映射<br><br>  <br>Content  <br>data class [Mapped](-mapped/index.md)<[T](-mapped/index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>(**data**: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [T](-mapped/index.md)>) : [Payload](-payload/index.md)  <br><br><br>
| [Paged](-paged/index.md)| [jvm]  <br>Brief description  <br><br><br>分页型负载<br><br>  <br>Content  <br>data class [Paged](-paged/index.md)<[T](-paged/index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>(**pages**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **page**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **limit**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **total**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **data**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](-paged/index.md)>) : [Payload](-payload/index.md)  <br><br><br>
| [Payload](-payload/index.md)| [jvm]  <br>Brief description  <br><br><br>负载<br><br>  <br>Content  <br>interface [Payload](-payload/index.md) : [Adaptive](../tech.whence.echo.container.accessor/-adaptive/index.md)  <br><br><br>
| [Searching](-searching/index.md)| [jvm]  <br>Brief description  <br><br><br>搜索<br><br>  <br>Content  <br>class [Searching](-searching/index.md)<[T](-searching/index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> : [Payload](-payload/index.md)  <br><br><br>
| [Single](-single/index.md)| [jvm]  <br>Brief description  <br><br><br>单项<br><br>  <br>Content  <br>data class [Single](-single/index.md)<[T](-single/index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>(**data**: [T](-single/index.md)) : [Payload](-payload/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [payloadOf](payload-of.md)| [jvm]  <br>Brief description  <br><br><br>生成负载<br><br>  <br>Content  <br>inline fun <[T](payload-of.md) : [Payload](-payload/index.md)> [payloadOf](payload-of.md)(): [T](payload-of.md)  <br><br><br>
| [searchingOf](searching-of.md)| [jvm]  <br>Brief description  <br><br><br>生成搜索条件<br><br>  <br>Content  <br>inline fun <[T](searching-of.md) : [Payload](-payload/index.md)> [searchingOf](searching-of.md)(consumer: [Consumer](../tech.whence.echo.function/-consumer/index.md)<[T](searching-of.md)>): [T](searching-of.md)  <br><br><br>

