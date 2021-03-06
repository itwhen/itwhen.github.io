---
title: AbstractNode -
---
//[echo](../../index.md)/[tech.whence.echo.dal.transfer.node](../index.md)/[AbstractNode](index.md)



# AbstractNode  
 [jvm] 

抽象节点

abstract class [AbstractNode](index.md)<[D](index.md) : [Dao](../../tech.whence.echo.dal.dao/-dao/index.md)<[Record](../../tech.whence.echo.dal.entity/-record/index.md), [PK](index.md), *>, [Queriable](../../tech.whence.echo.dal.dao/-queriable/index.md)<[Record](../../tech.whence.echo.dal.entity/-record/index.md), *, *, *, [QR](index.md), *, *, *, *, *>, [QR](index.md) : [Retriever](../../tech.whence.echo.dal.querier/-retriever/index.md)<[QR](index.md), [R](index.md), *, *, *>, [R](index.md) : [Restrictor](../../tech.whence.echo.dal.querier.component/-restrictor/index.md)<[R](index.md), [R](index.md), *, *>, [PK](index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>(**vertx**: Vertx, **setting**: [Setting](../../tech.whence.echo.dal.transfer.project/-setting/index.md), **mode**: [Mode](../../tech.whence.echo.dal.transfer/-mode/index.md)) : [Node](../-node/index.md)<[PK](index.md)>    


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| D| <br><br>数据层类型<br><br>
| PK| <br><br>主键类型<br><br>
| QR| <br><br>查询器类型<br><br>
| R| <br><br>查询条件类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [AbstractNode](-abstract-node.md)|  [jvm] <br><br><br><br>fun [AbstractNode](-abstract-node.md)(vertx: Vertx, setting: [Setting](../../tech.whence.echo.dal.transfer.project/-setting/index.md), mode: [Mode](../../tech.whence.echo.dal.transfer/-mode/index.md))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [count](count.md)| [jvm]  <br>Brief description  <br><br><br>计数<br><br>  <br>Content  <br>open suspend override fun [count](count.md)(direction: [Direction](../-direction/index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [name](name.md)| [jvm]  <br>Brief description  <br><br><br>名称<br><br>  <br>Content  <br>open override fun [name](name.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [preconnect](preconnect.md)| [jvm]  <br>Brief description  <br><br><br>预连接数据源<br><br>  <br>Content  <br>open override fun [preconnect](preconnect.md)(mode: [Mode](../../tech.whence.echo.dal.transfer/-mode/index.md), direction: [Direction](../-direction/index.md), connection: [ConnectionString](../../tech.whence.echo.dal.connection/-connection-string/index.md))  <br><br><br>
| [read](read.md)| [jvm]  <br>Brief description  <br><br><br>读取数据<br><br>  <br>Content  <br>open suspend override fun [read](read.md)(direction: [Direction](../-direction/index.md), relation: [Relation](../../tech.whence.echo.dal.transfer/-relation/index.md), batch: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[PK](index.md)>): [Records](../../tech.whence.echo.dal.entity/index.md#tech.whence.echo.dal.entity/Records///PointingToDeclaration/)  <br><br><br>
| [redefine](redefine.md)| [jvm]  <br>Brief description  <br><br><br>加载数据源结构<br><br>  <br>Content  <br>open suspend override fun [redefine](redefine.md)(direction: [Direction](../-direction/index.md))  <br><br><br>
| [root](../-node/root.md)| [jvm]  <br>Brief description  <br><br><br>转化为根节点<br><br>  <br>Content  <br>open override fun [root](../-node/root.md)(): [Root](../-root/index.md)<[Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), [Scope](../../tech.whence.echo.dal.transfer.scope/-scope/index.md)<[Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>>  <br><br><br>
| [schematize](schematize.md)| [jvm]  <br>Brief description  <br><br><br>取数据表<br><br>  <br>Content  <br>open override fun [schematize](schematize.md)(direction: [Direction](../-direction/index.md)): [Schema](../../tech.whence.echo.dal.schema/-schema/index.md)<[Record](../../tech.whence.echo.dal.entity/-record/index.md)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [write](write.md)| [jvm]  <br>Brief description  <br><br><br>写数据<br><br>  <br>Content  <br>open suspend override fun [write](write.md)(direction: [Direction](../-direction/index.md), data: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Record](../../tech.whence.echo.dal.entity/-record/index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br>open suspend override fun [write](write.md)(direction: [Direction](../-direction/index.md), data: [Record](../../tech.whence.echo.dal.entity/-record/index.md), update: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [location](index.md#tech.whence.echo.dal.transfer.node/AbstractNode/location/#/PointingToDeclaration/)|  [jvm] <br><br>Location 定位<br><br>abstract override val [location](index.md#tech.whence.echo.dal.transfer.node/AbstractNode/location/#/PointingToDeclaration/): [Location](../-location/index.md)   <br>
| [mode](index.md#tech.whence.echo.dal.transfer.node/AbstractNode/mode/#/PointingToDeclaration/)|  [jvm] <br><br>Mode 模式<br><br>open override val [mode](index.md#tech.whence.echo.dal.transfer.node/AbstractNode/mode/#/PointingToDeclaration/): [Mode](../../tech.whence.echo.dal.transfer/-mode/index.md)   <br>
| [setting](index.md#tech.whence.echo.dal.transfer.node/AbstractNode/setting/#/PointingToDeclaration/)|  [jvm] <br><br>Setting 配置<br><br>open override val [setting](index.md#tech.whence.echo.dal.transfer.node/AbstractNode/setting/#/PointingToDeclaration/): [Setting](../../tech.whence.echo.dal.transfer.project/-setting/index.md)   <br>
| [sourceChanged](index.md#tech.whence.echo.dal.transfer.node/AbstractNode/sourceChanged/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 数据表是否变化<br><br>open override val [sourceChanged](index.md#tech.whence.echo.dal.transfer.node/AbstractNode/sourceChanged/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>


## Inheritors  
  
|  Name| 
|---|
| [AbstractLeafNode](../-abstract-leaf-node/index.md)
| [AbstractParentNode](../-abstract-parent-node/index.md)

