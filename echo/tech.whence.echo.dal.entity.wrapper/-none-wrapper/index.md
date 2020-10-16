---
title: NoneWrapper -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity.wrapper](../index.md)/[NoneWrapper](index.md)



# NoneWrapper  
 [jvm] 

空打包器

class [NoneWrapper](index.md) : [AbstractWrapper](../-abstract-wrapper/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [NoneWrapper](-none-wrapper.md)|  [jvm] fun [NoneWrapper](-none-wrapper.md)()   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [attribute](attribute.md)| [jvm]  <br>Brief description  <br><br><br>取指定实体属性访问器<br><br>  <br>Content  <br>open override fun [attribute](attribute.md)(entity: [Entity](../../tech.whence.echo.dal.entity/-entity/index.md), attribute: [Attribute](../-attribute/index.md)): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)  <br><br><br>
| [check](../-abstract-wrapper/check.md)| [jvm]  <br>Brief description  <br><br><br>检查指定实体类型<br><br>  <br>Content  <br>open override fun <E : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [check](../-abstract-wrapper/check.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out E>)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>检查指定实体<br><br>  <br>Content  <br>open override fun <E : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [check](../-wrapper/check.md)(entity: E)  <br><br><br>
| [copy](../-wrapper/copy.md)| [jvm]  <br>Brief description  <br><br><br>复制实体<br><br>  <br>Content  <br>open override fun <E : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [copy](../-wrapper/copy.md)(entity: E): E  <br><br><br>
| [creates](../-abstract-wrapper/creates.md)| [jvm]  <br>Brief description  <br><br><br>判断是否生成并管理指定字段<br><br>  <br>Content  <br>open override fun [creates](../-abstract-wrapper/creates.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>判断是否生成了指定实体类型<br><br>  <br>Content  <br>open override fun [creates](../-abstract-wrapper/creates.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [valuate](../-abstract-wrapper/valuate.md)| [jvm]  <br>Brief description  <br><br><br>取指定实体指定字段的值 先检查实体有效性 再过滤掉由包装器生成的字段<br><br>  <br>Content  <br>override fun <E : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [valuate](../-abstract-wrapper/valuate.md)(entity: E, key: [Key](../../tech.whence.echo.dal.schema.key/-key/index.md)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?  <br><br><br>
| [wrap](wrap.md)| [jvm]  <br>Brief description  <br><br><br>打包<br><br>  <br>Content  <br>open override fun <[E](wrap.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [wrap](wrap.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [E](wrap.md)>, keys: [Keys](../../tech.whence.echo.dal.schema.key/-keys/index.md), valuate: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[Key](../../tech.whence.echo.dal.schema.key/-key/index.md), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>): [E](wrap.md)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [static](index.md#tech.whence.echo.dal.entity.wrapper/NoneWrapper/static/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否是静态实体<br><br>override val [static](index.md#tech.whence.echo.dal.entity.wrapper/NoneWrapper/static/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>

