---
title: assign -
---
//[echo](../../index.md)/[tech.whence.echo.support.jdbc.querier.component](../index.md)/[Definition](index.md)/[assign](assign.md)



# assign  
[jvm]  
Brief description  


将指定字段转换为赋值条件



#### Return  


Definition



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| columns| <br><br>List<SortedSet<Column>>) 指定字段<br><br>
  
  
Content  
fun [assign](assign.md)(columns: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[LinkedHashSet](https://docs.oracle.com/javase/8/docs/api/java/util/LinkedHashSet.html)<[Column](../-column/index.md)>>): [Definition](index.md)  


[jvm]  
Brief description  


将指定字段转换为赋值条件



#### Return  


Definition



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| columns| <br><br>SortedSet<Column> 指定字段<br><br>
  
  
Content  
fun [assign](assign.md)(columns: [LinkedHashSet](https://docs.oracle.com/javase/8/docs/api/java/util/LinkedHashSet.html)<[Column](../-column/index.md)>): [Definition](index.md)  


[jvm]  
Brief description  


将指定字段转换为赋值条件



#### Return  


Definition



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| creator| <br><br>Creator<List<SortedSet<Column>>> 指定字段提供<br><br>
  
  
Content  
fun [assign](assign.md)(creator: [Producer](../../tech.whence.echo.function/-producer/index.md)<[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[LinkedHashSet](https://docs.oracle.com/javase/8/docs/api/java/util/LinkedHashSet.html)<[Column](../-column/index.md)>>>): [Definition](index.md)  



