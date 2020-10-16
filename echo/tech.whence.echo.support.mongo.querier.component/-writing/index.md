---
title: Writing -
---
//[echo](../../index.md)/[tech.whence.echo.support.mongo.querier.component](../index.md)/[Writing](index.md)



# Writing  
 [jvm] 

写入策略

enum [Writing](index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Writing](index.md)>    


## Entries  
  
|  Name|  Summary| 
|---|---|
| [ACKNOWLEDGED](-a-c-k-n-o-w-l-e-d-g-e-d/index.md)|  [jvm] <br><br>默认<br><br>[ACKNOWLEDGED](-a-c-k-n-o-w-l-e-d-g-e-d/index.md)(WriteOption.ACKNOWLEDGED, WriteConcern.ACKNOWLEDGED)  <br>  <br>   <br>
| [UNACKNOWLEDGED](-u-n-a-c-k-n-o-w-l-e-d-g-e-d/index.md)|  [jvm] <br><br>不关注写入是否成功<br><br>[UNACKNOWLEDGED](-u-n-a-c-k-n-o-w-l-e-d-g-e-d/index.md)(WriteOption.UNACKNOWLEDGED, WriteConcern.UNACKNOWLEDGED)  <br>  <br>   <br>
| [MAJORITY](-m-a-j-o-r-i-t-y/index.md)|  [jvm] <br><br>多数节点成功就认为成功<br><br>[MAJORITY](-m-a-j-o-r-i-t-y/index.md)(WriteOption.MAJORITY, WriteConcern.MAJORITY)  <br>  <br>   <br>
| [JOURNALED](-j-o-u-r-n-a-l-e-d/index.md)|  [jvm] <br><br>写操作到journal文件才视作成功<br><br>[JOURNALED](-j-o-u-r-n-a-l-e-d/index.md)(WriteOption.JOURNALED, WriteConcern.JOURNALED)  <br>  <br>   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [compareTo](-j-o-u-r-n-a-l-e-d/index.md#kotlin/Enum/compareTo/#tech.whence.echo.support.mongo.querier.component.Writing/PointingToDeclaration/)| [jvm]  <br>Content  <br>operator override fun [compareTo](-j-o-u-r-n-a-l-e-d/index.md#kotlin/Enum/compareTo/#tech.whence.echo.support.mongo.querier.component.Writing/PointingToDeclaration/)(other: [Writing](index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [describe](describe.md)| [jvm]  <br>Brief description  <br><br><br>描述<br><br>  <br>Content  <br>fun [describe](describe.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>operator override fun [equals](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [finalize](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/finalize/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [finalize](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/finalize/#/PointingToDeclaration/)()  <br><br><br>
| [getDeclaringClass](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/getDeclaringClass/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [getDeclaringClass](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/getDeclaringClass/#/PointingToDeclaration/)(): [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[Writing](index.md)>  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [hashCode](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [concern](index.md#tech.whence.echo.support.mongo.querier.component/Writing/concern/#/PointingToDeclaration/)|  [jvm] <br><br>WriteConcern<br><br>val [concern](index.md#tech.whence.echo.support.mongo.querier.component/Writing/concern/#/PointingToDeclaration/): WriteConcern   <br>
| [name](index.md#tech.whence.echo.support.mongo.querier.component/Writing/name/#/PointingToDeclaration/)|  [jvm] override val [name](index.md#tech.whence.echo.support.mongo.querier.component/Writing/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [option](index.md#tech.whence.echo.support.mongo.querier.component/Writing/option/#/PointingToDeclaration/)|  [jvm] <br><br>WriteOption<br><br>val [option](index.md#tech.whence.echo.support.mongo.querier.component/Writing/option/#/PointingToDeclaration/): WriteOption   <br>
| [ordinal](index.md#tech.whence.echo.support.mongo.querier.component/Writing/ordinal/#/PointingToDeclaration/)|  [jvm] override val [ordinal](index.md#tech.whence.echo.support.mongo.querier.component/Writing/ordinal/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>

