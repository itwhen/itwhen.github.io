---
title: ArrayData -
---
//[echo](../../../index.md)/[tech.whence.echo.container.accessor](../../index.md)/[Factory](../index.md)/[ArrayData](index.md)



# ArrayData  
 [jvm] 

表单列表

data class [ArrayData](index.md)<[T](index.md)>(**data**: [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[T](index.md)>) : [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[T](index.md)>    


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| T| <br><br>存放数据类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [ArrayData](-array-data.md)|  [jvm] <br><br><br><br>fun <[T](index.md)> [ArrayData](-array-data.md)(data: [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[T](index.md)>)   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [add](index.md#kotlin.collections/MutableList/add/#TypeParam(bounds=[kotlin.Any?])/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [add](index.md#kotlin.collections/MutableList/add/#TypeParam(bounds=[kotlin.Any?])/PointingToDeclaration/)(element: [T](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br>open override fun [add](index.md#kotlin.collections/MutableList/add/#kotlin.Int#TypeParam(bounds=[kotlin.Any?])/PointingToDeclaration/)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), element: [T](index.md))  <br><br><br>
| [addAll](index.md#kotlin.collections/MutableList/addAll/#kotlin.collections.Collection[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [addAll](index.md#kotlin.collections/MutableList/addAll/#kotlin.collections.Collection[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/)(elements: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[T](index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br>open override fun [addAll](index.md#kotlin.collections/MutableList/addAll/#kotlin.Int#kotlin.collections.Collection[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), elements: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[T](index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [clear](index.md#kotlin.collections/MutableList/clear/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [clear](index.md#kotlin.collections/MutableList/clear/#/PointingToDeclaration/)()  <br><br><br>
| [component1](component1.md)| [jvm]  <br>Content  <br>operator fun [component1](component1.md)(): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[T](index.md)>  <br><br><br>
| [contains](index.md#kotlin.collections/List/contains/#TypeParam(bounds=[kotlin.Any?])/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [contains](index.md#kotlin.collections/List/contains/#TypeParam(bounds=[kotlin.Any?])/PointingToDeclaration/)(element: [T](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [containsAll](index.md#kotlin.collections/List/containsAll/#kotlin.collections.Collection[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [containsAll](index.md#kotlin.collections/List/containsAll/#kotlin.collections.Collection[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/)(elements: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[T](index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [copy](copy.md)| [jvm]  <br>Content  <br>fun [copy](copy.md)(data: [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[T](index.md)>): [Factory.ArrayData](index.md)<[T](index.md)>  <br><br><br>
| [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [forEach](index.md#kotlin.collections/Iterable/forEach/#java.util.function.Consumer[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [forEach](index.md#kotlin.collections/Iterable/forEach/#java.util.function.Consumer[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [T](index.md)>)  <br><br><br>
| [get](index.md#kotlin.collections/List/get/#kotlin.Int/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [get](index.md#kotlin.collections/List/get/#kotlin.Int/PointingToDeclaration/)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [T](index.md)  <br><br><br>
| [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [indexOf](index.md#kotlin.collections/List/indexOf/#TypeParam(bounds=[kotlin.Any?])/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [indexOf](index.md#kotlin.collections/List/indexOf/#TypeParam(bounds=[kotlin.Any?])/PointingToDeclaration/)(element: [T](index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [isEmpty](index.md#kotlin.collections/List/isEmpty/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [isEmpty](index.md#kotlin.collections/List/isEmpty/#/PointingToDeclaration/)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [iterator](index.md#kotlin.collections/List/iterator/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [iterator](index.md#kotlin.collections/List/iterator/#/PointingToDeclaration/)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[T](index.md)>  <br><br><br>
| [lastIndexOf](index.md#kotlin.collections/List/lastIndexOf/#TypeParam(bounds=[kotlin.Any?])/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [lastIndexOf](index.md#kotlin.collections/List/lastIndexOf/#TypeParam(bounds=[kotlin.Any?])/PointingToDeclaration/)(element: [T](index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [listIterator](index.md#kotlin.collections/MutableList/listIterator/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [listIterator](index.md#kotlin.collections/MutableList/listIterator/#/PointingToDeclaration/)(): [MutableListIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list-iterator/index.html)<[T](index.md)>  <br>open override fun [listIterator](index.md#kotlin.collections/MutableList/listIterator/#kotlin.Int/PointingToDeclaration/)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [MutableListIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list-iterator/index.html)<[T](index.md)>  <br><br><br>
| [parallelStream](index.md#kotlin.collections/Collection/parallelStream/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [parallelStream](index.md#kotlin.collections/Collection/parallelStream/#/PointingToDeclaration/)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[T](index.md)>  <br><br><br>
| [remove](index.md#kotlin.collections/MutableList/remove/#TypeParam(bounds=[kotlin.Any?])/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [remove](index.md#kotlin.collections/MutableList/remove/#TypeParam(bounds=[kotlin.Any?])/PointingToDeclaration/)(element: [T](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [removeAll](index.md#kotlin.collections/MutableList/removeAll/#kotlin.collections.Collection[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [removeAll](index.md#kotlin.collections/MutableList/removeAll/#kotlin.collections.Collection[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/)(elements: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[T](index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [removeAt](index.md#kotlin.collections/MutableList/removeAt/#kotlin.Int/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [removeAt](index.md#kotlin.collections/MutableList/removeAt/#kotlin.Int/PointingToDeclaration/)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [T](index.md)  <br><br><br>
| [removeIf](index.md#kotlin.collections/MutableCollection/removeIf/#java.util.function.Predicate[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [removeIf](index.md#kotlin.collections/MutableCollection/removeIf/#java.util.function.Predicate[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/)(p0: [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<in [T](index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [replaceAll](index.md#kotlin.collections/MutableList/replaceAll/#java.util.function.UnaryOperator[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [replaceAll](index.md#kotlin.collections/MutableList/replaceAll/#java.util.function.UnaryOperator[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/)(p0: [UnaryOperator](https://docs.oracle.com/javase/8/docs/api/java/util/function/UnaryOperator.html)<[T](index.md)>)  <br><br><br>
| [retainAll](index.md#kotlin.collections/MutableList/retainAll/#kotlin.collections.Collection[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [retainAll](index.md#kotlin.collections/MutableList/retainAll/#kotlin.collections.Collection[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/)(elements: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[T](index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [set](index.md#kotlin.collections/MutableList/set/#kotlin.Int#TypeParam(bounds=[kotlin.Any?])/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [set](index.md#kotlin.collections/MutableList/set/#kotlin.Int#TypeParam(bounds=[kotlin.Any?])/PointingToDeclaration/)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), element: [T](index.md)): [T](index.md)  <br><br><br>
| [sort](index.md#kotlin.collections/MutableList/sort/#java.util.Comparator[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [sort](index.md#kotlin.collections/MutableList/sort/#java.util.Comparator[TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/)(p0: [Comparator](https://docs.oracle.com/javase/8/docs/api/java/util/Comparator.html)<in [T](index.md)>)  <br><br><br>
| [spliterator](index.md#kotlin.collections/List/spliterator/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [spliterator](index.md#kotlin.collections/List/spliterator/#/PointingToDeclaration/)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](index.md)>  <br><br><br>
| [stream](index.md#kotlin.collections/Collection/stream/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [stream](index.md#kotlin.collections/Collection/stream/#/PointingToDeclaration/)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[T](index.md)>  <br><br><br>
| [subList](index.md#kotlin.collections/MutableList/subList/#kotlin.Int#kotlin.Int/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [subList](index.md#kotlin.collections/MutableList/subList/#kotlin.Int#kotlin.Int/PointingToDeclaration/)(fromIndex: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), toIndex: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[T](index.md)>  <br><br><br>
| [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [data](index.md#tech.whence.echo.container.accessor/Factory.ArrayData/data/#/PointingToDeclaration/)|  [jvm] <br><br>MutableList<T> 数据委托<br><br>val [data](index.md#tech.whence.echo.container.accessor/Factory.ArrayData/data/#/PointingToDeclaration/): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[T](index.md)>   <br>
| [size](index.md#tech.whence.echo.container.accessor/Factory.ArrayData/size/#/PointingToDeclaration/)|  [jvm] open override val [size](index.md#tech.whence.echo.container.accessor/Factory.ArrayData/size/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>

