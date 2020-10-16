---
title: Switching -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.api](../index.md)/[Switching](index.md)



# Switching  
 [jvm] 

开关

@[Target](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.annotation/-target/index.html)(allowedTargets = [[AnnotationTarget.FUNCTION](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.annotation/-annotation-target/-f-u-n-c-t-i-o-n/index.html)])  
  
annotation class [Switching](index.md)(**state**: [Switching.State](-state/index.md), **type**: [Switching.Type](-type/index.md), **security**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Switching](-switching.md)|  [jvm] <br><br><br><br>fun [Switching](-switching.md)(state: [Switching.State](-state/index.md), type: [Switching.Type](-type/index.md), security: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [State](-state/index.md)| [jvm]  <br>Brief description  <br><br><br>状态<br><br>  <br>Content  <br>enum [State](-state/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Switching.State](-state/index.md)>   <br><br><br>
| [Type](-type/index.md)| [jvm]  <br>Brief description  <br><br><br>类型<br><br>  <br>Content  <br>enum [Type](-type/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Switching.Type](-type/index.md)>   <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [security](index.md#tech.whence.echo.rpc.api/Switching/security/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否要求权限检查<br><br>val [security](index.md#tech.whence.echo.rpc.api/Switching/security/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [state](index.md#tech.whence.echo.rpc.api/Switching/state/#/PointingToDeclaration/)|  [jvm] <br><br>State 状态<br><br>val [state](index.md#tech.whence.echo.rpc.api/Switching/state/#/PointingToDeclaration/): [Switching.State](-state/index.md)   <br>
| [type](index.md#tech.whence.echo.rpc.api/Switching/type/#/PointingToDeclaration/)|  [jvm] <br><br>Type 开关类型<br><br>val [type](index.md#tech.whence.echo.rpc.api/Switching/type/#/PointingToDeclaration/): [Switching.Type](-type/index.md)   <br>

