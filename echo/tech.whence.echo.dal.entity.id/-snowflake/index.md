---
title: Snowflake -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity.id](../index.md)/[Snowflake](index.md)



# Snowflake  
 [jvm] 

Twitter Snowflake 分布式ID算法

class [Snowflake](index.md)(**datacenterId**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **workerId**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **sequence**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **epoch**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **datacenterIdBits**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **workerIdBits**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **sequenceBits**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) : [Identifier](../-identifier/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Snowflake](-snowflake.md)|  [jvm] <br><br><br><br>fun [Snowflake](-snowflake.md)(datacenterId: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), workerId: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), sequence: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), epoch: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), datacenterIdBits: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), workerIdBits: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), sequenceBits: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [next](next.md)| [jvm]  <br>Brief description  <br><br><br>取下一个编号 32进制 大写<br><br>  <br>Content  <br>open override fun [next](next.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [nextId](next-id.md)| [jvm]  <br>Brief description  <br><br><br>取下一个编号 数字格式<br><br>  <br>Content  <br>@[Synchronized](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-synchronized/index.html)()  <br>  <br>fun [nextId](next-id.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

