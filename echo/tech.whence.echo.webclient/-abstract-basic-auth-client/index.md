---
title: AbstractBasicAuthClient -
---
//[echo](../../index.md)/[tech.whence.echo.webclient](../index.md)/[AbstractBasicAuthClient](index.md)



# AbstractBasicAuthClient  
 [jvm] 

抽象基础授权客户端

abstract class [AbstractBasicAuthClient](index.md)<[C](index.md) : [AbstractBasicAuthClient](index.md)<[C](index.md), [A](index.md)>, [A](index.md) : [Actable](../-actable/index.md)>(**environment**: [Environment](../../tech.whence.echo.support/-environment/index.md), **allowedRequestMethods**: [EnumSet](https://docs.oracle.com/javase/8/docs/api/java/util/EnumSet.html)<[Request.Method](../../tech.whence.echo.webclient.request/-request/-method/index.md)>?, **responseType**: [Response.Type](../../tech.whence.echo.webclient.response/-response/-type/index.md)?, **logger**: Logger?) : [AbstractPasswordifyClient](../-abstract-passwordify-client/index.md)<[C](index.md), [A](index.md)>    


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| A| <br><br>: Action<br><br>
| C| <br><br>: AbstractBasicAuthClient<C, A><br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [AbstractBasicAuthClient](-abstract-basic-auth-client.md)|  [jvm] <br><br><br><br>fun [AbstractBasicAuthClient](-abstract-basic-auth-client.md)(environment: [Environment](../../tech.whence.echo.support/-environment/index.md), allowedRequestMethods: [EnumSet](https://docs.oracle.com/javase/8/docs/api/java/util/EnumSet.html)<[Request.Method](../../tech.whence.echo.webclient.request/-request/-method/index.md)>?, responseType: [Response.Type](../../tech.whence.echo.webclient.response/-response/-type/index.md)?, logger: Logger?)   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [authorize](../-abstract-tokenify-client/index.md#tech.whence.echo.webclient/AbstractAuthorizableClient/authorize/#tech.whence.echo.support.Environment#tech.whence.echo.webclient.Authorization/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>设置授权<br><br>  <br>Content  <br>override fun [authorize](../-abstract-tokenify-client/index.md#tech.whence.echo.webclient/AbstractAuthorizableClient/authorize/#tech.whence.echo.support.Environment#tech.whence.echo.webclient.Authorization/PointingToDeclaration/)(environment: [Environment](../../tech.whence.echo.support/-environment/index.md), authorization: [Authorization](../-authorization/index.md)): [C](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>添加授权<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>override fun [authorize](../-abstract-passwordify-client/authorize.md)(environment: [Environment](../../tech.whence.echo.support/-environment/index.md), user: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), password: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [C](index.md)  <br><br><br>
| [authorized](../-abstract-authorizable-client/authorized.md)| [jvm]  <br>Brief description  <br><br><br>获取当前环境下的授权信息<br><br>  <br>Content  <br>override fun [authorized](../-abstract-authorizable-client/authorized.md)(): [Authorization](../-authorization/index.md)  <br><br><br>
| [configure](../-abstract-client/configure.md)| [jvm]  <br>Brief description  <br><br><br>配置<br><br>  <br>Content  <br>override fun [configure](../-abstract-client/configure.md)(configurer: [RequestConfigurer](../../tech.whence.echo.webclient.request/-request-configurer/index.md)): [C](index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [get](../-abstract-client/get.md)| [jvm]  <br>Brief description  <br><br><br>发送GET请求<br><br>  <br>Content  <br>inline override fun <R : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [get](../-abstract-client/get.md)(action: [A](index.md)): [Invocation](../-invocation/index.md)<[A](index.md), R>  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [invoke](../-abstract-client/invoke.md)| [jvm]  <br>Brief description  <br><br><br>调用<br><br>  <br>Content  <br>open operator override fun <R : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [invoke](../-abstract-client/invoke.md)(config: [Config](../-config/index.md)<[A](index.md), R>): [Invocation](../-invocation/index.md)<[A](index.md), R>  <br><br><br>
| [mock](../-abstract-client/mock.md)| [jvm]  <br>Brief description  <br><br><br>模拟请求<br><br>  <br>Content  <br>override fun [mock](../-abstract-client/mock.md)(config: [Config](../-config/index.md)<[A](index.md), *>, request: [Request](../../tech.whence.echo.webclient.request/-request/index.md)<[A](index.md)>, purpose: [ResponseMocker.Purpose](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/index.md)): [Response](../../tech.whence.echo.webclient.response/-response/index.md)?  <br><br><br>
| [post](../-abstract-client/post.md)| [jvm]  <br>Brief description  <br><br><br>发送POST请求<br><br>  <br>Content  <br>inline override fun <R : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [post](../-abstract-client/post.md)(action: [A](index.md), parameters: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)): [Invocation](../-invocation/index.md)<[A](index.md), R>  <br><br><br>
| [require](../-abstract-client/require.md)| [jvm]  <br>Brief description  <br><br><br>设置结果类型要求<br><br>  <br>Content  <br>inline override fun <R : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [require](../-abstract-client/require.md)(): [ConfigBuilder](../-config-builder/index.md)<[C](index.md), [A](index.md), R>  <br>override fun <R : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [require](../-abstract-client/require.md)(clazz: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<R>): [ConfigBuilder](../-config-builder/index.md)<[C](index.md), [A](index.md), R>  <br>override fun <R : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [require](../-abstract-client/require.md)(klass: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<R>): [ConfigBuilder](../-config-builder/index.md)<[C](index.md), [A](index.md), R>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

