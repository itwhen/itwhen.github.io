---
title: Annotator -
---
//[echo](../../index.md)/[tech.whence.echo.dal.schema](../index.md)/[Annotator](index.md)



# Annotator  
 [jvm] 

注解器

class [Annotator](index.md)<[T](index.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)>(**builder**: [Builder](../-builder/index.md)<[T](index.md)>)   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| T| <br><br>: Entity 实体类<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Annotator](-annotator.md)|  [jvm] <br><br><br><br>fun <[T](index.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [Annotator](-annotator.md)(builder: [Builder](../-builder/index.md)<[T](index.md)>)   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [parse](parse.md)| [jvm]  <br>Brief description  <br><br><br>解析类注解 表名定义及键名重命名注解<br><br>  <br>Content  <br>fun [parse](parse.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[T](index.md)>): [Annotator](index.md)<[T](index.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>解析字段集合注解 主键定义及其他注解<br><br>  <br>Content  <br>fun [parse](parse.md)(keys: [Keys](../../tech.whence.echo.dal.schema.key/-keys/index.md)): [Annotator](index.md)<[T](index.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>解析指定字段注解<br><br>  <br>Content  <br>fun [parse](parse.md)(key: [Key](../../tech.whence.echo.dal.schema.key/-key/index.md), annotation: [Annotation](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-annotation/index.html)): [Annotator](index.md)<[T](index.md)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

