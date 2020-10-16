---
title: Column -
---
//[echo](../../index.md)/[tech.whence.echo.support.mongo.querier.component](../index.md)/[Column](index.md)



# Column  
 [jvm] 

字段

class [Column](index.md) : [AbstractAssignment](../../tech.whence.echo.dal.querier.component/-abstract-assignment/index.md)<[Column](index.md)>    


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Column](-column.md)|  [jvm] fun [Column](-column.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?)   <br>
| [Column](-column.md)|  [jvm] fun [Column](-column.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, control: [Assignment.Control](../../tech.whence.echo.dal.querier.component/-assignment/-control/index.md))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [compareTo](../../tech.whence.echo.dal.querier.component/-assignment/compare-to.md)| [jvm]  <br>Content  <br>open operator override fun [compareTo](../../tech.whence.echo.dal.querier.component/-assignment/compare-to.md)(other: [Assignment](../../tech.whence.echo.dal.querier.component/-assignment/index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [equals](equals.md)| [jvm]  <br>Content  <br>open operator override fun [equals](equals.md)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](hash-code.md)| [jvm]  <br>Content  <br>open override fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](to-string.md)| [jvm]  <br>Content  <br>open override fun [toString](to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [control](index.md#tech.whence.echo.support.mongo.querier.component/Column/control/#/PointingToDeclaration/)|  [jvm] <br><br>Control 控制器<br><br>open override val [control](index.md#tech.whence.echo.support.mongo.querier.component/Column/control/#/PointingToDeclaration/): [Assignment.Control](../../tech.whence.echo.dal.querier.component/-assignment/-control/index.md)   <br>
| [name](index.md#tech.whence.echo.support.mongo.querier.component/Column/name/#/PointingToDeclaration/)|  [jvm] <br><br>String 字段名<br><br>open override val [name](index.md#tech.whence.echo.support.mongo.querier.component/Column/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [primitive](index.md#tech.whence.echo.support.mongo.querier.component/Column/primitive/#/PointingToDeclaration/)|  [jvm] <br><br>String 原名<br><br>open override var [primitive](index.md#tech.whence.echo.support.mongo.querier.component/Column/primitive/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [value](index.md#tech.whence.echo.support.mongo.querier.component/Column/value/#/PointingToDeclaration/)|  [jvm] <br><br>Any? 值<br><br>open override val [value](index.md#tech.whence.echo.support.mongo.querier.component/Column/value/#/PointingToDeclaration/): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?   <br>

