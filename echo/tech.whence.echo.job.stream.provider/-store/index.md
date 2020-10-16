---
title: Store -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.provider](../index.md)/[Store](index.md)



# Store  
 [jvm] 

消息存储器

class [Store](index.md) : [Container](../../tech.whence.echo.container/-container/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Store](-store.md)|  [jvm] fun [Store](-store.md)()   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [add](add.md)| [jvm]  <br>Brief description  <br><br><br>添加消息 以消息的键做键<br><br>  <br>Content  <br>fun [add](add.md)(message: [Message](../../tech.whence.echo.job.stream.message/-message/index.md))  <br><br><br>
| [clear](clear.md)| [jvm]  <br>Brief description  <br><br><br>清理全部消息<br><br>  <br>Content  <br>fun [clear](clear.md)()  <br><br><br>[jvm]  <br>Brief description  <br><br><br>移除消息<br><br>  <br>Content  <br>fun [clear](clear.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Message](../../tech.whence.echo.job.stream.message/-message/index.md)?  <br>fun [clear](clear.md)(predicate: [Predicate](../../tech.whence.echo.function/-predicate/index.md)<[Message](../../tech.whence.echo.job.stream.message/-message/index.md)>)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [get](get.md)| [jvm]  <br>Brief description  <br><br><br>取全部数据<br><br>  <br>Content  <br>fun [get](get.md)(): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Message](../../tech.whence.echo.job.stream.message/-message/index.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>取消息<br><br>  <br>Content  <br>fun [get](get.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Message](../../tech.whence.echo.job.stream.message/-message/index.md)?  <br><br><br>
| [has](has.md)| [jvm]  <br>Brief description  <br><br><br>判断消息是否存在<br><br>  <br>Content  <br>fun [has](has.md)(message: [Message](../../tech.whence.echo.job.stream.message/-message/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [empty](index.md#tech.whence.echo.job.stream.provider/Store/empty/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 当前容器是否为空<br><br>open override val [empty](index.md#tech.whence.echo.job.stream.provider/Store/empty/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [size](index.md#tech.whence.echo.job.stream.provider/Store/size/#/PointingToDeclaration/)|  [jvm] <br><br>UInt 当前容器总数据量<br><br>open override val [size](index.md#tech.whence.echo.job.stream.provider/Store/size/#/PointingToDeclaration/): [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)   <br>

