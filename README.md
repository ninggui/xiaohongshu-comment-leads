# 小红书评论引流

![GitHub stars](https://img.shields.io/github/stars/ninggui/xiaohongshu-comment-leads)
![License](https://img.shields.io/github/license/ninggui/xiaohongshu-comment-leads)
[![SkillHub](https://img.shields.io/badge/SkillHub-在线安装-blue)](https://skillhub.cn/skills/xiaohongshu-comment-leads)

关键词搜索→他人评论区发引流评论的通用策略与风控体系。

## 这是什么

一个可复用的 AI Agent 技能（Skill），来自真实业务场景沉淀，含完整执行流程、避坑清单与验证步骤。

## 快速使用

将本仓库放入 Agent 技能目录后，用对应触发词调用（见 SKILL.md），Agent 会自动加载并执行完整流程。

## 核心能力

| 能力 | 说明 |
|------|------|
| 关键词分层与动态扩词 |
| 评论边界红线 |
| 频率与风控参数表 |
| 被ban判定与冷却流程 |

## 使用方式（安装）

- **Hermes**: 放入 `skills/` 目录
- **Claude**: 放入 `~/.claude/skills/`
- **其他 Agent**: 按对应 SKILL.md 格式放入技能目录
- **SkillHub 一键安装**: https://skillhub.cn/skills/xiaohongshu-comment-leads

## 优势

- 实测风控阈值（搜索180次/天触发）
- 解封检测状态机
- 写操作测试纪律
- 脱敏方法论，无隐私

## 内容结构

- `SKILL.md` — 核心技能定义（触发条件、执行流程、避坑清单）
- `references/` — 可选参考文件

## 许可

MIT
