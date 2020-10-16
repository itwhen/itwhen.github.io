---
title: Request -
---
//[echo](../../index.md)/[tech.whence.echo.webclient.request](../index.md)/[Request](index.md)



# Request  
 [jvm] 

请求类 用于保存请求数据

class [Request](index.md)<[A](index.md) : [Actable](../../tech.whence.echo.webclient/-actable/index.md)>   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| A| <br><br>: Action 请求行为<br><br>
  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>
| [Method](-method/index.md)| [jvm]  <br>Brief description  <br><br><br>请求方法<br><br>  <br>Content  <br>enum [Method](-method/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Request.Method](-method/index.md)>   <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [freeze](freeze.md)| [jvm]  <br>Brief description  <br><br><br>冻结<br><br>  <br>Content  <br>fun [freeze](freeze.md)(): [Request](index.md)<[A](index.md)>  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [renew](renew.md)| [jvm]  <br>Brief description  <br><br><br>重试<br><br>  <br>Content  <br>fun [renew](renew.md)(): [Request](index.md)<[A](index.md)>  <br><br><br>
| [toString](to-string.md)| [jvm]  <br>Content  <br>open override fun [toString](to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [action](index.md#tech.whence.echo.webclient.request/Request/action/#/PointingToDeclaration/)|  [jvm] <br><br>A 行为<br><br>val [action](index.md#tech.whence.echo.webclient.request/Request/action/#/PointingToDeclaration/): [A](index.md)   <br>
| [body](index.md#tech.whence.echo.webclient.request/Request/body/#/PointingToDeclaration/)|  [jvm] <br><br>RequestData 请求数据<br><br>val [body](index.md#tech.whence.echo.webclient.request/Request/body/#/PointingToDeclaration/): [RequestBody](../-request-body/index.md)   <br>
| [frozen](index.md#tech.whence.echo.webclient.request/Request/frozen/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否是冻结状态<br><br>var [frozen](index.md#tech.whence.echo.webclient.request/Request/frozen/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [headers](index.md#tech.whence.echo.webclient.request/Request/headers/#/PointingToDeclaration/)|  [jvm] <br><br>MutableMap<String, String> 请求头部参数<br><br>val [headers](index.md#tech.whence.echo.webclient.request/Request/headers/#/PointingToDeclaration/): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>   <br>
| [method](index.md#tech.whence.echo.webclient.request/Request/method/#/PointingToDeclaration/)|  [jvm] <br><br>Method 方法<br><br>val [method](index.md#tech.whence.echo.webclient.request/Request/method/#/PointingToDeclaration/): [Request.Method](-method/index.md)   <br>
| [query](index.md#tech.whence.echo.webclient.request/Request/query/#/PointingToDeclaration/)|  [jvm] <br><br>Accessor 查询数据<br><br>val [query](index.md#tech.whence.echo.webclient.request/Request/query/#/PointingToDeclaration/): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)   <br>
| [tried](index.md#tech.whence.echo.webclient.request/Request/tried/#/PointingToDeclaration/)|  [jvm] <br><br>Int 重试次数<br><br>var [tried](index.md#tech.whence.echo.webclient.request/Request/tried/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>
| [uri](index.md#tech.whence.echo.webclient.request/Request/uri/#/PointingToDeclaration/)|  [jvm] <br><br>URI 地址<br><br>var [uri](index.md#tech.whence.echo.webclient.request/Request/uri/#/PointingToDeclaration/): [URI](https://docs.oracle.com/javase/8/docs/api/java/net/URI.html)?   <br>

