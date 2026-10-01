# 变更记录

## v1.1.3（2026-09-30）

- 输出流程固定为四步：草稿 → 需要确认的点 → 轮盘确认 → 定稿（「需要确认的点」必须走轮盘，无例外）。
- 术语表规则收紧：只登记用户明确提供 / 确认的信息，AI 不得自行添加条目，逐条标注来源。
- `.claude-plugin` 按官方文档核对修正（code.claude.com/docs/en/plugins/manifest-reference 与 marketplace-reference）：plugin.json 移除 `skills` 字段（官方标准布局：根目录 SKILL.md 自动作为单一 skill 加载）、补 `displayName`/`repository`/`license`/`keywords`；marketplace.json 补顶层 `description`。

## v1.1.2（2026-09-30）

- 新增分发配套：`.claude-plugin/plugin.json`、`.claude-plugin/marketplace.json`（Claude Code 插件市场一键安装）。
- README 安装说明扩为四种方式（插件市场 / 手动 / OpenViking / 下载 ZIP）。

## v1.1.1（2026-09-30）

- 风格放宽：表情符号不强制禁止（书面汇报建议少用；群消息 / 聊天可保留自然语气）。
- 一致性规则修正：疑似同一对象的相似写法，先向用户确认再判定，不直接判为不一致。
- 黑名单扩充：新增「相似对象混为一谈」「寒暄铺垫过长」；诊断要求输出「原文 → 违反项 → 正确写法」对照表。
- 更新 `references/anti-patterns.md` 黑名单扩展项。

## v1.1.0（2026-09-30）

- 新增「角色与任务」「输出格式」「风格」「禁止事项（红线）」「一致性规则（术语管理）」「准确性（防幻觉）」「版本管理」章节。
- 新增 `references/glossary.md`（术语表模板）、`references/CHANGELOG.md`（本文件）。
- 三段式、黑名单、交互规则（轮盘）、主动汇报节点保持不变。

## v1.0.0

- 初始版本：三段式输出、汇报黑名单、交互规则、话术模板、反例对照、进阶手册、SBL 视角手册。
