# anthropic-prompt-zh

这是一个用于学习和研究的 Anthropic 模型提示词中文化归档项目，收集公开流传的 Anthropic 相关提示词材料，并提供中文翻译，方便中文读者学习提示词工程、模型行为设计与系统提示词结构。

## 项目用途

本项目主要用于提示词工程参考和研究。你可以通过这些材料观察和比较：

- 系统提示词的层级结构
- 安全策略与拒答策略的措辞方式
- 工具调用协议和参数约束
- 输出格式、引用规则和版权规则
- 记忆、搜索、文件处理等能力的提示词设计
- 不同模型版本之间的行为与提示风格差异

## 目录说明

- `ANTHROPIC/`：Anthropic 相关提示词材料与笔记。
- `*.zh.md`：简体中文翻译版本。
- `*.analysis.zh.md`：中文提示词工程分析。
- 原始文件名会尽量保留，便于对照原文和译文。

## 当前内容

- [Claude Fable 5 原文](ANTHROPIC/CLAUDE-FABLE-5.md)
- [Claude Fable 5 中文译文](ANTHROPIC/CLAUDE-FABLE-5.zh.md)
- [Claude Fable 5 提示词分析](ANTHROPIC/CLAUDE-FABLE-5.analysis.zh.md)

## 翻译约定

- Claude、Anthropic、API、MCP、Artifacts、Skills、Claude Code、Claude Platform、Claude Cowork、模型字符串和工具函数名等专有名词或接口标识默认保留原文。
- Markdown 结构标题优先保留原始标签，并在后面补充中文释义，例如 `## claude_behavior（Claude 行为）`，方便同时阅读译文和追踪原始提示词结构。
- 解释性正文尽量译成自然中文；JSON schema、枚举值、参数名、模型字符串和代码块中作为原始定义存在的英文通常不翻译。
- 对存在官方大小写或产品写法的名称，尽量保持原写法，例如 Claude in PowerPoint。

## 说明

本项目是非官方学习与研究仓库，与 Anthropic 无关，也不应被视为 Anthropic 产品文档或当前模型行为的权威来源。

部分材料可能来自公开泄露、社区流传或非官方整理，也可能已经过时、带有推测成分或与真实线上产品行为不完全一致。请批判性阅读；在需要准确性的场景中，应以官方文档和实际产品行为为准。

本仓库仅供翻译、学习、研究和提示词工程分析参考。使用相关材料时，请遵守适用法律、平台条款与知识产权规则。
