---
title: Reason -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.response](../index.md)/[Reason](index.md)



# Reason  
 [jvm] 

错误原因

enum [Reason](index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Reason](index.md)> , [StringConst](../../tech.whence.echo.container.constant/-string-const/index.md)   


## Entries  
  
|  Name|  Summary| 
|---|---|
| [Unavailable](-unavailable/index.md)|  [jvm] <br><br>不可用<br><br>[Unavailable](-unavailable/index.md)("1503", "Maintained", HttpResponseStatus.SERVICE_UNAVAILABLE, Transformer {<br>    UnavailableException(it.message)<br>  })  <br>  <br>   <br>
| [Timeout](-timeout/index.md)|  [jvm] <br><br>连接超时<br><br>[Timeout](-timeout/index.md)("1408", "Timeout", HttpResponseStatus.REQUEST_TIMEOUT, Transformer {<br>    ResponseException(it.message, ReplyFailure.TIMEOUT)<br>  })  <br>  <br>   <br>
| [Dated](-dated/index.md)|  [jvm] <br><br>版本过期的<br><br>[Dated](-dated/index.md)("1426", "Dated", HttpResponseStatus.UPGRADE_REQUIRED, Transformer {<br>    ResponseException(it.message, ReplyFailure.RECIPIENT_FAILURE)<br>  })  <br>  <br>   <br>
| [Todo](-todo/index.md)|  [jvm] <br><br>待开发<br><br>[Todo](-todo/index.md)("1501", "Todo", HttpResponseStatus.NOT_IMPLEMENTED, Transformer {<br>    TodoException(it.message)<br>  })  <br>  <br>   <br>
| [Unrecognized](-unrecognized/index.md)|  [jvm] <br><br>无法识别<br><br>[Unrecognized](-unrecognized/index.md)("1400", "Unrecognized", HttpResponseStatus.BAD_REQUEST, Transformer {<br>    UnrecognizedException(it.message)<br>  })  <br>  <br>   <br>
| [Unauthorized](-unauthorized/index.md)|  [jvm] <br><br>无效授权<br><br>[Unauthorized](-unauthorized/index.md)("1401", "Unauthorized", HttpResponseStatus.UNAUTHORIZED, Transformer {<br>    UnrecognizedException(it.message)<br>  })  <br>  <br>   <br>
| [Invalidated](-invalidated/index.md)|  [jvm] <br><br>数据校验失败<br><br>[Invalidated](-invalidated/index.md)("1422", "Invalidated", HttpResponseStatus.UNPROCESSABLE_ENTITY, Transformer {<br>      InvalidatedException(it.errors ?: Errors())<br>    })  <br>  <br>   <br>
| [Conflicted](-conflicted/index.md)|  [jvm] <br><br>数据重复<br><br>[Conflicted](-conflicted/index.md)("1409", "Conflicted", HttpResponseStatus.CONFLICT, Transformer {<br>    ConflictedException(it.message)<br>  })  <br>  <br>   <br>
| [Missing](-missing/index.md)|  [jvm] <br><br>找不到指定记录<br><br>[Missing](-missing/index.md)("1404", "Missing", HttpResponseStatus.NOT_FOUND, Transformer {<br>    MissingException(it.message)<br>  })  <br>  <br>   <br>
| [Error](-error/index.md)|  [jvm] <br><br>错误<br><br>[Error](-error/index.md)("1500", "Error", HttpResponseStatus.INTERNAL_SERVER_ERROR, Transformer {<br>    ResponseException(it.message)<br>  })  <br>  <br>   <br>
| [Failed](-failed/index.md)|  [jvm] <br><br>操作失败<br><br>[Failed](-failed/index.md)("1507", "Failed", HttpResponseStatus.INSUFFICIENT_STORAGE, Transformer {<br>    ResponseException(it.message)<br>  })  <br>  <br>   <br>
| [Unchanged](-unchanged/index.md)|  [jvm] <br><br>数据未变更<br><br>[Unchanged](-unchanged/index.md)("1412", "Unchanged", HttpResponseStatus.PRECONDITION_FAILED, Transformer {<br>    ResponseException(it.message)<br>  })  <br>  <br>   <br>
| [Unoperatable](-unoperatable/index.md)|  [jvm] <br><br>无法操作的<br><br>[Unoperatable](-unoperatable/index.md)("1418", "Unoperatable", HttpResponseStatus.INTERNAL_SERVER_ERROR, Transformer {<br>    ResponseException(it.message)<br>  })  <br>  <br>   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [are](../../tech.whence.echo.container.constant/-string-const/are.md)| [jvm]  <br>Brief description  <br><br><br>根据值判断是否是当前常量<br><br>  <br>Content  <br>open override fun [are](../../tech.whence.echo.container.constant/-string-const/are.md)(value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [compareTo](-unoperatable/index.md#kotlin/Enum/compareTo/#tech.whence.echo.rpc.response.Reason/PointingToDeclaration/)| [jvm]  <br>Content  <br>operator override fun [compareTo](-unoperatable/index.md#kotlin/Enum/compareTo/#tech.whence.echo.rpc.response.Reason/PointingToDeclaration/)(other: [Reason](index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [convert](../../tech.whence.echo.container.constant/-string-const/convert.md)| [jvm]  <br>Brief description  <br><br><br>转换指定值 若无法处理返回空<br><br>  <br>Content  <br>open override fun [convert](../../tech.whence.echo.container.constant/-string-const/convert.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>operator override fun [equals](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [finalize](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/finalize/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [finalize](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/finalize/#/PointingToDeclaration/)()  <br><br><br>
| [getDeclaringClass](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/getDeclaringClass/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [getDeclaringClass](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/getDeclaringClass/#/PointingToDeclaration/)(): [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[Reason](index.md)>  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [hashCode](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [name](index.md#tech.whence.echo.rpc.response/Reason/name/#/PointingToDeclaration/)|  [jvm] override val [name](index.md#tech.whence.echo.rpc.response/Reason/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [ordinal](index.md#tech.whence.echo.rpc.response/Reason/ordinal/#/PointingToDeclaration/)|  [jvm] override val [ordinal](index.md#tech.whence.echo.rpc.response/Reason/ordinal/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>
| [status](index.md#tech.whence.echo.rpc.response/Reason/status/#/PointingToDeclaration/)|  [jvm] <br><br>HttpResponseStatus<br><br>val [status](index.md#tech.whence.echo.rpc.response/Reason/status/#/PointingToDeclaration/): HttpResponseStatus   <br>
| [title](index.md#tech.whence.echo.rpc.response/Reason/title/#/PointingToDeclaration/)|  [jvm] <br><br>String 描述<br><br>open override val [title](index.md#tech.whence.echo.rpc.response/Reason/title/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [transformer](index.md#tech.whence.echo.rpc.response/Reason/transformer/#/PointingToDeclaration/)|  [jvm] <br><br>Transformer<String?, ResponseException> 异常生成<br><br>val [transformer](index.md#tech.whence.echo.rpc.response/Reason/transformer/#/PointingToDeclaration/): [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[Failure](../-failure/index.md), [ResponseException](../../tech.whence.echo.rpc.exception/-response-exception/index.md)>?   <br>
| [value](index.md#tech.whence.echo.rpc.response/Reason/value/#/PointingToDeclaration/)|  [jvm] <br><br>String 业务编码<br><br>open override val [value](index.md#tech.whence.echo.rpc.response/Reason/value/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>

