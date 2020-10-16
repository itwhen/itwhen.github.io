---
title: Entity -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity](../index.md)/[Entity](index.md)



# Entity  
 [jvm] 

实体接口

interface [Entity](index.md) : [Readable](../../tech.whence.echo.container.accessor/-readable/index.md), [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [access](access.md)| [jvm]  <br>Brief description  <br><br><br>转换<br><br>  <br>Content  <br>open override fun [access](access.md)(): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>使用多个策略将实体转换为字段键值映射 获取实体中实际字段数据及附加数据 再针对字段值的不同类型分别处理 再应用策略处理<br><br>  <br>Content  <br>open fun [access](access.md)(strategist: [Strategist](../../tech.whence.echo.strategy/-strategist/index.md)): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [into](into.md)| [jvm]  <br>Brief description  <br><br><br>转换为指定类型<br><br>  <br>Content  <br>open fun <[T](into.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [into](into.md)(declarer: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[T](into.md)>): [T](into.md)  <br>open fun <[T](into.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [into](into.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[T](into.md)>): [T](into.md)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Inheritors  
  
|  Name| 
|---|
| [Record](../-record/index.md)
| [Resource](../../tech.whence.echo.rpc.sample.resource/-resource/index.md)


## Extensions  
  
|  Name|  Summary| 
|---|---|
| [get](../get.md)| [jvm]  <br>Brief description  <br><br><br>实体取值操作<br><br>  <br>Content  <br>operator fun [Entity](index.md).[get](../get.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?  <br><br><br>
| [set](../set.md)| [jvm]  <br>Brief description  <br><br><br>实体赋值操作<br><br>  <br>Content  <br>operator fun [Entity](index.md).[set](../set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?)  <br><br><br>

