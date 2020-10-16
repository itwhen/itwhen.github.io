---
title: Decorator -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.response](../index.md)/[Decorator](index.md)



# Decorator  
 [jvm] 

响应负载修饰器

fun fun interface [Decorator](index.md)<[P](index.md) : [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md), [D](index.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)>   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| D| <br><br>: Entity 实体<br><br>
| P| <br><br>: Payload 负载<br><br>
  


## Functions  
  
|  Name|  Summary| 
|---|---|
| [decorate](decorate.md)| [jvm]  <br>Brief description  <br><br><br>修饰<br><br>  <br>Content  <br>abstract fun [decorate](decorate.md)(payload: [P](index.md), data: [D](index.md))  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [plus](plus.md)| [jvm]  <br>Brief description  <br><br><br>合并<br><br>  <br>Content  <br>open operator fun [plus](plus.md)(decorator: [Decorator](index.md)<[P](index.md), [D](index.md)>): [Decorator](index.md)<[P](index.md), [D](index.md)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Inheritors  
  
|  Name| 
|---|
| [Result](../../tech.whence.echo.rpc.association/-result/index.md)

