---
title: Operator -
---
//[echo](../../index.md)/[tech.whence.echo.dal.filter](../index.md)/[Operator](index.md)



# Operator  
 [jvm] 

操作符

enum [Operator](index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Operator](index.md)> , [StringConst](../../tech.whence.echo.container.constant/-string-const/index.md)   


## Entries  
  
|  Name|  Summary| 
|---|---|
| [EQUAL](-e-q-u-a-l/index.md)|  [jvm] <br><br>相等<br><br>[EQUAL](-e-q-u-a-l/index.md)("eq")  <br>  <br>   <br>
| [NOT_EQUAL](-n-o-t_-e-q-u-a-l/index.md)|  [jvm] <br><br>不等<br><br>[NOT_EQUAL](-n-o-t_-e-q-u-a-l/index.md)("ne")  <br>  <br>   <br>
| [IS_NULL](-i-s_-n-u-l-l/index.md)|  [jvm] <br><br>为空<br><br>[IS_NULL](-i-s_-n-u-l-l/index.md)("n")  <br>  <br>   <br>
| [IS_NOT_NULL](-i-s_-n-o-t_-n-u-l-l/index.md)|  [jvm] <br><br>不为空<br><br>[IS_NOT_NULL](-i-s_-n-o-t_-n-u-l-l/index.md)("nn")  <br>  <br>   <br>
| [GREATER_THAN](-g-r-e-a-t-e-r_-t-h-a-n/index.md)|  [jvm] <br><br>大于<br><br>[GREATER_THAN](-g-r-e-a-t-e-r_-t-h-a-n/index.md)("gt")  <br>  <br>   <br>
| [GREATER_THAN_OR_EQUAL](-g-r-e-a-t-e-r_-t-h-a-n_-o-r_-e-q-u-a-l/index.md)|  [jvm] <br><br>大于等于<br><br>[GREATER_THAN_OR_EQUAL](-g-r-e-a-t-e-r_-t-h-a-n_-o-r_-e-q-u-a-l/index.md)("gte")  <br>  <br>   <br>
| [LESS_THAN](-l-e-s-s_-t-h-a-n/index.md)|  [jvm] <br><br>小于<br><br>[LESS_THAN](-l-e-s-s_-t-h-a-n/index.md)("lt")  <br>  <br>   <br>
| [LESS_THAN_OR_EQUAL](-l-e-s-s_-t-h-a-n_-o-r_-e-q-u-a-l/index.md)|  [jvm] <br><br>小于等于<br><br>[LESS_THAN_OR_EQUAL](-l-e-s-s_-t-h-a-n_-o-r_-e-q-u-a-l/index.md)("lte")  <br>  <br>   <br>
| [LIKE](-l-i-k-e/index.md)|  [jvm] <br><br>相似<br><br>[LIKE](-l-i-k-e/index.md)("lk")  <br>  <br>   <br>
| [NOT_LIKE](-n-o-t_-l-i-k-e/index.md)|  [jvm] <br><br>不相似<br><br>[NOT_LIKE](-n-o-t_-l-i-k-e/index.md)("nl")  <br>  <br>   <br>
| [START_WITH](-s-t-a-r-t_-w-i-t-h/index.md)|  [jvm] <br><br>开始于<br><br>[START_WITH](-s-t-a-r-t_-w-i-t-h/index.md)("sw")  <br>  <br>   <br>
| [NOT_START_WITH](-n-o-t_-s-t-a-r-t_-w-i-t-h/index.md)|  [jvm] <br><br>不开始于<br><br>[NOT_START_WITH](-n-o-t_-s-t-a-r-t_-w-i-t-h/index.md)("nsw")  <br>  <br>   <br>
| [END_WITH](-e-n-d_-w-i-t-h/index.md)|  [jvm] <br><br>结尾于<br><br>[END_WITH](-e-n-d_-w-i-t-h/index.md)("ew")  <br>  <br>   <br>
| [NOT_END_WITH](-n-o-t_-e-n-d_-w-i-t-h/index.md)|  [jvm] <br><br>不结尾于<br><br>[NOT_END_WITH](-n-o-t_-e-n-d_-w-i-t-h/index.md)("new")  <br>  <br>   <br>
| [IN](-i-n/index.md)|  [jvm] <br><br>在多值内<br><br>[IN](-i-n/index.md)("in")  <br>  <br>   <br>
| [NOT_IN](-n-o-t_-i-n/index.md)|  [jvm] <br><br>不在多值内<br><br>[NOT_IN](-n-o-t_-i-n/index.md)("nin")  <br>  <br>   <br>
| [BETWEEN](-b-e-t-w-e-e-n/index.md)|  [jvm] <br><br>在范围内<br><br>[BETWEEN](-b-e-t-w-e-e-n/index.md)("b")  <br>  <br>   <br>
| [NOT_BETWEEN](-n-o-t_-b-e-t-w-e-e-n/index.md)|  [jvm] <br><br>不在范围内<br><br>[NOT_BETWEEN](-n-o-t_-b-e-t-w-e-e-n/index.md)("nb")  <br>  <br>   <br>
| [MATCH](-m-a-t-c-h/index.md)|  [jvm] <br><br>匹配<br><br>[MATCH](-m-a-t-c-h/index.md)("m")  <br>  <br>   <br>
| [NOT_MATCH](-n-o-t_-m-a-t-c-h/index.md)|  [jvm] <br><br>不匹配<br><br>[NOT_MATCH](-n-o-t_-m-a-t-c-h/index.md)("nm")  <br>  <br>   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [are](../../tech.whence.echo.container.constant/-string-const/are.md)| [jvm]  <br>Brief description  <br><br><br>根据值判断是否是当前常量<br><br>  <br>Content  <br>open override fun [are](../../tech.whence.echo.container.constant/-string-const/are.md)(value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [compareTo](-n-o-t_-m-a-t-c-h/index.md#kotlin/Enum/compareTo/#tech.whence.echo.dal.filter.Operator/PointingToDeclaration/)| [jvm]  <br>Content  <br>operator override fun [compareTo](-n-o-t_-m-a-t-c-h/index.md#kotlin/Enum/compareTo/#tech.whence.echo.dal.filter.Operator/PointingToDeclaration/)(other: [Operator](index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [convert](../../tech.whence.echo.container.constant/-string-const/convert.md)| [jvm]  <br>Brief description  <br><br><br>转换指定值 若无法处理返回空<br><br>  <br>Content  <br>open override fun [convert](../../tech.whence.echo.container.constant/-string-const/convert.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>operator override fun [equals](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [finalize](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/finalize/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [finalize](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/finalize/#/PointingToDeclaration/)()  <br><br><br>
| [getDeclaringClass](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/getDeclaringClass/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [getDeclaringClass](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/getDeclaringClass/#/PointingToDeclaration/)(): [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[Operator](index.md)>  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [hashCode](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [name](index.md#tech.whence.echo.dal.filter/Operator/name/#/PointingToDeclaration/)|  [jvm] override val [name](index.md#tech.whence.echo.dal.filter/Operator/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [ordinal](index.md#tech.whence.echo.dal.filter/Operator/ordinal/#/PointingToDeclaration/)|  [jvm] override val [ordinal](index.md#tech.whence.echo.dal.filter/Operator/ordinal/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>
| [title](index.md#tech.whence.echo.dal.filter/Operator/title/#/PointingToDeclaration/)|  [jvm] <br><br>String 描述<br><br>open override val [title](index.md#tech.whence.echo.dal.filter/Operator/title/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [value](index.md#tech.whence.echo.dal.filter/Operator/value/#/PointingToDeclaration/)|  [jvm] <br><br>String 缩略词<br><br>open override val [value](index.md#tech.whence.echo.dal.filter/Operator/value/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>

