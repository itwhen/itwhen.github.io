---
title: Wrapper -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity.wrapper](../index.md)/[Wrapper](index.md)



# Wrapper  
 [jvm] 

实体打包器

interface [Wrapper](index.md)   


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [attribute](attribute.md)| [jvm]  <br>Brief description  <br><br><br>取指定实体属性访问器<br><br>  <br>Content  <br>abstract fun [attribute](attribute.md)(entity: [Entity](../../tech.whence.echo.dal.entity/-entity/index.md), attribute: [Attribute](../-attribute/index.md)): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)  <br><br><br>
| [check](check.md)| [jvm]  <br>Brief description  <br><br><br>检查指定实体<br><br>  <br>Content  <br>open fun <[E](check.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [check](check.md)(entity: [E](check.md))  <br><br><br>[jvm]  <br>Brief description  <br><br><br>检查指定实体类型<br><br>  <br>Content  <br>abstract fun <[E](check.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [check](check.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [E](check.md)>)  <br><br><br>
| [copy](copy.md)| [jvm]  <br>Brief description  <br><br><br>复制实体<br><br>  <br>Content  <br>open fun <[E](copy.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [copy](copy.md)(entity: [E](copy.md)): [E](copy.md)  <br><br><br>
| [creates](creates.md)| [jvm]  <br>Brief description  <br><br><br>判断是否生成并管理指定字段<br><br>  <br>Content  <br>abstract fun [creates](creates.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>判断是否生成了指定实体类型<br><br>  <br>Content  <br>abstract fun [creates](creates.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [wrap](wrap.md)| [jvm]  <br>Brief description  <br><br><br>打包<br><br>  <br>Content  <br>abstract fun <[E](wrap.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [wrap](wrap.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [E](wrap.md)>, keys: [Keys](../../tech.whence.echo.dal.schema.key/-keys/index.md), valuate: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[Key](../../tech.whence.echo.dal.schema.key/-key/index.md), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>): [E](wrap.md)  <br><br><br>


## Inheritors  
  
|  Name| 
|---|
| [AbstractWrapper](../-abstract-wrapper/index.md)

