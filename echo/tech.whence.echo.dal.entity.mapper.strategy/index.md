---
title: tech.whence.echo.dal.entity.mapper.strategy -
---
//[echo](../index.md)/[tech.whence.echo.dal.entity.mapper.strategy](index.md)



# Package tech.whence.echo.dal.entity.mapper.strategy  


## Types  
  
|  Name|  Summary| 
|---|---|
| [BatchSettlingStrategy](-batch-settling-strategy/index.md)| [jvm]  <br>Brief description  <br><br><br>批量结算策略<br><br>  <br>Content  <br>abstract class [BatchSettlingStrategy](-batch-settling-strategy/index.md)<[E](-batch-settling-strategy/index.md) : [Entity](../tech.whence.echo.dal.entity/-entity/index.md), [K](-batch-settling-strategy/index.md), [V](-batch-settling-strategy/index.md)> : [SettlingStrategy](-settling-strategy/index.md)<[E](-batch-settling-strategy/index.md)>   <br><br><br>
| [ConverterStrategy](-converter-strategy/index.md)| [jvm]  <br>Brief description  <br><br><br>值转换策略<br><br>  <br>Content  <br>fun fun interface [ConverterStrategy](-converter-strategy/index.md) : [Strategy](../tech.whence.echo.strategy/-strategy/index.md)  <br><br><br>
| [FilterStrategy](-filter-strategy/index.md)| [jvm]  <br>Brief description  <br><br><br>过滤策略<br><br>  <br>Content  <br>fun fun interface [FilterStrategy](-filter-strategy/index.md) : [Strategy](../tech.whence.echo.strategy/-strategy/index.md)  <br><br><br>
| [KeyFilterStrategy](-key-filter-strategy/index.md)| [jvm]  <br>Brief description  <br><br><br>字段过滤策略<br><br>  <br>Content  <br>class [KeyFilterStrategy](-key-filter-strategy/index.md)(**remain**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **creator**: [Producer](../tech.whence.echo.function/-producer/index.md)<[Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>>) : [FilterStrategy](-filter-strategy/index.md)  <br><br><br>
| [SettlingStrategy](-settling-strategy/index.md)| [jvm]  <br>Brief description  <br><br><br>批量结算策略<br><br>  <br>Content  <br>fun fun interface [SettlingStrategy](-settling-strategy/index.md)<[E](-settling-strategy/index.md) : [Entity](../tech.whence.echo.dal.entity/-entity/index.md)> : [Strategy](../tech.whence.echo.strategy/-strategy/index.md)  <br><br><br>
| [SkipNullsFilterStrategy](-skip-nulls-filter-strategy/index.md)| [jvm]  <br>Brief description  <br><br><br>空值过滤器<br><br>  <br>Content  <br>class [SkipNullsFilterStrategy](-skip-nulls-filter-strategy/index.md) : [FilterStrategy](-filter-strategy/index.md)  <br><br><br>

