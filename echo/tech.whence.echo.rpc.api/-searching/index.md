---
title: Searching -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.api](../index.md)/[Searching](index.md)



# Searching  
 [jvm] 

操作

@[Target](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.annotation/-target/index.html)(allowedTargets = [[AnnotationTarget.FUNCTION](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.annotation/-annotation-target/-f-u-n-c-t-i-o-n/index.html)])  
  
annotation class [Searching](index.md)(**request**: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md)>, **response**: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md)>, **security**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Searching](-searching.md)|  [jvm] <br><br><br><br>fun [Searching](-searching.md)(request: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md)>, response: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md)>, security: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [request](index.md#tech.whence.echo.rpc.api/Searching/request/#/PointingToDeclaration/)|  [jvm] <br><br>KClass<out Payload> 请求类<br><br>val [request](index.md#tech.whence.echo.rpc.api/Searching/request/#/PointingToDeclaration/): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md)>   <br>
| [response](index.md#tech.whence.echo.rpc.api/Searching/response/#/PointingToDeclaration/)|  [jvm] <br><br>KClass<out Payload> 响应类<br><br>val [response](index.md#tech.whence.echo.rpc.api/Searching/response/#/PointingToDeclaration/): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md)>   <br>
| [security](index.md#tech.whence.echo.rpc.api/Searching/security/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否要求权限检查<br><br>val [security](index.md#tech.whence.echo.rpc.api/Searching/security/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>

