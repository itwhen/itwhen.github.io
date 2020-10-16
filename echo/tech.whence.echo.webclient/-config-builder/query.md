---
title: query -
---
//[echo](../../index.md)/[tech.whence.echo.webclient](../index.md)/[ConfigBuilder](index.md)/[query](query.md)



# query  
[jvm]  
Brief description  


根据回调设置查询数据



#### Return  


ConfigBuilder<C, A, R>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| creator| <br><br>Creator<Accessor> 数据创建<br><br>
  
  
Content  
fun [query](query.md)(creator: [Producer](../../tech.whence.echo.function/-producer/index.md)<[Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)>): [ConfigBuilder](index.md)<[C](index.md), [A](index.md), [R](index.md)>  


[jvm]  
Brief description  


设置查询数据



#### Return  


ConfigBuilder<C, A, R>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>Accessor 指定数据<br><br>
  
  
Content  
fun [query](query.md)(data: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)): [ConfigBuilder](index.md)<[C](index.md), [A](index.md), [R](index.md)>  



