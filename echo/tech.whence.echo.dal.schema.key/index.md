---
title: tech.whence.echo.dal.schema.key -
---
//[echo](../index.md)/[tech.whence.echo.dal.schema.key](index.md)



# Package tech.whence.echo.dal.schema.key  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Constraint](-constraint/index.md)| [jvm]  <br>Brief description  <br><br><br>约束<br><br>  <br>Content  <br>enum [Constraint](-constraint/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Constraint](-constraint/index.md)>   <br><br><br>
| [Existence](-existence/index.md)| [jvm]  <br>Brief description  <br><br><br>存在方式<br><br>  <br>Content  <br>enum [Existence](-existence/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Existence](-existence/index.md)>   <br><br><br>
| [Identity](-identity/index.md)| [jvm]  <br>Brief description  <br><br><br>身份<br><br>  <br>Content  <br>enum [Identity](-identity/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Identity](-identity/index.md)>   <br><br><br>
| [Indexer](-indexer/index.md)| [jvm]  <br>Brief description  <br><br><br>字段排序器<br><br>  <br>Content  <br>fun fun interface [Indexer](-indexer/index.md)  <br><br><br>
| [Key](-key/index.md)| [jvm]  <br>Brief description  <br><br><br>数据表字段<br><br>  <br>Content  <br>class [Key](-key/index.md) : [Codec.Definition](../tech.whence.echo.codec/-codec/-definition/index.md)  <br><br><br>
| [KeyDuplicateException](-key-duplicate-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>字段重复<br><br>  <br>Content  <br>class [KeyDuplicateException](-key-duplicate-exception/index.md)(**key**: [Key](-key/index.md)?, **message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **cause**: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)?) : [DataAccessException](../tech.whence.echo.dal/-data-access-exception/index.md)  <br><br><br>
| [KeyIllformedException](-key-illformed-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>字段名称非法<br><br>  <br>Content  <br>class [KeyIllformedException](-key-illformed-exception/index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [DataAccessException](../tech.whence.echo.dal/-data-access-exception/index.md)  <br><br><br>
| [Keys](-keys/index.md)| [jvm]  <br>Brief description  <br><br><br>数据表字段集合<br><br>  <br>Content  <br>class [Keys](-keys/index.md) : [Container](../tech.whence.echo.container/-container/index.md)  <br><br><br>
| [KeyUnassignedException](-key-unassigned-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>字段未赋值的<br><br>  <br>Content  <br>class [KeyUnassignedException](-key-unassigned-exception/index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [DataAccessException](../tech.whence.echo.dal/-data-access-exception/index.md)  <br><br><br>
| [KeyUnprovidedException](-key-unprovided-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>字段未提供<br><br>  <br>Content  <br>class [KeyUnprovidedException](-key-unprovided-exception/index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [DataAccessException](../tech.whence.echo.dal/-data-access-exception/index.md)  <br><br><br>
| [KeyUnretrievableException](-key-unretrievable-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>字段无法读取<br><br>  <br>Content  <br>class [KeyUnretrievableException](-key-unretrievable-exception/index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [DataAccessException](../tech.whence.echo.dal/-data-access-exception/index.md)  <br><br><br>
| [KeyUnupdatableException](-key-unupdatable-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>字段无法更新<br><br>  <br>Content  <br>class [KeyUnupdatableException](-key-unupdatable-exception/index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [DataAccessException](../tech.whence.echo.dal/-data-access-exception/index.md)  <br><br><br>
| [PrimaryKey](-primary-key/index.md)| [jvm]  <br>Brief description  <br><br><br>主键字段<br><br>  <br>Content  <br>class [PrimaryKey](-primary-key/index.md)  <br><br><br>
| [ValidatedKey](-validated-key/index.md)| [jvm]  <br>Brief description  <br><br><br>已受检字段名<br><br>  <br>Content  <br>data class [ValidatedKey](-validated-key/index.md)(**value**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [CharSequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html)  <br><br><br>
| [Watcher](-watcher/index.md)| [jvm]  <br>Brief description  <br><br><br>字段读写观察<br><br>  <br>Content  <br>interface [Watcher](-watcher/index.md)  <br><br><br>

