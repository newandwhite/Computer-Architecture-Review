# 12 计算机性能分析
### 计算机系统性能评价指标
* 不同系统关注的性能，影响性能的因素，性能最本质的定义
* 名词解释：CPI（每条指令的时钟周期数）、MIPS（每秒执行百万条指令数）、MFLOPS（每秒执行百万浮点运算数）、TPS（每秒执行事务数）、FPS（每秒帧数）、MBPS（指每秒传输的位（比特）数量）、MHz（兆赫）
* 并行系统的评价指标:加速比（同一个任务在单处理器系统和并行处理器系统中运行所耗费时间的比率），Amdahl定律

### 性能测试程序集
* 常见的基准测试程序：Coremark，LMBench，Stream；SPEC CPU，EEMBC；Splash2，PARSEC，NPB，Linpack；SPECjvm，SPECjbb，Octane...

### 计算机性能分析方法
* 理论建模、模拟器、性能测量(性能计数器)
* 常见模拟器：SimOS、Simplescalar、GEM5...
* 性能分析工具: perf、Oprofile

### 性能分析和测试实例