---
title: Handler -
---
//[echo](../../../index.md)/[tech.whence.echo.support.jdbc.driver.mysql.querier](../../index.md)/[Insert](../index.md)/[Handler](index.md)



# Handler  
 [jvm] 

异常处理方式

sealed class [Handler](index.md)   


## Types  
  
|  Name|  Summary| 
|---|---|
| [Ignore](-ignore/index.md)| [jvm]  <br>Brief description  <br><br><br>忽视<br><br>  <br>Content  <br>object [Ignore](-ignore/index.md) : [Insert.Handler](index.md)  <br><br><br>
| [Reassign](-reassign/index.md)| [jvm]  <br>Brief description  <br><br><br>重新赋值<br><br>  <br>Content  <br>class [Reassign](-reassign/index.md)(**reassignment**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [Insert.Handler](index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [tail](index.md#tech.whence.echo.support.jdbc.driver.mysql.querier/Insert.Handler/tail/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否附加在尾部<br><br>val [tail](index.md#tech.whence.echo.support.jdbc.driver.mysql.querier/Insert.Handler/tail/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [text](index.md#tech.whence.echo.support.jdbc.driver.mysql.querier/Insert.Handler/text/#/PointingToDeclaration/)|  [jvm] <br><br>String 语句文本<br><br>val [text](index.md#tech.whence.echo.support.jdbc.driver.mysql.querier/Insert.Handler/text/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>


## Inheritors  
  
|  Name| 
|---|
| [Insert.Handler](-ignore/index.md)
| [Insert.Handler](-reassign/index.md)

