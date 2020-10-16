---
title: partition -
---
//[echo](../../index.md)/[tech.whence.echo.support.kafka.sender](../index.md)/[LimitablePartitioner](index.md)/[partition](partition.md)



# partition  
[jvm]  
Brief description  


指定分区



#### Return  


Int



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| cluster| <br><br>Cluster 集群<br><br>
| key| <br><br>Any 键<br><br>
| keyBytes| <br><br>ByteArray<br><br>
| pipeline| <br><br>String 管道<br><br>
| value| <br><br>Any 值<br><br>
| valueBytes| <br><br>ByteArray<br><br>
  
  
Content  
open override fun [partition](partition.md)(pipeline: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), key: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, keyBytes: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)?, value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, valueBytes: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)?, cluster: Cluster): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  



