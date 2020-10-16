---
title: ClientSupplier -
---
//[echo](../../index.md)/[tech.whence.echo.support.kafka.stream](../index.md)/[ClientSupplier](index.md)



# ClientSupplier  
 [jvm] 

客户端提供者

class [ClientSupplier](index.md) : KafkaClientSupplier   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [ClientSupplier](-client-supplier.md)|  [jvm] fun [ClientSupplier](-client-supplier.md)()   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [getAdmin](get-admin.md)| [jvm]  <br>Brief description  <br><br><br>创建管理者<br><br>  <br>Content  <br>open override fun [getAdmin](get-admin.md)(config: [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>?): Admin  <br><br><br>
| [getAdminClient](index.md#org.apache.kafka.streams/KafkaClientSupplier/getAdminClient/#kotlin.collections.MutableMap[kotlin.String,kotlin.Any]/PointingToDeclaration/)| [jvm]  <br>Content  <br>~~open~~ ~~override~~ ~~fun~~ [~~getAdminClient~~](index.md#org.apache.kafka.streams/KafkaClientSupplier/getAdminClient/#kotlin.collections.MutableMap[kotlin.String,kotlin.Any]/PointingToDeclaration/)~~(~~~~p0~~~~:~~ [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>~~)~~~~:~~ AdminClient  <br><br><br>
| [getConsumer](get-consumer.md)| [jvm]  <br>Brief description  <br><br><br>创建消费者<br><br>  <br>Content  <br>open override fun [getConsumer](get-consumer.md)(config: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>?): Consumer<[ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html), [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)>  <br><br><br>
| [getGlobalConsumer](get-global-consumer.md)| [jvm]  <br>Brief description  <br><br><br>创建全局表(GlobalKTable)消费者<br><br>  <br>Content  <br>open override fun [getGlobalConsumer](get-global-consumer.md)(config: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>?): Consumer<[ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html), [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)>  <br><br><br>
| [getProducer](get-producer.md)| [jvm]  <br>Brief description  <br><br><br>创建生产者<br><br>  <br>Content  <br>open override fun [getProducer](get-producer.md)(config: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>?): Producer<[ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html), [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)>  <br><br><br>
| [getRestoreConsumer](get-restore-consumer.md)| [jvm]  <br>Brief description  <br><br><br>创建状态存储器(StateStore)消费者<br><br>  <br>Content  <br>open override fun [getRestoreConsumer](get-restore-consumer.md)(config: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>?): Consumer<[ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html), [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)>  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

