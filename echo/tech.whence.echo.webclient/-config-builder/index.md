---
title: ConfigBuilder -
---
//[echo](../../index.md)/[tech.whence.echo.webclient](../index.md)/[ConfigBuilder](index.md)



# ConfigBuilder  
 [jvm] 

配置构建器

class [ConfigBuilder](index.md)<[C](index.md) : [AbstractClient](../-abstract-client/index.md)<[C](index.md), [A](index.md)>, [A](index.md) : [Actable](../-actable/index.md), [R](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| A| <br><br>: Action<br><br>
| C| <br><br>: AbstractWebAPI<C, A><br><br>
| R| <br><br>: Any<br><br>
  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [exceptionally](exceptionally.md)| [jvm]  <br>Brief description  <br><br><br>设置异常处理器<br><br>  <br>Content  <br>fun [exceptionally](exceptionally.md)(handler: [ExceptionHandler](../-exception-handler/index.md)): [ConfigBuilder](index.md)<[C](index.md), [A](index.md), [R](index.md)>  <br><br><br>
| [get](get.md)| [jvm]  <br>Brief description  <br><br><br>发起GET请求<br><br>  <br>Content  <br>fun [get](get.md)(action: [A](index.md)): [Invocation](../-invocation/index.md)<[A](index.md), [R](index.md)>  <br><br><br>
| [handle](handle.md)| [jvm]  <br>Brief description  <br><br><br>设置响应处理器<br><br>  <br>Content  <br>fun [handle](handle.md)(handler: [ResponseHandler](../../tech.whence.echo.webclient.response/-response-handler/index.md)<[A](index.md), [R](index.md)>): [ConfigBuilder](index.md)<[C](index.md), [A](index.md), [R](index.md)>  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [identify](identify.md)| [jvm]  <br>Brief description  <br><br><br>设置配置编码<br><br>  <br>Content  <br>fun [identify](identify.md)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [ConfigBuilder](index.md)<[C](index.md), [A](index.md), [R](index.md)>  <br><br><br>
| [invoke](invoke.md)| [jvm]  <br>Brief description  <br><br><br>根据请求方式发生调用<br><br>  <br>Content  <br>fun [invoke](invoke.md)(method: [Request.Method](../../tech.whence.echo.webclient.request/-request/-method/index.md), action: [A](index.md)): [Invocation](../-invocation/index.md)<[A](index.md), [R](index.md)>  <br><br><br>
| [mock](mock.md)| [jvm]  <br>Brief description  <br><br><br>模拟响应<br><br>  <br>Content  <br>fun [mock](mock.md)(purpose: [ResponseMocker.Purpose](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/index.md), mocker: [ResponseMocker](../../tech.whence.echo.webclient.response/-response-mocker/index.md)<[A](index.md)>): [ConfigBuilder](index.md)<[C](index.md), [A](index.md), [R](index.md)>  <br><br><br>
| [parameterize](parameterize.md)| [jvm]  <br>Brief description  <br><br><br>设置文件上传形式的提交数据<br><br>  <br>Content  <br>fun [parameterize](parameterize.md)(file: AsyncFile): [ConfigBuilder](index.md)<[C](index.md), [A](index.md), [R](index.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置流形式的提交数据<br><br>  <br>Content  <br>fun [parameterize](parameterize.md)(stream: ReadStream<Buffer>): [ConfigBuilder](index.md)<[C](index.md), [A](index.md), [R](index.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置文本形式的提交数据<br><br>  <br>Content  <br>fun [parameterize](parameterize.md)(text: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [ConfigBuilder](index.md)<[C](index.md), [A](index.md), [R](index.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置提交数据<br><br>  <br>Content  <br>fun [parameterize](parameterize.md)(parameters: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)): [ConfigBuilder](index.md)<[C](index.md), [A](index.md), [R](index.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置提交数据回调<br><br>  <br>Content  <br>fun [parameterize](parameterize.md)(creator: [Producer](../../tech.whence.echo.function/-producer/index.md)<[Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)>): [ConfigBuilder](index.md)<[C](index.md), [A](index.md), [R](index.md)>  <br><br><br>
| [post](post.md)| [jvm]  <br>Brief description  <br><br><br>发起POST请求<br><br>  <br>Content  <br>fun [post](post.md)(action: [A](index.md)): [Invocation](../-invocation/index.md)<[A](index.md), [R](index.md)>  <br><br><br>
| [query](query.md)| [jvm]  <br>Brief description  <br><br><br>设置查询数据<br><br>  <br>Content  <br>fun [query](query.md)(data: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)): [ConfigBuilder](index.md)<[C](index.md), [A](index.md), [R](index.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>根据回调设置查询数据<br><br>  <br>Content  <br>fun [query](query.md)(creator: [Producer](../../tech.whence.echo.function/-producer/index.md)<[Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)>): [ConfigBuilder](index.md)<[C](index.md), [A](index.md), [R](index.md)>  <br><br><br>
| [require](require.md)| [jvm]  <br>Brief description  <br><br><br>设置结果类<br><br>  <br>Content  <br>fun [require](require.md)(resultClass: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[R](index.md)>): [ConfigBuilder](index.md)<[C](index.md), [A](index.md), [R](index.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置结果类型<br><br>  <br>Content  <br>fun [require](require.md)(resultType: [ResultType](../-result-type/index.md)<[R](index.md)>): [ConfigBuilder](index.md)<[C](index.md), [A](index.md), [R](index.md)>  <br><br><br>
| [retry](retry.md)| [jvm]  <br>Brief description  <br><br><br>设置重试策略<br><br>  <br>Content  <br>fun [retry](retry.md)(retry: [Retry](../../tech.whence.echo.retry/-retry/index.md)): [ConfigBuilder](index.md)<[C](index.md), [A](index.md), [R](index.md)>  <br><br><br>
| [timeout](timeout.md)| [jvm]  <br>Brief description  <br><br><br>设置每次请求超时时间<br><br>  <br>Content  <br>fun [timeout](timeout.md)(duration: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)): [ConfigBuilder](index.md)<[C](index.md), [A](index.md), [R](index.md)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [unsuccessfully](unsuccessfully.md)| [jvm]  <br>Brief description  <br><br><br>指定业务失败时的可重试设置<br><br>  <br>Content  <br>fun [unsuccessfully](unsuccessfully.md)(vararg retries: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [ResponseRetry](../../tech.whence.echo.webclient.response/-response-retry/index.md)>): [ConfigBuilder](index.md)<[C](index.md), [A](index.md), [R](index.md)>  <br><br><br>

