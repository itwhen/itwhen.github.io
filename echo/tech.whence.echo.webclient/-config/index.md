---
title: Config -
---
//[echo](../../index.md)/[tech.whence.echo.webclient](../index.md)/[Config](index.md)



# Config  
 [jvm] 

配置

class [Config](index.md)<[A](index.md) : [Actable](../-actable/index.md), [R](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| A| <br><br>: Action 行为<br><br>
| R| <br><br>: Any 结果<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Config](-config.md)|  [jvm] <br><br>: Action 行为<br><br>fun [Config](-config.md)()   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [action](index.md#tech.whence.echo.webclient/Config/action/#/PointingToDeclaration/)|  [jvm] <br><br>A 行为<br><br>lateinit var [action](index.md#tech.whence.echo.webclient/Config/action/#/PointingToDeclaration/): [A](index.md)   <br>
| [exceptionHandler](index.md#tech.whence.echo.webclient/Config/exceptionHandler/#/PointingToDeclaration/)|  [jvm] <br><br>ExceptionHandler? 异常处理器<br><br>var [exceptionHandler](index.md#tech.whence.echo.webclient/Config/exceptionHandler/#/PointingToDeclaration/): [ExceptionHandler](../-exception-handler/index.md)?   <br>
| [id](index.md#tech.whence.echo.webclient/Config/id/#/PointingToDeclaration/)|  [jvm] <br><br>String 唯一标识<br><br>var [id](index.md#tech.whence.echo.webclient/Config/id/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [redoing](index.md#tech.whence.echo.webclient/Config/redoing/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 当前是否在重新请求中<br><br>var [redoing](index.md#tech.whence.echo.webclient/Config/redoing/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [requestMethod](index.md#tech.whence.echo.webclient/Config/requestMethod/#/PointingToDeclaration/)|  [jvm] <br><br>Method 请求方法<br><br>lateinit var [requestMethod](index.md#tech.whence.echo.webclient/Config/requestMethod/#/PointingToDeclaration/): [Request.Method](../../tech.whence.echo.webclient.request/-request/-method/index.md)   <br>
| [requestParameterizer](index.md#tech.whence.echo.webclient/Config/requestParameterizer/#/PointingToDeclaration/)|  [jvm] <br><br>RequestParameterizer? 提交数据处理器<br><br>var [requestParameterizer](index.md#tech.whence.echo.webclient/Config/requestParameterizer/#/PointingToDeclaration/): [RequestParameterizer](../../tech.whence.echo.webclient.request/-request-parameterizer/index.md)?   <br>
| [requestQuery](index.md#tech.whence.echo.webclient/Config/requestQuery/#/PointingToDeclaration/)|  [jvm] <br><br>Accessor? 查询数据<br><br>var [requestQuery](index.md#tech.whence.echo.webclient/Config/requestQuery/#/PointingToDeclaration/): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)?   <br>
| [requestTimeout](index.md#tech.whence.echo.webclient/Config/requestTimeout/#/PointingToDeclaration/)|  [jvm] <br><br>Duration 请求超时<br><br>var [requestTimeout](index.md#tech.whence.echo.webclient/Config/requestTimeout/#/PointingToDeclaration/): [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)   <br>
| [responseHandler](index.md#tech.whence.echo.webclient/Config/responseHandler/#/PointingToDeclaration/)|  [jvm] <br><br>ResponseHandler<A, R>? 响应处理器<br><br>var [responseHandler](index.md#tech.whence.echo.webclient/Config/responseHandler/#/PointingToDeclaration/): [ResponseHandler](../../tech.whence.echo.webclient.response/-response-handler/index.md)<[A](index.md), *>?   <br>
| [responseMocker](index.md#tech.whence.echo.webclient/Config/responseMocker/#/PointingToDeclaration/)|  [jvm] <br><br>ResponseMocker<A>? 响应模拟器<br><br>var [responseMocker](index.md#tech.whence.echo.webclient/Config/responseMocker/#/PointingToDeclaration/): [ResponseMocker](../../tech.whence.echo.webclient.response/-response-mocker/index.md)<[A](index.md)>?   <br>
| [responseMockerPurpose](index.md#tech.whence.echo.webclient/Config/responseMockerPurpose/#/PointingToDeclaration/)|  [jvm] <br><br>Purpose? 响应模拟目标<br><br>var [responseMockerPurpose](index.md#tech.whence.echo.webclient/Config/responseMockerPurpose/#/PointingToDeclaration/): [ResponseMocker.Purpose](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/index.md)?   <br>
| [responseRetries](index.md#tech.whence.echo.webclient/Config/responseRetries/#/PointingToDeclaration/)|  [jvm] <br><br>List<ResponseRetry>? 响应重试<br><br>var [responseRetries](index.md#tech.whence.echo.webclient/Config/responseRetries/#/PointingToDeclaration/): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[ResponseRetry](../../tech.whence.echo.webclient.response/-response-retry/index.md)>?   <br>
| [resultType](index.md#tech.whence.echo.webclient/Config/resultType/#/PointingToDeclaration/)|  [jvm] <br><br>ResultType<R>? 结果类型<br><br>var [resultType](index.md#tech.whence.echo.webclient/Config/resultType/#/PointingToDeclaration/): [ResultType](../-result-type/index.md)<[R](index.md)>?   <br>
| [retry](index.md#tech.whence.echo.webclient/Config/retry/#/PointingToDeclaration/)|  [jvm] <br><br>Retry? 重试策略<br><br>var [retry](index.md#tech.whence.echo.webclient/Config/retry/#/PointingToDeclaration/): [Retry](../../tech.whence.echo.retry/-retry/index.md)   <br>

