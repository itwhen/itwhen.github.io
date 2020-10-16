---
title: disassemble -
---
//[echo](../../index.md)/[tech.whence.echo.support.jdbc.driver.general](../index.md)/[JdbcEntityAssembler](index.md)/[disassemble](disassemble.md)



# disassemble  
[jvm]  
Brief description  




解码指定数据到实体 将指定数据F解码为指定实体 仅处理指定字段keys 默认为指定实体类型中所有字段



先将数据中相应字段提取[extract](extract.md)出其值 再反编译decompile每个字段的值 再将所有字段及值设置到指定实体内





#### Return  


E



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>F 指定数据<br><br>
| declarer| <br><br>KClass<E> 指定实体类型<br><br>
| keys| <br><br>Keys 指定实体字段集合<br><br>
  
  
Content  
open override fun <[E](disassemble.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [disassemble](disassemble.md)(data: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md), declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[E](disassemble.md)>, keys: [Keys](../../tech.whence.echo.dal.schema.key/-keys/index.md)): [E](disassemble.md)  



