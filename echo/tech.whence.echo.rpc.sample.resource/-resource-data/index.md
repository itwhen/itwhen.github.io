---
title: ResourceData -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.sample.resource](../index.md)/[ResourceData](index.md)



# ResourceData  
 [jvm] 

资源数据

interface [ResourceData](index.md) : [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [createdAt](index.md#tech.whence.echo.rpc.sample.resource/ResourceData/createdAt/#/PointingToDeclaration/)|  [jvm] <br><br>LocalDateTime 创建时间<br><br>abstract val [createdAt](index.md#tech.whence.echo.rpc.sample.resource/ResourceData/createdAt/#/PointingToDeclaration/): [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)   <br>
| [creator](index.md#tech.whence.echo.rpc.sample.resource/ResourceData/creator/#/PointingToDeclaration/)|  [jvm] <br><br>String? 创建人<br><br>abstract val [creator](index.md#tech.whence.echo.rpc.sample.resource/ResourceData/creator/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [id](index.md#tech.whence.echo.rpc.sample.resource/ResourceData/id/#/PointingToDeclaration/)|  [jvm] <br><br>String 编号<br><br>abstract val [id](index.md#tech.whence.echo.rpc.sample.resource/ResourceData/id/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [remark](index.md#tech.whence.echo.rpc.sample.resource/ResourceData/remark/#/PointingToDeclaration/)|  [jvm] <br><br>String? 备注<br><br>abstract val [remark](index.md#tech.whence.echo.rpc.sample.resource/ResourceData/remark/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [updatedAt](index.md#tech.whence.echo.rpc.sample.resource/ResourceData/updatedAt/#/PointingToDeclaration/)|  [jvm] <br><br>LocalDateTime? 更新时间<br><br>abstract val [updatedAt](index.md#tech.whence.echo.rpc.sample.resource/ResourceData/updatedAt/#/PointingToDeclaration/): [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)?   <br>
| [updater](index.md#tech.whence.echo.rpc.sample.resource/ResourceData/updater/#/PointingToDeclaration/)|  [jvm] <br><br>String? 更新人<br><br>abstract val [updater](index.md#tech.whence.echo.rpc.sample.resource/ResourceData/updater/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>


## Inheritors  
  
|  Name| 
|---|
| [DetailData](../../tech.whence.echo.rpc.sample.detail/-detail-data/index.md)
| [FlowData](../../tech.whence.echo.rpc.sample.flow/-flow-data/index.md)
| [ItemData](../../tech.whence.echo.rpc.sample.item/-item-data/index.md)

