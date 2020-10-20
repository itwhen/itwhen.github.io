---
title: Scope -
---
//[echo](../../index.md)/[tech.whence.echo.dal.transfer.cell](../index.md)/[Scope](index.md)



# Scope  
 [jvm] 

范围

interface [Scope](index.md)<[T](index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| T| <br><br>: Serializable 数值类型<br><br>
  


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [split](split.md)| [jvm]  <br>Brief description  <br><br><br>切分<br><br>  <br>Content  <br>abstract fun [split](split.md)(root: [Root](../../tech.whence.echo.dal.transfer.node/-root/index.md)<*, *>, direction: [Direction](../../tech.whence.echo.dal.transfer.node/-direction/index.md), size: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Querier](../-querier/index.md)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [max](index.md#tech.whence.echo.dal.transfer.scope/Scope/max/#/PointingToDeclaration/)|  [jvm] <br><br>T? 最大值<br><br>abstract var [max](index.md#tech.whence.echo.dal.transfer.scope/Scope/max/#/PointingToDeclaration/): [T](index.md)?   <br>
| [min](index.md#tech.whence.echo.dal.transfer.scope/Scope/min/#/PointingToDeclaration/)|  [jvm] <br><br>T? 最小值<br><br>abstract var [min](index.md#tech.whence.echo.dal.transfer.scope/Scope/min/#/PointingToDeclaration/): [T](index.md)?   <br>


## Inheritors  
  
|  Name| 
|---|
| [DateScope](../-date-scope/index.md)
| [NumberScope](../-number-scope/index.md)

