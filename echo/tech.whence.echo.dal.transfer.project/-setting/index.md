---
title: Setting -
---
//[echo](../../index.md)/[tech.whence.echo.dal.transfer.project](../index.md)/[Setting](index.md)



# Setting  
 [jvm] 

设置

interface [Setting](index.md)   


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [createDAO](create-d-a-o.md)| [jvm]  <br>Brief description  <br><br><br>创建数据层<br><br>  <br>Content  <br>abstract fun [createDAO](create-d-a-o.md)(mode: [Mode](../../tech.whence.echo.dal.transfer/-mode/index.md), direction: [Direction](../../tech.whence.echo.dal.transfer.node/-direction/index.md)): [Dao](../../tech.whence.echo.dal.dao/-dao/index.md)<[Record](../../tech.whence.echo.dal.entity/-record/index.md), *, *>  <br><br><br>
| [createNode](create-node.md)| [jvm]  <br>Brief description  <br><br><br>创建节点<br><br>  <br>Content  <br>abstract fun [createNode](create-node.md)(mode: [Mode](../../tech.whence.echo.dal.transfer/-mode/index.md)): [Node](../../tech.whence.echo.dal.transfer.node/-node/index.md)<out [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [relate](relate.md)| [jvm]  <br>Brief description  <br><br><br>关联<br><br>  <br>Content  <br>abstract fun [relate](relate.md)(mode: [Mode](../../tech.whence.echo.dal.transfer/-mode/index.md)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Relation](../../tech.whence.echo.dal.transfer/-relation/index.md)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [name](index.md#tech.whence.echo.dal.transfer.project/Setting/name/#/PointingToDeclaration/)|  [jvm] <br><br>String 名称<br><br>abstract val [name](index.md#tech.whence.echo.dal.transfer.project/Setting/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [traceable](index.md#tech.whence.echo.dal.transfer.project/Setting/traceable/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否可跟踪<br><br>abstract val [traceable](index.md#tech.whence.echo.dal.transfer.project/Setting/traceable/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>

