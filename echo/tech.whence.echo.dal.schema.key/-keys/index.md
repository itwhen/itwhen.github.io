---
title: Keys -
---
//[echo](../../index.md)/[tech.whence.echo.dal.schema.key](../index.md)/[Keys](index.md)



# Keys  
 [jvm] 

数据表字段集合

class [Keys](index.md) : [Container](../../tech.whence.echo.container/-container/index.md)   


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [access](access.md)| [jvm]  <br>Brief description  <br><br><br>根据指定字段转换器生成数据访问器<br><br>  <br>Content  <br>fun [access](access.md)(transformer: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[Key](../-key/index.md), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)  <br><br><br>
| [annotate](annotate.md)| [jvm]  <br>Brief description  <br><br><br>查找含指定注解的字段<br><br>  <br>Content  <br>inline fun <[A](annotate.md) : [Annotation](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-annotation/index.html)> [annotate](annotate.md)(): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[Key](../-key/index.md), [A](annotate.md)>  <br><br><br>
| [arrange](arrange.md)| [jvm]  <br>Brief description  <br><br><br>根据指定字段名列表生成新的字段集合<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [arrange](arrange.md)(keys: [Iterable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>, indexer: [Indexer](../-indexer/index.md)?): [Keys](index.md)  <br><br><br>
| [assemble](assemble.md)| [jvm]  <br>Brief description  <br><br><br>根据指定的实体类型与当前字段数据组装成一个新的字段集合<br><br>  <br>Content  <br>fun [assemble](assemble.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)>): [Keys](index.md)  <br><br><br>
| [create](create.md)| [jvm]  <br>Brief description  <br><br><br>根据当前字段集合创建字段<br><br>  <br>Content  <br>fun [create](create.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), type: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>, existence: [Existence](../-existence/index.md)): [Key](../-key/index.md)  <br><br><br>
| [diff](diff.md)| [jvm]  <br>Brief description  <br><br><br>找出指定字段集合与当前集合的字段差异<br><br>  <br>Content  <br>fun [diff](diff.md)(keys: [Keys](index.md)): [Keys](index.md)  <br><br><br>
| [each](each.md)| [jvm]  <br>Brief description  <br><br><br>遍历所有字段执行指定回调<br><br>  <br>Content  <br>fun [each](each.md)(consumer: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<[Key](../-key/index.md)>)  <br><br><br>
| [equals](equals.md)| [jvm]  <br>Content  <br>open operator override fun [equals](equals.md)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [extract](extract.md)| [jvm]  <br>Brief description  <br><br><br>提取指定条件下的字段<br><br>  <br>Content  <br>fun [extract](extract.md)(predicate: [Predicate](../../tech.whence.echo.function/-predicate/index.md)<[Key](../-key/index.md)>): [Keys](index.md)  <br><br><br>
| [get](get.md)| [jvm]  <br>Brief description  <br><br><br>根据字段名取字段<br><br>  <br>Content  <br>operator fun [get](get.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Key](../-key/index.md)?  <br><br><br>
| [has](has.md)| [jvm]  <br>Brief description  <br><br><br>判断指定字段名是否存在<br><br>  <br>Content  <br>fun [has](has.md)(vararg keys: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](hash-code.md)| [jvm]  <br>Content  <br>open override fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [load](load.md)| [jvm]  <br>Brief description  <br><br><br>加载字段 若已经加载则忽略之 将检查指定字段集合与当前集合是否一个实体 将检查指定字段集合中的字段是否与当前集合里一致 检查通过后将覆盖当前集合数据 将待检字段置为虚拟字段 并设置为已经加载<br><br>  <br>Content  <br>fun [load](load.md)(keys: [Keys](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [merge](merge.md)| [jvm]  <br>Brief description  <br><br><br>合并指定字段集合 生成新的字段集合<br><br>  <br>Content  <br>fun [merge](merge.md)(keys: [Keys](index.md), override: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Keys](index.md)  <br><br><br>
| [prepare](prepare.md)| [jvm]  <br>Brief description  <br><br><br>准备字段 若不存在自动增加<br><br>  <br>Content  <br>fun [prepare](prepare.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), type: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>?): [Key](../-key/index.md)  <br><br><br>
| [remove](remove.md)| [jvm]  <br>Brief description  <br><br><br>移除指定字段<br><br>  <br>Content  <br>fun [remove](remove.md)(vararg keys: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>)  <br><br><br>
| [rename](rename.md)| [jvm]  <br>Brief description  <br><br><br>重命名字段名<br><br>  <br>Content  <br>fun [rename](rename.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [sequence](sequence.md)| [jvm]  <br>Brief description  <br><br><br>序列化<br><br>  <br>Content  <br>fun [sequence](sequence.md)(): [Sequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.sequences/-sequence/index.html)<[Key](../-key/index.md)>  <br><br><br>
| [set](set.md)| [jvm]  <br>Brief description  <br><br><br>设置指定字段并返回是否成功 若已加载返回假 虚拟键不受限 否则添加到数据中并返回真 重复字段将合并注解(实现接口时)<br><br>  <br>Content  <br>fun [set](set.md)(key: [Key](../-key/index.md), renew: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [toString](to-string.md)| [jvm]  <br>Content  <br>open override fun [toString](to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [declaration](index.md#tech.whence.echo.dal.schema.key/Keys/declaration/#/PointingToDeclaration/)|  [jvm] <br><br>Map<String, KClass<*>> 相关字段类型映射<br><br>val [declaration](index.md#tech.whence.echo.dal.schema.key/Keys/declaration/#/PointingToDeclaration/): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>>   <br>
| [declarer](index.md#tech.whence.echo.dal.schema.key/Keys/declarer/#/PointingToDeclaration/)|  [jvm] <br><br>KClass<out Entity> 相关实体类型<br><br>lateinit var [declarer](index.md#tech.whence.echo.dal.schema.key/Keys/declarer/#/PointingToDeclaration/): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)>   <br>
| [empty](index.md#tech.whence.echo.dal.schema.key/Keys/empty/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 当前字段映射是否为空<br><br>open override val [empty](index.md#tech.whence.echo.dal.schema.key/Keys/empty/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [indexes](index.md#tech.whence.echo.dal.schema.key/Keys/indexes/#/PointingToDeclaration/)|  [jvm] <br><br>Set<String> 相关字段名集合<br><br>val [indexes](index.md#tech.whence.echo.dal.schema.key/Keys/indexes/#/PointingToDeclaration/): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>   <br>
| [loaded](index.md#tech.whence.echo.dal.schema.key/Keys/loaded/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否已经加载<br><br>var [loaded](index.md#tech.whence.echo.dal.schema.key/Keys/loaded/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [size](index.md#tech.whence.echo.dal.schema.key/Keys/size/#/PointingToDeclaration/)|  [jvm] <br><br>UInt 相关字段数量<br><br>open override val [size](index.md#tech.whence.echo.dal.schema.key/Keys/size/#/PointingToDeclaration/): [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)   <br>
| [subsistent](index.md#tech.whence.echo.dal.schema.key/Keys/subsistent/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否实际存在<br><br>val [subsistent](index.md#tech.whence.echo.dal.schema.key/Keys/subsistent/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>

