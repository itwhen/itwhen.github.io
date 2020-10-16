---
title: Change -
---
//[echo](../../../index.md)/[tech.whence.echo.dal.entity](../../index.md)/[EntityAccessor](../index.md)/[Change](index.md)



# Change  
 [jvm] 

实体变更记录

data class [Change](index.md)<[V](index.md)>(**key**: [Key](../../../tech.whence.echo.dal.schema.key/-key/index.md), **oldValue**: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, **newValue**: [V](index.md)?)   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| V| <br><br>实体类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Change](-change.md)|  [jvm] <br><br><br><br>fun <[V](index.md)> [Change](-change.md)(key: [Key](../../../tech.whence.echo.dal.schema.key/-key/index.md), oldValue: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, newValue: [V](index.md)?)   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [component1](component1.md)| [jvm]  <br>Content  <br>operator fun [component1](component1.md)(): [Key](../../../tech.whence.echo.dal.schema.key/-key/index.md)  <br><br><br>
| [component2](component2.md)| [jvm]  <br>Content  <br>operator fun [component2](component2.md)(): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?  <br><br><br>
| [component3](component3.md)| [jvm]  <br>Content  <br>operator fun [component3](component3.md)(): [V](index.md)?  <br><br><br>
| [copy](copy.md)| [jvm]  <br>Content  <br>fun [copy](copy.md)(key: [Key](../../../tech.whence.echo.dal.schema.key/-key/index.md), oldValue: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, newValue: [V](index.md)?): [EntityAccessor.Change](index.md)<[V](index.md)>  <br><br><br>
| [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [key](index.md#tech.whence.echo.dal.entity/EntityAccessor.Change/key/#/PointingToDeclaration/)|  [jvm] <br><br>Key 字段<br><br>val [key](index.md#tech.whence.echo.dal.entity/EntityAccessor.Change/key/#/PointingToDeclaration/): [Key](../../../tech.whence.echo.dal.schema.key/-key/index.md)   <br>
| [newValue](index.md#tech.whence.echo.dal.entity/EntityAccessor.Change/newValue/#/PointingToDeclaration/)|  [jvm] <br><br>V? 新值<br><br>val [newValue](index.md#tech.whence.echo.dal.entity/EntityAccessor.Change/newValue/#/PointingToDeclaration/): [V](index.md)?   <br>
| [oldValue](index.md#tech.whence.echo.dal.entity/EntityAccessor.Change/oldValue/#/PointingToDeclaration/)|  [jvm] <br><br>Any? 旧值<br><br>val [oldValue](index.md#tech.whence.echo.dal.entity/EntityAccessor.Change/oldValue/#/PointingToDeclaration/): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?   <br>

