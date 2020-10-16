---
title: StringConst -
---
//[echo](../../index.md)/[tech.whence.echo.container.constant](../index.md)/[StringConst](index.md)



# StringConst  
 [jvm] 

字符串常量

interface [StringConst](index.md) : [Const](../-const/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>    


## Functions  
  
|  Name|  Summary| 
|---|---|
| [are](are.md)| [jvm]  <br>Brief description  <br><br><br>根据值判断是否是当前常量<br><br>  <br>Content  <br>open override fun [are](are.md)(value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [convert](convert.md)| [jvm]  <br>Brief description  <br><br><br>转换指定值 若无法处理返回空<br><br>  <br>Content  <br>open override fun [convert](convert.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [name](index.md#tech.whence.echo.container.constant/StringConst/name/#/PointingToDeclaration/)|  [jvm] <br><br>String 名称<br><br>abstract override val [name](index.md#tech.whence.echo.container.constant/StringConst/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [title](index.md#tech.whence.echo.container.constant/StringConst/title/#/PointingToDeclaration/)|  [jvm] <br><br>String 描述<br><br>open override val [title](index.md#tech.whence.echo.container.constant/StringConst/title/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [value](index.md#tech.whence.echo.container.constant/StringConst/value/#/PointingToDeclaration/)|  [jvm] <br><br>V 值<br><br>abstract override val [value](index.md#tech.whence.echo.container.constant/StringConst/value/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>


## Inheritors  
  
|  Name| 
|---|
| [Operator](../../tech.whence.echo.dal.filter/-operator/index.md)
| [Ordering](../../tech.whence.echo.dal.querier.component/-ordering/index.md)
| [Control](../../tech.whence.echo.job.shell/-control/index.md)
| [Operation](../../tech.whence.echo.job.shell/-operation/index.md)
| [Reason](../../tech.whence.echo.rpc.response/-reason/index.md)
| [Select](../../tech.whence.echo.support.jdbc.driver.mysql.querier/-select/-plan/index.md)
| [FulltextMatch](../../tech.whence.echo.support.jdbc.querier.criterion/-fulltext-match/-mode/index.md)

