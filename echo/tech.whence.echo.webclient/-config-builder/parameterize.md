---
title: parameterize -
---
//[echo](../../index.md)/[tech.whence.echo.webclient](../index.md)/[ConfigBuilder](index.md)/[parameterize](parameterize.md)



# parameterize  
[jvm]  
Brief description  


设置提交数据回调



#### Return  


ConfigBuilder<C, A, R>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| creator| <br><br>Creator<Accessor> 数据创建<br><br>
  
  
Content  
fun [parameterize](parameterize.md)(creator: [Producer](../../tech.whence.echo.function/-producer/index.md)<[Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)>): [ConfigBuilder](index.md)<[C](index.md), [A](index.md), [R](index.md)>  


[jvm]  
Brief description  


设置提交数据



#### Return  


ConfigBuilder<C, A, R>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| parameters| <br><br>Accessor 指定数据<br><br>
  
  
Content  
fun [parameterize](parameterize.md)(parameters: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)): [ConfigBuilder](index.md)<[C](index.md), [A](index.md), [R](index.md)>  


[jvm]  
Brief description  


设置文本形式的提交数据



#### Return  


ConfigBuilder<C, A, R>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| text| <br><br>String 指定文本<br><br>
  
  
Content  
fun [parameterize](parameterize.md)(text: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [ConfigBuilder](index.md)<[C](index.md), [A](index.md), [R](index.md)>  


[jvm]  
Brief description  


设置文件上传形式的提交数据



#### Return  


ConfigBuilder<C, A, R>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| file| <br><br>AsyncFile 指定文件<br><br>
  
  
Content  
fun [parameterize](parameterize.md)(file: AsyncFile): [ConfigBuilder](index.md)<[C](index.md), [A](index.md), [R](index.md)>  


[jvm]  
Brief description  


设置流形式的提交数据



#### Return  


ConfigBuilder<C, A, R>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| stream| <br><br>ReadStream<Buffer> 指定流<br><br>
  
  
Content  
fun [parameterize](parameterize.md)(stream: ReadStream<Buffer>): [ConfigBuilder](index.md)<[C](index.md), [A](index.md), [R](index.md)>  



