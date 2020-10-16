---
title: Invoking -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.api](../index.md)/[Invoking](index.md)



# Invoking  
 [jvm] 

调用

@[Target](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.annotation/-target/index.html)(allowedTargets = [[AnnotationTarget.FUNCTION](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.annotation/-annotation-target/-f-u-n-c-t-i-o-n/index.html)])  
  
annotation class [Invoking](index.md)(**id**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **path**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **location**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **parameters**: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Parameter](../-parameter/index.md)>, **method**: HttpMethod, **target**: [Invoking.Target](-target/index.md), **request**: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md)>, **response**: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md)>, **security**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Invoking](-invoking.md)|  [jvm] <br><br><br><br>fun [Invoking](-invoking.md)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), path: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), location: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), parameters: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Parameter](../-parameter/index.md)>, method: HttpMethod, target: [Invoking.Target](-target/index.md), request: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md)>, response: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md)>, security: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Target](-target/index.md)| [jvm]  <br>Brief description  <br><br><br>操作目标<br><br>  <br>Content  <br>enum [Target](-target/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Invoking.Target](-target/index.md)>   <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [id](index.md#tech.whence.echo.rpc.api/Invoking/id/#/PointingToDeclaration/)|  [jvm] <br><br>String 唯一编号<br><br>val [id](index.md#tech.whence.echo.rpc.api/Invoking/id/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [location](index.md#tech.whence.echo.rpc.api/Invoking/location/#/PointingToDeclaration/)|  [jvm] <br><br>String 位置<br><br>val [location](index.md#tech.whence.echo.rpc.api/Invoking/location/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [method](index.md#tech.whence.echo.rpc.api/Invoking/method/#/PointingToDeclaration/)|  [jvm] <br><br>Method 请求方法<br><br>val [method](index.md#tech.whence.echo.rpc.api/Invoking/method/#/PointingToDeclaration/): HttpMethod   <br>
| [parameters](index.md#tech.whence.echo.rpc.api/Invoking/parameters/#/PointingToDeclaration/)|  [jvm] val [parameters](index.md#tech.whence.echo.rpc.api/Invoking/parameters/#/PointingToDeclaration/): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Parameter](../-parameter/index.md)>   <br>
| [path](index.md#tech.whence.echo.rpc.api/Invoking/path/#/PointingToDeclaration/)|  [jvm] <br><br>String 路径<br><br>val [path](index.md#tech.whence.echo.rpc.api/Invoking/path/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [request](index.md#tech.whence.echo.rpc.api/Invoking/request/#/PointingToDeclaration/)|  [jvm] <br><br>KClass<out Payload> 请求类<br><br>val [request](index.md#tech.whence.echo.rpc.api/Invoking/request/#/PointingToDeclaration/): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md)>   <br>
| [response](index.md#tech.whence.echo.rpc.api/Invoking/response/#/PointingToDeclaration/)|  [jvm] <br><br>KClass<out Payload> 响应类<br><br>val [response](index.md#tech.whence.echo.rpc.api/Invoking/response/#/PointingToDeclaration/): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md)>   <br>
| [security](index.md#tech.whence.echo.rpc.api/Invoking/security/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否要求权限检查<br><br>val [security](index.md#tech.whence.echo.rpc.api/Invoking/security/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [target](index.md#tech.whence.echo.rpc.api/Invoking/target/#/PointingToDeclaration/)|  [jvm] <br><br>Target 操作目标<br><br>val [target](index.md#tech.whence.echo.rpc.api/Invoking/target/#/PointingToDeclaration/): [Invoking.Target](-target/index.md)   <br>

