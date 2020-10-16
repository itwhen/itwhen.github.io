---
title: Operations -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.sample.flow](../index.md)/[Operations](index.md)



# Operations  
 [jvm] 

流程操作的前后节点数据

class [Operations](index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Operations](-operations.md)|  [jvm] fun [Operations](-operations.md)()   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [allow](allow.md)| [jvm]  <br>Brief description  <br><br><br>取节点可执行操作<br><br>  <br>Content  <br>fun [allow](allow.md)(node: [Node](../-node/index.md)): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Operation](../-operation/index.md)>  <br><br><br>
| [attain](attain.md)| [jvm]  <br>Brief description  <br><br><br>判断节点可及<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [attain](attain.md)(operation: [Operation](../-operation/index.md), to: [Node](../-node/index.md), right: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [depend](depend.md)| [jvm]  <br>Brief description  <br><br><br>判断节点可追溯<br><br>  <br>Content  <br>fun [depend](depend.md)(operation: [Operation](../-operation/index.md), from: [Node](../-node/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [set](set.md)| [jvm]  <br>Brief description  <br><br><br>设置操作的前后节点<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [set](set.md)(operation: [Operation](../-operation/index.md), from: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Node](../-node/index.md)>, right: [Node](../-node/index.md)?, left: [Node](../-node/index.md)?): [Operations](index.md)  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [set](set.md)(operation: [Operation](../-operation/index.md), from: [Node](../-node/index.md), right: [Node](../-node/index.md)?, left: [Node](../-node/index.md)?): [Operations](index.md)  <br><br><br>
| [target](target.md)| [jvm]  <br>Brief description  <br><br><br>取目标节点<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [target](target.md)(operation: [Operation](../-operation/index.md), right: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Node](../-node/index.md)?  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

