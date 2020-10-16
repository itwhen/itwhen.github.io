---
title: Builder -
---
//[echo](../../index.md)/[tech.whence.echo.dal.schema](../index.md)/[Builder](index.md)



# Builder  
 [jvm] 

数据表构造器

class [Builder](index.md)<[T](index.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)>   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| T| <br><br>: Entity 实体类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Builder](-builder.md)|  [jvm] <br><br>: Entity 实体类型<br><br>fun [Builder](-builder.md)()   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [build](build.md)| [jvm]  <br>Brief description  <br><br><br>构造数据表<br><br>  <br>Content  <br>fun [build](build.md)(verifier: [Verifier](../-verifier/index.md)?): [Schema](../-schema/index.md)<[T](index.md)>  <br><br><br>
| [constraint](constraint.md)| [jvm]  <br>Brief description  <br><br><br>设置字段约束<br><br>  <br>Content  <br>fun [constraint](constraint.md)(operation: [Operation](../../tech.whence.echo.dal.dao/-operation/index.md), constraint: [Constraint](../../tech.whence.echo.dal.schema.key/-constraint/index.md), vararg keys: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [CharSequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html)>): [Builder](index.md)<[T](index.md)>  <br><br><br>
| [debug](debug.md)| [jvm]  <br>Brief description  <br><br><br>开启调试模式<br><br>  <br>Content  <br>fun [debug](debug.md)(): [Builder](index.md)<[T](index.md)>  <br><br><br>
| [declarer](declarer.md)| [jvm]  <br>Brief description  <br><br><br>设置实体类型及其字段 将生成动态实体<br><br>  <br>Content  <br>fun [declarer](declarer.md)(): [Builder](index.md)<[T](index.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>根据字段名及类型设置实体类型及其字段集合 将生成动态实体<br><br>  <br>Content  <br>fun [declarer](declarer.md)(keys: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>>): [Builder](index.md)<[T](index.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置实体类型及其字段集合 将生成静态实体<br><br>  <br>Content  <br>fun [declarer](declarer.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[T](index.md)>): [Builder](index.md)<[T](index.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>根据数据表描述器设置实体类型及其字段 将生成动态实体<br><br>  <br>Content  <br>fun [declarer](declarer.md)(describer: [Describer](../-describer/index.md)): [Builder](index.md)<[T](index.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>根据字段集合设置实体类型及其字段 将生成动态实体<br><br>  <br>Content  <br>fun [declarer](declarer.md)(keys: [Keys](../../tech.whence.echo.dal.schema.key/-keys/index.md)): [Builder](index.md)<[T](index.md)>  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [identity](identity.md)| [jvm]  <br>Brief description  <br><br><br>设置字段身份<br><br>  <br>Content  <br>fun [identity](identity.md)(identity: [Identity](../../tech.whence.echo.dal.schema.key/-identity/index.md), vararg keys: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [CharSequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html)>): [Builder](index.md)<[T](index.md)>  <br><br><br>
| [ignore](ignore.md)| [jvm]  <br>Brief description  <br><br><br>设置忽略字段<br><br>  <br>Content  <br>fun [ignore](ignore.md)(operation: [Operation](../../tech.whence.echo.dal.dao/-operation/index.md), vararg keys: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [CharSequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html)>): [Builder](index.md)<[T](index.md)>  <br><br><br>
| [index](--index--.md)| [jvm]  <br>Brief description  <br><br><br>设置索引<br><br>  <br>Content  <br>fun [index](--index--.md)(key: [CharSequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html)): [Builder](index.md)<[T](index.md)>  <br><br><br>
| [primary](primary.md)| [jvm]  <br>Brief description  <br><br><br>设置主键<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [primary](primary.md)(key: [CharSequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html), type: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<*>, generate: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), proxy: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [Builder](index.md)<[T](index.md)>  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [primary](primary.md)(key: [CharSequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html), type: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>?, generate: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), proxy: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [Builder](index.md)<[T](index.md)>  <br><br><br>
| [readonly](readonly.md)| [jvm]  <br>Brief description  <br><br><br>设置字段只读模式<br><br>  <br>Content  <br>fun [readonly](readonly.md)(key: [CharSequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html)): [Builder](index.md)<[T](index.md)>  <br><br><br>
| [renaming](renaming.md)| [jvm]  <br>Brief description  <br><br><br>设置字段映射策略<br><br>  <br>Content  <br>fun [renaming](renaming.md)(strategy: [NamingStrategy](../../tech.whence.echo.strategy/-naming-strategy/index.md)): [Builder](index.md)<[T](index.md)>  <br><br><br>
| [require](require.md)| [jvm]  <br>Brief description  <br><br><br>设置必填字段<br><br>  <br>Content  <br>fun [require](require.md)(operation: [Operation](../../tech.whence.echo.dal.dao/-operation/index.md), vararg keys: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [CharSequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html)>): [Builder](index.md)<[T](index.md)>  <br><br><br>
| [sharding](sharding.md)| [jvm]  <br>Brief description  <br><br><br>设置分区字段 在数据创建时必填 在数据修改时忽略<br><br>  <br>Content  <br>fun [sharding](sharding.md)(key: [CharSequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html)): [Builder](index.md)<[T](index.md)>  <br><br><br>
| [table](table.md)| [jvm]  <br>Brief description  <br><br><br>设置表名<br><br>  <br>Content  <br>fun [table](table.md)(table: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Builder](index.md)<[T](index.md)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [transaction](transaction.md)| [jvm]  <br>Brief description  <br><br><br>支持事务<br><br>  <br>Content  <br>fun [transaction](transaction.md)(): [Builder](index.md)<[T](index.md)>  <br><br><br>
| [unique](unique.md)| [jvm]  <br>Brief description  <br><br><br>设置唯一索引<br><br>  <br>Content  <br>fun [unique](unique.md)(key: [CharSequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html)): [Builder](index.md)<[T](index.md)>  <br><br><br>
| [virtual](virtual.md)| [jvm]  <br>Brief description  <br><br><br>设置虚拟字段 需先定义字段集合及实体类型<br><br>  <br>Content  <br>fun [virtual](virtual.md)(key: [CharSequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html), type: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<*>): [Builder](index.md)<[T](index.md)>  <br>fun [virtual](virtual.md)(key: [CharSequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html), type: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>): [Builder](index.md)<[T](index.md)>  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [constraints](index.md#tech.whence.echo.dal.schema/Builder/constraints/#/PointingToDeclaration/)|  [jvm] <br><br>MutableMap<EntityOperation, MutableMap<String, Constraint>> 约束<br><br>val [constraints](index.md#tech.whence.echo.dal.schema/Builder/constraints/#/PointingToDeclaration/): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Operation](../../tech.whence.echo.dal.dao/-operation/index.md), [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Constraint](../../tech.whence.echo.dal.schema.key/-constraint/index.md)>>   <br>
| [debug](debug.md)|  [jvm] <br><br>Boolean 是否开启调试<br><br>var [debug](debug.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [declarer](declarer.md)|  [jvm] <br><br>KClass<T>? 实体类型<br><br>var [declarer](declarer.md): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[T](index.md)>?   <br>
| [identities](index.md#tech.whence.echo.dal.schema/Builder/identities/#/PointingToDeclaration/)|  [jvm] <br><br>MutableMap<String, Identity> 身份<br><br>val [identities](index.md#tech.whence.echo.dal.schema/Builder/identities/#/PointingToDeclaration/): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [MutableSet](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-set/index.html)<[Identity](../../tech.whence.echo.dal.schema.key/-identity/index.md)>>   <br>
| [keymaker](index.md#tech.whence.echo.dal.schema/Builder/keymaker/#/PointingToDeclaration/)|  [jvm] <br><br>NamingStrategy? 实体与数据源字段映射策略<br><br>var [keymaker](index.md#tech.whence.echo.dal.schema/Builder/keymaker/#/PointingToDeclaration/): [NamingStrategy](../../tech.whence.echo.strategy/-naming-strategy/index.md)?   <br>
| [keys](index.md#tech.whence.echo.dal.schema/Builder/keys/#/PointingToDeclaration/)|  [jvm] <br><br>Keys? 字段集合<br><br>var [keys](index.md#tech.whence.echo.dal.schema/Builder/keys/#/PointingToDeclaration/): [Keys](../../tech.whence.echo.dal.schema.key/-keys/index.md)?   <br>
| [primary](index.md#tech.whence.echo.dal.schema/Builder/primary/#/PointingToDeclaration/)|  [jvm] <br><br>PrimaryKey? 主键<br><br>var [primary](index.md#tech.whence.echo.dal.schema/Builder/primary/#/PointingToDeclaration/): [PrimaryKey](../../tech.whence.echo.dal.schema.key/-primary-key/index.md)?   <br>
| [table](index.md#tech.whence.echo.dal.schema/Builder/table/#/PointingToDeclaration/)|  [jvm] <br><br>String? 表名<br><br>var [table](index.md#tech.whence.echo.dal.schema/Builder/table/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [transactional](index.md#tech.whence.echo.dal.schema/Builder/transactional/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否支持事务<br><br>var [transactional](index.md#tech.whence.echo.dal.schema/Builder/transactional/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>

