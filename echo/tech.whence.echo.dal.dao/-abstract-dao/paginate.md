---
title: paginate -
---
//[echo](../../index.md)/[tech.whence.echo.dal.dao](../index.md)/[AbstractDao](index.md)/[paginate](paginate.md)



# paginate  
[jvm]  
Brief description  


分页查找



#### Return  


Paginator<E>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| retriever| <br><br>QR 查询器<br><br>
  
  
Content  
open suspend override fun [paginate](paginate.md)(retriever: [QR](index.md)): [Paginator](../../tech.whence.echo.container/-paginator/index.md)<[E](index.md)>  


[jvm]  
Brief description  


分页查找



#### Return  


Paginator<E>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| criteria| <br><br>Criteria 查询条件<br><br>
  
  
Content  
open suspend override fun [paginate](paginate.md)(criteria: [Criteria](../../tech.whence.echo.dal.filter/-criteria/index.md)): [Paginator](../../tech.whence.echo.container/-paginator/index.md)<[E](index.md)>  



