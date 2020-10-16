---
title: Style -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.api](../index.md)/[Style](index.md)



# Style  
 [jvm] 

样式

enum [Style](index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Style](index.md)>    


## Entries  
  
|  Name|  Summary| 
|---|---|
| [Id](-id/index.md)|  [jvm] <br><br>id<br><br>[Id](-id/index.md)({ it.type("string").pattern("[A-Z0-9]+") })  <br>  <br>   <br>
| [Ip](-ip/index.md)|  [jvm] <br><br>ip<br><br>[Ip](-ip/index.md)({ it.type("string").pattern(Validation.REGEX_IP.pattern) })  <br>  <br>   <br>
| [Url](-url/index.md)|  [jvm] <br><br>url<br><br>[Url](-url/index.md)({ it.type("string").pattern(Validation.REGEX_URL.pattern) })  <br>  <br>   <br>
| [Email](-email/index.md)|  [jvm] <br><br>email<br><br>[Email](-email/index.md)({ it.type("string").format("email") })  <br>  <br>   <br>
| [Mobile](-mobile/index.md)|  [jvm] <br><br>手机<br><br>[Mobile](-mobile/index.md)({ it.type("string").pattern(Validation.REGEX_MOBILE.pattern) })  <br>  <br>   <br>
| [Telephone](-telephone/index.md)|  [jvm] <br><br>电话<br><br>[Telephone](-telephone/index.md)({ it.type("string").pattern(Validation.REGEX_TELEPHONE.pattern) })  <br>  <br>   <br>
| [None](-none/index.md)|  [jvm] <br><br>无<br><br>[None](-none/index.md)({ it })  <br>  <br>   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [compareTo](-none/index.md#kotlin/Enum/compareTo/#tech.whence.echo.rpc.api.Style/PointingToDeclaration/)| [jvm]  <br>Content  <br>operator override fun [compareTo](-none/index.md#kotlin/Enum/compareTo/#tech.whence.echo.rpc.api.Style/PointingToDeclaration/)(other: [Style](index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>operator override fun [equals](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [finalize](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/finalize/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [finalize](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/finalize/#/PointingToDeclaration/)()  <br><br><br>
| [getDeclaringClass](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/getDeclaringClass/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [getDeclaringClass](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/getDeclaringClass/#/PointingToDeclaration/)(): [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[Style](index.md)>  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [hashCode](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [invoke](invoke.md)| [jvm]  <br>Brief description  <br><br><br>调用<br><br>  <br>Content  <br>operator fun [invoke](invoke.md)(schema: Schema<*>): Schema<*>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [name](index.md#tech.whence.echo.rpc.api/Style/name/#/PointingToDeclaration/)|  [jvm] override val [name](index.md#tech.whence.echo.rpc.api/Style/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [ordinal](index.md#tech.whence.echo.rpc.api/Style/ordinal/#/PointingToDeclaration/)|  [jvm] override val [ordinal](index.md#tech.whence.echo.rpc.api/Style/ordinal/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>

