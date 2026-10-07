# InnoSkill 文档索引

## 正式文档

| 文档 | 用途 | 状态 |
| --- | --- | --- |
| [问题定义](requirements/problem_definition.md) | 5W1H、定位、价值与业务方向 | 已整理需求访谈；痛点待验证 |
| [产品需求](requirements/product_requirements.md) | 用户故事、需求 ID 与验收条件 | 草案，首期范围待确认 |
| [逻辑架构](software/architecture.md) | 模块边界、实体与关键流程 | 建议方案，技术栈未定 |
| [测试策略](software/testing_strategy.md) | 需求验证与风险测试 | 计划，尚无执行结果 |
| [路线图](mgmt/roadmap.md) | 阶段、风险与交付目标 | 建议计划 |
| [许可状态](mgmt/licensing.md) | 仓库许可与 Skill 授权边界 | 协议和授权细则待定 |
| [Wiki 维护说明](mgmt/wiki_guidelines.md) | Wiki 分工与发布步骤 | 本地工作约定草案 |

## 协作与知识入口

- [项目首页](../README.md)
- [贡献指南](../CONTRIBUTING.md)
- [社区行为准则](../CODE_OF_CONDUCT.md)
- [安全流程](../SECURITY.md)
- [变更记录](../CHANGELOG.md)
- [Wiki 首页草稿](wiki/Home.md)
- [常见问题](wiki/FAQ.md)

## 文档维护规则

1. 产品与业务方向以问题定义为基础；需求文档细化验收条件，架构和测试文档追踪需求 ID。
2. 尚未作出的决定必须标为待定；备选方案不得写成已选定方案。
3. 功能实现、部署和测试结果只有在可验证后才能标为完成。
4. 业务规则调整时同步需求、设计、测试和 README；实质性变更写入变更记录。
5. 正式文档通过 PR 评审；FAQ、经验和讨论可在 Wiki 沉淀，但不得覆盖正式需求。
6. 如出现冲突，先登记并确认决定，再同步所有相关文档，不默默依赖某一份草案。

## 组织依据

参考[《在 GitHub 中使用 Markdown 和 Wiki》](https://github.com/bettermorn/IntelligentSWEPractice/wiki/%E3%80%90%E8%BD%AF%E4%BB%B6%E5%BC%80%E5%8F%91%E3%80%91%E5%9C%A8GitHub%E4%B8%AD%E4%BD%BF%E7%94%A8Markdown%E5%92%8CWiki#2-%E5%85%B8%E5%9E%8B%E4%BD%BF%E7%94%A8%E5%9C%BA%E6%99%AF)中的典型场景：README 是入口，仓库 Markdown 保存需评审和版本管理的正式内容，Wiki 保存 FAQ、经验和讨论。当前未发布文档网站，也未配置远程 Wiki。
