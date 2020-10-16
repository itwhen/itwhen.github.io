---
title: DataSource -
---
//[echo](../../index.md)/[tech.whence.echo.support.kafka.sender](../index.md)/[DataSource](index.md)



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
| [acks](index.md#tech.whence.echo.support.kafka.sender/DataSource/acks/#/PointingToDeclaration/)|  [jvm] <br><br>producer需要server接收到数据之后发出的确认接收的信号 此项配置就是指procuder需要多少个这样的确认信号 此配置实际上代表了数据备份的可用性 以下设置为常用选项： （1）acks=0： 设置为0表示producer不需要等待任何确认收到的信息。副本将立即加到socket buffer并认为已经发送。没有任何保障可以保证此种情况下server已经成功接收数据，同时重试配置不会发生作用（因为客户端不知道是否失败）回馈的offset会总是设置为-1； （2）acks=1： 这意味着至少要等待leader已经成功将数据写入本地log，但是并没有等待所有follower是否成功写入。这种情况下，如果follower没有成功备份数据，而此时leader又挂掉，则消息会丢失。 （3）acks=all： 这意味着leader需要等待所有备份都成功写入日志，这种策略会保证只要有一个备份存活就不会丢失数据。这是最强的保证。<br><br>var [acks](index.md#tech.whence.echo.support.kafka.sender/DataSource/acks/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [batchSize](index.md#tech.whence.echo.support.kafka.sender/DataSource/batchSize/#/PointingToDeclaration/)|  [jvm] <br><br>producer将试图批处理消息记录，以减少请求次数 这将改善client与server之间的性能。 这项配置控制默认的批量处理消息字节数。 不会试图处理大于这个字节数的消息字节数。 发送到brokers的请求将包含多个批量处理，其中会包含对每个partition的一个请求。 较小的批量处理数值比较少用，并且可能降低吞吐量（0则会仅用批量处理）。 较大的批量处理数值将会浪费更多内存空间，这样就需要分配特定批量处理数值的内存大小。<br><br>var [batchSize](index.md#tech.whence.echo.support.kafka.sender/DataSource/batchSize/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?   <br>
| [bufferMemory](index.md#tech.whence.echo.support.kafka.sender/DataSource/bufferMemory/#/PointingToDeclaration/)|  [jvm] <br><br>producer可以用来缓存数据的内存大小 如果数据产生速度大于向broker发送的速度，producer会阻塞或者抛出异常，以“block.on.buffer.full”来表明。 这项设置将和producer能够使用的总内存相关，但并不是一个硬性的限制，因为不是producer使用的所有内存都是用于缓存。 一些额外的内存会用于压缩（如果引入压缩机制），同样还有一些用于维护请求。<br><br>var [bufferMemory](index.md#tech.whence.echo.support.kafka.sender/DataSource/bufferMemory/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?   <br>
| [clientId](index.md#tech.whence.echo.support.kafka.sender/DataSource/clientId/#/PointingToDeclaration/)|  [jvm] <br><br>当向server发出请求时 这个字符串会发送给server 目的是能够追踪请求源头，以此来允许ip/port许可列表之外的一些应用可以发送信息 这项应用可以设置任意字符串，因为没有任何功能性的目的，除了记录和跟踪<br><br>override var [clientId](index.md#tech.whence.echo.support.kafka.sender/DataSource/clientId/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [compressionType](index.md#tech.whence.echo.support.kafka.sender/DataSource/compressionType/#/PointingToDeclaration/)|  [jvm] <br><br>producer用于压缩数据的压缩类型。 默认是无压缩。 正确的选项值是none、gzip、snappy。压缩最好用于批量处理，批量处理消息越多，压缩性能越好<br><br>var [compressionType](index.md#tech.whence.echo.support.kafka.sender/DataSource/compressionType/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [connections](index.md#tech.whence.echo.support.kafka.sender/DataSource/connections/#/PointingToDeclaration/)|  [jvm] <br><br>用于建立与kafka集群连接的host/port组 数据将会在所有servers上均衡加载 不管哪些server是指定用于bootstrapping 这个列表仅仅影响初始化的hosts（用于发现全部的servers） 这个列表格式: host1:port1,host2:port2,... 因为这些server仅仅是用于初始化的连接，以发现集群所有成员关系（可能会动态的变化），这个列表不需要包含所有的servers（你可能想要不止一个server，尽管这样，可能某个server宕机了） 如果没有server在这个列表出现，则发送数据会一直失败，直到列表可用。<br><br>override var [connections](index.md#tech.whence.echo.support.kafka.sender/DataSource/connections/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [connectionsMaxIdleMs](index.md#tech.whence.echo.support.kafka.sender/DataSource/connectionsMaxIdleMs/#/PointingToDeclaration/)|  [jvm] <br><br>关闭连接空闲时间<br><br>override var [connectionsMaxIdleMs](index.md#tech.whence.echo.support.kafka.sender/DataSource/connectionsMaxIdleMs/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [lingerMs](index.md#tech.whence.echo.support.kafka.sender/DataSource/lingerMs/#/PointingToDeclaration/)|  [jvm] <br><br>producer组将会汇总任何在请求与发送之间到达的消息记录一个单独批量的请求。 通常来说，这只有在记录产生速度大于发送速度的时候才能发生。 然而，在某些条件下，客户端将希望降低请求的数量，甚至降低到中等负载一下。 这项设置将通过增加小的延迟来完成–即，不是立即发送一条记录，producer将会等待给定的延迟时间以允许其他消息记录发送，这些消息记录可以批量处理。 这可以认为是TCP种Nagle的算法类似。 这项设置设定了批量处理的更高的延迟边界：一旦我们获得某个partition的batch.size，他将会立即发送而不顾这项设置，然而如果我们获得消息字节数比这项设置要小的多，我们需要“linger”特定的时间以获取更多的消息。 设置默认为0，即没有延迟。 设定linger.ms=5，例如，将会减少请求数目，但是同时会增加5ms的延迟。<br><br>var [lingerMs](index.md#tech.whence.echo.support.kafka.sender/DataSource/lingerMs/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?   <br>
| [maxBlockMs](index.md#tech.whence.echo.support.kafka.sender/DataSource/maxBlockMs/#/PointingToDeclaration/)|  [jvm] <br><br>控制block的时长,当buffer空间不够或者metadata丢失时产生block<br><br>var [maxBlockMs](index.md#tech.whence.echo.support.kafka.sender/DataSource/maxBlockMs/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?   <br>
| [maxInFlightRequestsPerConnection](index.md#tech.whence.echo.support.kafka.sender/DataSource/maxInFlightRequestsPerConnection/#/PointingToDeclaration/)|  [jvm] <br><br>kafka可以在一个connection中发送多个请求，叫作一个flight,这样可以减少开销，但是如果产生错误，可能会造成数据的发送顺序改变,默认是5 (修改）<br><br>var [maxInFlightRequestsPerConnection](index.md#tech.whence.echo.support.kafka.sender/DataSource/maxInFlightRequestsPerConnection/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?   <br>
| [maxRequestSize](index.md#tech.whence.echo.support.kafka.sender/DataSource/maxRequestSize/#/PointingToDeclaration/)|  [jvm] <br><br>请求的最大字节数。这也是对最大记录尺寸的有效覆盖。 注意：server具有自己对消息记录尺寸的覆盖，这些尺寸和这个设置不同。 此项设置将会限制producer每次批量发送请求的数目，以防发出巨量的请求。<br><br>var [maxRequestSize](index.md#tech.whence.echo.support.kafka.sender/DataSource/maxRequestSize/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?   <br>
| [metadataMaxAgeMs](index.md#tech.whence.echo.support.kafka.sender/DataSource/metadataMaxAgeMs/#/PointingToDeclaration/)|  [jvm] <br><br>以毫秒为单位的时间，是在我们强制更新metadata的时间间隔。 即使我们没有看到任何partition leadership改变。<br><br>override var [metadataMaxAgeMs](index.md#tech.whence.echo.support.kafka.sender/DataSource/metadataMaxAgeMs/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [receiveBufferBytes](index.md#tech.whence.echo.support.kafka.sender/DataSource/receiveBufferBytes/#/PointingToDeclaration/)|  [jvm] <br><br>TCP的接收缓存 SO_RCVBUF 空间大小 用于读取数据<br><br>override var [receiveBufferBytes](index.md#tech.whence.echo.support.kafka.sender/DataSource/receiveBufferBytes/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?   <br>
| [reconnectBackoffMs](index.md#tech.whence.echo.support.kafka.sender/DataSource/reconnectBackoffMs/#/PointingToDeclaration/)|  [jvm] <br><br>连接失败重新连接时的等待时间<br><br>override var [reconnectBackoffMs](index.md#tech.whence.echo.support.kafka.sender/DataSource/reconnectBackoffMs/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [requestTimeoutMs](index.md#tech.whence.echo.support.kafka.sender/DataSource/requestTimeoutMs/#/PointingToDeclaration/)|  [jvm] <br><br>客户端将等待请求的响应的最大时间,如果在这个时间内没有收到响应，客户端将重发请求;超过重试次数将抛异常<br><br>override var [requestTimeoutMs](index.md#tech.whence.echo.support.kafka.sender/DataSource/requestTimeoutMs/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?   <br>
| [retries](index.md#tech.whence.echo.support.kafka.sender/DataSource/retries/#/PointingToDeclaration/)|  [jvm] <br><br>设置大于0的值将使客户端重新发送任何数据，一旦这些数据发送失败 注意，这些重试与客户端接收到发送错误时的重试没有什么不同 允许重试将潜在的改变数据的顺序，如果这两个消息记录都是发送到同一个partition，则第一个消息失败第二个发送成功，则第二条消息会比第一条消息出现要早。<br><br>var [retries](index.md#tech.whence.echo.support.kafka.sender/DataSource/retries/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?   <br>
| [retryBackoffMs](index.md#tech.whence.echo.support.kafka.sender/DataSource/retryBackoffMs/#/PointingToDeclaration/)|  [jvm] <br><br>在重试发送失败的request前的等待时间 防止若目的Broker完全挂掉的情况下Producer一直陷入死循环发送 折中的方法<br><br>override var [retryBackoffMs](index.md#tech.whence.echo.support.kafka.sender/DataSource/retryBackoffMs/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [sendBufferBytes](index.md#tech.whence.echo.support.kafka.sender/DataSource/sendBufferBytes/#/PointingToDeclaration/)|  [jvm] <br><br>TCP的发送缓存 SO_SNDBUF 空间大小 用于发送数据<br><br>override var [sendBufferBytes](index.md#tech.whence.echo.support.kafka.sender/DataSource/sendBufferBytes/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>

