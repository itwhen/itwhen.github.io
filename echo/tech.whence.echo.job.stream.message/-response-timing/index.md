---
title: ResponseTiming -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.message](../index.md)/[ResponseTiming](index.md)



# ResponseTiming  
 [jvm] 

消息响应时机

enum [ResponseTiming](index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[ResponseTiming](index.md)>    


## Entries  
  
|  Name|  Summary| 
|---|---|
| [WHEN_MESSAGE_PROVIDED](-w-h-e-n_-m-e-s-s-a-g-e_-p-r-o-v-i-d-e-d/index.md)|  [jvm] <br><br>消息提供时<br><br>[WHEN_MESSAGE_PROVIDED](-w-h-e-n_-m-e-s-s-a-g-e_-p-r-o-v-i-d-e-d/index.md)()  <br>  <br>   <br>
| [WHEN_MESSAGES_WORKED](-w-h-e-n_-m-e-s-s-a-g-e-s_-w-o-r-k-e-d/index.md)|  [jvm] <br><br>消息消费时<br><br>[WHEN_MESSAGES_WORKED](-w-h-e-n_-m-e-s-s-a-g-e-s_-w-o-r-k-e-d/index.md)(Stage.WORKING)  <br>  <br>   <br>
| [WHEN_MESSAGE_RESPONDED](-w-h-e-n_-m-e-s-s-a-g-e_-r-e-s-p-o-n-d-e-d/index.md)|  [jvm] <br><br>消息响应<br><br>[WHEN_MESSAGE_RESPONDED](-w-h-e-n_-m-e-s-s-a-g-e_-r-e-s-p-o-n-d-e-d/index.md)()  <br>  <br>   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [compareTo](-w-h-e-n_-m-e-s-s-a-g-e_-r-e-s-p-o-n-d-e-d/index.md#kotlin/Enum/compareTo/#tech.whence.echo.job.stream.message.ResponseTiming/PointingToDeclaration/)| [jvm]  <br>Content  <br>operator override fun [compareTo](-w-h-e-n_-m-e-s-s-a-g-e_-r-e-s-p-o-n-d-e-d/index.md#kotlin/Enum/compareTo/#tech.whence.echo.job.stream.message.ResponseTiming/PointingToDeclaration/)(other: [ResponseTiming](index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>operator override fun [equals](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [finalize](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/finalize/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [finalize](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/finalize/#/PointingToDeclaration/)()  <br><br><br>
| [getDeclaringClass](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/getDeclaringClass/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [getDeclaringClass](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/getDeclaringClass/#/PointingToDeclaration/)(): [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[ResponseTiming](index.md)>  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [hashCode](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [valid](valid.md)| [jvm]  <br>Brief description  <br><br><br>判断指定阶段是否符合时机<br><br>  <br>Content  <br>fun [valid](valid.md)(stage: [Stage](../../tech.whence.echo.job.stream.provider/-stage/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [name](index.md#tech.whence.echo.job.stream.message/ResponseTiming/name/#/PointingToDeclaration/)|  [jvm] override val [name](index.md#tech.whence.echo.job.stream.message/ResponseTiming/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [ordinal](index.md#tech.whence.echo.job.stream.message/ResponseTiming/ordinal/#/PointingToDeclaration/)|  [jvm] override val [ordinal](index.md#tech.whence.echo.job.stream.message/ResponseTiming/ordinal/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>

