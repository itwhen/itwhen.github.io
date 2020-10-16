---
title: RequestBody -
---
//[echo](../../index.md)/[tech.whence.echo.webclient.request](../index.md)/[RequestBody](index.md)



# RequestBody  
 [jvm] 

请求数据

class [RequestBody](index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [RequestBody](-request-body.md)|  [jvm] fun [RequestBody](-request-body.md)()   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [clear](clear.md)| [jvm]  <br>Brief description  <br><br><br>清理<br><br>  <br>Content  <br>fun [clear](clear.md)()  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [setBinary](set-binary.md)| [jvm]  <br>Brief description  <br><br><br>设置二进制内容<br><br>  <br>Content  <br>fun [setBinary](set-binary.md)(data: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)): [RequestBody](index.md)  <br><br><br>
| [setFile](set-file.md)| [jvm]  <br>Brief description  <br><br><br>设置文件内容<br><br>  <br>Content  <br>fun [setFile](set-file.md)(data: AsyncFile): [RequestBody](index.md)  <br><br><br>
| [setJson](set-json.md)| [jvm]  <br>Brief description  <br><br><br>设置 JsonObject<br><br>  <br>Content  <br>fun [setJson](set-json.md)(data: JsonObject): [RequestBody](index.md)  <br><br><br>
| [setParameters](set-parameters.md)| [jvm]  <br>Brief description  <br><br><br>设置Form参数<br><br>  <br>Content  <br>fun [setParameters](set-parameters.md)(data: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)): [RequestBody](index.md)  <br><br><br>
| [setStream](set-stream.md)| [jvm]  <br>Brief description  <br><br><br>设置输入流<br><br>  <br>Content  <br>fun [setStream](set-stream.md)(data: ReadStream<Buffer>): [RequestBody](index.md)  <br><br><br>
| [setText](set-text.md)| [jvm]  <br>Brief description  <br><br><br>设置文本内容<br><br>  <br>Content  <br>fun [setText](set-text.md)(data: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [RequestBody](index.md)  <br><br><br>
| [toString](to-string.md)| [jvm]  <br>Content  <br>open override fun [toString](to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [binary](index.md#tech.whence.echo.webclient.request/RequestBody/binary/#/PointingToDeclaration/)|  [jvm] <br><br>ByteArray? 二进制内容<br><br>var [binary](index.md#tech.whence.echo.webclient.request/RequestBody/binary/#/PointingToDeclaration/): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)?   <br>
| [file](index.md#tech.whence.echo.webclient.request/RequestBody/file/#/PointingToDeclaration/)|  [jvm] <br><br>AsyncFile? 文件内容<br><br>var [file](index.md#tech.whence.echo.webclient.request/RequestBody/file/#/PointingToDeclaration/): AsyncFile?   <br>
| [json](index.md#tech.whence.echo.webclient.request/RequestBody/json/#/PointingToDeclaration/)|  [jvm] <br><br>JsonObject? JSON<br><br>var [json](index.md#tech.whence.echo.webclient.request/RequestBody/json/#/PointingToDeclaration/): JsonObject?   <br>
| [parameters](index.md#tech.whence.echo.webclient.request/RequestBody/parameters/#/PointingToDeclaration/)|  [jvm] <br><br>Accessor? 表单参数<br><br>var [parameters](index.md#tech.whence.echo.webclient.request/RequestBody/parameters/#/PointingToDeclaration/): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)?   <br>
| [stream](index.md#tech.whence.echo.webclient.request/RequestBody/stream/#/PointingToDeclaration/)|  [jvm] <br><br>ReadStream<Buffer>? 输入流<br><br>var [stream](index.md#tech.whence.echo.webclient.request/RequestBody/stream/#/PointingToDeclaration/): ReadStream<Buffer>?   <br>
| [text](index.md#tech.whence.echo.webclient.request/RequestBody/text/#/PointingToDeclaration/)|  [jvm] <br><br>String? 文本内容<br><br>var [text](index.md#tech.whence.echo.webclient.request/RequestBody/text/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>

