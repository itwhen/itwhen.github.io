---
title: Relation -
---
//[echo](../../index.md)/[tech.whence.echo.dal.transfer](../index.md)/[Relation](index.md)



# Relation  
 [jvm] 

关联

data class [Relation](index.md)(**target**: [Setting](../../tech.whence.echo.dal.transfer.project/-setting/index.md), **baseKey**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **relator**: [Relation.Relator](-relator/index.md), **targetKey**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **condition**: [Relation.Condition](-condition/index.md))   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Relation](-relation.md)|  [jvm] <br><br><br><br>fun [Relation](-relation.md)(target: [Setting](../../tech.whence.echo.dal.transfer.project/-setting/index.md), baseKey: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), relator: [Relation.Relator](-relator/index.md), targetKey: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), condition: [Relation.Condition](-condition/index.md))   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>
| [Condition](-condition/index.md)| [jvm]  <br>Brief description  <br><br><br>条件<br><br>  <br>Content  <br>enum [Condition](-condition/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Relation.Condition](-condition/index.md)>   <br><br><br>
| [Relator](-relator/index.md)| [jvm]  <br>Brief description  <br><br><br>关联类型<br><br>  <br>Content  <br>enum [Relator](-relator/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Relation.Relator](-relator/index.md)>   <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [component1](component1.md)| [jvm]  <br>Content  <br>operator fun [component1](component1.md)(): [Setting](../../tech.whence.echo.dal.transfer.project/-setting/index.md)  <br><br><br>
| [component2](component2.md)| [jvm]  <br>Content  <br>operator fun [component2](component2.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [component3](component3.md)| [jvm]  <br>Content  <br>operator fun [component3](component3.md)(): [Relation.Relator](-relator/index.md)  <br><br><br>
| [component4](component4.md)| [jvm]  <br>Content  <br>operator fun [component4](component4.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [component5](component5.md)| [jvm]  <br>Content  <br>operator fun [component5](component5.md)(): [Relation.Condition](-condition/index.md)  <br><br><br>
| [copy](copy.md)| [jvm]  <br>Content  <br>fun [copy](copy.md)(target: [Setting](../../tech.whence.echo.dal.transfer.project/-setting/index.md), baseKey: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), relator: [Relation.Relator](-relator/index.md), targetKey: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), condition: [Relation.Condition](-condition/index.md)): [Relation](index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [baseKey](index.md#tech.whence.echo.dal.transfer/Relation/baseKey/#/PointingToDeclaration/)|  [jvm] <br><br>String 本地字段<br><br>val [baseKey](index.md#tech.whence.echo.dal.transfer/Relation/baseKey/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [condition](index.md#tech.whence.echo.dal.transfer/Relation/condition/#/PointingToDeclaration/)|  [jvm] <br><br>Condition 条件<br><br>val [condition](index.md#tech.whence.echo.dal.transfer/Relation/condition/#/PointingToDeclaration/): [Relation.Condition](-condition/index.md)   <br>
| [relator](index.md#tech.whence.echo.dal.transfer/Relation/relator/#/PointingToDeclaration/)|  [jvm] <br><br>Relator 关联类型<br><br>val [relator](index.md#tech.whence.echo.dal.transfer/Relation/relator/#/PointingToDeclaration/): [Relation.Relator](-relator/index.md)   <br>
| [target](index.md#tech.whence.echo.dal.transfer/Relation/target/#/PointingToDeclaration/)|  [jvm] <br><br>Setting 目标设置<br><br>val [target](index.md#tech.whence.echo.dal.transfer/Relation/target/#/PointingToDeclaration/): [Setting](../../tech.whence.echo.dal.transfer.project/-setting/index.md)   <br>
| [targetKey](index.md#tech.whence.echo.dal.transfer/Relation/targetKey/#/PointingToDeclaration/)|  [jvm] <br><br>String 目标字段<br><br>val [targetKey](index.md#tech.whence.echo.dal.transfer/Relation/targetKey/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>

