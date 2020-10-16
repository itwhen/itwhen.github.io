---
title: DataSource -
---
//[echo](../../index.md)/[tech.whence.echo.support.kafka.stream](../index.md)/[DataSource](index.md)



# DataSource  
 [jvm] 

数据源

class [DataSource](index.md) : [AbstractDataSource](../../tech.whence.echo.support.kafka/-abstract-data-source/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [DataSource](-data-source.md)|  [jvm] fun [DataSource](-data-source.md)()   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [clientId](index.md#tech.whence.echo.support.kafka.stream/DataSource/clientId/#/PointingToDeclaration/)|  [jvm] <br><br>当向server发出请求时 这个字符串会发送给server 目的是能够追踪请求源头，以此来允许ip/port许可列表之外的一些应用可以发送信息 这项应用可以设置任意字符串，因为没有任何功能性的目的，除了记录和跟踪<br><br>override var [clientId](index.md#tech.whence.echo.support.kafka.stream/DataSource/clientId/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [connections](index.md#tech.whence.echo.support.kafka.stream/DataSource/connections/#/PointingToDeclaration/)|  [jvm] <br><br>用于建立与kafka集群连接的host/port组 数据将会在所有servers上均衡加载 不管哪些server是指定用于bootstrapping 这个列表仅仅影响初始化的hosts（用于发现全部的servers） 这个列表格式: host1:port1,host2:port2,... 因为这些server仅仅是用于初始化的连接，以发现集群所有成员关系（可能会动态的变化），这个列表不需要包含所有的servers（你可能想要不止一个server，尽管这样，可能某个server宕机了） 如果没有server在这个列表出现，则发送数据会一直失败，直到列表可用。<br><br>override var [connections](index.md#tech.whence.echo.support.kafka.stream/DataSource/connections/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [connectionsMaxIdleMs](index.md#tech.whence.echo.support.kafka.stream/DataSource/connectionsMaxIdleMs/#/PointingToDeclaration/)|  [jvm] <br><br>关闭连接空闲时间<br><br>override var [connectionsMaxIdleMs](index.md#tech.whence.echo.support.kafka.stream/DataSource/connectionsMaxIdleMs/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [metadataMaxAgeMs](index.md#tech.whence.echo.support.kafka.stream/DataSource/metadataMaxAgeMs/#/PointingToDeclaration/)|  [jvm] <br><br>以毫秒为单位的时间，是在我们强制更新metadata的时间间隔。 即使我们没有看到任何partition leadership改变。<br><br>override var [metadataMaxAgeMs](index.md#tech.whence.echo.support.kafka.stream/DataSource/metadataMaxAgeMs/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [receiveBufferBytes](index.md#tech.whence.echo.support.kafka.stream/DataSource/receiveBufferBytes/#/PointingToDeclaration/)|  [jvm] <br><br>TCP的接收缓存 SO_RCVBUF 空间大小 用于读取数据<br><br>override var [receiveBufferBytes](index.md#tech.whence.echo.support.kafka.stream/DataSource/receiveBufferBytes/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?   <br>
| [reconnectBackoffMs](index.md#tech.whence.echo.support.kafka.stream/DataSource/reconnectBackoffMs/#/PointingToDeclaration/)|  [jvm] <br><br>连接失败重新连接时的等待时间<br><br>override var [reconnectBackoffMs](index.md#tech.whence.echo.support.kafka.stream/DataSource/reconnectBackoffMs/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [requestTimeoutMs](index.md#tech.whence.echo.support.kafka.stream/DataSource/requestTimeoutMs/#/PointingToDeclaration/)|  [jvm] <br><br>客户端将等待请求的响应的最大时间,如果在这个时间内没有收到响应，客户端将重发请求;超过重试次数将抛异常<br><br>override var [requestTimeoutMs](index.md#tech.whence.echo.support.kafka.stream/DataSource/requestTimeoutMs/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?   <br>
| [retryBackoffMs](index.md#tech.whence.echo.support.kafka.stream/DataSource/retryBackoffMs/#/PointingToDeclaration/)|  [jvm] <br><br>在重试发送失败的request前的等待时间 防止若目的Broker完全挂掉的情况下Producer一直陷入死循环发送 折中的方法<br><br>override var [retryBackoffMs](index.md#tech.whence.echo.support.kafka.stream/DataSource/retryBackoffMs/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [sendBufferBytes](index.md#tech.whence.echo.support.kafka.stream/DataSource/sendBufferBytes/#/PointingToDeclaration/)|  [jvm] <br><br>TCP的发送缓存 SO_SNDBUF 空间大小 用于发送数据<br><br>override var [sendBufferBytes](index.md#tech.whence.echo.support.kafka.stream/DataSource/sendBufferBytes/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>

