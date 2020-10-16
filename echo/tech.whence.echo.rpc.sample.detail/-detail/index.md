---
title: Detail -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.sample.detail](../index.md)/[Detail](index.md)



# Detail  
 [jvm] 

明细数据

interface [Detail](index.md) : [Resource](../../tech.whence.echo.rpc.sample.resource/-resource/index.md)   


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
| [createdAt](index.md#tech.whence.echo.rpc.sample.detail/Detail/createdAt/#/PointingToDeclaration/)|  [jvm] <br><br>LocalDateTime 创建时间<br><br>abstract override var [createdAt](index.md#tech.whence.echo.rpc.sample.detail/Detail/createdAt/#/PointingToDeclaration/): [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)?   <br>
| [creator](index.md#tech.whence.echo.rpc.sample.detail/Detail/creator/#/PointingToDeclaration/)|  [jvm] <br><br>String? 创建人<br><br>abstract override var [creator](index.md#tech.whence.echo.rpc.sample.detail/Detail/creator/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [id](index.md#tech.whence.echo.rpc.sample.detail/Detail/id/#/PointingToDeclaration/)|  [jvm] <br><br>String 编号<br><br>abstract override var [id](index.md#tech.whence.echo.rpc.sample.detail/Detail/id/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [line](index.md#tech.whence.echo.rpc.sample.detail/Detail/line/#/PointingToDeclaration/)|  [jvm] <br><br>Int 行号<br><br>abstract var [line](index.md#tech.whence.echo.rpc.sample.detail/Detail/line/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>
| [mainId](index.md#tech.whence.echo.rpc.sample.detail/Detail/mainId/#/PointingToDeclaration/)|  [jvm] <br><br>String 主数据编号<br><br>abstract var [mainId](index.md#tech.whence.echo.rpc.sample.detail/Detail/mainId/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [remark](index.md#tech.whence.echo.rpc.sample.detail/Detail/remark/#/PointingToDeclaration/)|  [jvm] <br><br>String? 备注<br><br>abstract override var [remark](index.md#tech.whence.echo.rpc.sample.detail/Detail/remark/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [updatedAt](index.md#tech.whence.echo.rpc.sample.detail/Detail/updatedAt/#/PointingToDeclaration/)|  [jvm] <br><br>LocalDateTime? 更新时间<br><br>abstract override var [updatedAt](index.md#tech.whence.echo.rpc.sample.detail/Detail/updatedAt/#/PointingToDeclaration/): [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)?   <br>
| [updater](index.md#tech.whence.echo.rpc.sample.detail/Detail/updater/#/PointingToDeclaration/)|  [jvm] <br><br>String? 更新人<br><br>abstract override var [updater](index.md#tech.whence.echo.rpc.sample.detail/Detail/updater/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>

