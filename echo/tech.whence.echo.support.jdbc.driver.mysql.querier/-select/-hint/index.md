---
title: Hint -
---
//[echo](../../../index.md)/[tech.whence.echo.support.jdbc.driver.mysql.querier](../../index.md)/[Select](../index.md)/[Hint](index.md)



# Hint  
 [jvm] 

索引提示

sealed class [Hint](index.md)   


## Types  
  
|  Name|  Summary| 
|---|---|
| [ForceIndex](-force-index/index.md)| [jvm]  <br>Brief description  <br><br><br>强制使用索引<br><br>  <br>Content  <br>class [ForceIndex](-force-index/index.md)(**indexes**: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>) : [Select.Hint](index.md)  <br><br><br>
| [ForceIndexForGroupBy](-force-index-for-group-by/index.md)| [jvm]  <br>Brief description  <br><br><br>在分组时强制使用索引<br><br>  <br>Content  <br>class [ForceIndexForGroupBy](-force-index-for-group-by/index.md)(**indexes**: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>) : [Select.Hint](index.md)  <br><br><br>
| [ForceIndexForJoin](-force-index-for-join/index.md)| [jvm]  <br>Brief description  <br><br><br>在联表时强制使用索引<br><br>  <br>Content  <br>class [ForceIndexForJoin](-force-index-for-join/index.md)(**indexes**: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>) : [Select.Hint](index.md)  <br><br><br>
| [ForceIndexForOrderBy](-force-index-for-order-by/index.md)| [jvm]  <br>Brief description  <br><br><br>在排序时强制使用索引<br><br>  <br>Content  <br>class [ForceIndexForOrderBy](-force-index-for-order-by/index.md)(**indexes**: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>) : [Select.Hint](index.md)  <br><br><br>
| [IgnoreIndex](-ignore-index/index.md)| [jvm]  <br>Brief description  <br><br><br>忽略索引<br><br>  <br>Content  <br>class [IgnoreIndex](-ignore-index/index.md)(**indexes**: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>) : [Select.Hint](index.md)  <br><br><br>
| [IgnoreIndexForGroupBy](-ignore-index-for-group-by/index.md)| [jvm]  <br>Brief description  <br><br><br>在分组时忽略索引<br><br>  <br>Content  <br>class [IgnoreIndexForGroupBy](-ignore-index-for-group-by/index.md)(**indexes**: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>) : [Select.Hint](index.md)  <br><br><br>
| [IgnoreIndexForJoin](-ignore-index-for-join/index.md)| [jvm]  <br>Brief description  <br><br><br>在联表时忽略索引<br><br>  <br>Content  <br>class [IgnoreIndexForJoin](-ignore-index-for-join/index.md)(**indexes**: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>) : [Select.Hint](index.md)  <br><br><br>
| [IgnoreIndexForOrderBy](-ignore-index-for-order-by/index.md)| [jvm]  <br>Brief description  <br><br><br>在排序时忽略索引<br><br>  <br>Content  <br>class [IgnoreIndexForOrderBy](-ignore-index-for-order-by/index.md)(**indexes**: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>) : [Select.Hint](index.md)  <br><br><br>
| [UseIndex](-use-index/index.md)| [jvm]  <br>Brief description  <br><br><br>使用索引<br><br>  <br>Content  <br>class [UseIndex](-use-index/index.md)(**indexes**: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>) : [Select.Hint](index.md)  <br><br><br>
| [UseIndexForGroupBy](-use-index-for-group-by/index.md)| [jvm]  <br>Brief description  <br><br><br>在分组时使用索引<br><br>  <br>Content  <br>class [UseIndexForGroupBy](-use-index-for-group-by/index.md)(**indexes**: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>) : [Select.Hint](index.md)  <br><br><br>
| [UseIndexForJoin](-use-index-for-join/index.md)| [jvm]  <br>Brief description  <br><br><br>在联表时使用索引<br><br>  <br>Content  <br>class [UseIndexForJoin](-use-index-for-join/index.md)(**indexes**: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>) : [Select.Hint](index.md)  <br><br><br>
| [UseIndexForOrderBy](-use-index-for-order-by/index.md)| [jvm]  <br>Brief description  <br><br><br>在排序时使用索引<br><br>  <br>Content  <br>class [UseIndexForOrderBy](-use-index-for-order-by/index.md)(**indexes**: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>) : [Select.Hint](index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [indexes](index.md#tech.whence.echo.support.jdbc.driver.mysql.querier/Select.Hint/indexes/#/PointingToDeclaration/)|  [jvm] <br><br>Array<out String> 指定索引<br><br>val [indexes](index.md#tech.whence.echo.support.jdbc.driver.mysql.querier/Select.Hint/indexes/#/PointingToDeclaration/): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>   <br>
| [text](index.md#tech.whence.echo.support.jdbc.driver.mysql.querier/Select.Hint/text/#/PointingToDeclaration/)|  [jvm] <br><br>String 语句文本<br><br>val [text](index.md#tech.whence.echo.support.jdbc.driver.mysql.querier/Select.Hint/text/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>


## Inheritors  
  
|  Name| 
|---|
| [Select.Hint](-use-index/index.md)
| [Select.Hint](-use-index-for-join/index.md)
| [Select.Hint](-use-index-for-order-by/index.md)
| [Select.Hint](-use-index-for-group-by/index.md)
| [Select.Hint](-ignore-index/index.md)
| [Select.Hint](-ignore-index-for-join/index.md)
| [Select.Hint](-ignore-index-for-order-by/index.md)
| [Select.Hint](-ignore-index-for-group-by/index.md)
| [Select.Hint](-force-index/index.md)
| [Select.Hint](-force-index-for-join/index.md)
| [Select.Hint](-force-index-for-order-by/index.md)
| [Select.Hint](-force-index-for-group-by/index.md)

