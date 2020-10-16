---
title: tech.whence.echo.dal.entity -
---
//[echo](../index.md)/[tech.whence.echo.dal.entity](index.md)



# Package tech.whence.echo.dal.entity  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Entities](-entities/index.md)| [jvm]  <br>Brief description  <br><br><br>实体集合<br><br>  <br>Content  <br>open class [Entities](-entities/index.md)<[T](-entities/index.md) : [Entity](-entity/index.md)>(**data**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](-entities/index.md)>) : [Container](../tech.whence.echo.container/-container/index.md), [Sequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.sequences/-sequence/index.html)<[T](-entities/index.md)>   <br><br><br>
| [Entity](-entity/index.md)| [jvm]  <br>Brief description  <br><br><br>实体接口<br><br>  <br>Content  <br>interface [Entity](-entity/index.md) : [Readable](../tech.whence.echo.container.accessor/-readable/index.md), [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)  <br><br><br>
| [EntityAccessor](-entity-accessor/index.md)| [jvm]  <br>Brief description  <br><br><br>实体访问器<br><br>  <br>Content  <br>object [EntityAccessor](-entity-accessor/index.md)  <br><br><br>
| [EntityMapper](-entity-mapper/index.md)| [jvm]  <br>Brief description  <br><br><br>实体转换器<br><br>  <br>Content  <br>object [EntityMapper](-entity-mapper/index.md)  <br><br><br>
| [InoperableException](-inoperable-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>实体无法操作<br><br>  <br>Content  <br>class [InoperableException](-inoperable-exception/index.md)(**message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **cause**: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)?) : [IllegalStateException](https://docs.oracle.com/javase/8/docs/api/java/lang/IllegalStateException.html)  <br><br><br>
| [Instantiator](-instantiator/index.md)| [jvm]  <br>Brief description  <br><br><br>实例化器<br><br>  <br>Content  <br>interface [Instantiator](-instantiator/index.md)<[D](-instantiator/index.md), [E](-instantiator/index.md) : [Entity](-entity/index.md)>  <br><br><br>
| [Record](-record/index.md)| [jvm]  <br>Brief description  <br><br><br>动态实体<br><br>  <br>Content  <br>data class [Record](-record/index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **keys**: [Keys](../tech.whence.echo.dal.schema.key/-keys/index.md), **data**: [Accessor](../tech.whence.echo.container.accessor/-accessor/index.md), **fillable**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) : [Entity](-entity/index.md), [Accessibility](../tech.whence.echo.container/-accessibility/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> , [Container](../tech.whence.echo.container/-container/index.md)  <br><br><br>
| [Records](index.md#tech.whence.echo.dal.entity/Records///PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>动态实体集合<br><br>  <br>Content  <br>typealias [Records](index.md#tech.whence.echo.dal.entity/Records///PointingToDeclaration/) = [Entities](-entities/index.md)<[Record](-record/index.md)>  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [box](box.md)| [jvm]  <br>Brief description  <br><br><br>封装<br><br>  <br>Content  <br>fun <[T](box.md) : [Entity](-entity/index.md)> [Iterable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)<[T](box.md)>.[box](box.md)(): [Entities](-entities/index.md)<[T](box.md)>  <br>fun <[T](box.md) : [Entity](-entity/index.md)> [Sequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.sequences/-sequence/index.html)<[T](box.md)>.[box](box.md)(): [Entities](-entities/index.md)<[T](box.md)>  <br><br><br>
| [entityOf](entity-of.md)| [jvm]  <br>Brief description  <br><br><br>生成实体<br><br>  <br>Content  <br>inline fun <[T](entity-of.md) : [Entity](-entity/index.md)> [entityOf](entity-of.md)(init: [Consumer](../tech.whence.echo.function/-consumer/index.md)<[T](entity-of.md)>?): [T](entity-of.md)  <br><br><br>
| [get](get.md)| [jvm]  <br>Brief description  <br><br><br>实体取值操作<br><br>  <br>Content  <br>operator fun [Entity](-entity/index.md).[get](get.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?  <br><br><br>
| [set](set.md)| [jvm]  <br>Brief description  <br><br><br>实体赋值操作<br><br>  <br>Content  <br>operator fun [Entity](-entity/index.md).[set](set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?)  <br><br><br>

