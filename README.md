# LOVE20BSC Docs

LOVE20BSC 协议（BSC 版）的对外公开文档。

本仓库只收录可对外发布的定稿内容，面向集成方、审计方、运维方与协议使用者。

## 范围

| 类别 | 内容 |
| --- | --- |
| 协议概览 | 白皮书、经济模型、代币与轮次模型 |
| 架构 | 模块划分、合约职责、依赖关系与调用链 |
| 接口 | 对外 ABI、事件与错误码、集成指南 |
| 部署 | 网络与合约地址、部署参数、运维与升级说明 |
| 安全 | 审计结论、已知约束与风险提示 |
| 参考 | 术语表、版本与变更记录 |

## 边界

- 源码与测试放在各代码库，不进本仓库。
- 规格审查、票据、决策过程与组织级协作规范在 [matt-gov](https://github.com/LOVE20BSC/matt-gov)。
- 构建、门禁与实现细节见各代码库 README。

## 权威来源

| 事项 | 来源 |
| --- | --- |
| 协议行为规格 | [matt-gov/docs/specs](https://github.com/LOVE20BSC/matt-gov/tree/main/docs/specs) |
| 合约接口 | [core/src/interfaces](https://github.com/LOVE20BSC/core/tree/main/src/interfaces) |
| 事件与错误规范 | [event-standards.md](https://github.com/LOVE20BSC/matt-gov/blob/main/docs/event-standards.md)、[error-standards.md](https://github.com/LOVE20BSC/matt-gov/blob/main/docs/error-standards.md) |
| 白皮书核心部分 | [core/docs/whitepaper-core.md](https://github.com/LOVE20BSC/core/blob/main/docs/whitepaper-core.md) |

本仓库的文档是上述来源的对外表述，不另立定义。出现不一致时以规格与代码库为准，并同步修正本仓库。

相关代码库：[libs](https://github.com/LOVE20BSC/libs)、[core](https://github.com/LOVE20BSC/core)、[dex](https://github.com/LOVE20BSC/dex)、[action](https://github.com/LOVE20BSC/action)、[group-chat](https://github.com/LOVE20BSC/group-chat)。

## 组织方式

- 按主题分目录，一个文档只讲一个主题；文件名用小写连字符。
- 中文叙述；合约名、函数、事件与错误名保留英文原文。
- 文档只写当前确定的设计，修改过程留在提交信息里。
