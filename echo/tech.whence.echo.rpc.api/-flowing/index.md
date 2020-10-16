---
title: Flowing -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.api](../index.md)/[Flowing](index.md)



# Flowing  
 [jvm] 

流程切换

@[Target](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.annotation/-target/index.html)(allowedTargets = [[AnnotationTarget.FUNCTION](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.annotation/-annotation-target/-f-u-n-c-t-i-o-n/index.html)])  
  
annotation class [Flowing](index.md)(**operation**: [Operation](../../tech.whence.echo.rpc.sample.flow/-operation/index.md), **request**: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md)>, **security**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Flowing](-flowing.md)|  [jvm] <br><br><br><br>fun [Flowing](-flowing.md)(operation: [Operation](../../tech.whence.echo.rpc.sample.flow/-operation/index.md), request: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md)>, security: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [operation](index.md#tech.whence.echo.rpc.api/Flowing/operation/#/PointingToDeclaration/)|  [jvm] <br><br>Operation 操作<br><br>val [operation](index.md#tech.whence.echo.rpc.api/Flowing/operation/#/PointingToDeclaration/): [Operation](../../tech.whence.echo.rpc.sample.flow/-operation/index.md)   <br>
| [request](index.md#tech.whence.echo.rpc.api/Flowing/request/#/PointingToDeclaration/)|  [jvm] <br><br>KClass<out Payload> 请求类<br><br>val [request](index.md#tech.whence.echo.rpc.api/Flowing/request/#/PointingToDeclaration/): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md)>   <br>
| [security](index.md#tech.whence.echo.rpc.api/Flowing/security/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean<br><br>val [security](index.md#tech.whence.echo.rpc.api/Flowing/security/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>

