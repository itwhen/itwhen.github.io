---
title: Insert -
---
//[echo](../../index.md)/[tech.whence.echo.support.mongo.querier](../index.md)/[Insert](index.md)



# Insert  
 [jvm] 

Insert

class [Insert](index.md) : [AbstractCreator](../../tech.whence.echo.dal.querier/-abstract-creator/index.md)<[Insert](index.md), [Column](../../tech.whence.echo.support.mongo.querier.component/-column/index.md), [Definition](../../tech.whence.echo.support.mongo.querier.component/-definition/index.md)<[Writing](../../tech.whence.echo.support.mongo.querier.component/-writing/index.md)>> , [Setter](../../tech.whence.echo.support.mongo.querier.component/-setter/index.md)<[Insert](index.md)> , [Definer](../../tech.whence.echo.support.mongo.querier.component/-definer/index.md)<[Insert](index.md), [Writing](../../tech.whence.echo.support.mongo.querier.component/-writing/index.md)>    


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Insert](-insert.md)|  [jvm] fun [Insert](-insert.md)()   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [bulk](bulk.md)| [jvm]  <br>Brief description  <br><br><br>批量化<br><br>  <br>Content  <br>open override fun [bulk](bulk.md)(): [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<BulkOperation, BulkWriteOptions>  <br><br><br>
| [define](define.md)| [jvm]  <br>Brief description  <br><br><br>生成定义<br><br>  <br>Content  <br>open override fun [define](define.md)(): [Definition](../../tech.whence.echo.support.mongo.querier.component/-definition/index.md)<[Writing](../../tech.whence.echo.support.mongo.querier.component/-writing/index.md)>  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [into](../../tech.whence.echo.dal.querier/-abstract-creator/into.md)| [jvm]  <br>Brief description  <br><br><br>指定创建目的地<br><br>  <br>Content  <br>open override fun [into](../../tech.whence.echo.dal.querier/-abstract-creator/into.md)(schema: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Insert](index.md)  <br><br><br>
| [set](../../tech.whence.echo.support.mongo.querier.component/-setter/index.md#tech.whence.echo.dal.querier.component/Setter/set/#kotlin.Array[tech.whence.echo.support.mongo.querier.component.Column]/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [set](../../tech.whence.echo.support.mongo.querier.component/-setter/index.md#tech.whence.echo.dal.querier.component/Setter/set/#kotlin.Array[tech.whence.echo.support.mongo.querier.component.Column]/PointingToDeclaration/)(vararg assignments: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [Column](../../tech.whence.echo.support.mongo.querier.component/-column/index.md)>): [Insert](index.md)  <br>open override fun [set](index.md#tech.whence.echo.dal.querier/AbstractCreator/set/#kotlin.collections.Set[tech.whence.echo.support.mongo.querier.component.Column]/PointingToDeclaration/)(assignments: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Column](../../tech.whence.echo.support.mongo.querier.component/-column/index.md)>): [Insert](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>指定 BigDecimal<br><br>  <br>Content  <br>open override fun [set](../../tech.whence.echo.support.mongo.querier.component/-setter/set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [BigDecimal](https://docs.oracle.com/javase/8/docs/api/java/math/BigDecimal.html)): [Insert](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>指定 BigInteger<br><br>  <br>Content  <br>open override fun [set](../../tech.whence.echo.support.mongo.querier.component/-setter/set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [BigInteger](https://docs.oracle.com/javase/8/docs/api/java/math/BigInteger.html)): [Insert](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置日期<br><br>  <br>Content  <br>open override fun [set](../../tech.whence.echo.support.mongo.querier.component/-setter/set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [LocalDate](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDate.html)): [Insert](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置日期时间<br><br>  <br>Content  <br>open override fun [set](../../tech.whence.echo.support.mongo.querier.component/-setter/set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)): [Insert](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置时间<br><br>  <br>Content  <br>open override fun [set](../../tech.whence.echo.support.mongo.querier.component/-setter/set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [LocalTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalTime.html)): [Insert](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>指定字符序列<br><br>  <br>Content  <br>open override fun [set](../../tech.whence.echo.support.mongo.querier.component/-setter/set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [CharSequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html)): [Insert](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置数值型<br><br>  <br>Content  <br>open override fun [set](../../tech.whence.echo.support.mongo.querier.component/-setter/set.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)): [Insert](index.md)  <br><br><br>
| [toString](to-string.md)| [jvm]  <br>Content  <br>open override fun [toString](to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [writing](writing.md)| [jvm]  <br>Brief description  <br><br><br>设置写入策略<br><br>  <br>Content  <br>fun [writing](writing.md)(writing: [Writing](../../tech.whence.echo.support.mongo.querier.component/-writing/index.md)): [Insert](index.md)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [description](index.md#tech.whence.echo.support.mongo.querier/Insert/description/#/PointingToDeclaration/)|  [jvm] open override val [description](index.md#tech.whence.echo.support.mongo.querier/Insert/description/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [renamer](index.md#tech.whence.echo.support.mongo.querier/Insert/renamer/#/PointingToDeclaration/)|  [jvm] override var [renamer](index.md#tech.whence.echo.support.mongo.querier/Insert/renamer/#/PointingToDeclaration/): [Fixer](../../tech.whence.echo.function/-fixer/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>   <br>
| [valid](index.md#tech.whence.echo.support.mongo.querier/Insert/valid/#/PointingToDeclaration/)|  [jvm] open override val [valid](index.md#tech.whence.echo.support.mongo.querier/Insert/valid/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>

