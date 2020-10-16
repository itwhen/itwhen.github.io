---
title: Generator -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.api](../index.md)/[Generator](index.md)



# Generator  
 [jvm] 

生成器

class [Generator](index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Generator](-generator.md)|  [jvm] fun [Generator](-generator.md)()   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [describe](describe.md)| [jvm]  <br>Brief description  <br><br><br>初始化<br><br>  <br>Content  <br>fun [describe](describe.md)(title: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), version: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Generator](index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [format](format.md)| [jvm]  <br>Brief description  <br><br><br>格式化<br><br>  <br>Content  <br>fun [format](format.md)(api: OpenAPI, format: [Format](../-format/index.md)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [generate](generate.md)| [jvm]  <br>Brief description  <br><br><br>生成文档<br><br>  <br>Content  <br>fun [generate](generate.md)(): OpenAPI  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [into](into.md)| [jvm]  <br>Brief description  <br><br><br>保存到指定目录<br><br>  <br>Content  <br>fun [into](into.md)(file: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), format: [Format](../-format/index.md))  <br><br><br>
| [parse](parse.md)| [jvm]  <br>Brief description  <br><br><br>解析指定类<br><br>  <br>Content  <br>fun [parse](parse.md)(declarer: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<*>): [Generator](index.md)  <br>fun [parse](parse.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>): [Generator](index.md)  <br><br><br>
| [secure](secure.md)| [jvm]  <br>Brief description  <br><br><br>设置安全策略<br><br>  <br>Content  <br>fun [secure](secure.md)(schemes: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), SecurityScheme>, requirement: SecurityRequirement): [Generator](index.md)  <br><br><br>
| [serve](serve.md)| [jvm]  <br>Brief description  <br><br><br>增加服务器选项<br><br>  <br>Content  <br>fun [serve](serve.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), url: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Generator](index.md)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

