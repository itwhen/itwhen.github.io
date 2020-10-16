---
title: Key -
---
//[echo](../../index.md)/[tech.whence.echo.dal.schema.key](../index.md)/[Key](index.md)



# Key  
 [jvm] 

数据表字段

class [Key](index.md) : [Codec.Definition](../../tech.whence.echo.codec/-codec/-definition/index.md)   


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>
| [Definition](-definition/index.md)| [jvm]  <br>Brief description  <br><br><br>数据源定义<br><br>  <br>Content  <br>data class [Definition](-definition/index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **title**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **type**: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>?, **retrievable**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **updatable**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [annotate](../../tech.whence.echo.codec/-codec/-definition/annotate.md)| [jvm]  <br>Brief description  <br><br><br>取相关字段指定注解<br><br>  <br>Content  <br>inline override fun <T : [Annotation](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-annotation/index.html)> [annotate](../../tech.whence.echo.codec/-codec/-definition/annotate.md)(): T?  <br><br><br>
| [belong](../../tech.whence.echo.codec/-codec/-definition/belong.md)| [jvm]  <br>Brief description  <br><br><br>判断是否是指定类型<br><br>  <br>Content  <br>override fun [belong](../../tech.whence.echo.codec/-codec/-definition/belong.md)(type: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [cast](cast.md)| [jvm]  <br>Brief description  <br><br><br>根据定义类型转换指定值<br><br>  <br>Content  <br>fun [cast](cast.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [fit](../../tech.whence.echo.codec/-codec/-definition/fit.md)| [jvm]  <br>Brief description  <br><br><br>判断指定值是否无需解析<br><br>  <br>Content  <br>override fun [fit](../../tech.whence.echo.codec/-codec/-definition/fit.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [get](get.md)| [jvm]  <br>Brief description  <br><br><br>从指定实体中获取当前字段的值 若当前取值器[watcher](index.md#tech.whence.echo.dal.schema.key/Key/watcher/#/PointingToDeclaration/)有效则直接转换(可用作mock) 若raw为真时获取原始数据 若当前是静态实体字段且相关字段属性存在则获取实体中值 若当前是动态实体字段获取原始数据后根据指定字段类型再进行转换<br><br>  <br>Content  <br>fun <[E](get.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [get](get.md)(entity: [E](get.md), raw: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [renew](renew.md)| [jvm]  <br>Brief description  <br><br><br>更新所在字段集合中的序号 若当前序号为空则返回自身 否则创建一个新字段返回<br><br>  <br>Content  <br>fun [renew](renew.md)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?): [Key](index.md)  <br><br><br>
| [respond](../../tech.whence.echo.codec/-codec/-definition/respond.md)| [jvm]  <br>Brief description  <br><br><br>判断是否由指定类型定义<br><br>  <br>Content  <br>override fun [respond](../../tech.whence.echo.codec/-codec/-definition/respond.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [set](set.md)| [jvm]  <br>Brief description  <br><br><br>给指定实体设置当前字段的值 若指定实体是动态实体则直接设置 否则相关实体属性存在则也设置<br><br>  <br>Content  <br>fun <[E](set.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [set](set.md)(entity: [E](set.md), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, process: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Key](index.md)  <br><br><br>
| [toString](to-string.md)| [jvm]  <br>Content  <br>open override fun [toString](to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [annotations](index.md#tech.whence.echo.dal.schema.key/Key/annotations/#/PointingToDeclaration/)|  [jvm] <br><br>List<Annotation>? 相关注解<br><br>open override val [annotations](index.md#tech.whence.echo.dal.schema.key/Key/annotations/#/PointingToDeclaration/): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Annotation](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-annotation/index.html)>   <br>
| [declarer](index.md#tech.whence.echo.dal.schema.key/Key/declarer/#/PointingToDeclaration/)|  [jvm] <br><br>KClass<out Entity>? 相关实体类型<br><br>open override val [declarer](index.md#tech.whence.echo.dal.schema.key/Key/declarer/#/PointingToDeclaration/): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)>?   <br>
| [definition](index.md#tech.whence.echo.dal.schema.key/Key/definition/#/PointingToDeclaration/)|  [jvm] <br><br>Definition 定义<br><br>val [definition](index.md#tech.whence.echo.dal.schema.key/Key/definition/#/PointingToDeclaration/): [Key.Definition](-definition/index.md)   <br>
| [dynamic](index.md#tech.whence.echo.dal.schema.key/Key/dynamic/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否是动态的<br><br>val [dynamic](index.md#tech.whence.echo.dal.schema.key/Key/dynamic/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [index](index.md#tech.whence.echo.dal.schema.key/Key/index/#/PointingToDeclaration/)|  [jvm] <br><br>UInt? 在当前数据表字段定义中的序号<br><br>var [index](index.md#tech.whence.echo.dal.schema.key/Key/index/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?   <br>
| [name](index.md#tech.whence.echo.dal.schema.key/Key/name/#/PointingToDeclaration/)|  [jvm] <br><br>String 名称<br><br>open override val [name](index.md#tech.whence.echo.dal.schema.key/Key/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [property](index.md#tech.whence.echo.dal.schema.key/Key/property/#/PointingToDeclaration/)|  [jvm] <br><br>KProperty<*>? 相关实体属性<br><br>open override val [property](index.md#tech.whence.echo.dal.schema.key/Key/property/#/PointingToDeclaration/): [KProperty](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-property/index.html)<*>?   <br>
| [retrievable](index.md#tech.whence.echo.dal.schema.key/Key/retrievable/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否需要从数据源获取<br><br>val [retrievable](index.md#tech.whence.echo.dal.schema.key/Key/retrievable/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [static](index.md#tech.whence.echo.dal.schema.key/Key/static/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否是静态的<br><br>val [static](index.md#tech.whence.echo.dal.schema.key/Key/static/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [subsistent](index.md#tech.whence.echo.dal.schema.key/Key/subsistent/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否实际存在的 当字段信息从实体或数据源获取而来时为真<br><br>val [subsistent](index.md#tech.whence.echo.dal.schema.key/Key/subsistent/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [title](index.md#tech.whence.echo.dal.schema.key/Key/title/#/PointingToDeclaration/)|  [jvm] <br><br>String 标题 用作数据导出时的字段翻译<br><br>val [title](index.md#tech.whence.echo.dal.schema.key/Key/title/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [type](index.md#tech.whence.echo.dal.schema.key/Key/type/#/PointingToDeclaration/)|  [jvm] <br><br>KClass<*> 自身类型<br><br>open override val [type](index.md#tech.whence.echo.dal.schema.key/Key/type/#/PointingToDeclaration/): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>   <br>
| [unchecked](index.md#tech.whence.echo.dal.schema.key/Key/unchecked/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否是待检的<br><br>val [unchecked](index.md#tech.whence.echo.dal.schema.key/Key/unchecked/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [updatable](index.md#tech.whence.echo.dal.schema.key/Key/updatable/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否可更新到数据源<br><br>val [updatable](index.md#tech.whence.echo.dal.schema.key/Key/updatable/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [virtual](index.md#tech.whence.echo.dal.schema.key/Key/virtual/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否是虚拟的<br><br>val [virtual](index.md#tech.whence.echo.dal.schema.key/Key/virtual/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [watcher](index.md#tech.whence.echo.dal.schema.key/Key/watcher/#/PointingToDeclaration/)|  [jvm] <br><br>Watcher? 观察者<br><br>val [watcher](index.md#tech.whence.echo.dal.schema.key/Key/watcher/#/PointingToDeclaration/): [Watcher](../-watcher/index.md)?   <br>

