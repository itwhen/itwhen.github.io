---
title: send -
---
//[echo](../../index.md)/[tech.whence.echo.support.kafka.sender](../index.md)/[Sender](index.md)/[send](send.md)



# send  
[jvm]  
Brief description  


发送



#### Return  


Reply<R>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| key| <br><br>String 键<br><br>
| partition| <br><br>Int? 分区<br><br>
| topic| <br><br>String 主题<br><br>
| value| <br><br>Accessor 值<br><br>
  
  
Content  
open suspend override fun [send](send.md)(topic: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), partition: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)): [Reply](../../tech.whence.echo.container/-reply/index.md)<[Result](../-result/index.md)>  



