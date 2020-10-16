---
title: AbstractBuilder -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.work](../index.md)/[AbstractBuilder](index.md)/[AbstractBuilder](-abstract-builder.md)



# AbstractBuilder  
[jvm]  
Brief description  


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| A| <br><br>: Builder<A, W, S, B> 子类<br><br>
| B| <br><br>: AbstractWorkstageBuilder<B, *> 工作阶段构造器类型<br><br>
| S| <br><br>: AbstractWorkstage 工作阶段类型<br><br>
| W| <br><br>: AbstractWork<S, B, *> 工作类型<br><br>
  
  
Content  
fun <[W](index.md) : [AbstractWork](../-abstract-work/index.md)<[S](index.md), [B](index.md), *>> [AbstractBuilder](-abstract-builder.md)(vertx: Vertx, work: [W](index.md))  



