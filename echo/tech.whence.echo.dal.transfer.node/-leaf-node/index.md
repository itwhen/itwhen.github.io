---
title: LeafNode -
---
//[echo](../../index.md)/[tech.whence.echo.dal.transfer.node](../index.md)/[LeafNode](index.md)



# LeafNode  
 [jvm] 

子节点

interface [LeafNode](index.md)<[PK](index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)> : [ChildNode](../-child-node/index.md)<[PK](index.md)>    


## Functions  
  
|  Name|  Summary| 
|---|---|
| [count](../-node/count.md)| [jvm]  <br>Brief description  <br><br><br>计数<br><br>  <br>Content  <br>abstract suspend override fun [count](../-node/count.md)(direction: [Direction](../-direction/index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [name](../../tech.whence.echo.definition/-namer/name.md)| [jvm]  <br>Brief description  <br><br><br>名称<br><br>  <br>Content  <br>abstract override fun [name](../../tech.whence.echo.definition/-namer/name.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [preconnect](../-node/preconnect.md)| [jvm]  <br>Brief description  <br><br><br>预连接数据源<br><br>  <br>Content  <br>abstract override fun [preconnect](../-node/preconnect.md)(mode: [Mode](../../tech.whence.echo.dal.transfer/-mode/index.md), direction: [Direction](../-direction/index.md), connection: [ConnectionString](../../tech.whence.echo.dal.connection/-connection-string/index.md))  <br><br><br>
| [read](read.md)| [jvm]  <br>Brief description  <br><br><br>读取数据<br><br>  <br>Content  <br>abstract suspend fun [read](read.md)(direction: [Direction](../-direction/index.md), key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), values: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>): [Records](../../tech.whence.echo.dal.entity/index.md#tech.whence.echo.dal.entity/Records///PointingToDeclaration/)  <br>abstract suspend override fun [read](../-node/read.md)(direction: [Direction](../-direction/index.md), relation: [Relation](../../tech.whence.echo.dal.transfer/-relation/index.md), batch: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[PK](index.md)>): [Records](../../tech.whence.echo.dal.entity/index.md#tech.whence.echo.dal.entity/Records///PointingToDeclaration/)  <br><br><br>
| [redefine](../-node/redefine.md)| [jvm]  <br>Brief description  <br><br><br>加载数据源结构<br><br>  <br>Content  <br>abstract suspend override fun [redefine](../-node/redefine.md)(direction: [Direction](../-direction/index.md))  <br><br><br>
| [remove](remove.md)| [jvm]  <br>Brief description  <br><br><br>删除数据<br><br>  <br>Content  <br>abstract suspend fun [remove](remove.md)(direction: [Direction](../-direction/index.md), key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), values: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [root](../-node/root.md)| [jvm]  <br>Brief description  <br><br><br>转化为根节点<br><br>  <br>Content  <br>open override fun [root](../-node/root.md)(): [Root](../-root/index.md)<[Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), [Scope](../../tech.whence.echo.dal.transfer.scope/-scope/index.md)<[Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>>  <br><br><br>
| [schematize](../-node/schematize.md)| [jvm]  <br>Brief description  <br><br><br>取数据表<br><br>  <br>Content  <br>abstract override fun [schematize](../-node/schematize.md)(direction: [Direction](../-direction/index.md)): [Schema](../../tech.whence.echo.dal.schema/-schema/index.md)<[Record](../../tech.whence.echo.dal.entity/-record/index.md)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [write](../-node/write.md)| [jvm]  <br>Brief description  <br><br><br>写数据<br><br>  <br>Content  <br>abstract suspend override fun [write](../-node/write.md)(direction: [Direction](../-direction/index.md), data: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Record](../../tech.whence.echo.dal.entity/-record/index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br>abstract suspend override fun [write](../-node/write.md)(direction: [Direction](../-direction/index.md), data: [Record](../../tech.whence.echo.dal.entity/-record/index.md), update: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [location](index.md#tech.whence.echo.dal.transfer.node/LeafNode/location/#/PointingToDeclaration/)|  [jvm] <br><br>Location 定位<br><br>open override val [location](index.md#tech.whence.echo.dal.transfer.node/LeafNode/location/#/PointingToDeclaration/): [Location](../-location/index.md)   <br>
| [mode](index.md#tech.whence.echo.dal.transfer.node/LeafNode/mode/#/PointingToDeclaration/)|  [jvm] <br><br>Mode 模式<br><br>abstract override val [mode](index.md#tech.whence.echo.dal.transfer.node/LeafNode/mode/#/PointingToDeclaration/): [Mode](../../tech.whence.echo.dal.transfer/-mode/index.md)   <br>
| [setting](index.md#tech.whence.echo.dal.transfer.node/LeafNode/setting/#/PointingToDeclaration/)|  [jvm] <br><br>Setting 设置<br><br>abstract override val [setting](index.md#tech.whence.echo.dal.transfer.node/LeafNode/setting/#/PointingToDeclaration/): [Setting](../../tech.whence.echo.dal.transfer.project/-setting/index.md)   <br>
| [sourceChanged](index.md#tech.whence.echo.dal.transfer.node/LeafNode/sourceChanged/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 数据表是否变化<br><br>open override val [sourceChanged](index.md#tech.whence.echo.dal.transfer.node/LeafNode/sourceChanged/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>


## Inheritors  
  
|  Name| 
|---|
| [AbstractLeafNode](../-abstract-leaf-node/index.md)

