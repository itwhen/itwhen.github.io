---
title: Schema -
---
//[echo](../../index.md)/[tech.whence.echo.dal.schema](../index.md)/[Schema](index.md)



# Schema  
 [jvm] 

数据表

class [Schema](index.md)<[T](index.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)>   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| T| <br><br>: Entity 相关实体<br><br>
  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [check](check.md)| [jvm]  <br>Brief description  <br><br><br>检查主键有效性<br><br>  <br>Content  <br>fun [check](check.md)()  <br><br><br>[jvm]  <br>Brief description  <br><br><br>检查实体有效性<br><br>  <br>Content  <br>fun [check](check.md)(entity: [T](index.md))  <br><br><br>
| [checkPrimaryKeyProvision](check-primary-key-provision.md)| [jvm]  <br>Brief description  <br><br><br>检查实体主键情况<br><br>  <br>Content  <br>fun [checkPrimaryKeyProvision](check-primary-key-provision.md)(entity: [T](index.md))  <br><br><br>
| [checkRequirement](check-requirement.md)| [jvm]  <br>Brief description  <br><br><br>检查必填字段<br><br>  <br>Content  <br>fun [checkRequirement](check-requirement.md)(entity: [T](index.md), operation: [Operation](../../tech.whence.echo.dal.dao/-operation/index.md))  <br><br><br>
| [entitify](entitify.md)| [jvm]  <br>Brief description  <br><br><br>实体化数据<br><br>  <br>Content  <br>fun [entitify](entitify.md)(data: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)): [T](index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [getConstrainedKeys](get-constrained-keys.md)| [jvm]  <br>Brief description  <br><br><br>取指定操作下受约束的字段名集合<br><br>  <br>Content  <br>fun [getConstrainedKeys](get-constrained-keys.md)(operation: [Operation](../../tech.whence.echo.dal.dao/-operation/index.md), constraint: [Constraint](../../tech.whence.echo.dal.schema.key/-constraint/index.md)): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>  <br><br><br>
| [getKey](get-key.md)| [jvm]  <br>Brief description  <br><br><br>根据指定字段名取相应字段<br><br>  <br>Content  <br>fun [getKey](get-key.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Key](../../tech.whence.echo.dal.schema.key/-key/index.md)?  <br><br><br>
| [getKeyIdentity](get-key-identity.md)| [jvm]  <br>Brief description  <br><br><br>取指定字段名的字段身份<br><br>  <br>Content  <br>fun [getKeyIdentity](get-key-identity.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Identity](../../tech.whence.echo.dal.schema.key/-identity/index.md)>  <br><br><br>
| [getKeys](get-keys.md)| [jvm]  <br>Brief description  <br><br><br>获取指定身份的字段集合<br><br>  <br>Content  <br>fun [getKeys](get-keys.md)(vararg identities: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [Identity](../../tech.whence.echo.dal.schema.key/-identity/index.md)>): [Keys](../../tech.whence.echo.dal.schema.key/-keys/index.md)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [isKeyConstrained](is-key-constrained.md)| [jvm]  <br>Brief description  <br><br><br>判断在指定操作下指定字段有没有受到指定限制<br><br>  <br>Content  <br>fun [isKeyConstrained](is-key-constrained.md)(operation: [Operation](../../tech.whence.echo.dal.dao/-operation/index.md), key: [Key](../../tech.whence.echo.dal.schema.key/-key/index.md), constraint: [Constraint](../../tech.whence.echo.dal.schema.key/-constraint/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [loadKeys](load-keys.md)| [jvm]  <br>Brief description  <br><br><br>根据描述器加载字段集合<br><br>  <br>Content  <br>fun [loadKeys](load-keys.md)(describer: [Describer](../-describer/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>加载指定字段集合<br><br>  <br>Content  <br>fun [loadKeys](load-keys.md)(keys: [Keys](../../tech.whence.echo.dal.schema.key/-keys/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [debug](index.md#tech.whence.echo.dal.schema/Schema/debug/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否调试模式<br><br>val [debug](index.md#tech.whence.echo.dal.schema/Schema/debug/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [declarer](index.md#tech.whence.echo.dal.schema/Schema/declarer/#/PointingToDeclaration/)|  [jvm] <br><br>KClass<T> 相关实体类型<br><br>val [declarer](index.md#tech.whence.echo.dal.schema/Schema/declarer/#/PointingToDeclaration/): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[T](index.md)>   <br>
| [instantiable](index.md#tech.whence.echo.dal.schema/Schema/instantiable/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否可实例化<br><br>val [instantiable](index.md#tech.whence.echo.dal.schema/Schema/instantiable/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [keys](index.md#tech.whence.echo.dal.schema/Schema/keys/#/PointingToDeclaration/)|  [jvm] <br><br>Keys 字段集合<br><br>val [keys](index.md#tech.whence.echo.dal.schema/Schema/keys/#/PointingToDeclaration/): [Keys](../../tech.whence.echo.dal.schema.key/-keys/index.md)   <br>
| [name](index.md#tech.whence.echo.dal.schema/Schema/name/#/PointingToDeclaration/)|  [jvm] <br><br>String 名称<br><br>val [name](index.md#tech.whence.echo.dal.schema/Schema/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [primary](index.md#tech.whence.echo.dal.schema/Schema/primary/#/PointingToDeclaration/)|  [jvm] <br><br>PrimaryKey 主键<br><br>val [primary](index.md#tech.whence.echo.dal.schema/Schema/primary/#/PointingToDeclaration/): [PrimaryKey](../../tech.whence.echo.dal.schema.key/-primary-key/index.md)   <br>
| [stable](index.md#tech.whence.echo.dal.schema/Schema/stable/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否已声明<br><br>val [stable](index.md#tech.whence.echo.dal.schema/Schema/stable/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [transactional](index.md#tech.whence.echo.dal.schema/Schema/transactional/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否支持事务<br><br>val [transactional](index.md#tech.whence.echo.dal.schema/Schema/transactional/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>

