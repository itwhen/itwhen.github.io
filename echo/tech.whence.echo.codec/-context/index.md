---
title: Context -
---
//[echo](../../index.md)/[tech.whence.echo.codec](../index.md)/[Context](index.md)



# Context  
 [jvm] 

上下文 存储解编过程中的键值/解编器定义/解编方式 提供解编顺序支持 提供解编跟踪支持

class [Context](index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **value**: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, **definition**: [Codec.Definition](../-codec/-definition/index.md), **method**: [Codec.Method](../-codec/-method/index.md), **traces**: [LinkedList](https://docs.oracle.com/javase/8/docs/api/java/util/LinkedList.html)<[Context.Trace](-trace/index.md)>)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Context](-context.md)|  [jvm] <br><br><br><br>fun [Context](-context.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, definition: [Codec.Definition](../-codec/-definition/index.md), method: [Codec.Method](../-codec/-method/index.md), traces: [LinkedList](https://docs.oracle.com/javase/8/docs/api/java/util/LinkedList.html)<[Context.Trace](-trace/index.md)>)   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Trace](-trace/index.md)| [jvm]  <br>Brief description  <br><br><br>跟踪数据<br><br>  <br>Content  <br>data class [Trace](-trace/index.md)(**handler**: [Codec](../-codec/index.md)?, **from**: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, **to**: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [lead](lead.md)| [jvm]  <br>Brief description  <br><br><br>前置处理 若值为空不处理 若解码时遍历所有解编器解码指定值 若有编码器将指定值处理为空则返回假 若编码时仅判断是否可处理指定值 其他返回真<br><br>  <br>Content  <br>fun [lead](lead.md)(transfers: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Codec](../-codec/index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [tail](tail.md)| [jvm]  <br>Brief description  <br><br><br>后置处理 若编码时反向遍历所有解码器编码指定值<br><br>  <br>Content  <br>fun [tail](tail.md)(transfers: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Codec](../-codec/index.md)>)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [trace](trace.md)| [jvm]  <br>Brief description  <br><br><br>记录跟踪信息 当处理后的值为空时返回假告知不可继续处理<br><br>  <br>Content  <br>fun [trace](trace.md)(handler: [Codec](../-codec/index.md)?, value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [definition](index.md#tech.whence.echo.codec/Context/definition/#/PointingToDeclaration/)|  [jvm] <br><br>Definition 解编器定义<br><br>val [definition](index.md#tech.whence.echo.codec/Context/definition/#/PointingToDeclaration/): [Codec.Definition](../-codec/-definition/index.md)   <br>
| [method](index.md#tech.whence.echo.codec/Context/method/#/PointingToDeclaration/)|  [jvm] <br><br>Method 指定解编方法<br><br>val [method](index.md#tech.whence.echo.codec/Context/method/#/PointingToDeclaration/): [Codec.Method](../-codec/-method/index.md)   <br>
| [name](index.md#tech.whence.echo.codec/Context/name/#/PointingToDeclaration/)|  [jvm] <br><br>String 键名<br><br>val [name](index.md#tech.whence.echo.codec/Context/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [traces](index.md#tech.whence.echo.codec/Context/traces/#/PointingToDeclaration/)|  [jvm] <br><br>LinkedList<Trace> 跟踪信息存储<br><br>val [traces](index.md#tech.whence.echo.codec/Context/traces/#/PointingToDeclaration/): [LinkedList](https://docs.oracle.com/javase/8/docs/api/java/util/LinkedList.html)<[Context.Trace](-trace/index.md)>   <br>
| [value](index.md#tech.whence.echo.codec/Context/value/#/PointingToDeclaration/)|  [jvm] <br><br>Any? 待解编值<br><br>var [value](index.md#tech.whence.echo.codec/Context/value/#/PointingToDeclaration/): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?   <br>

