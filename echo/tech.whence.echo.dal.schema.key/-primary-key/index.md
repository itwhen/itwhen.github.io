---
title: PrimaryKey -
---
//[echo](../../index.md)/[tech.whence.echo.dal.schema.key](../index.md)/[PrimaryKey](index.md)



# PrimaryKey  
 [jvm] 

主键字段

class [PrimaryKey](index.md)   


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [check](check.md)| [jvm]  <br>Brief description  <br><br><br>检查指定字段集合 若无主键则跳过 若指定字段未加载则跳过<br><br>  <br>Content  <br>fun [check](check.md)(keys: [Keys](../-keys/index.md))  <br><br><br>[jvm]  <br>Brief description  <br><br><br>检查指定字段集合<br><br>  <br>Content  <br>fun <[E](check.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [check](check.md)(keys: [Keys](../-keys/index.md), entity: [E](check.md))  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [has](has.md)| [jvm]  <br>Brief description  <br><br><br>判断是否存在指定字段<br><br>  <br>Content  <br>fun [has](has.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [identify](identify.md)| [jvm]  <br>Brief description  <br><br><br>鉴定指定实体<br><br>  <br>Content  <br>fun <[E](identify.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [identify](identify.md)(entity: [E](identify.md)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [toString](to-string.md)| [jvm]  <br>Content  <br>open override fun [toString](to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [generate](index.md#tech.whence.echo.dal.schema.key/PrimaryKey/generate/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否数据源内自动创建<br><br>val [generate](index.md#tech.whence.echo.dal.schema.key/PrimaryKey/generate/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [key](index.md#tech.whence.echo.dal.schema.key/PrimaryKey/key/#/PointingToDeclaration/)|  [jvm] <br><br>Key 字段名<br><br>val [key](index.md#tech.whence.echo.dal.schema.key/PrimaryKey/key/#/PointingToDeclaration/): [Key](../-key/index.md)   <br>
| [name](index.md#tech.whence.echo.dal.schema.key/PrimaryKey/name/#/PointingToDeclaration/)|  [jvm] <br><br>String 字段名<br><br>val [name](index.md#tech.whence.echo.dal.schema.key/PrimaryKey/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>

