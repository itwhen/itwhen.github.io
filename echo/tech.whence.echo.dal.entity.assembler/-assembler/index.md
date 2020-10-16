---
title: Assembler -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity.assembler](../index.md)/[Assembler](index.md)



# Assembler  
 [jvm] 

实体组装器 用于各种数据与实体数据的转换 将外部数据视作黑箱数据 将外部数据转到实体数据成为解码 将实体数据转到外部数据成为编码

interface [Assembler](index.md)<[F](index.md), [T](index.md), [I](index.md)>   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| F| <br><br>当前待组装类型<br><br>
| I| <br><br>当前实体字段及其值待转换类型<br><br>
| T| <br><br>当前待分拆类型<br><br>
  


## Functions  
  
|  Name|  Summary| 
|---|---|
| [access](access.md)| [jvm]  <br>Brief description  <br><br><br>将指定数据组装成数据访问器 仅处理数据中指定的字段keys<br><br>  <br>Content  <br>abstract fun [access](access.md)(data: [F](index.md), keys: [Keys](../../tech.whence.echo.dal.schema.key/-keys/index.md)): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)  <br><br><br>
| [assemble](assemble.md)| [jvm]  <br>Brief description  <br><br><br>编码实体到目标数据 先找到需要分拆的字段 再将每个字段及其值编译[compile](compile.md) 再将每个字段数据封装[pack](pack.md)成目标数据可用类型 再整体编码为目标数据<br><br>  <br>Content  <br>abstract fun <[E](assemble.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [assemble](assemble.md)(entity: [E](assemble.md), strategist: [Strategist](../../tech.whence.echo.strategy/-strategist/index.md)): [T](index.md)?  <br><br><br>
| [capably](capably.md)| [jvm]  <br>Brief description  <br><br><br>扩展能力 增加指定解编器给当前组装器 扩展其转换更多类型数据的能力<br><br>  <br>Content  <br>abstract fun [capably](capably.md)(codecs: [Codecs](../../tech.whence.echo.codec/-codecs/index.md))  <br><br><br>
| [compile](compile.md)| [jvm]  <br>Brief description  <br><br><br>编译指定键值<br><br>  <br>Content  <br>open fun [compile](compile.md)(key: [Key](../../tech.whence.echo.dal.schema.key/-key/index.md), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?  <br><br><br>
| [decompile](decompile.md)| [jvm]  <br>Brief description  <br><br><br>反编译指定字段<br><br>  <br>Content  <br>abstract fun [decompile](decompile.md)(key: [Key](../../tech.whence.echo.dal.schema.key/-key/index.md), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?  <br><br><br>
| [disassemble](disassemble.md)| [jvm]  <br>Brief description  <br><br><br><br><br>解码指定数据到实体 将指定数据[F](index.md)解码为指定实体 仅处理指定字段keys 默认为指定实体类型中所有字段<br><br><br><br>先将数据中相应字段提取[extract](extract.md)出其值 再反编译[decompile](decompile.md)每个字段的值 再将所有字段及值设置到指定实体内<br><br><br><br>  <br>Content  <br>abstract fun <[E](disassemble.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [disassemble](disassemble.md)(data: [F](index.md), declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[E](disassemble.md)>, keys: [Keys](../../tech.whence.echo.dal.schema.key/-keys/index.md)): [E](disassemble.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [extract](extract.md)| [jvm]  <br>Brief description  <br><br><br>提取指定数据字段<br><br>  <br>Content  <br>abstract fun [extract](extract.md)(data: [F](index.md), key: [Key](../../tech.whence.echo.dal.schema.key/-key/index.md)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [pack](pack.md)| [jvm]  <br>Brief description  <br><br><br>封装实体指定字段数据供整体分拆使用<br><br>  <br>Content  <br>abstract fun [pack](pack.md)(key: [Key](../../tech.whence.echo.dal.schema.key/-key/index.md), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [I](index.md)?  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [wrap](wrap.md)| [jvm]  <br>Brief description  <br><br><br>打包实体 代理指定实体来扩展更多的数据存储能力<br><br>  <br>Content  <br>abstract fun <[E](wrap.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [wrap](wrap.md)(entity: [E](wrap.md)): [E](wrap.md)  <br><br><br>


## Inheritors  
  
|  Name| 
|---|
| [AbstractAssembler](../-abstract-assembler/index.md)

