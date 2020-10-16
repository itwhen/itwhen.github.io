---
title: Order -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.sample.order](../index.md)/[Order](index.md)



# Order  
 [jvm] 

单据数据

interface [Order](index.md) : [Flow](../../tech.whence.echo.rpc.sample.flow/-flow/index.md)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [access](../../tech.whence.echo.dal.entity/-entity/access.md)| [jvm]  <br>Brief description  <br><br><br>转换<br><br>  <br>Content  <br>open override fun [access](../../tech.whence.echo.dal.entity/-entity/access.md)(): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>使用多个策略将实体转换为字段键值映射 获取实体中实际字段数据及附加数据 再针对字段值的不同类型分别处理 再应用策略处理<br><br>  <br>Content  <br>open override fun [access](../../tech.whence.echo.dal.entity/-entity/access.md)(strategist: [Strategist](../../tech.whence.echo.strategy/-strategist/index.md)): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [into](../../tech.whence.echo.dal.entity/-entity/into.md)| [jvm]  <br>Brief description  <br><br><br>转换为指定类型<br><br>  <br>Content  <br>open override fun <T : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [into](../../tech.whence.echo.dal.entity/-entity/into.md)(declarer: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<T>): T  <br>open override fun <T : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [into](../../tech.whence.echo.dal.entity/-entity/into.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<T>): T  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [auditedAt](index.md#tech.whence.echo.rpc.sample.order/Order/auditedAt/#/PointingToDeclaration/)|  [jvm] <br><br>LocalDateTime? 审核时间<br><br>abstract override var [auditedAt](index.md#tech.whence.echo.rpc.sample.order/Order/auditedAt/#/PointingToDeclaration/): [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)?   <br>
| [auditor](index.md#tech.whence.echo.rpc.sample.order/Order/auditor/#/PointingToDeclaration/)|  [jvm] <br><br>String? 审核人<br><br>abstract override var [auditor](index.md#tech.whence.echo.rpc.sample.order/Order/auditor/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [createdAt](index.md#tech.whence.echo.rpc.sample.order/Order/createdAt/#/PointingToDeclaration/)|  [jvm] <br><br>LocalDateTime 创建时间<br><br>abstract override var [createdAt](index.md#tech.whence.echo.rpc.sample.order/Order/createdAt/#/PointingToDeclaration/): [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)?   <br>
| [creator](index.md#tech.whence.echo.rpc.sample.order/Order/creator/#/PointingToDeclaration/)|  [jvm] <br><br>String? 创建人<br><br>abstract override var [creator](index.md#tech.whence.echo.rpc.sample.order/Order/creator/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [id](index.md#tech.whence.echo.rpc.sample.order/Order/id/#/PointingToDeclaration/)|  [jvm] <br><br>String 编号<br><br>abstract override var [id](index.md#tech.whence.echo.rpc.sample.order/Order/id/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [number](index.md#tech.whence.echo.rpc.sample.order/Order/number/#/PointingToDeclaration/)|  [jvm] <br><br>String 单号<br><br>abstract var [number](index.md#tech.whence.echo.rpc.sample.order/Order/number/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [remark](index.md#tech.whence.echo.rpc.sample.order/Order/remark/#/PointingToDeclaration/)|  [jvm] <br><br>String? 备注<br><br>abstract override var [remark](index.md#tech.whence.echo.rpc.sample.order/Order/remark/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [sourceId](index.md#tech.whence.echo.rpc.sample.order/Order/sourceId/#/PointingToDeclaration/)|  [jvm] <br><br>String? 来源单据编号<br><br>abstract var [sourceId](index.md#tech.whence.echo.rpc.sample.order/Order/sourceId/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [sourceKind](index.md#tech.whence.echo.rpc.sample.order/Order/sourceKind/#/PointingToDeclaration/)|  [jvm] <br><br>String? 来源单据类型<br><br>abstract var [sourceKind](index.md#tech.whence.echo.rpc.sample.order/Order/sourceKind/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [submittedAt](index.md#tech.whence.echo.rpc.sample.order/Order/submittedAt/#/PointingToDeclaration/)|  [jvm] <br><br>LocalDateTime 申请时间<br><br>abstract override var [submittedAt](index.md#tech.whence.echo.rpc.sample.order/Order/submittedAt/#/PointingToDeclaration/): [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)?   <br>
| [submitter](index.md#tech.whence.echo.rpc.sample.order/Order/submitter/#/PointingToDeclaration/)|  [jvm] <br><br>String? 申请人<br><br>abstract override var [submitter](index.md#tech.whence.echo.rpc.sample.order/Order/submitter/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [targetId](index.md#tech.whence.echo.rpc.sample.order/Order/targetId/#/PointingToDeclaration/)|  [jvm] <br><br>String? 目标单据编号<br><br>abstract var [targetId](index.md#tech.whence.echo.rpc.sample.order/Order/targetId/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [targetKind](index.md#tech.whence.echo.rpc.sample.order/Order/targetKind/#/PointingToDeclaration/)|  [jvm] <br><br>String? 目标单据类型<br><br>abstract var [targetKind](index.md#tech.whence.echo.rpc.sample.order/Order/targetKind/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [updatedAt](index.md#tech.whence.echo.rpc.sample.order/Order/updatedAt/#/PointingToDeclaration/)|  [jvm] <br><br>LocalDateTime? 更新时间<br><br>abstract override var [updatedAt](index.md#tech.whence.echo.rpc.sample.order/Order/updatedAt/#/PointingToDeclaration/): [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)?   <br>
| [updater](index.md#tech.whence.echo.rpc.sample.order/Order/updater/#/PointingToDeclaration/)|  [jvm] <br><br>String? 更新人<br><br>abstract override var [updater](index.md#tech.whence.echo.rpc.sample.order/Order/updater/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>

