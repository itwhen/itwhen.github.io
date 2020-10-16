---
title: Control -
---
//[echo](../../index.md)/[tech.whence.echo.job.shell](../index.md)/[Control](index.md)



# Control  
 [jvm] 

作业命令

enum [Control](index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Control](index.md)> , [StringConst](../../tech.whence.echo.container.constant/-string-const/index.md)   


## Entries  
  
|  Name|  Summary| 
|---|---|
| [START](-s-t-a-r-t/index.md)|  [jvm] <br><br>启动<br><br>[START](-s-t-a-r-t/index.md)("start", Operation.START)  <br>  <br>   <br>
| [STOP](-s-t-o-p/index.md)|  [jvm] <br><br>停止<br><br>[STOP](-s-t-o-p/index.md)("stop", Operation.STOP)  <br>  <br>   <br>
| [SUSPEND](-s-u-s-p-e-n-d/index.md)|  [jvm] <br><br>挂起<br><br>[SUSPEND](-s-u-s-p-e-n-d/index.md)("suspend", Operation.SUSPEND)  <br>  <br>   <br>
| [RESUME](-r-e-s-u-m-e/index.md)|  [jvm] <br><br>恢复<br><br>[RESUME](-r-e-s-u-m-e/index.md)("resume", Operation.RESUME)  <br>  <br>   <br>
| [STATUS](-s-t-a-t-u-s/index.md)|  [jvm] <br><br>查看状态<br><br>[STATUS](-s-t-a-t-u-s/index.md)("status", null)  <br>  <br>   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [are](../../tech.whence.echo.container.constant/-string-const/are.md)| [jvm]  <br>Brief description  <br><br><br>根据值判断是否是当前常量<br><br>  <br>Content  <br>open override fun [are](../../tech.whence.echo.container.constant/-string-const/are.md)(value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [compareTo](-s-t-a-t-u-s/index.md#kotlin/Enum/compareTo/#tech.whence.echo.job.shell.Control/PointingToDeclaration/)| [jvm]  <br>Content  <br>operator override fun [compareTo](-s-t-a-t-u-s/index.md#kotlin/Enum/compareTo/#tech.whence.echo.job.shell.Control/PointingToDeclaration/)(other: [Control](index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [convert](../../tech.whence.echo.container.constant/-string-const/convert.md)| [jvm]  <br>Brief description  <br><br><br>转换指定值 若无法处理返回空<br><br>  <br>Content  <br>open override fun [convert](../../tech.whence.echo.container.constant/-string-const/convert.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>operator override fun [equals](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [finalize](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/finalize/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [finalize](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/finalize/#/PointingToDeclaration/)()  <br><br><br>
| [getDeclaringClass](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/getDeclaringClass/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [getDeclaringClass](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/getDeclaringClass/#/PointingToDeclaration/)(): [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[Control](index.md)>  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [hashCode](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [process](process.md)| [jvm]  <br>Brief description  <br><br><br>执行命令返回响应<br><br>  <br>Content  <br>open fun [process](process.md)(manager: ServiceManager, services: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Context](../-context/index.md)>): [Responder](../-responder/index.md)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [name](index.md#tech.whence.echo.job.shell/Control/name/#/PointingToDeclaration/)|  [jvm] override val [name](index.md#tech.whence.echo.job.shell/Control/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [ordinal](index.md#tech.whence.echo.job.shell/Control/ordinal/#/PointingToDeclaration/)|  [jvm] override val [ordinal](index.md#tech.whence.echo.job.shell/Control/ordinal/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>
| [title](index.md#tech.whence.echo.job.shell/Control/title/#/PointingToDeclaration/)|  [jvm] <br><br>String 描述<br><br>open override val [title](index.md#tech.whence.echo.job.shell/Control/title/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [value](index.md#tech.whence.echo.job.shell/Control/value/#/PointingToDeclaration/)|  [jvm] <br><br>String<br><br>open override val [value](index.md#tech.whence.echo.job.shell/Control/value/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>

