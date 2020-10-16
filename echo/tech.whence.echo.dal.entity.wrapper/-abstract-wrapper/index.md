---
title: AbstractWrapper -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity.wrapper](../index.md)/[AbstractWrapper](index.md)



# AbstractWrapper  
 [jvm] 

实体打包器抽象

abstract class [AbstractWrapper](index.md)(**static**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) : [Wrapper](../-wrapper/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [AbstractWrapper](-abstract-wrapper.md)|  [jvm] <br><br><br><br>fun [AbstractWrapper](-abstract-wrapper.md)(static: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [attribute](../-wrapper/attribute.md)| [jvm]  <br>Brief description  <br><br><br>取指定实体属性访问器<br><br>  <br>Content  <br>abstract override fun [attribute](../-wrapper/attribute.md)(entity: [Entity](../../tech.whence.echo.dal.entity/-entity/index.md), attribute: [Attribute](../-attribute/index.md)): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)  <br><br><br>
| [check](check.md)| [jvm]  <br>Brief description  <br><br><br>检查指定实体类型<br><br>  <br>Content  <br>open override fun <[E](check.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [check](check.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [E](check.md)>)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>检查指定实体<br><br>  <br>Content  <br>open override fun <E : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [check](../-wrapper/check.md)(entity: E)  <br><br><br>
| [copy](../-wrapper/copy.md)| [jvm]  <br>Brief description  <br><br><br>复制实体<br><br>  <br>Content  <br>open override fun <E : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [copy](../-wrapper/copy.md)(entity: E): E  <br><br><br>
| [creates](creates.md)| [jvm]  <br>Brief description  <br><br><br>判断是否生成并管理指定字段<br><br>  <br>Content  <br>open override fun [creates](creates.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>判断是否生成了指定实体类型<br><br>  <br>Content  <br>open override fun [creates](creates.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [valuate](valuate.md)| [jvm]  <br>Brief description  <br><br><br>取指定实体指定字段的值 先检查实体有效性 再过滤掉由包装器生成的字段<br><br>  <br>Content  <br>fun <[E](valuate.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [valuate](valuate.md)(entity: [E](valuate.md), key: [Key](../../tech.whence.echo.dal.schema.key/-key/index.md)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?  <br><br><br>
| [wrap](../-wrapper/wrap.md)| [jvm]  <br>Brief description  <br><br><br>打包<br><br>  <br>Content  <br>abstract override fun <E : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [wrap](../-wrapper/wrap.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out E>, keys: [Keys](../../tech.whence.echo.dal.schema.key/-keys/index.md), valuate: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[Key](../../tech.whence.echo.dal.schema.key/-key/index.md), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>): E  <br><br><br>


## Inheritors  
  
|  Name| 
|---|
| [DynamicWrapper](../-dynamic-wrapper/index.md)
| [NoneWrapper](../-none-wrapper/index.md)
| [StaticCglibWrapper](../-static-cglib-wrapper/index.md)

