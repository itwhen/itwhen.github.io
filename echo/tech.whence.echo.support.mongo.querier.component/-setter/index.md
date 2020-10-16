---
title: Setter -
---
//[echo](../../index.md)/[tech.whence.echo.support.mongo.querier.component](../index.md)/[Setter](index.md)



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
| [set](index.md#tech.whence.echo.dal.querier.component/Setter/set/#kotlin.Array[tech.whence.echo.support.mongo.querier.component.Column]/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>设置赋值作业<br><br>  <br>Content  <br>open override fun [set](index.md#tech.whence.echo.dal.querier.component/Setter/set/#kotlin.Array[tech.whence.echo.support.mongo.querier.component.Column]/PointingToDeclaration/)(vararg assignments: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [Column](../-column/index.md)>): [T](index.md)  <br>abstract override fun [set](index.md#tech.whence.echo.dal.querier.component/Setter/set/#kotlin.collections.Set[tech.whence.echo.support.mongo.querier.component.Column]/PointingToDeclaration/)(assignments: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Column](../-column/index.md)>): [T](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>指定 BigDecimal<br><br>  <br>Content  <br>open fun [set](set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [BigDecimal](https://docs.oracle.com/javase/8/docs/api/java/math/BigDecimal.html)): [T](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>指定 BigInteger<br><br>  <br>Content  <br>open fun [set](set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [BigInteger](https://docs.oracle.com/javase/8/docs/api/java/math/BigInteger.html)): [T](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置日期<br><br>  <br>Content  <br>open fun [set](set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [LocalDate](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDate.html)): [T](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置日期时间<br><br>  <br>Content  <br>open fun [set](set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)): [T](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置时间<br><br>  <br>Content  <br>open fun [set](set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [LocalTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalTime.html)): [T](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>指定字符序列<br><br>  <br>Content  <br>open fun [set](set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [CharSequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html)): [T](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置数值型<br><br>  <br>Content  <br>open fun [set](set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)): [T](index.md)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Inheritors  
  
|  Name| 
|---|
| [Insert](../../tech.whence.echo.support.mongo.querier/-insert/index.md)
| [Update](../../tech.whence.echo.support.mongo.querier/-update/index.md)

