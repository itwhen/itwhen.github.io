---
title: OrderData -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.sample.order](../index.md)/[OrderData](index.md)



# OrderData  
 [jvm] 

单据数据

interface [OrderData](index.md) : [FlowData](../../tech.whence.echo.rpc.sample.flow/-flow-data/index.md)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [auditedAt](index.md#tech.whence.echo.rpc.sample.order/OrderData/auditedAt/#/PointingToDeclaration/)|  [jvm] <br><br>LocalDateTime? 审核时间<br><br>abstract override val [auditedAt](index.md#tech.whence.echo.rpc.sample.order/OrderData/auditedAt/#/PointingToDeclaration/): [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)?   <br>
| [auditor](index.md#tech.whence.echo.rpc.sample.order/OrderData/auditor/#/PointingToDeclaration/)|  [jvm] <br><br>String? 审核人<br><br>abstract override val [auditor](index.md#tech.whence.echo.rpc.sample.order/OrderData/auditor/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [createdAt](index.md#tech.whence.echo.rpc.sample.order/OrderData/createdAt/#/PointingToDeclaration/)|  [jvm] <br><br>LocalDateTime 创建时间<br><br>abstract override val [createdAt](index.md#tech.whence.echo.rpc.sample.order/OrderData/createdAt/#/PointingToDeclaration/): [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)   <br>
| [creator](index.md#tech.whence.echo.rpc.sample.order/OrderData/creator/#/PointingToDeclaration/)|  [jvm] <br><br>String? 创建人<br><br>abstract override val [creator](index.md#tech.whence.echo.rpc.sample.order/OrderData/creator/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [id](index.md#tech.whence.echo.rpc.sample.order/OrderData/id/#/PointingToDeclaration/)|  [jvm] <br><br>String 编号<br><br>abstract override val [id](index.md#tech.whence.echo.rpc.sample.order/OrderData/id/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [number](index.md#tech.whence.echo.rpc.sample.order/OrderData/number/#/PointingToDeclaration/)|  [jvm] <br><br>String 单号<br><br>abstract val [number](index.md#tech.whence.echo.rpc.sample.order/OrderData/number/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [operable](index.md#tech.whence.echo.rpc.sample.order/OrderData/operable/#/PointingToDeclaration/)|  [jvm] <br><br>String? 可操作的<br><br>abstract override var [operable](index.md#tech.whence.echo.rpc.sample.order/OrderData/operable/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [remark](index.md#tech.whence.echo.rpc.sample.order/OrderData/remark/#/PointingToDeclaration/)|  [jvm] <br><br>String? 备注<br><br>abstract override val [remark](index.md#tech.whence.echo.rpc.sample.order/OrderData/remark/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [sourceId](index.md#tech.whence.echo.rpc.sample.order/OrderData/sourceId/#/PointingToDeclaration/)|  [jvm] <br><br>String? 来源单据编号<br><br>abstract val [sourceId](index.md#tech.whence.echo.rpc.sample.order/OrderData/sourceId/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [sourceKind](index.md#tech.whence.echo.rpc.sample.order/OrderData/sourceKind/#/PointingToDeclaration/)|  [jvm] <br><br>String? 来源单据类型<br><br>abstract val [sourceKind](index.md#tech.whence.echo.rpc.sample.order/OrderData/sourceKind/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [submittedAt](index.md#tech.whence.echo.rpc.sample.order/OrderData/submittedAt/#/PointingToDeclaration/)|  [jvm] <br><br>LocalDateTime? 提交时间<br><br>abstract override val [submittedAt](index.md#tech.whence.echo.rpc.sample.order/OrderData/submittedAt/#/PointingToDeclaration/): [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)?   <br>
| [submitter](index.md#tech.whence.echo.rpc.sample.order/OrderData/submitter/#/PointingToDeclaration/)|  [jvm] <br><br>String? 提交人<br><br>abstract override val [submitter](index.md#tech.whence.echo.rpc.sample.order/OrderData/submitter/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [targetId](index.md#tech.whence.echo.rpc.sample.order/OrderData/targetId/#/PointingToDeclaration/)|  [jvm] <br><br>String? 目标单据编号<br><br>abstract val [targetId](index.md#tech.whence.echo.rpc.sample.order/OrderData/targetId/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [targetKind](index.md#tech.whence.echo.rpc.sample.order/OrderData/targetKind/#/PointingToDeclaration/)|  [jvm] <br><br>String? 目标单据类型<br><br>abstract val [targetKind](index.md#tech.whence.echo.rpc.sample.order/OrderData/targetKind/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [updatedAt](index.md#tech.whence.echo.rpc.sample.order/OrderData/updatedAt/#/PointingToDeclaration/)|  [jvm] <br><br>LocalDateTime? 更新时间<br><br>abstract override val [updatedAt](index.md#tech.whence.echo.rpc.sample.order/OrderData/updatedAt/#/PointingToDeclaration/): [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)?   <br>
| [updater](index.md#tech.whence.echo.rpc.sample.order/OrderData/updater/#/PointingToDeclaration/)|  [jvm] <br><br>String? 更新人<br><br>abstract override val [updater](index.md#tech.whence.echo.rpc.sample.order/OrderData/updater/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>

