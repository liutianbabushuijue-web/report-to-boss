# report-to-boss

一个「向上级汇报」的 AI skill。核心理念：**汇报的本质是交付判断，不是告知**——让老板听完只需点头，不用再花时间想怎么办。

## 适用场景

- 向上级 / 老板汇报工作、项目进展
- 请示决策、报风险 / 坏消息
- 述职、年度 / 阶段总结
- 优化汇报话术、避开汇报雷区

## 核心方法论

1. **三段式输出**：结论先行（一句话）→ 数据 / 事实 / 案例支撑 → 带底气的判断（方案 + 预测）。
2. **汇报黑名单**：只说问题不说方案、模糊词、隐瞒坏消息、让领导猜。
3. **四维度翻译**：把工作成果翻译成领导关心的「目标 / 进度 / 风险 / 资源」。
4. **主动汇报节点** + 3 分钟上限 + 「外脑而非手脚」的心态定位。
5. **工程化约束**：固定角色 / 格式 / 风格；术语一致性规则（术语表）；防幻觉红线（不编造、不确定就追问）；版本化（CHANGELOG 可回滚、可 A/B 测试）。

## 目录结构

```
report-to-boss/
├── SKILL.md
├── README.md
├── LICENSE
└── references/
    ├── phrasing-templates.md    # 话术模板 + 量化对照
    ├── anti-patterns.md         # 黑名单反例对照
    ├── advanced-playbook.md     # 分对象/述职/载体进阶手册
    ├── sbl-playbook.md          # 书面汇报结构 + 方案评估（ACCA SBL 视角）
    ├── glossary.md              # 术语表（专有名词一致性登记）
    └── CHANGELOG.md             # 版本变更记录
```

## 安装 / 使用

- **Claude Code / 通用 agent skill**：把本仓库放进 skills 目录，例如
  `~/.claude/skills/report-to-boss/`。
- **OpenViking**：用 `add_skill` 导入本仓库（需 OpenViking 服务可用）。

## License

[MIT](./LICENSE)
