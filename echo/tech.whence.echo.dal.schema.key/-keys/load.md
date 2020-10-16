---
title: load -
---
//[echo](../../index.md)/[tech.whence.echo.dal.schema.key](../index.md)/[Keys](index.md)/[load](load.md)



# load  
[jvm]  
Brief description  


加载字段 若已经加载则忽略之 将检查指定字段集合与当前集合是否一个实体 将检查指定字段集合中的字段是否与当前集合里一致 检查通过后将覆盖当前集合数据 将待检字段置为虚拟字段 并设置为已经加载



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| keys| <br><br>Keys 字段集合<br><br>
  
  
Content  
fun [load](load.md)(keys: [Keys](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  



