---
title: AbstractClient -
---
//[echo](../../index.md)/[tech.whence.echo.webclient](../index.md)/[AbstractClient](index.md)



# AbstractClient  
 [jvm] 

抽象客户端

abstract class [AbstractClient](index.md)<[C](index.md) : [AbstractClient](index.md)<[C](index.md), [A](index.md)>, [A](index.md) : [Actable](../-actable/index.md)>(**environment**: [Environment](../../tech.whence.echo.support/-environment/index.md), **allowedRequestMethods**: [EnumSet](https://docs.oracle.com/javase/8/docs/api/java/util/EnumSet.html)<[Request.Method](../../tech.whence.echo.webclient.request/-request/-method/index.md)>?, **responseType**: [Response.Type](../../tech.whence.echo.webclient.response/-response/-type/index.md)?, **logger**: Logger?) : [Client](../-client/index.md)<[C](index.md), [A](index.md)>    


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| A| <br><br>行为<br><br>
| C| <br><br>客户端<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [AbstractClient](-abstract-client.md)|  [jvm] <br><br><br><br>fun [AbstractClient](-abstract-client.md)(environment: [Environment](../../tech.whence.echo.support/-environment/index.md), allowedRequestMethods: [EnumSet](https://docs.oracle.com/javase/8/docs/api/java/util/EnumSet.html)<[Request.Method](../../tech.whence.echo.webclient.request/-request/-method/index.md)>?, responseType: [Response.Type](../../tech.whence.echo.webclient.response/-response/-type/index.md)?, logger: Logger?)   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [configure](configure.md)| [jvm]  <br>Brief description  <br><br><br>配置<br><br>  <br>Content  <br>fun [configure](configure.md)(configurer: [RequestConfigurer](../../tech.whence.echo.webclient.request/-request-configurer/index.md)): [C](index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [get](get.md)| [jvm]  <br>Brief description  <br><br><br>发送GET请求<br><br>  <br>Content  <br>inline fun <[R](get.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [get](get.md)(action: [A](index.md)): [Invocation](../-invocation/index.md)<[A](index.md), [R](get.md)>  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [invoke](invoke.md)| [jvm]  <br>Brief description  <br><br><br>调用<br><br>  <br>Content  <br>open operator override fun <[R](invoke.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [invoke](invoke.md)(config: [Config](../-config/index.md)<[A](index.md), [R](invoke.md)>): [Invocation](../-invocation/index.md)<[A](index.md), [R](invoke.md)>  <br><br><br>
| [mock](mock.md)| [jvm]  <br>Brief description  <br><br><br>模拟请求<br><br>  <br>Content  <br>fun [mock](mock.md)(config: [Config](../-config/index.md)<[A](index.md), *>, request: [Request](../../tech.whence.echo.webclient.request/-request/index.md)<[A](index.md)>, purpose: [ResponseMocker.Purpose](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/index.md)): [Response](../../tech.whence.echo.webclient.response/-response/index.md)?  <br><br><br>
| [post](post.md)| [jvm]  <br>Brief description  <br><br><br>发送POST请求<br><br>  <br>Content  <br>inline fun <[R](post.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [post](post.md)(action: [A](index.md), parameters: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)): [Invocation](../-invocation/index.md)<[A](index.md), [R](post.md)>  <br><br><br>
| [require](require.md)| [jvm]  <br>Brief description  <br><br><br>设置结果类型要求<br><br>  <br>Content  <br>inline fun <[R](require.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [require](require.md)(): [ConfigBuilder](../-config-builder/index.md)<[C](index.md), [A](index.md), [R](require.md)>  <br>fun <[R](require.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [require](require.md)(clazz: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[R](require.md)>): [ConfigBuilder](../-config-builder/index.md)<[C](index.md), [A](index.md), [R](require.md)>  <br>fun <[R](require.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [require](require.md)(klass: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[R](require.md)>): [ConfigBuilder](../-config-builder/index.md)<[C](index.md), [A](index.md), [R](require.md)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Inheritors  
  
|  Name| 
|---|
| [AbstractAuthorizableClient](../-abstract-authorizable-client/index.md)

