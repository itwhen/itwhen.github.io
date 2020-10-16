---
title: set -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.sample.flow](../index.md)/[Operations](index.md)/[set](set.md)



# set  
[jvm]  
Brief description  


设置操作的前后节点



#### Return  


Flowing



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| from| <br><br>Set<Node> 来源节点<br><br>
| left| <br><br>Node? 拒绝目标节点<br><br>
| operation| <br><br>Operation 指定操作<br><br>
| right| <br><br>Node? 允许目标节点<br><br>
  
  
Content  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [set](set.md)(operation: [Operation](../-operation/index.md), from: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Node](../-node/index.md)>, right: [Node](../-node/index.md)?, left: [Node](../-node/index.md)?): [Operations](index.md)  


[jvm]  
Brief description  


设置操作的前后节点



#### Return  


Flowing



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| from| <br><br>Node 来源节点<br><br>
| left| <br><br>Node? 拒绝目标节点<br><br>
| operation| <br><br>Operation 指定操作<br><br>
| right| <br><br>Node? 允许目标节点<br><br>
  
  
Content  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [set](set.md)(operation: [Operation](../-operation/index.md), from: [Node](../-node/index.md), right: [Node](../-node/index.md)?, left: [Node](../-node/index.md)?): [Operations](index.md)  



