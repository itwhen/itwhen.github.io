---
title: FlowService -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.sample.flow](../index.md)/[FlowService](index.md)



# FlowService  
 [jvm] 

流程服务抽象

abstract class [FlowService](index.md)<[T](index.md) : [FlowService](index.md)<[T](index.md), [C](index.md), [U](index.md), [S](index.md), [R](index.md), [N](index.md), [E](index.md), [D](index.md)>, [C](index.md) : [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md), [U](index.md) : [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md), [S](index.md) : [FlowSearching](../-flow-searching/index.md), [R](index.md) : [FlowData](../-flow-data/index.md), [N](index.md) : [IntConst](../../tech.whence.echo.container.constant/-int-const/index.md), [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[N](index.md)>, [Trackable](../-trackable/index.md), [E](index.md) : [Flow](../-flow/index.md), [D](index.md) : [Dao](../../tech.whence.echo.dal.dao/-dao/index.md)<[E](index.md), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), *>, [Queriable](../../tech.whence.echo.dal.dao/-queriable/index.md)<[E](index.md), *, *, *, *, *, *, *, *, *>>(**source**: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[E](index.md)>, **flow**: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[N](index.md)>, **dao**: [D](index.md), **identifier**: [Identifier](../../tech.whence.echo.dal.entity.id/-identifier/index.md)) : [ResourceService](../../tech.whence.echo.rpc.sample.resource/-resource-service/index.md)<[T](index.md), [C](index.md), [U](index.md), [S](index.md), [R](index.md), [E](index.md), [D](index.md)> , [FlowFacade](../-flow-facade/index.md)<[C](index.md), [U](index.md), [S](index.md), [R](index.md)>    


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| C| <br><br>创建负载<br><br>
| D| <br><br>数据层<br><br>
| E| <br><br>实体<br><br>
| N| <br><br>状态<br><br>
| R| <br><br>响应负载<br><br>
| S| <br><br>搜索负载<br><br>
| T| <br><br>子类<br><br>
| U| <br><br>更新负载<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [FlowService](-flow-service.md)|  [jvm] <br><br><br><br>fun <[N](index.md) : [IntConst](../../tech.whence.echo.container.constant/-int-const/index.md), [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[N](index.md)>, [Trackable](../-trackable/index.md), [E](index.md) : [Flow](../-flow/index.md), [D](index.md) : [Dao](../../tech.whence.echo.dal.dao/-dao/index.md)<[E](index.md), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), *>, [Queriable](../../tech.whence.echo.dal.dao/-queriable/index.md)<[E](index.md), *, *, *, *, *, *, *, *, *>> [FlowService](-flow-service.md)(source: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[E](index.md)>, flow: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[N](index.md)>, dao: [D](index.md), identifier: [Identifier](../../tech.whence.echo.dal.entity.id/-identifier/index.md))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [audit](audit.md)| [jvm]  <br>Brief description  <br><br><br>审核<br><br>  <br>Content  <br>open override fun [audit](audit.md)(batch: [Batch](../../tech.whence.echo.rpc.request/-batch/index.md), approved: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[Empty](../../tech.whence.echo.rpc.payload/-empty/index.md)>)  <br><br><br>
| [close](close.md)| [jvm]  <br>Brief description  <br><br><br>关闭<br><br>  <br>Content  <br>open override fun [close](close.md)(batch: [Batch](../../tech.whence.echo.rpc.request/-batch/index.md), responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[Empty](../../tech.whence.echo.rpc.payload/-empty/index.md)>)  <br><br><br>
| [create](../../tech.whence.echo.rpc.sample.resource/-resource-service/create.md)| [jvm]  <br>Content  <br>open override fun [create](../../tech.whence.echo.rpc.sample.resource/-resource-service/create.md)(request: [Request](../../tech.whence.echo.rpc.request/-request/index.md)<[C](index.md)>, responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[Single](../../tech.whence.echo.rpc.payload/-single/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>>)  <br><br><br>
| [delete](../../tech.whence.echo.rpc.sample.resource/-resource-service/delete.md)| [jvm]  <br>Content  <br>open override fun [delete](../../tech.whence.echo.rpc.sample.resource/-resource-service/delete.md)(batch: [Batch](../../tech.whence.echo.rpc.request/-batch/index.md), responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[Empty](../../tech.whence.echo.rpc.payload/-empty/index.md)>)  <br><br><br>
| [detail](detail.md)| [jvm]  <br>Brief description  <br><br><br>是否支持变更明细<br><br>  <br>Content  <br>open override fun [detail](detail.md)(data: [E](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [retrieve](index.md#tech.whence.echo.rpc.sample.resource/ResourceService/retrieve/#tech.whence.echo.rpc.request.Id#io.vertx.core.Handler[io.vertx.core.AsyncResult[tech.whence.echo.rpc.response.Response[TypeParam(bounds=[tech.whence.echo.rpc.sample.flow.FlowData])]]]/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [retrieve](index.md#tech.whence.echo.rpc.sample.resource/ResourceService/retrieve/#tech.whence.echo.rpc.request.Id#io.vertx.core.Handler[io.vertx.core.AsyncResult[tech.whence.echo.rpc.response.Response[TypeParam(bounds=[tech.whence.echo.rpc.sample.flow.FlowData])]]]/PointingToDeclaration/)(id: [Id](../../tech.whence.echo.rpc.request/-id/index.md), responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[R](index.md)>)  <br><br><br>
| [retrieves](index.md#tech.whence.echo.rpc.sample.resource/ResourceService/retrieves/#tech.whence.echo.rpc.request.Batch#io.vertx.core.Handler[io.vertx.core.AsyncResult[tech.whence.echo.rpc.response.Response[tech.whence.echo.rpc.payload.Listed[TypeParam(bounds=[tech.whence.echo.rpc.sample.flow.FlowData])]]]]/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [retrieves](index.md#tech.whence.echo.rpc.sample.resource/ResourceService/retrieves/#tech.whence.echo.rpc.request.Batch#io.vertx.core.Handler[io.vertx.core.AsyncResult[tech.whence.echo.rpc.response.Response[tech.whence.echo.rpc.payload.Listed[TypeParam(bounds=[tech.whence.echo.rpc.sample.flow.FlowData])]]]]/PointingToDeclaration/)(batch: [Batch](../../tech.whence.echo.rpc.request/-batch/index.md), responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[Listed](../../tech.whence.echo.rpc.payload/-listed/index.md)<[R](index.md)>>)  <br><br><br>
| [search](index.md#tech.whence.echo.rpc.sample.resource/ResourceService/search/#tech.whence.echo.rpc.request.Request[tech.whence.echo.rpc.payload.Searching[TypeParam(bounds=[tech.whence.echo.rpc.sample.flow.FlowSearching])]]#io.vertx.core.Handler[io.vertx.core.AsyncResult[tech.whence.echo.rpc.response.Response[tech.whence.echo.rpc.payload.Paged[TypeParam(bounds=[tech.whence.echo.rpc.sample.flow.FlowData])]]]]/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [search](index.md#tech.whence.echo.rpc.sample.resource/ResourceService/search/#tech.whence.echo.rpc.request.Request[tech.whence.echo.rpc.payload.Searching[TypeParam(bounds=[tech.whence.echo.rpc.sample.flow.FlowSearching])]]#io.vertx.core.Handler[io.vertx.core.AsyncResult[tech.whence.echo.rpc.response.Response[tech.whence.echo.rpc.payload.Paged[TypeParam(bounds=[tech.whence.echo.rpc.sample.flow.FlowData])]]]]/PointingToDeclaration/)(request: [Request](../../tech.whence.echo.rpc.request/-request/index.md)<[Searching](../../tech.whence.echo.rpc.payload/-searching/index.md)<[S](index.md)>>, responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[Paged](../../tech.whence.echo.rpc.payload/-paged/index.md)<[R](index.md)>>)  <br><br><br>
| [submit](submit.md)| [jvm]  <br>Brief description  <br><br><br>申请<br><br>  <br>Content  <br>open override fun [submit](submit.md)(batch: [Batch](../../tech.whence.echo.rpc.request/-batch/index.md), responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[Empty](../../tech.whence.echo.rpc.payload/-empty/index.md)>)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [update](../../tech.whence.echo.rpc.sample.resource/-resource-service/update.md)| [jvm]  <br>Content  <br>open override fun [update](../../tech.whence.echo.rpc.sample.resource/-resource-service/update.md)(id: [Id](../../tech.whence.echo.rpc.request/-id/index.md), request: [Request](../../tech.whence.echo.rpc.request/-request/index.md)<[U](index.md)>, responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[Empty](../../tech.whence.echo.rpc.payload/-empty/index.md)>)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [source](index.md#tech.whence.echo.rpc.sample.flow/FlowService/source/#/PointingToDeclaration/)|  [jvm] <br><br>KClass<E> 实体类<br><br>override val [source](index.md#tech.whence.echo.rpc.sample.flow/FlowService/source/#/PointingToDeclaration/): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[E](index.md)>   <br>


## Inheritors  
  
|  Name| 
|---|
| [OrderService](../../tech.whence.echo.rpc.sample.order/-order-service/index.md)

