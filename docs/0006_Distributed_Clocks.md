# Distributed Clocks

## 参考文档

英文数据手册197页

## 简要说明

* 分布时钟(DC，Distributed Clock) 可以使所有EtherCAT设备使用相同的系统时间，从而控制各设备任务的|百j步执行。从站设备可以根据同步的系统时间产生同步信号，用于中断控制或触发数字最输入输出。
* 分布时钟机制使所有的从站都|百j步于一个参考时钟。主站连接的第一个具有分布时钟功能的从站作为参考时钟，以参考时钟来同步其他设备和主站的从时钟。
* 引脚SYNC0和SYNC1用于指示是否发生了时间事件；