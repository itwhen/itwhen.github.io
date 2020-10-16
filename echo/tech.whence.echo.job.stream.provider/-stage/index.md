---
title: Stage -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.provider](../index.md)/[Stage](index.md)



# Stage  
 [jvm] 

提供者阶段

enum [Stage](index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Stage](index.md)>    


## Entries  
  
|  Name|  Summary| 
|---|---|
| [READY](-r-e-a-d-y/index.md)|  [jvm] <br><br>准备<br><br>[READY](-r-e-a-d-y/index.md)(Collector.State.RUNNING, false)  <br>  <br>   <br>
| [WORKING](-w-o-r-k-i-n-g/index.md)|  [jvm] <br><br>工作中<br><br>[WORKING](-w-o-r-k-i-n-g/index.md)(Collector.State.RUNNING, true)  <br>  <br>   <br>
| [STOPPING](-s-t-o-p-p-i-n-g/index.md)|  [jvm] <br><br>停止中<br><br>[STOPPING](-s-t-o-p-p-i-n-g/index.md)(Collector.State.SUSPENDED, false)  <br>  <br>   <br>
| [STOPPED](-s-t-o-p-p-e-d/index.md)|  [jvm] <br><br>已停止<br><br>[STOPPED](-s-t-o-p-p-e-d/index.md)(Collector.State.CLOSED, false)  <br>  <br>   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [compareTo](-s-t-o-p-p-e-d/index.md#kotlin/Enum/compareTo/#tech.whence.echo.job.stream.provider.Stage/PointingToDeclaration/)| [jvm]  <br>Content  <br>operator override fun [compareTo](-s-t-o-p-p-e-d/index.md#kotlin/Enum/compareTo/#tech.whence.echo.job.stream.provider.Stage/PointingToDeclaration/)(other: [Stage](index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>operator override fun [equals](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [finalize](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/finalize/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [finalize](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/finalize/#/PointingToDeclaration/)()  <br><br><br>
| [getDeclaringClass](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/getDeclaringClass/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [getDeclaringClass](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/getDeclaringClass/#/PointingToDeclaration/)(): [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[Stage](index.md)>  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [hashCode](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [name](index.md#tech.whence.echo.job.stream.provider/Stage/name/#/PointingToDeclaration/)|  [jvm] override val [name](index.md#tech.whence.echo.job.stream.provider/Stage/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [ordinal](index.md#tech.whence.echo.job.stream.provider/Stage/ordinal/#/PointingToDeclaration/)|  [jvm] override val [ordinal](index.md#tech.whence.echo.job.stream.provider/Stage/ordinal/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>
| [responsive](index.md#tech.whence.echo.job.stream.provider/Stage/responsive/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否可响应<br><br>val [responsive](index.md#tech.whence.echo.job.stream.provider/Stage/responsive/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [state](index.md#tech.whence.echo.job.stream.provider/Stage/state/#/PointingToDeclaration/)|  [jvm] <br><br>State 收集者状态<br><br>val [state](index.md#tech.whence.echo.job.stream.provider/Stage/state/#/PointingToDeclaration/): [Collector.State](../../tech.whence.echo.job.stream.collector/-collector/-state/index.md)   <br>

