---
title: tech.whence.echo.dal.entity.mapper -
---
//[echo](../index.md)/[tech.whence.echo.dal.entity.mapper](index.md)



# Package tech.whence.echo.dal.entity.mapper  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Batcher](-batcher/index.md)| [jvm]  <br>Brief description  <br><br><br>实体批量转换器 缓存实体及其数据做中间用途<br><br>  <br>Content  <br>class [Batcher](-batcher/index.md)<[E](-batcher/index.md) : [Entity](../tech.whence.echo.dal.entity/-entity/index.md)>(**entities**: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[E](-batcher/index.md)>, **strategist**: [Strategist](../tech.whence.echo.strategy/-strategist/index.md))  <br><br><br>
| [Mapper](-mapper/index.md)| [jvm]  <br>Brief description  <br><br><br>实体转换接口<br><br>  <br>Content  <br>interface [Mapper](-mapper/index.md)<[E](-mapper/index.md) : [Entity](../tech.whence.echo.dal.entity/-entity/index.md), [T](-mapper/index.md)>  <br><br><br>
| [Serialization](-serialization/index.md)| [jvm]  <br>Brief description  <br><br><br>序列化格式<br><br>  <br>Content  <br>enum [Serialization](-serialization/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Serialization](-serialization/index.md)>   <br><br><br>
| [Stratagem](-stratagem/index.md)| [jvm]  <br>Brief description  <br><br><br>策略特征<br><br>  <br>Content  <br>interface [Stratagem](-stratagem/index.md)<[D](-stratagem/index.md) : [Dao](../tech.whence.echo.dal.dao/-dao/index.md)<*, *, *>>  <br><br><br>

