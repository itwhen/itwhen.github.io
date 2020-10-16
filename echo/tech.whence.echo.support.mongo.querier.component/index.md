---
title: tech.whence.echo.support.mongo.querier.component -
---
//[echo](../index.md)/[tech.whence.echo.support.mongo.querier.component](index.md)



# Package tech.whence.echo.support.mongo.querier.component  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Ability](-ability/index.md)| [jvm]  <br>Brief description  <br><br><br>专业能力<br><br>  <br>Content  <br>object [Ability](-ability/index.md)  <br><br><br>
| [Column](-column/index.md)| [jvm]  <br>Brief description  <br><br><br>字段<br><br>  <br>Content  <br>class [Column](-column/index.md) : [AbstractAssignment](../tech.whence.echo.dal.querier.component/-abstract-assignment/index.md)<[Column](-column/index.md)>   <br><br><br>
| [Criteria](-criteria/index.md)| [jvm]  <br>Brief description  <br><br><br>约束<br><br>  <br>Content  <br>interface [Criteria](-criteria/index.md)<[T](-criteria/index.md) : [Criteria](-criteria/index.md)<[T](-criteria/index.md)>> : [Criteria](../tech.whence.echo.dal.querier.component/-criteria/index.md)<[T](-criteria/index.md), [Where](-where/index.md), [Column](-column/index.md), [Criterion](-criterion/index.md)<*>>   <br><br><br>
| [Criterion](-criterion/index.md)| [jvm]  <br>Brief description  <br><br><br>操作<br><br>  <br>Content  <br>abstract class [Criterion](-criterion/index.md)<[T](-criterion/index.md)>(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **value**: [T](-criterion/index.md), **template**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [Criterion](../tech.whence.echo.dal.querier.component/-criterion/index.md)<[T](-criterion/index.md), [Column](-column/index.md), JsonObject>   <br><br><br>
| [Definer](-definer/index.md)| [jvm]  <br>Brief description  <br><br><br>定义器<br><br>  <br>Content  <br>interface [Definer](-definer/index.md)<[T](-definer/index.md) : [Definer](-definer/index.md)<[T](-definer/index.md), [O](-definer/index.md)>, [O](-definer/index.md)> : [Definer](../tech.whence.echo.dal.querier.component/-definer/index.md)<[T](-definer/index.md), [Definition](-definition/index.md)<[O](-definer/index.md)>>   <br><br><br>
| [Definition](-definition/index.md)| [jvm]  <br>Brief description  <br><br><br>定义<br><br>  <br>Content  <br>class [Definition](-definition/index.md)<[O](-definition/index.md)> : [AbstractDefinition](../tech.whence.echo.dal.querier.component/-abstract-definition/index.md)<[Definition](-definition/index.md)<[O](-definition/index.md)>, JsonObject, JsonObject>   <br><br><br>
| [Setter](-setter/index.md)| [jvm]  <br>Brief description  <br><br><br>赋值器<br><br>  <br>Content  <br>interface [Setter](-setter/index.md)<[T](-setter/index.md) : [Setter](-setter/index.md)<[T](-setter/index.md)>> : [Setter](../tech.whence.echo.dal.querier.component/-setter/index.md)<[T](-setter/index.md), [Column](-column/index.md)>   <br><br><br>
| [Where](-where/index.md)| [jvm]  <br>Brief description  <br><br><br>查询条件<br><br>  <br>Content  <br>class [Where](-where/index.md) : [Criteria](-criteria/index.md)<[Where](-where/index.md)> , [Restrictor](../tech.whence.echo.dal.querier.component/-restrictor/index.md)<[Where](-where/index.md), [Where](-where/index.md), [Column](-column/index.md), [Criterion](-criterion/index.md)<*>> , [Container](../tech.whence.echo.container/-container/index.md)  <br><br><br>
| [Writing](-writing/index.md)| [jvm]  <br>Brief description  <br><br><br>写入策略<br><br>  <br>Content  <br>enum [Writing](-writing/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Writing](-writing/index.md)>   <br><br><br>

