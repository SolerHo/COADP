# 第一章 导论

## 知识框架
![](https://github.com/SolerHo/COADP/blob/master/Chapter01/Images/%E7%AC%AC%E4%B8%80%E7%AB%A0%20%E5%AF%BC%E8%AE%BA.png)

## 中英文词
arithmetic and logic unit（ALU）：算术逻辑单元

control processing unit（CPU）：中央处理单元，中央处理器

computer architecture：计算机体系结构，计算机系统结构

computer organization：计算机组成，计算机组织

control unit：控制器，控制单元

input-output：输入/输出

main memory：主存

processor：处理器

register：寄存器

system bus：系统总线


### 1. 计算机组成与体系结构
- **计算机体系结构**：就是程序员可见的系统属性，而且这些属性会对程序的逻辑执行造成最直接的影响。
- **计算机组成**：实现结构规范的操作单元及其相互连接。


### 2.功能和组成

#### 功能
![](https://github.com/SolerHo/COADP/blob/master/Chapter01/Images/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%9A%84%E5%8A%9F%E8%83%BD.png)

- 数据处理
- 数据存储
- 数据传送
    - **输入输出（I/O）**：当数据从直接与计算机相连的设备发送或接收时，这叫输入输出（I/O）过程，设备叫做外部设备。
    - **数据通信**：数据的传输和接收从远处设备开始，此时叫数据通信。
- 控制

#### 结构
计算机是以某种方式与其外部环境交互的实体。

根据与外部环境的连接方式分为：**外围设备**和**通信线路**。

### 计算机的顶层结构
![](https://github.com/SolerHo/COADP/blob/master/Chapter01/Images/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%9A%84%E9%A1%B6%E5%B1%82%E7%BB%93%E6%9E%84.png)

计算机本身的四个主要内部组件：
#### 中央处理单元（CPU）
`控制`计算机的`操作`且`执行数据处理`的功能，也就是经常说的**处理器**。**处理器是唯一的**。

- 控制单元
控制CPU甚至是整个计算机的操作。

- 算术逻辑单元（ALU）
执行计算机的数据处理功能

- 寄存器
提供CPU的内部存储
- CPU内部互连
提供控制器、ALU和寄存器之间的某种通信机制。



#### 主存存储
存储数据
#### I/O
在计算机及其外部环境之间传输数据。
#### 系统互连
为CPU、主存储器和I/O之间提供一些通信机制。

