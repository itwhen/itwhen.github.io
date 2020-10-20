---
title: Ruler -
---
//[echo](../../index.md)/[tech.whence.echo.validation](../index.md)/[Ruler](index.md)



# Ruler  
 [jvm] 

规则

class [Ruler](index.md)(**key**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **validator**: [Validator](../-validator/index.md))   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Ruler](-ruler.md)|  [jvm] <br><br><br><br>fun [Ruler](-ruler.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), validator: [Validator](../-validator/index.md))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [accepted](accepted.md)| [jvm]  <br>Brief description  <br><br><br>当前属性值是一个用户表示接受的值 如 "yes" "on" "1" 1 true "true"<br><br>  <br>Content  <br>fun [accepted](accepted.md)(): [Ruler](index.md)  <br><br><br>
| [after](after.md)| [jvm]  <br>Brief description  <br><br><br>当前属性晚于指定日期<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [after](after.md)(min: [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html), at: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Ruler](index.md)  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [after](after.md)(min: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), at: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Ruler](index.md)  <br><br><br>
| [before](before.md)| [jvm]  <br>Brief description  <br><br><br>当前属性早于指定日期<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [before](before.md)(max: [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html), at: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Ruler](index.md)  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [before](before.md)(max: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), at: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Ruler](index.md)  <br><br><br>
| [boolean](boolean.md)| [jvm]  <br>Brief description  <br><br><br>当前属性是一个布尔值<br><br>  <br>Content  <br>fun [boolean](boolean.md)(): [Ruler](index.md)  <br><br><br>
| [collection](collection.md)| [jvm]  <br>Brief description  <br><br><br>当前属性值是一个集合<br><br>  <br>Content  <br>fun [collection](collection.md)(): [Ruler](index.md)  <br><br><br>
| [constant](constant.md)| [jvm]  <br>Brief description  <br><br><br>当前属性是一个常量<br><br>  <br>Content  <br>fun [constant](constant.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Const](../../tech.whence.echo.container.constant/-const/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>): [Ruler](index.md)  <br><br><br>
| [date](date.md)| [jvm]  <br>Brief description  <br><br><br>当前属性是一个日期<br><br>  <br>Content  <br>fun [date](date.md)(): [Ruler](index.md)  <br><br><br>
| [datetime](datetime.md)| [jvm]  <br>Brief description  <br><br><br>当前属性是一个日期时间<br><br>  <br>Content  <br>fun [datetime](datetime.md)(): [Ruler](index.md)  <br><br><br>
| [different](different.md)| [jvm]  <br>Brief description  <br><br><br>当前属性与另外一个属性的值不一致<br><br>  <br>Content  <br>fun [different](different.md)(target: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Ruler](index.md)  <br><br><br>
| [during](during.md)| [jvm]  <br>Brief description  <br><br><br>当前属性在指定日期时间范围内<br><br>  <br>Content  <br>fun [during](during.md)(min: [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html), max: [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html), at: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Ruler](index.md)  <br>fun [during](during.md)(min: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), max: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), at: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Ruler](index.md)  <br><br><br>
| [email](email.md)| [jvm]  <br>Brief description  <br><br><br>当前属性是一个电子邮箱地址<br><br>  <br>Content  <br>fun [email](email.md)(): [Ruler](index.md)  <br><br><br>
| [end](end.md)| [jvm]  <br>Brief description  <br><br><br>结束<br><br>  <br>Content  <br>fun [end](end.md)(): [Validator](../-validator/index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [fewer](fewer.md)| [jvm]  <br>Brief description  <br><br><br>当前属性值不多于指定项<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [fewer](fewer.md)(max: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), at: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Ruler](index.md)  <br><br><br>
| [float](float.md)| [jvm]  <br>Brief description  <br><br><br>当前属性是一个数字<br><br>  <br>Content  <br>fun [float](float.md)(): [Ruler](index.md)  <br><br><br>
| [greater](greater.md)| [jvm]  <br>Brief description  <br><br><br>当前属性值大于指定值<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [greater](greater.md)(min: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), equal: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Ruler](index.md)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [int](int.md)| [jvm]  <br>Brief description  <br><br><br>当前属性是一个整数<br><br>  <br>Content  <br>fun [int](int.md)(): [Ruler](index.md)  <br><br><br>
| [ip](ip.md)| [jvm]  <br>Brief description  <br><br><br>当前属性是一个IP地址<br><br>  <br>Content  <br>fun [ip](ip.md)(): [Ruler](index.md)  <br><br><br>
| [length](length.md)| [jvm]  <br>Brief description  <br><br><br>当前属性值长度在指定大小范围内<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [length](length.md)(min: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), max: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), at: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Ruler](index.md)  <br><br><br>
| [lengthed](lengthed.md)| [jvm]  <br>Brief description  <br><br><br>当前属性值是指定长度<br><br>  <br>Content  <br>fun [lengthed](lengthed.md)(value: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Ruler](index.md)  <br><br><br>
| [less](less.md)| [jvm]  <br>Brief description  <br><br><br>当前属性值小于指定值<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [less](less.md)(max: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), equal: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Ruler](index.md)  <br><br><br>
| [longer](longer.md)| [jvm]  <br>Brief description  <br><br><br>当前属性值不短于指定值<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [longer](longer.md)(min: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), at: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Ruler](index.md)  <br><br><br>
| [mobile](mobile.md)| [jvm]  <br>Brief description  <br><br><br>当前属性是一个手机号码<br><br>  <br>Content  <br>fun [mobile](mobile.md)(): [Ruler](index.md)  <br><br><br>
| [more](more.md)| [jvm]  <br>Brief description  <br><br><br>当前属性值不少于指定项<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [more](more.md)(min: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), at: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Ruler](index.md)  <br><br><br>
| [range](range.md)| [jvm]  <br>Brief description  <br><br><br>当前属性值在指定大小范围内<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [range](range.md)(min: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), max: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), equal: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Ruler](index.md)  <br><br><br>
| [required](required.md)| [jvm]  <br>Brief description  <br><br><br>当前属性有有效值<br><br>  <br>Content  <br>fun [required](required.md)(): [Ruler](index.md)  <br><br><br>
| [requiredIf](required-if.md)| [jvm]  <br>Brief description  <br><br><br>当另外一个属性提供了特定值时当前属性必填<br><br>  <br>Content  <br>fun [requiredIf](required-if.md)(target: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), vararg scope: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [Ruler](index.md)  <br>fun [requiredIf](required-if.md)(target: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), scope: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [Ruler](index.md)  <br><br><br>
| [requiredUnless](required-unless.md)| [jvm]  <br>Brief description  <br><br><br>当另外一个属性没有提供特定值时当前属性必填<br><br>  <br>Content  <br>fun [requiredUnless](required-unless.md)(target: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), vararg scope: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [Ruler](index.md)  <br>fun [requiredUnless](required-unless.md)(target: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), scope: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [Ruler](index.md)  <br><br><br>
| [requiredWith](required-with.md)| [jvm]  <br>Brief description  <br><br><br>当指定属性之一有有效值时时当前属性必填<br><br>  <br>Content  <br>fun [requiredWith](required-with.md)(vararg targets: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>): [Ruler](index.md)  <br>fun [requiredWith](required-with.md)(targets: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>): [Ruler](index.md)  <br><br><br>
| [requiredWithAll](required-with-all.md)| [jvm]  <br>Brief description  <br><br><br>当指定属性全部有有效值时时当前属性必填<br><br>  <br>Content  <br>fun [requiredWithAll](required-with-all.md)(vararg targets: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>): [Ruler](index.md)  <br>fun [requiredWithAll](required-with-all.md)(targets: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>): [Ruler](index.md)  <br><br><br>
| [requiredWithout](required-without.md)| [jvm]  <br>Brief description  <br><br><br>当指定属性之一无有效值时时当前属性必填<br><br>  <br>Content  <br>fun [requiredWithout](required-without.md)(vararg targets: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>): [Ruler](index.md)  <br>fun [requiredWithout](required-without.md)(targets: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>): [Ruler](index.md)  <br><br><br>
| [requiredWithoutAll](required-without-all.md)| [jvm]  <br>Brief description  <br><br><br>当指定属性全部无有效值时时当前属性必填<br><br>  <br>Content  <br>fun [requiredWithoutAll](required-without-all.md)(vararg targets: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>): [Ruler](index.md)  <br>fun [requiredWithoutAll](required-without-all.md)(targets: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>): [Ruler](index.md)  <br><br><br>
| [rule](rule.md)| [jvm]  <br>Brief description  <br><br><br>新增一条规则<br><br>  <br>Content  <br>fun [rule](rule.md)(rule: [Rule](../../tech.whence.echo.validation.rule/-rule/index.md)): [Ruler](index.md)  <br><br><br>
| [same](same.md)| [jvm]  <br>Brief description  <br><br><br>当前属性与另外一个属性的值一致<br><br>  <br>Content  <br>fun [same](same.md)(target: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Ruler](index.md)  <br><br><br>
| [set](set.md)| [jvm]  <br>Brief description  <br><br><br>继续设置下一个属性的规则<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [set](set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), title: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [Ruler](index.md)  <br><br><br>
| [shorter](shorter.md)| [jvm]  <br>Brief description  <br><br><br>当前属性值不长于指定值<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [shorter](shorter.md)(max: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), at: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Ruler](index.md)  <br><br><br>
| [size](size.md)| [jvm]  <br>Brief description  <br><br><br>当前属性项在指定范围内<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [size](size.md)(min: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), max: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), at: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Ruler](index.md)  <br><br><br>
| [sized](sized.md)| [jvm]  <br>Brief description  <br><br><br>当前属性是否是指定项<br><br>  <br>Content  <br>fun [sized](sized.md)(value: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Ruler](index.md)  <br><br><br>
| [sometimes](sometimes.md)| [jvm]  <br>Brief description  <br><br><br>若当前属性值为空则跳过后续规则 若strict为真时将检查字符串长度/容器大小否则只检查是否为空<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [sometimes](sometimes.md)(strict: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Ruler](index.md)  <br><br><br>
| [string](string.md)| [jvm]  <br>Brief description  <br><br><br>当前属性是一个字符串<br><br>  <br>Content  <br>fun [string](string.md)(): [Ruler](index.md)  <br><br><br>
| [telephone](telephone.md)| [jvm]  <br>Brief description  <br><br><br>当前属性是一个固定电话号码<br><br>  <br>Content  <br>fun [telephone](telephone.md)(): [Ruler](index.md)  <br><br><br>
| [time](time.md)| [jvm]  <br>Brief description  <br><br><br>当前属性是一个时间<br><br>  <br>Content  <br>fun [time](time.md)(): [Ruler](index.md)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [url](url.md)| [jvm]  <br>Brief description  <br><br><br>当前属性是一个网址<br><br>  <br>Content  <br>fun [url](url.md)(): [Ruler](index.md)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [key](index.md#tech.whence.echo.validation/Ruler/key/#/PointingToDeclaration/)|  [jvm] <br><br>String 指定属性<br><br>val [key](index.md#tech.whence.echo.validation/Ruler/key/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [validator](index.md#tech.whence.echo.validation/Ruler/validator/#/PointingToDeclaration/)|  [jvm] <br><br>Validator 当前校验器<br><br>val [validator](index.md#tech.whence.echo.validation/Ruler/validator/#/PointingToDeclaration/): [Validator](../-validator/index.md)   <br>
