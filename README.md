# MIPS CPU 单周期与多周期微程序设计资源指南

本指南提供了一套全面的计算机组成原理实验资源，专为学习 MIPS 架构 CPU 设计的同学准备。本资源包覆盖了华中科技大学计算机组成原理实验的关键内容，旨在通过实践加深对单周期 CPU、多周期 CPU 和微程序控制的理解。

## 资源概述

- **单周期 CPU（8 条指令）**：提供了基础的单周期 CPU 设计，支持 8 种基本 MIPS 指令，所有逻辑集成在一个 .circ 文件中，便于学习和调试。

- **多周期 CPU 与微程序地址转移**：扩展到 24 条指令，采用多周期执行模型，并引入微程序控制技术。这部分包括：

  - 详细的 .circ 文件，展示如何在多个时钟周期内完成指令执行。

  - 控制信号表 Excel 文件，清晰罗列出每条指令对应的控制信号，帮助理解控制路径的设计原则。

  - 微程序地址转移的 Excel 表格，解释微指令如何引导程序流程。

## 辅助材料

- **.jar 工具**：用于辅助电路仿真和分析的 Java 应用 jar 包，确保你能顺利进行 CPU 模拟。

  - **课程设计文档**：包含完整的设计报告，指导从理论到实现的全过程。文档不仅解析了设计思路，还提供了实验步骤、结果分析和可能遇到的问题及其解决方法。

## 使用指南

1. **环境准备**：确保你的电脑上安装有合适的电路仿真软件来打开 .circ 文件，如 Logisim 或其他兼容工具。

2. **阅读文档**：首先，仔细阅读课程设计文档，了解整体设计框架和具体实施步骤。

3. **操作实践**：使用提供的 .circ 文件在仿真软件中搭建 CPU 模型，并利用 Excel 表作为参考，理解并调整控制信号。

4. **微程序理解**：深入研究多周期 CPU 的微程序设计部分，尤其是地址转移策略，通过 Excel 表进行学习。

5. **实验验证**：编写测试代码或使用已提供的示例，验证 CPU设计的正确性。

## 注意事项

- 在使用 .jar 文件时，请确保 Java 环境已正确配置。

- 对于 .circ 文件中的任何修改，建议先备份原文件以防意外丢失重要数据。

- 学习过程中遇到问题，可参照课程文档中的常见问题解答或寻求专业论坛的帮助。

通过本资源的学习，你将能够深刻理解 MIPS CPU 从单周期到多周期，再到微程序控制的演进过程，为深入计算机硬件领域打下坚实基础。祝你在计算机组成原理的学习旅程中收获满满！

## 下载链接

[24条指令CPUMIPS单周期与多周期微程序设计资源](https://pan.quark.cn/s/c4960860a238)