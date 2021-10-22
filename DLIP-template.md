---
 dlip : <待分配> 
title : <DLIP 标题是几个词，不是一个完整的句子> 
description : <Description 是一个完整的（短）句子> 
author : <作者或作者姓名的列表(s) 和/或用户名，或姓名和电子邮件，例如（与括号或三角括号一起使用）：FirstName LastName (@GitHubUsername), FirstName LastName <foo@bar.com>, FirstName (@GitHubUsername) 和 GitHubUsername (@GitHubUsername)>
discussions-to: ：<URL>一般是discussion的入口
status: Draft、Review、Final
type: <标准跟踪、元数据或信息>，例如Cash、Governance、Project
category: （*仅标准轨道需要）：<核心、网络、接口或 ERC> 已
created: <创建日期，采用 ISO 8601 (yyyy-mm-dd) 格式>
requires: (*可选）：<DLIP 编号>
replaces: (*可选）：< DLIP号码>
---

## 解释
**摘要**
摘要是多句（短段）技术摘要。这应该是规范部分的一个非常简洁易读的版本。有人应该能够只阅读摘要以了解该规范的主要内容。

**动机**
动机部分应描述此 DLIP 的“原因”。它解决什么问题？为什么有人要实施这个标准？它为以太坊生态系统提供了什么好处？这个 DLIP 地址有哪些用例？

**规格**
技术规范应该描述任何新特性的语法和语义。该规范应该足够详细，以允许任何当前以太坊平台（go-ethereum、parity、cpp-ethereum、ethereumj、ethereumjs等）的竞争性、互操作性实现。

**基本原理**
基本原理通过描述设计的动机以及做出特定设计决策的原因来充实规范。它应该描述所考虑的替代设计和相关工作，例如其他语言如何支持该功能。

**向后兼容**
所有引入向后不兼容的 DLIP 都必须包含描述这些不兼容及其严重性的部分。DLIP 必须解释作者提议如何处理这些不兼容性。没有足够的向后兼容性论文的 DLIP 提交可能会被彻底拒绝。

**测试用例**
对于影响共识更改的 DLIP，实施的测试用例是强制性的。如果测试套件太大而无法合理地内联包含，则考虑将其作为一个或多个文件添加到../assets/DLIP-####/.

**参考实现**
包含参考/示例实现的可选部分，人们可以使用它来帮助理解或实现本规范。如果实现太大而无法合理地内联包含，则考虑将其作为一个或多个文件添加到../assets/DLIP-####/.

**安全注意事项**
所有 DLIP 都必须包含一个部分，讨论与提议的更改相关的安全影响/注意事项。包括可能对安全讨论很重要的信息、表面风险并且可以在提案的整个生命周期中使用。例如，包括与安全相关的设计决策、关注点、重要讨论、特定于实施的指南和陷阱、威胁和风险的概述以及如何解决它们。缺少“安全注意事项”部分的 DLIP 提交将被拒绝。如果没有审查人员认为足够的安全注意事项讨论，DLIP 无法进入“最终”状态。

**版权**
通过[CC0](https://creativecommons.org/publicdomain/zero/1.0/)放弃版权和相关权。

