---
title: Actable -
---
//[echo](../../index.md)/[tech.whence.echo.webclient](../index.md)/[Actable](index.md)



# Actable  
 [jvm] 

行为

interface [Actable](index.md)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [getGateway](get-gateway.md)| [jvm]  <br>Brief description  <br><br><br>根据环境取调用地址<br><br>  <br>Content  <br>abstract fun [getGateway](get-gateway.md)(env: [Environment](../../tech.whence.echo.support/-environment/index.md)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [getPath](get-path.md)| [jvm]  <br>Brief description  <br><br><br>根据环境取调用路径<br><br>  <br>Content  <br>abstract fun [getPath](get-path.md)(env: [Environment](../../tech.whence.echo.support/-environment/index.md)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [getURL](get-u-r-l.md)| [jvm]  <br>Brief description  <br><br><br>根据指定环境/参数获取服务地址<br><br>  <br>Content  <br>open fun [getURL](get-u-r-l.md)(env: [Environment](../../tech.whence.echo.support/-environment/index.md), query: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)?): [URL](https://docs.oracle.com/javase/8/docs/api/java/net/URL.html)  <br><br><br>
| [handle](handle.md)| [jvm]  <br>Brief description  <br><br><br>处理响应<br><br>  <br>Content  <br>open fun [handle](handle.md)(response: [Response](../../tech.whence.echo.webclient.response/-response/index.md)): [Response](../../tech.whence.echo.webclient.response/-response/index.md)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [name](index.md#tech.whence.echo.webclient/Actable/name/#/PointingToDeclaration/)|  [jvm] <br><br>行为名称<br><br>abstract val [name](index.md#tech.whence.echo.webclient/Actable/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>

