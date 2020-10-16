---
title: Mode -
---
//[echo](../../../index.md)/[tech.whence.echo.support.jdbc.querier.criterion](../../index.md)/[FulltextMatch](../index.md)/[Mode](index.md)



# Mode  
 [jvm] 

匹配模式

enum [Mode](index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[FulltextMatch.Mode](index.md)> , [StringConst](../../../tech.whence.echo.container.constant/-string-const/index.md)   


## Entries  
  
|  Name|  Summary| 
|---|---|
| [DEFAULT](-d-e-f-a-u-l-t/index.md)|  [jvm] <br><br>默认<br><br>[DEFAULT](-d-e-f-a-u-l-t/index.md)("")  <br>  <br>   <br>
| [BOOLEAN](-b-o-o-l-e-a-n/index.md)|  [jvm] <br><br>布尔全文搜索<br><br>[BOOLEAN](-b-o-o-l-e-a-n/index.md)(" IN BOOLEAN MODE")  <br>  <br>   <br>
| [NATURAL](-n-a-t-u-r-a-l/index.md)|  [jvm] <br><br>自然语言全文搜索<br><br>[NATURAL](-n-a-t-u-r-a-l/index.md)(" IN NATURAL LANGUAGE MODE")  <br>  <br>   <br>
| [NATURAL_QUERY](-n-a-t-u-r-a-l_-q-u-e-r-y/index.md)|  [jvm] <br><br>带查询扩展的自然语言全文搜索<br><br>[NATURAL_QUERY](-n-a-t-u-r-a-l_-q-u-e-r-y/index.md)(" IN NATURAL LANGUAGE MODE WITH QUERY EXPANSION")  <br>  <br>   <br>
| [QUERY](-q-u-e-r-y/index.md)|  [jvm] <br><br>查询扩展全文搜索<br><br>[QUERY](-q-u-e-r-y/index.md)(" WITH QUERY EXPANSION")  <br>  <br>   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [are](../../../tech.whence.echo.container.constant/-string-const/are.md)| [jvm]  <br>Brief description  <br><br><br>根据值判断是否是当前常量<br><br>  <br>Content  <br>open override fun [are](../../../tech.whence.echo.container.constant/-string-const/are.md)(value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [compareTo](-q-u-e-r-y/index.md#kotlin/Enum/compareTo/#tech.whence.echo.support.jdbc.querier.criterion.FulltextMatch.Mode/PointingToDeclaration/)| [jvm]  <br>Content  <br>operator override fun [compareTo](-q-u-e-r-y/index.md#kotlin/Enum/compareTo/#tech.whence.echo.support.jdbc.querier.criterion.FulltextMatch.Mode/PointingToDeclaration/)(other: [FulltextMatch.Mode](index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [convert](../../../tech.whence.echo.container.constant/-string-const/convert.md)| [jvm]  <br>Brief description  <br><br><br>转换指定值 若无法处理返回空<br><br>  <br>Content  <br>open override fun [convert](../../../tech.whence.echo.container.constant/-string-const/convert.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?  <br><br><br>
| [equals](../../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>operator override fun [equals](../../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [finalize](../../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/finalize/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [finalize](../../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/finalize/#/PointingToDeclaration/)()  <br><br><br>
| [getDeclaringClass](../../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/getDeclaringClass/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [getDeclaringClass](../../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/getDeclaringClass/#/PointingToDeclaration/)(): [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[FulltextMatch.Mode](index.md)>  <br><br><br>
| [hashCode](../../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [hashCode](../../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [name](index.md#tech.whence.echo.support.jdbc.querier.criterion/FulltextMatch.Mode/name/#/PointingToDeclaration/)|  [jvm] override val [name](index.md#tech.whence.echo.support.jdbc.querier.criterion/FulltextMatch.Mode/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [ordinal](index.md#tech.whence.echo.support.jdbc.querier.criterion/FulltextMatch.Mode/ordinal/#/PointingToDeclaration/)|  [jvm] override val [ordinal](index.md#tech.whence.echo.support.jdbc.querier.criterion/FulltextMatch.Mode/ordinal/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>
| [title](index.md#tech.whence.echo.support.jdbc.querier.criterion/FulltextMatch.Mode/title/#/PointingToDeclaration/)|  [jvm] <br><br>String 描述<br><br>open override val [title](index.md#tech.whence.echo.support.jdbc.querier.criterion/FulltextMatch.Mode/title/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [value](index.md#tech.whence.echo.support.jdbc.querier.criterion/FulltextMatch.Mode/value/#/PointingToDeclaration/)|  [jvm] <br><br>String<br><br>open override val [value](index.md#tech.whence.echo.support.jdbc.querier.criterion/FulltextMatch.Mode/value/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>

