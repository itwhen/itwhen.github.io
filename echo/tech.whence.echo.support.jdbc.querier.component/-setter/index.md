---
title: Setter -
---
//[echo](../../index.md)/[tech.whence.echo.support.jdbc.querier.component](../index.md)/[Setter](index.md)



# Setter  
 [jvm] 

赋值器

interface [Setter](index.md)<[T](index.md) : [Setter](index.md)<[T](index.md)>> : [Setter](../../tech.whence.echo.dal.querier.component/-setter/index.md)<[T](index.md), [Column](../-column/index.md)>    


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| T| <br><br><br><br>
  


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [set](index.md#tech.whence.echo.dal.querier.component/Setter/set/#kotlin.Array[tech.whence.echo.support.jdbc.querier.component.Column]/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>设置赋值作业<br><br>  <br>Content  <br>open override fun [set](index.md#tech.whence.echo.dal.querier.component/Setter/set/#kotlin.Array[tech.whence.echo.support.jdbc.querier.component.Column]/PointingToDeclaration/)(vararg assignments: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [Column](../-column/index.md)>): [T](index.md)  <br>abstract override fun [set](index.md#tech.whence.echo.dal.querier.component/Setter/set/#kotlin.collections.Set[tech.whence.echo.support.jdbc.querier.component.Column]/PointingToDeclaration/)(assignments: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Column](../-column/index.md)>): [T](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置多个字段<br><br>  <br>Content  <br>open fun [set](set.md)(columns: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>): [T](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置指定字段为 BigDecimal<br><br>  <br>Content  <br>open fun [set](set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [BigDecimal](https://docs.oracle.com/javase/8/docs/api/java/math/BigDecimal.html)): [T](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置指定字段为 BigInteger<br><br>  <br>Content  <br>open fun [set](set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [BigInteger](https://docs.oracle.com/javase/8/docs/api/java/math/BigInteger.html)): [T](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置指定字段为 Duration<br><br>  <br>Content  <br>open fun [set](set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)): [T](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置指定字段为 LocalDate<br><br>  <br>Content  <br>open fun [set](set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [LocalDate](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDate.html)): [T](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置指定字段为 LocalDateTime<br><br>  <br>Content  <br>open fun [set](set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)): [T](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置指定字段为 LocalTime<br><br>  <br>Content  <br>open fun [set](set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [LocalTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalTime.html)): [T](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置指定字段为日期<br><br>  <br>Content  <br>open fun [set](set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Date](https://docs.oracle.com/javase/8/docs/api/java/util/Date.html)): [T](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置指定字段为布尔值<br><br>  <br>Content  <br>open fun [set](set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [T](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置指定字段为双精度浮点型<br><br>  <br>Content  <br>open fun [set](set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [T](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置指定字段为浮点型<br><br>  <br>Content  <br>open fun [set](set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [T](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置字段为整型<br><br>  <br>Content  <br>open fun [set](set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [T](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置指定字段为长整型<br><br>  <br>Content  <br>open fun [set](set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): [T](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置指定字段为字符串值<br><br>  <br>Content  <br>open fun [set](set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [T](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置指定字段为原生语句<br><br>  <br>Content  <br>open fun [set](set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Raw](../../tech.whence.echo.dal.querier.component/-raw/index.md)): [T](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置指定字段的值及其类型<br><br>  <br>Content  <br>open fun [set](set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, type: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [T](index.md)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Inheritors  
  
|  Name| 
|---|
| [AbstractInsert](../../tech.whence.echo.support.jdbc.querier/-abstract-insert/index.md)
| [AbstractUpdate](../../tech.whence.echo.support.jdbc.querier/-abstract-update/index.md)

