---
title: AbstractAssignment -
---
//[echo](../../index.md)/[tech.whence.echo.dal.querier.component](../index.md)/[AbstractAssignment](index.md)



# AbstractAssignment  
 [jvm] 

抽象赋值作业

abstract class [AbstractAssignment](index.md)<[A](index.md) : [AbstractAssignment](index.md)<[A](index.md)>>(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **value**: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, **control**: [Assignment.Control](../-assignment/-control/index.md), **primitive**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [Assignment](../-assignment/index.md)   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| A| <br><br>子类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [AbstractAssignment](-abstract-assignment.md)|  [jvm] <br><br><br><br>fun [AbstractAssignment](-abstract-assignment.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, control: [Assignment.Control](../-assignment/-control/index.md), primitive: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [compareTo](../-assignment/compare-to.md)| [jvm]  <br>Content  <br>open operator override fun [compareTo](../-assignment/compare-to.md)(other: [Assignment](../-assignment/index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [control](index.md#tech.whence.echo.dal.querier.component/AbstractAssignment/control/#/PointingToDeclaration/)|  [jvm] <br><br>Control 控制器<br><br>open override val [control](index.md#tech.whence.echo.dal.querier.component/AbstractAssignment/control/#/PointingToDeclaration/): [Assignment.Control](../-assignment/-control/index.md)   <br>
| [name](index.md#tech.whence.echo.dal.querier.component/AbstractAssignment/name/#/PointingToDeclaration/)|  [jvm] <br><br>String 字段名<br><br>open override val [name](index.md#tech.whence.echo.dal.querier.component/AbstractAssignment/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [primitive](index.md#tech.whence.echo.dal.querier.component/AbstractAssignment/primitive/#/PointingToDeclaration/)|  [jvm] <br><br>String 原名<br><br>open override var [primitive](index.md#tech.whence.echo.dal.querier.component/AbstractAssignment/primitive/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [value](index.md#tech.whence.echo.dal.querier.component/AbstractAssignment/value/#/PointingToDeclaration/)|  [jvm] <br><br>Any? 值<br><br>open override val [value](index.md#tech.whence.echo.dal.querier.component/AbstractAssignment/value/#/PointingToDeclaration/): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?   <br>


## Inheritors  
  
|  Name| 
|---|
| [Column](../../tech.whence.echo.support.jdbc.querier.component/-column/index.md)
| [Column](../../tech.whence.echo.support.mongo.querier.component/-column/index.md)

