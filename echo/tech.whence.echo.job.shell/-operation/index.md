---
title: Operation -
---
//[echo](../../index.md)/[tech.whence.echo.job.shell](../index.md)/[Operation](index.md)



# Operation  
 [jvm] 

操作

enum [Operation](index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Operation](index.md)> , [StringConst](../../tech.whence.echo.container.constant/-string-const/index.md)   


## Entries  
  
|  Name|  Summary| 
|---|---|
| [START](-s-t-a-r-t/index.md)|  [jvm] <br><br>启动<br><br>[START](-s-t-a-r-t/index.md)("start", "start current job")  <br>  <br>   <br>
| [STOP](-s-t-o-p/index.md)|  [jvm] <br><br>停止<br><br>[STOP](-s-t-o-p/index.md)("stop", "stop current job")  <br>  <br>   <br>
| [SUSPEND](-s-u-s-p-e-n-d/index.md)|  [jvm] <br><br>挂起<br><br>[SUSPEND](-s-u-s-p-e-n-d/index.md)("suspend", "suspend current job")  <br>  <br>   <br>
| [RESUME](-r-e-s-u-m-e/index.md)|  [jvm] <br><br>恢复<br><br>[RESUME](-r-e-s-u-m-e/index.md)("resume", "resume current job")  <br>  <br>   <br>
| [STATUS](-s-t-a-t-u-s/index.md)|  [jvm] <br><br>查看状态<br><br>[STATUS](-s-t-a-t-u-s/index.md)("status", "view state of current job", "--duration=NUMBER //default 15m, max 1440m")  <br>  <br>   <br>
| [CONFIGURE](-c-o-n-f-i-g-u-r-e/index.md)|  [jvm] <br><br>配置<br><br>[CONFIGURE](-c-o-n-f-i-g-u-r-e/index.md)("configure", "using current parameters to update configuration", "--data=data //QUERY format")  <br>  <br>   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [are](../../tech.whence.echo.container.constant/-string-const/are.md)| [jvm]  <br>Brief description  <br><br><br>根据值判断是否是当前常量<br><br>  <br>Content  <br>open override fun [are](../../tech.whence.echo.container.constant/-string-const/are.md)(value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [compareTo](-c-o-n-f-i-g-u-r-e/index.md#kotlin/Enum/compareTo/#tech.whence.echo.job.shell.Operation/PointingToDeclaration/)| [jvm]  <br>Content  <br>operator override fun [compareTo](-c-o-n-f-i-g-u-r-e/index.md#kotlin/Enum/compareTo/#tech.whence.echo.job.shell.Operation/PointingToDeclaration/)(other: [Operation](index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [convert](../../tech.whence.echo.container.constant/-string-const/convert.md)| [jvm]  <br>Brief description  <br><br><br>转换指定值 若无法处理返回空<br><br>  <br>Content  <br>open override fun [convert](../../tech.whence.echo.container.constant/-string-const/convert.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>operator override fun [equals](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [finalize](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/finalize/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [finalize](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/finalize/#/PointingToDeclaration/)()  <br><br><br>
| [getDeclaringClass](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/getDeclaringClass/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [getDeclaringClass](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/getDeclaringClass/#/PointingToDeclaration/)(): [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[Operation](index.md)>  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [hashCode](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [process](process.md)| [jvm]  <br>Brief description  <br><br><br>执行<br><br>  <br>Content  <br>abstract fun [process](process.md)(context: [Context](../-context/index.md), parameters: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)): [Responder](../-responder/index.md)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [name](index.md#tech.whence.echo.job.shell/Operation/name/#/PointingToDeclaration/)|  [jvm] override val [name](index.md#tech.whence.echo.job.shell/Operation/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [ordinal](index.md#tech.whence.echo.job.shell/Operation/ordinal/#/PointingToDeclaration/)|  [jvm] override val [ordinal](index.md#tech.whence.echo.job.shell/Operation/ordinal/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>
| [parameters](index.md#tech.whence.echo.job.shell/Operation/parameters/#/PointingToDeclaration/)|  [jvm] <br><br>Array<out String><br><br>val [parameters](index.md#tech.whence.echo.job.shell/Operation/parameters/#/PointingToDeclaration/): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>   <br>
| [title](index.md#tech.whence.echo.job.shell/Operation/title/#/PointingToDeclaration/)|  [jvm] <br><br>String<br><br>open override val [title](index.md#tech.whence.echo.job.shell/Operation/title/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [value](index.md#tech.whence.echo.job.shell/Operation/value/#/PointingToDeclaration/)|  [jvm] <br><br>String<br><br>open override val [value](index.md#tech.whence.echo.job.shell/Operation/value/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>

