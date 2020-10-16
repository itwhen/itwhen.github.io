---
title: Criterion -
---
//[echo](../../index.md)/[tech.whence.echo.dal.querier.component](../index.md)/[Criterion](index.md)



# Criterion  
 [jvm] 

操作

abstract class [Criterion](index.md)<[T](index.md), [A](index.md) : [Assignment](../-assignment/index.md), [P](index.md)>(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **value**: [T](index.md))   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| A| <br><br>赋值类型<br><br>
| T| <br><br>值类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Criterion](-criterion.md)|  [jvm] <br><br><br><br>fun <[T](index.md)> [Criterion](-criterion.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, value: [T](index.md))   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Chain](-chain/index.md)| [jvm]  <br>Brief description  <br><br><br>约束链<br><br>  <br>Content  <br>interface [Chain](-chain/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [describe](describe.md)| [jvm]  <br>Brief description  <br><br><br>描述当前操作字段及其值<br><br>  <br>Content  <br>abstract fun [describe](describe.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [prepare](prepare.md)| [jvm]  <br>Brief description  <br><br><br>准备预备查询字符串及其赋值<br><br>  <br>Content  <br>abstract fun [prepare](prepare.md)(): [P](index.md)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [index](index.md#tech.whence.echo.dal.querier.component/Criterion/index/#/PointingToDeclaration/)|  [jvm] <br><br>序号<br><br>var [index](index.md#tech.whence.echo.dal.querier.component/Criterion/index/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>
| [name](index.md#tech.whence.echo.dal.querier.component/Criterion/name/#/PointingToDeclaration/)|  [jvm] <br><br>String? 字段名<br><br>open val [name](index.md#tech.whence.echo.dal.querier.component/Criterion/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [value](index.md#tech.whence.echo.dal.querier.component/Criterion/value/#/PointingToDeclaration/)|  [jvm] <br><br>T 相关值<br><br>open val [value](index.md#tech.whence.echo.dal.querier.component/Criterion/value/#/PointingToDeclaration/): [T](index.md)   <br>


## Inheritors  
  
|  Name| 
|---|
| [Criterion](../../tech.whence.echo.support.jdbc.querier.component/-criterion/index.md)
| [Criterion](../../tech.whence.echo.support.mongo.querier.component/-criterion/index.md)

