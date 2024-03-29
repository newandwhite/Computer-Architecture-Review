# 09章 指令流水线
### 五级流水线时空图
* 通过指令调度避免流水线阻塞（循环展开等）

### 动态流水线按节拍执行过程
* 通过保留站把有序变成乱序以提高性能
* 通过ROB把乱序变成有序以保证正确

### 转移猜测原理及1位和2位BHT表的猜测准确性
* ```
for (i=0;i<10000;i++) 
    if (i%2) {...} else {...}
```

### 高速缓存结构
* 不同容量、结构、块大小的offset、index、tag位置
* 替换算法、写命中和写不命中算法的重要概念
    * 替换算法：随机替换、LRU、FIFO
    * 块索引方式：直接相联、全相连、组相联
    * 写策略：写穿透、写回
* AMAT计算公式
    * AMAT = HitTime + MissRate × Penalty
    （无论是否命中，HitTime都要计入）
    > 下级AMAT都理解为Penalty