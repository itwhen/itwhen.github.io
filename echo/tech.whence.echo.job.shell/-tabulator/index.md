---
title: Tabulator -
---
//[echo](../../index.md)/[tech.whence.echo.job.shell](../index.md)/[Tabulator](index.md)



# Tabulator  
 [jvm] 

制表器

class [Tabulator](index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Tabulator](-tabulator.md)|  [jvm] fun [Tabulator](-tabulator.md)()   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>
| [Tag](-tag/index.md)| [jvm]  <br>Brief description  <br><br><br>标签<br><br>  <br>Content  <br>data class [Tag](-tag/index.md)(**prefix**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **infix**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **postfix**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **padding**: [Char](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char/index.html), **start**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **end**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))  <br><br><br>
| [Tags](-tags/index.md)| [jvm]  <br>Brief description  <br><br><br>制表标签<br><br>  <br>Content  <br>sealed class [Tags](-tags/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [stringify](stringify.md)| [jvm]  <br>Brief description  <br><br><br>字符串化<br><br>  <br>Content  <br>fun [stringify](stringify.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [body](index.md#tech.whence.echo.job.shell/Tabulator/body/#/PointingToDeclaration/)|  [jvm] <br><br>List<Map<String, Any?>> 主体<br><br>var [body](index.md#tech.whence.echo.job.shell/Tabulator/body/#/PointingToDeclaration/): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>>   <br>
| [eol](index.md#tech.whence.echo.job.shell/Tabulator/eol/#/PointingToDeclaration/)|  [jvm] <br><br>String 换行符<br><br>var [eol](index.md#tech.whence.echo.job.shell/Tabulator/eol/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [footer](index.md#tech.whence.echo.job.shell/Tabulator/footer/#/PointingToDeclaration/)|  [jvm] <br><br>List<String> 表尾<br><br>var [footer](index.md#tech.whence.echo.job.shell/Tabulator/footer/#/PointingToDeclaration/): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>   <br>
| [header](index.md#tech.whence.echo.job.shell/Tabulator/header/#/PointingToDeclaration/)|  [jvm] <br><br>List<String> 表头<br><br>var [header](index.md#tech.whence.echo.job.shell/Tabulator/header/#/PointingToDeclaration/): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>   <br>
| [padding](index.md#tech.whence.echo.job.shell/Tabulator/padding/#/PointingToDeclaration/)|  [jvm] <br><br>Int 值左右填充<br><br>var [padding](index.md#tech.whence.echo.job.shell/Tabulator/padding/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>
| [tags](index.md#tech.whence.echo.job.shell/Tabulator/tags/#/PointingToDeclaration/)|  [jvm] <br><br>Tags 标签<br><br>var [tags](index.md#tech.whence.echo.job.shell/Tabulator/tags/#/PointingToDeclaration/): [Tabulator.Tags](-tags/index.md)   <br>

