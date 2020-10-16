---
title: Reply -
---
//[echo](../../index.md)/[tech.whence.echo.container](../index.md)/[Reply](index.md)



# Reply  
 [jvm] 

响应

class [Reply](index.md)<[V](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| V| <br><br>值类型<br><br>
  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [analyze](analyze.md)| [jvm]  <br>Brief description  <br><br><br>分析异常<br><br>  <br>Content  <br>fun [analyze](analyze.md)(handler: [Handler](../../tech.whence.echo.function/-handler/index.md)<[Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)>): [Reply](index.md)<[V](index.md)>  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [filter](filter.md)| [jvm]  <br>Brief description  <br><br><br>过滤<br><br>  <br>Content  <br>fun [filter](filter.md)(predicate: [Predicate](../../tech.whence.echo.function/-predicate/index.md)<[V](index.md)>): [Reply](index.md)<[V](index.md)>  <br><br><br>
| [get](get.md)| [jvm]  <br>Brief description  <br><br><br>取值<br><br>  <br>Content  <br>fun [get](get.md)(): [V](index.md)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [into](into.md)| [jvm]  <br>Brief description  <br><br><br>若无异常且非空值则执行回调<br><br>  <br>Content  <br>fun <[R](into.md)> [into](into.md)(transformer: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[V](index.md), [R](into.md)?>): [R](into.md)?  <br><br><br>
| [invoke](invoke.md)| [jvm]  <br>Brief description  <br><br><br>返回非空结果 若有异常先抛出 再检查结果是否为空<br><br>  <br>Content  <br>operator fun [invoke](invoke.md)(): [V](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>若异常或者空值时返回指定默认值<br><br>  <br>Content  <br>operator fun [invoke](invoke.md)(default: [V](index.md)): [V](index.md)  <br><br><br>
| [map](map.md)| [jvm]  <br>Brief description  <br><br><br>转换到另一个结果<br><br>  <br>Content  <br>fun <[R](map.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [map](map.md)(transformer: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[V](index.md), [R](map.md)?>): [Reply](index.md)<[R](map.md)>  <br><br><br>
| [orCatch](or-catch.md)| [jvm]  <br>Brief description  <br><br><br>若异常时执行回调<br><br>  <br>Content  <br>fun [orCatch](or-catch.md)(transformer: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html), [V](index.md)?>): [V](index.md)?  <br><br><br>
| [orElse](or-else.md)| [jvm]  <br>Brief description  <br><br><br>若异常或者空值时返回指定默认值<br><br>  <br>Content  <br>fun [orElse](or-else.md)(default: [V](index.md)): [V](index.md)  <br>fun [orElse](or-else.md)(default: [Producer](../../tech.whence.echo.function/-producer/index.md)<[V](index.md)>): [V](index.md)  <br><br><br>
| [orFail](or-fail.md)| [jvm]  <br>Brief description  <br><br><br>若异常时直接抛出业务错误<br><br>  <br>Content  <br>fun [orFail](or-fail.md)(failure: [Producer](../../tech.whence.echo.function/-producer/index.md)<[Failure](../../tech.whence.echo.rpc.response/-failure/index.md)>): [V](index.md)  <br><br><br>
| [orNull](or-null.md)| [jvm]  <br>Brief description  <br><br><br>若异常时返回空<br><br>  <br>Content  <br>fun [orNull](or-null.md)(): [V](index.md)?  <br><br><br>
| [orThrow](or-throw.md)| [jvm]  <br>Brief description  <br><br><br>若异常时直接抛出<br><br>  <br>Content  <br>fun [orThrow](or-throw.md)(): [V](index.md)  <br>fun [orThrow](or-throw.md)(message: [Producer](../../tech.whence.echo.function/-producer/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>): [V](index.md)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [exception](index.md#tech.whence.echo.container/Reply/exception/#/PointingToDeclaration/)|  [jvm] <br><br>Throwable? 异常<br><br>val [exception](index.md#tech.whence.echo.container/Reply/exception/#/PointingToDeclaration/): [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)?   <br>
| [message](index.md#tech.whence.echo.container/Reply/message/#/PointingToDeclaration/)|  [jvm] <br><br>Producer<String>? 消息提供<br><br>val [message](index.md#tech.whence.echo.container/Reply/message/#/PointingToDeclaration/): [Producer](../../tech.whence.echo.function/-producer/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>?   <br>
| [present](index.md#tech.whence.echo.container/Reply/present/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否有值<br><br>val [present](index.md#tech.whence.echo.container/Reply/present/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [value](index.md#tech.whence.echo.container/Reply/value/#/PointingToDeclaration/)|  [jvm] <br><br>V? 查询结果<br><br>val [value](index.md#tech.whence.echo.container/Reply/value/#/PointingToDeclaration/): [V](index.md)?   <br>

