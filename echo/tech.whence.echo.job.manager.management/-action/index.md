---
title: Action -
---
//[echo](../../index.md)/[tech.whence.echo.job.manager.management](../index.md)/[Action](index.md)



# Action  
 [jvm] 

行为

enum [Action](index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Action](index.md)> , [ClassConst](../../tech.whence.echo.container.constant/-class-const/index.md)<[Event](../../tech.whence.echo.job.manager/-event/index.md)>    


## Entries  
  
|  Name|  Summary| 
|---|---|
| [START](-s-t-a-r-t/index.md)|  [jvm] <br><br>启动<br><br>[START](-s-t-a-r-t/index.md)(Event.Starting::class, "start")  <br>  <br>   <br>
| [SUSPEND](-s-u-s-p-e-n-d/index.md)|  [jvm] <br><br>挂起<br><br>[SUSPEND](-s-u-s-p-e-n-d/index.md)(Event.Suspending::class, "suspend")  <br>  <br>   <br>
| [RESUME](-r-e-s-u-m-e/index.md)|  [jvm] <br><br>恢复<br><br>[RESUME](-r-e-s-u-m-e/index.md)(Event.Resuming::class, "resume")  <br>  <br>   <br>
| [STOP](-s-t-o-p/index.md)|  [jvm] <br><br>停止<br><br>[STOP](-s-t-o-p/index.md)(Event.Stopping::class, "stop")  <br>  <br>   <br>
| [DISPATCH](-d-i-s-p-a-t-c-h/index.md)|  [jvm] <br><br>调度<br><br>[DISPATCH](-d-i-s-p-a-t-c-h/index.md)(Nothing::class, "dispatch")  <br>  <br>   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [are](-d-i-s-p-a-t-c-h/index.md#tech.whence.echo.container.constant/ClassConst/are/#kotlin.reflect.KClass[tech.whence.echo.job.manager.Event]/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>根据值判断是否是当前常量<br><br>  <br>Content  <br>open override fun [are](-d-i-s-p-a-t-c-h/index.md#tech.whence.echo.container.constant/ClassConst/are/#kotlin.reflect.KClass[tech.whence.echo.job.manager.Event]/PointingToDeclaration/)(value: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Event](../../tech.whence.echo.job.manager/-event/index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [compareTo](-d-i-s-p-a-t-c-h/index.md#kotlin/Enum/compareTo/#tech.whence.echo.job.manager.management.Action/PointingToDeclaration/)| [jvm]  <br>Content  <br>operator override fun [compareTo](-d-i-s-p-a-t-c-h/index.md#kotlin/Enum/compareTo/#tech.whence.echo.job.manager.management.Action/PointingToDeclaration/)(other: [Action](index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [convert](../../tech.whence.echo.container.constant/-class-const/convert.md)| [jvm]  <br>Brief description  <br><br><br>转换指定值 若无法处理返回空<br><br>  <br>Content  <br>open override fun [convert](../../tech.whence.echo.container.constant/-class-const/convert.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Event](../../tech.whence.echo.job.manager/-event/index.md)>?  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>operator override fun [equals](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [finalize](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/finalize/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [finalize](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/finalize/#/PointingToDeclaration/)()  <br><br><br>
| [getDeclaringClass](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/getDeclaringClass/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [getDeclaringClass](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/getDeclaringClass/#/PointingToDeclaration/)(): [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[Action](index.md)>  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [hashCode](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [name](index.md#tech.whence.echo.job.manager.management/Action/name/#/PointingToDeclaration/)|  [jvm] override val [name](index.md#tech.whence.echo.job.manager.management/Action/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [ordinal](index.md#tech.whence.echo.job.manager.management/Action/ordinal/#/PointingToDeclaration/)|  [jvm] override val [ordinal](index.md#tech.whence.echo.job.manager.management/Action/ordinal/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>
| [title](index.md#tech.whence.echo.job.manager.management/Action/title/#/PointingToDeclaration/)|  [jvm] <br><br>String 描述<br><br>open override val [title](index.md#tech.whence.echo.job.manager.management/Action/title/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [value](index.md#tech.whence.echo.job.manager.management/Action/value/#/PointingToDeclaration/)|  [jvm] <br><br>KClass<out Event> 指定事件<br><br>open override val [value](index.md#tech.whence.echo.job.manager.management/Action/value/#/PointingToDeclaration/): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Event](../../tech.whence.echo.job.manager/-event/index.md)>   <br>
