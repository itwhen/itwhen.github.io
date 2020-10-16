---
title: tech.whence.echo.dal.connection -
---
//[echo](../index.md)/[tech.whence.echo.dal.connection](index.md)



# Package tech.whence.echo.dal.connection  


## Types  
  
|  Name|  Summary| 
|---|---|
| [ConnectionEndpoint](-connection-endpoint/index.md)| [jvm]  <br>Brief description  <br><br><br>数据库连接端点<br><br>  <br>Content  <br>enum [ConnectionEndpoint](-connection-endpoint/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[ConnectionEndpoint](-connection-endpoint/index.md)>   <br><br><br>
| [ConnectionFailedException](-connection-failed-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>数据库连接失败<br><br>  <br>Content  <br>class [ConnectionFailedException](-connection-failed-exception/index.md)(**message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [DataAccessException](../tech.whence.echo.dal/-data-access-exception/index.md)  <br><br><br>
| [ConnectionGoneException](-connection-gone-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>数据库连接丢失<br><br>  <br>Content  <br>class [ConnectionGoneException](-connection-gone-exception/index.md) : [DataAccessException](../tech.whence.echo.dal/-data-access-exception/index.md)  <br><br><br>
| [ConnectionInvoker](-connection-invoker/index.md)| [jvm]  <br>Brief description  <br><br><br>数据库连接调用器<br><br>  <br>Content  <br>interface [ConnectionInvoker](-connection-invoker/index.md)<[C](-connection-invoker/index.md), [D](-connection-invoker/index.md)>  <br><br><br>
| [ConnectionString](-connection-string/index.md)| [jvm]  <br>Brief description  <br><br><br>数据库连接字符串<br><br>  <br>Content  <br>data class [ConnectionString](-connection-string/index.md)(**driver**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **username**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **password**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **host**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **port**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, **database**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **parameters**: [Accessor](../tech.whence.echo.container.accessor/-accessor/index.md))  <br><br><br>
| [ConnectionStrings](-connection-strings/index.md)| [jvm]  <br>Brief description  <br><br><br>数据库连接字符串<br><br>  <br>Content  <br>data class [ConnectionStrings](-connection-strings/index.md)(**data**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[ConnectionString](-connection-string/index.md)>, **parameters**: [Accessor](../tech.whence.echo.container.accessor/-accessor/index.md))  <br><br><br>
| [ConnectionUnprovidedException](-connection-unprovided-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>数据库连接未提供<br><br>  <br>Content  <br>class [ConnectionUnprovidedException](-connection-unprovided-exception/index.md) : [DataAccessException](../tech.whence.echo.dal/-data-access-exception/index.md)  <br><br><br>

