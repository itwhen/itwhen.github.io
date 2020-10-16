---
title: ClassConst -
---
//[echo](../../index.md)/[tech.whence.echo.container.constant](../index.md)/[ClassConst](index.md)



# ClassConst  
 [jvm] 

类常量

interface [ClassConst](index.md)<[T](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> : [Const](../-const/index.md)<[KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [T](index.md)>>    


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| T| <br><br>: Any 数据类型<br><br>
  


## Functions  
  
|  Name|  Summary| 
|---|---|
| [are](are.md)| [jvm]  <br>Brief description  <br><br><br>根据值判断是否是当前常量<br><br>  <br>Content  <br>open override fun [are](are.md)(value: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [T](index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [convert](convert.md)| [jvm]  <br>Brief description  <br><br><br>转换指定值 若无法处理返回空<br><br>  <br>Content  <br>open override fun [convert](convert.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [T](index.md)>?  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [name](index.md#tech.whence.echo.container.constant/ClassConst/name/#/PointingToDeclaration/)|  [jvm] <br><br>String 名称<br><br>abstract override val [name](index.md#tech.whence.echo.container.constant/ClassConst/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [title](index.md#tech.whence.echo.container.constant/ClassConst/title/#/PointingToDeclaration/)|  [jvm] <br><br>String 描述<br><br>abstract override val [title](index.md#tech.whence.echo.container.constant/ClassConst/title/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [value](index.md#tech.whence.echo.container.constant/ClassConst/value/#/PointingToDeclaration/)|  [jvm] <br><br>V 值<br><br>abstract override val [value](index.md#tech.whence.echo.container.constant/ClassConst/value/#/PointingToDeclaration/): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [T](index.md)>   <br>


## Inheritors  
  
|  Name| 
|---|
| [Action](../../tech.whence.echo.job.manager.management/-action/index.md)

