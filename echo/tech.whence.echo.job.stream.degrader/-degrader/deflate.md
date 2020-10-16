---
title: deflate -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.degrader](../index.md)/[Degrader](index.md)/[deflate](deflate.md)



# deflate  
[jvm]  
Brief description  


收缩 若不收缩则全部通过 若全部收缩则只允许一个通过 否则允许请求量扣除收缩比率的部分



#### Return  


Int 可通行量



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| value| <br><br>Int 当前请求量<br><br>
  
  
Content  
fun [deflate](deflate.md)(value: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  



