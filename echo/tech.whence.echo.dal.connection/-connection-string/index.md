---
title: ConnectionString -
---
//[echo](../../index.md)/[tech.whence.echo.dal.connection](../index.md)/[ConnectionString](index.md)



# ConnectionString  
 [jvm] 

数据库连接字符串

data class [ConnectionString](index.md)(**driver**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **username**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **password**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **host**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **port**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, **database**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **parameters**: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md))   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [ConnectionString](-connection-string.md)|  [jvm] <br><br><br><br>fun [ConnectionString](-connection-string.md)(driver: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), username: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), password: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), host: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), port: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, database: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), parameters: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md))   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [component1](component1.md)| [jvm]  <br>Content  <br>operator fun [component1](component1.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [component2](component2.md)| [jvm]  <br>Content  <br>operator fun [component2](component2.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [component3](component3.md)| [jvm]  <br>Content  <br>operator fun [component3](component3.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [component4](component4.md)| [jvm]  <br>Content  <br>operator fun [component4](component4.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [component5](component5.md)| [jvm]  <br>Content  <br>operator fun [component5](component5.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?  <br><br><br>
| [component6](component6.md)| [jvm]  <br>Content  <br>operator fun [component6](component6.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [component7](component7.md)| [jvm]  <br>Content  <br>operator fun [component7](component7.md)(): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)  <br><br><br>
| [copy](copy.md)| [jvm]  <br>Content  <br>fun [copy](copy.md)(driver: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), username: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), password: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), host: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), port: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, database: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), parameters: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)): [ConnectionString](index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [format](format.md)| [jvm]  <br>Brief description  <br><br><br>格式化<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [format](format.md)(driver: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), parametrize: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](to-string.md)| [jvm]  <br>Content  <br>open override fun [toString](to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [database](index.md#tech.whence.echo.dal.connection/ConnectionString/database/#/PointingToDeclaration/)|  [jvm] <br><br>String? 数据库<br><br>val [database](index.md#tech.whence.echo.dal.connection/ConnectionString/database/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [driver](index.md#tech.whence.echo.dal.connection/ConnectionString/driver/#/PointingToDeclaration/)|  [jvm] <br><br>String 驱动<br><br>val [driver](index.md#tech.whence.echo.dal.connection/ConnectionString/driver/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [host](index.md#tech.whence.echo.dal.connection/ConnectionString/host/#/PointingToDeclaration/)|  [jvm] <br><br>String? 主机<br><br>val [host](index.md#tech.whence.echo.dal.connection/ConnectionString/host/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [parameters](index.md#tech.whence.echo.dal.connection/ConnectionString/parameters/#/PointingToDeclaration/)|  [jvm] <br><br>Accessor 其他参数<br><br>val [parameters](index.md#tech.whence.echo.dal.connection/ConnectionString/parameters/#/PointingToDeclaration/): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)   <br>
| [password](index.md#tech.whence.echo.dal.connection/ConnectionString/password/#/PointingToDeclaration/)|  [jvm] <br><br>String? 密码<br><br>val [password](index.md#tech.whence.echo.dal.connection/ConnectionString/password/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [port](index.md#tech.whence.echo.dal.connection/ConnectionString/port/#/PointingToDeclaration/)|  [jvm] <br><br>Int? 端口<br><br>val [port](index.md#tech.whence.echo.dal.connection/ConnectionString/port/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?   <br>
| [username](index.md#tech.whence.echo.dal.connection/ConnectionString/username/#/PointingToDeclaration/)|  [jvm] <br><br>String? 用户<br><br>val [username](index.md#tech.whence.echo.dal.connection/ConnectionString/username/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>

