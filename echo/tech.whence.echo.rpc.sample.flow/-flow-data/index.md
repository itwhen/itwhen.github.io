---
title: FlowData -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.sample.flow](../index.md)/[FlowData](index.md)



# FlowData  
 [jvm] 

流程数据

interface [FlowData](index.md) : [ResourceData](../../tech.whence.echo.rpc.sample.resource/-resource-data/index.md)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [auditedAt](index.md#tech.whence.echo.rpc.sample.flow/FlowData/auditedAt/#/PointingToDeclaration/)|  [jvm] <br><br>LocalDateTime? 审核时间<br><br>abstract val [auditedAt](index.md#tech.whence.echo.rpc.sample.flow/FlowData/auditedAt/#/PointingToDeclaration/): [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)?   <br>
| [auditor](index.md#tech.whence.echo.rpc.sample.flow/FlowData/auditor/#/PointingToDeclaration/)|  [jvm] <br><br>String? 审核人<br><br>abstract val [auditor](index.md#tech.whence.echo.rpc.sample.flow/FlowData/auditor/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [createdAt](index.md#tech.whence.echo.rpc.sample.flow/FlowData/createdAt/#/PointingToDeclaration/)|  [jvm] <br><br>LocalDateTime 创建时间<br><br>abstract override val [createdAt](index.md#tech.whence.echo.rpc.sample.flow/FlowData/createdAt/#/PointingToDeclaration/): [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)   <br>
| [creator](index.md#tech.whence.echo.rpc.sample.flow/FlowData/creator/#/PointingToDeclaration/)|  [jvm] <br><br>String? 创建人<br><br>abstract override val [creator](index.md#tech.whence.echo.rpc.sample.flow/FlowData/creator/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [id](index.md#tech.whence.echo.rpc.sample.flow/FlowData/id/#/PointingToDeclaration/)|  [jvm] <br><br>String 编号<br><br>abstract override val [id](index.md#tech.whence.echo.rpc.sample.flow/FlowData/id/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [operable](index.md#tech.whence.echo.rpc.sample.flow/FlowData/operable/#/PointingToDeclaration/)|  [jvm] <br><br>String? 可操作的<br><br>abstract var [operable](index.md#tech.whence.echo.rpc.sample.flow/FlowData/operable/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [remark](index.md#tech.whence.echo.rpc.sample.flow/FlowData/remark/#/PointingToDeclaration/)|  [jvm] <br><br>String? 备注<br><br>abstract override val [remark](index.md#tech.whence.echo.rpc.sample.flow/FlowData/remark/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [submittedAt](index.md#tech.whence.echo.rpc.sample.flow/FlowData/submittedAt/#/PointingToDeclaration/)|  [jvm] <br><br>LocalDateTime? 提交时间<br><br>abstract val [submittedAt](index.md#tech.whence.echo.rpc.sample.flow/FlowData/submittedAt/#/PointingToDeclaration/): [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)?   <br>
| [submitter](index.md#tech.whence.echo.rpc.sample.flow/FlowData/submitter/#/PointingToDeclaration/)|  [jvm] <br><br>String? 提交人<br><br>abstract val [submitter](index.md#tech.whence.echo.rpc.sample.flow/FlowData/submitter/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [updatedAt](index.md#tech.whence.echo.rpc.sample.flow/FlowData/updatedAt/#/PointingToDeclaration/)|  [jvm] <br><br>LocalDateTime? 更新时间<br><br>abstract override val [updatedAt](index.md#tech.whence.echo.rpc.sample.flow/FlowData/updatedAt/#/PointingToDeclaration/): [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)?   <br>
| [updater](index.md#tech.whence.echo.rpc.sample.flow/FlowData/updater/#/PointingToDeclaration/)|  [jvm] <br><br>String? 更新人<br><br>abstract override val [updater](index.md#tech.whence.echo.rpc.sample.flow/FlowData/updater/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>


## Inheritors  
  
|  Name| 
|---|
| [OrderData](../../tech.whence.echo.rpc.sample.order/-order-data/index.md)

