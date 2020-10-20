---
title: tech.whence.echo.webclient -
---
//[echo](../index.md)/[tech.whence.echo.webclient](index.md)



# Package tech.whence.echo.webclient  


## Types  
  
|  Name|  Summary| 
|---|---|
| [AbstractAuthorizableClient](-abstract-authorizable-client/index.md)| [jvm]  <br>Brief description  <br><br><br>抽象可授权客户端<br><br>  <br>Content  <br>abstract class [AbstractAuthorizableClient](-abstract-authorizable-client/index.md)<[C](-abstract-authorizable-client/index.md) : [AbstractAuthorizableClient](-abstract-authorizable-client/index.md)<[C](-abstract-authorizable-client/index.md), [A](-abstract-authorizable-client/index.md), [T](-abstract-authorizable-client/index.md)>, [A](-abstract-authorizable-client/index.md) : [Actable](-actable/index.md), [T](-abstract-authorizable-client/index.md)>(**environment**: [Environment](../tech.whence.echo.support/-environment/index.md), **allowedRequestMethods**: [EnumSet](https://docs.oracle.com/javase/8/docs/api/java/util/EnumSet.html)<[Request.Method](../tech.whence.echo.webclient.request/-request/-method/index.md)>?, **responseType**: [Response.Type](../tech.whence.echo.webclient.response/-response/-type/index.md)?, **logger**: Logger?) : [AbstractClient](-abstract-client/index.md)<[C](-abstract-authorizable-client/index.md), [A](-abstract-authorizable-client/index.md)>   <br><br><br>
| [AbstractBasicAuthClient](-abstract-basic-auth-client/index.md)| [jvm]  <br>Brief description  <br><br><br>抽象基础授权客户端<br><br>  <br>Content  <br>abstract class [AbstractBasicAuthClient](-abstract-basic-auth-client/index.md)<[C](-abstract-basic-auth-client/index.md) : [AbstractBasicAuthClient](-abstract-basic-auth-client/index.md)<[C](-abstract-basic-auth-client/index.md), [A](-abstract-basic-auth-client/index.md)>, [A](-abstract-basic-auth-client/index.md) : [Actable](-actable/index.md)>(**environment**: [Environment](../tech.whence.echo.support/-environment/index.md), **allowedRequestMethods**: [EnumSet](https://docs.oracle.com/javase/8/docs/api/java/util/EnumSet.html)<[Request.Method](../tech.whence.echo.webclient.request/-request/-method/index.md)>?, **responseType**: [Response.Type](../tech.whence.echo.webclient.response/-response/-type/index.md)?, **logger**: Logger?) : [AbstractPasswordifyClient](-abstract-passwordify-client/index.md)<[C](-abstract-basic-auth-client/index.md), [A](-abstract-basic-auth-client/index.md)>   <br><br><br>
| [AbstractClient](-abstract-client/index.md)| [jvm]  <br>Brief description  <br><br><br>抽象客户端<br><br>  <br>Content  <br>abstract class [AbstractClient](-abstract-client/index.md)<[C](-abstract-client/index.md) : [AbstractClient](-abstract-client/index.md)<[C](-abstract-client/index.md), [A](-abstract-client/index.md)>, [A](-abstract-client/index.md) : [Actable](-actable/index.md)>(**environment**: [Environment](../tech.whence.echo.support/-environment/index.md), **allowedRequestMethods**: [EnumSet](https://docs.oracle.com/javase/8/docs/api/java/util/EnumSet.html)<[Request.Method](../tech.whence.echo.webclient.request/-request/-method/index.md)>?, **responseType**: [Response.Type](../tech.whence.echo.webclient.response/-response/-type/index.md)?, **logger**: Logger?) : [Client](-client/index.md)<[C](-abstract-client/index.md), [A](-abstract-client/index.md)>   <br><br><br>
| [AbstractPasswordifyClient](-abstract-passwordify-client/index.md)| [jvm]  <br>Brief description  <br><br><br>抽象账号密码验证客户端<br><br>  <br>Content  <br>abstract class [AbstractPasswordifyClient](-abstract-passwordify-client/index.md)<[C](-abstract-passwordify-client/index.md) : [AbstractPasswordifyClient](-abstract-passwordify-client/index.md)<[C](-abstract-passwordify-client/index.md), [A](-abstract-passwordify-client/index.md)>, [A](-abstract-passwordify-client/index.md) : [Actable](-actable/index.md)>(**environment**: [Environment](../tech.whence.echo.support/-environment/index.md), **allowedRequestMethods**: [EnumSet](https://docs.oracle.com/javase/8/docs/api/java/util/EnumSet.html)<[Request.Method](../tech.whence.echo.webclient.request/-request/-method/index.md)>?, **responseType**: [Response.Type](../tech.whence.echo.webclient.response/-response/-type/index.md)?, **logger**: Logger?) : [AbstractAuthorizableClient](-abstract-authorizable-client/index.md)<[C](-abstract-passwordify-client/index.md), [A](-abstract-passwordify-client/index.md), [Authorization](-authorization/index.md)>   <br><br><br>
| [AbstractTokenifyClient](-abstract-tokenify-client/index.md)| [jvm]  <br>Brief description  <br><br><br>抽象令牌验证客户端<br><br>  <br>Content  <br>abstract class [AbstractTokenifyClient](-abstract-tokenify-client/index.md)<[C](-abstract-tokenify-client/index.md) : [AbstractTokenifyClient](-abstract-tokenify-client/index.md)<[C](-abstract-tokenify-client/index.md), [A](-abstract-tokenify-client/index.md)>, [A](-abstract-tokenify-client/index.md) : [Actable](-actable/index.md)>(**environment**: [Environment](../tech.whence.echo.support/-environment/index.md), **allowedRequestMethods**: [EnumSet](https://docs.oracle.com/javase/8/docs/api/java/util/EnumSet.html)<[Request.Method](../tech.whence.echo.webclient.request/-request/-method/index.md)>?, **responseType**: [Response.Type](../tech.whence.echo.webclient.response/-response/-type/index.md)?, **logger**: Logger?) : [AbstractAuthorizableClient](-abstract-authorizable-client/index.md)<[C](-abstract-tokenify-client/index.md), [A](-abstract-tokenify-client/index.md), [Authorization](-authorization/index.md)>   <br><br><br>
| [Actable](-actable/index.md)| [jvm]  <br>Brief description  <br><br><br>行为<br><br>  <br>Content  <br>interface [Actable](-actable/index.md)  <br><br><br>
| [Authorization](-authorization/index.md)| [jvm]  <br>Brief description  <br><br><br>授权<br><br>  <br>Content  <br>data class [Authorization](-authorization/index.md)(**key**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **secret**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **token**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?)  <br><br><br>
| [Client](-client/index.md)| [jvm]  <br>Brief description  <br><br><br>客户端<br><br>  <br>Content  <br>interface [Client](-client/index.md)<[C](-client/index.md) : [Client](-client/index.md)<[C](-client/index.md), [A](-client/index.md)>, [A](-client/index.md) : [Actable](-actable/index.md)>  <br><br><br>
| [Config](-config/index.md)| [jvm]  <br>Brief description  <br><br><br>配置<br><br>  <br>Content  <br>class [Config](-config/index.md)<[A](-config/index.md) : [Actable](-actable/index.md), [R](-config/index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>  <br><br><br>
| [ConfigBuilder](-config-builder/index.md)| [jvm]  <br>Brief description  <br><br><br>配置构建器<br><br>  <br>Content  <br>class [ConfigBuilder](-config-builder/index.md)<[C](-config-builder/index.md) : [AbstractClient](-abstract-client/index.md)<[C](-config-builder/index.md), [A](-config-builder/index.md)>, [A](-config-builder/index.md) : [Actable](-actable/index.md), [R](-config-builder/index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>  <br><br><br>
| [ExceptionHandler](-exception-handler/index.md)| [jvm]  <br>Brief description  <br><br><br>异常处理器<br><br>  <br>Content  <br>fun fun interface [ExceptionHandler](-exception-handler/index.md)  <br><br><br>
| [Invocation](-invocation/index.md)| [jvm]  <br>Brief description  <br><br><br>调用<br><br>  <br>Content  <br>data class [Invocation](-invocation/index.md)<[A](-invocation/index.md) : [Actable](-actable/index.md), [R](-invocation/index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>(**request**: [Request](../tech.whence.echo.webclient.request/-request/index.md)<[A](-invocation/index.md)>, **response**: [Response](../tech.whence.echo.webclient.response/-response/index.md), **result**: [R](-invocation/index.md)?)  <br><br><br>
| [InvocationException](-invocation-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>调用异常<br><br>  <br>Content  <br>open class [InvocationException](-invocation-exception/index.md)(**message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **cause**: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)?, **retryable**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) : [RuntimeException](https://docs.oracle.com/javase/8/docs/api/java/lang/RuntimeException.html)  <br><br><br>
| [Operation](-operation/index.md)| [jvm]  <br>Brief description  <br><br><br>操作<br><br>  <br>Content  <br>enum [Operation](-operation/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Operation](-operation/index.md)>   <br><br><br>
| [ResultType](-result-type/index.md)| [jvm]  <br>Brief description  <br><br><br>结果类型<br><br>  <br>Content  <br>class [ResultType](-result-type/index.md)<[E](-result-type/index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>(**type**: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [E](-result-type/index.md)>)  <br><br><br>
