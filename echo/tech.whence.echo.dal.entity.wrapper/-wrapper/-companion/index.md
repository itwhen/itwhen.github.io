---
title: Companion -
---
//[echo](../../../index.md)/[tech.whence.echo.dal.entity.wrapper](../../index.md)/[Wrapper](../index.md)/[Companion](index.md)



# Companion  
 [jvm] object [Companion](index.md)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [lookup](lookup.md)| [jvm]  <br>Brief description  <br><br><br>寻找可服务指定实体的打包器<br><br>  <br>Content  <br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  <br>  <br>fun <[E](lookup.md) : [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md)> [lookup](lookup.md)(entity: [E](lookup.md)): [Wrapper](../index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>寻找可服务指定实体类型的打包器<br><br>  <br>Content  <br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  <br>  <br>fun <[E](lookup.md) : [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md)> [lookup](lookup.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [E](lookup.md)>): [Wrapper](../index.md)  <br><br><br>
| [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [wrap](wrap.md)| [jvm]  <br>Brief description  <br><br><br>打包实体 若无需打包则复制指定实体 若已正确打包过则返回指定实体<br><br>  <br>Content  <br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  <br>  <br>fun <[E](wrap.md) : [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md)> [wrap](wrap.md)(entity: [E](wrap.md)): [E](wrap.md)?  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [NONE](index.md#tech.whence.echo.dal.entity.wrapper/Wrapper.Companion/NONE/#/PointingToDeclaration/)|  [jvm] <br><br>空打包器<br><br>val [NONE](index.md#tech.whence.echo.dal.entity.wrapper/Wrapper.Companion/NONE/#/PointingToDeclaration/): [Wrapper](../index.md)   <br>

