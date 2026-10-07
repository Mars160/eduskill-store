# InnoSkill

**让教师智慧可读、可用、可传承。**

InnoSkill 是面向中小学教师与职前教师的教育 AI Skill 创作、分享、复用与学习社区，旨在将教师的默会知识转化为文字化、可执行、可阅读的 Skill。教师既可以借助 AI 使用他人的方法，也可以通过阅读 Skill 学习教学技巧。

> 项目状态：需求定义与方案设计阶段。当前仓库尚无可运行实现，以下为规划能力，不代表已上线。预计交付日期为 **2026 年 12 月 31 日**，首期范围与正式发布时间待确认。

## 规划能力

- **创作**：模板填写、可视化编辑、AI 辅助生成与修改、上传已有 Skill 文件。
- **分享与学习**：分类与 Tag、Skill 阅读、Star、Issue、Fork 和二次开发。
- **使用**：优先通过平台 AI（如 InnoSpark）运行，并计划支持 WorkBuddy、Codex、Claude Code、pi-coding-agent、dsh、zcode 等外部工具；兼容范围待验证。
- **扩展**：初始分类为备课、出题、PBL 设计，不限制后续教学任务。
- **创作者收益**：支持免费分享和自主收费；收费 Skill 交易由平台抽成，免费 Skill 不收交易抽成。
- **运行计费**：使用平台 AI 需支付 Token 费用，免费 Skill 不等于免费运行。
- **衍生贡献**：若原 Skill 定价为 a、衍生创作者新增部分定价为 b，则衍生 Skill 标价为 a + b，对应收益分别归属上游与衍生创作者；授权、抽成扣除及结算细则待定。

## 当前如何参与

1. 阅读[问题定义与 5W1H 报告](docs/requirements/problem_definition.md)。
2. 阅读[需求草案](docs/requirements/product_requirements.md)，讨论用户故事与验收条件。
3. 按[贡献指南](CONTRIBUTING.md)提交建议或文档变更；如仓库托管于 GitHub，可使用 Issue 和 Pull Request。

当前没有可验证的安装、启动、部署命令或在线演示。待实现与运行方式确定后，再补充可复现的快速开始说明。

## 文档导航

| 文档 | 内容 |
| --- | --- |
| [文档索引](docs/README.md) | 正式文档入口、文档状态与维护规则 |
| [问题定义](docs/requirements/problem_definition.md) | 5W1H、定位、商业机制与待确认事项 |
| [产品需求](docs/requirements/product_requirements.md) | 用户故事、需求与验收条件 |
| [逻辑架构草案](docs/software/architecture.md) | 系统边界、领域模型与模块职责 |
| [测试策略](docs/software/testing_strategy.md) | 验证方法、需求追踪与风险测试 |
| [路线图](docs/mgmt/roadmap.md) | 阶段建议、交付目标与风险 |
| [Wiki 维护说明](docs/mgmt/wiki_guidelines.md) | FAQ、讨论与知识沉淀的组织方式 |
| [贡献指南](CONTRIBUTING.md) | Issue、PR、评审与提交规范 |
| [社区行为准则](CODE_OF_CONDUCT.md) | 尊重、隐私与社区协作 |
| [安全报告流程](SECURITY.md) | 私密报告与敏感信息保护 |
| [变更记录](CHANGELOG.md) | 尚未发布的变更与后续版本历史 |
| [许可状态](docs/mgmt/licensing.md) | 仓库协议与平台 Skill 授权的区别 |

## 仓库结构

```text
.github/             GitHub 协作模板与工作流目录
code/
  frontend/          前端实现预留目录
  backend/           后端实现预留目录
  core_engine/       Skill 核心引擎预留目录
docs/
  requirements/      产品与需求文档
  software/          软件设计与测试文档
  algorithm/         算法文档预留目录
  mgmt/              项目管理与协作规则
  retrospection/     复盘资料预留目录
  wiki/              待发布的 Wiki 草稿
tests/
  unit/              单元测试预留目录
  integration/       集成测试预留目录
```

目录仅表达当前组织意图，不表示相应组件已实现。

## 许可与安全

仓库开源协议尚未选定，当前不提供 `LICENSE`，不应据此推断已授予开源使用许可。平台上 Skill 的免费/收费、阅读、执行、Fork 和再销售权利需要单独定义，见[许可状态](docs/mgmt/licensing.md)。

请勿在公开 Issue、PR 或 Skill 示例中提交凭据、真实学生数据或漏洞利用细节；安全问题见 [SECURITY.md](SECURITY.md)。
