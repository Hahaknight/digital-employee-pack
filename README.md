# 数字员工配置包 — 把 Claude Code 变成你的全天候同事 🧑‍💼

> **先看 [EXAMPLES.md](EXAMPLES.md)——技能在作者真实工作数据上的输出示例（周报/PPT 大纲），不是演示数据。**

<p align="center"><img src="assets_cover.png" width="360" alt="数字员工配置包：6大岗位技能 + 防护Hooks + 工作流SOP，早鸟¥12.9"/></p>

> 你已经会用 AI 聊天了。但你的同事开始用 AI **干活**了：周报自动生成、乱表格一键清洗、1 小时录音 3 分钟出纪要。
>
> 差距不在模型，在**配置**。

> 来自同一作者：工程师向的 [claude-skills-pro](https://github.com/Hahaknight/claude-skills-pro)（15 个工程工作流 skills，7 个免费 MIT）。

这个仓库给你一套开箱即用的配置：1 份入职培训模板 + 6 个岗位技能 + 自动防护 + 3 套工作流 SOP。全部中文、面向上班族、不需要编程基础。

## 免费样例（本仓库可直接用）

| 文件 | 它能帮你做什么 |
|---|---|
| [周报生成器](free-sample/skills/weekly-report/SKILL.md) | 口述碎片 → 一屏以内的周报，每条成果自动带数据 |
| [PPT 大纲设计](free-sample/skills/ppt-outline/SKILL.md) | 先出故事线再出逐页稿，每页标题都是结论句 |
| [会议纪要生成器](free-sample/skills/meeting-minutes/SKILL.md) | 速记 → 结论先行 + 行动项带负责人日期，3 分钟可发群 |
| [SOP：把重复工作交给 AI](free-sample/SOP-把重复工作交给Agent.md) | 五步法把你每周重复做的事变成一句话指令 |

## 完整版包含（6 技能 + 4 模块）

| 模块 | 内容 |
|---|---|
| 🧠 入职培训模板 | `CLAUDE.md` 个人效率助手配置：5 分钟让 AI 记住你的规则、偏好、禁区 |
| 🛠 6 个岗位技能 | 周报生成 / 简历诊断改写 / 会议纪要（完整版含 3 场景模板与行动项跟踪） / 表格数据清洗 / PPT 大纲 / 高难度邮件 |
| 🛡 自动防护 Hooks | 敏感信息拦截（密钥/身份证号）+ 文件改动自动备份 |
| 📋 3 套工作流 SOP | 重复工作固化流程 / 大任务四步交付法 / 三层快速调研法 |

**适合谁**：每天和文档、表格、汇报打交道的职场人；带团队想让 AI 标准化提效的管理者；用 AI 聊天很久、但还没让 AI 真正干活的任何人。

**不适合谁**：想找"躺赚"秘籍的人（这里只有省时间的工具）。

## 快速开始（免费样例）

```bash
# 1. 在你的工作目录创建技能文件夹
mkdir -p .claude/skills/weekly-report

# 2. 把样例里的 SKILL.md 放进去
# 3. 启动 Claude Code，直接说：「周报」
```

## 获取完整版

🚚 **完整包已在 [Releases v1.0](../../releases/tag/v1.0) 上线**（密码保护，购买后发送解压密码）。**现在就能买**：在 [claude-skills-pro issue #1](https://github.com/Hahaknight/claude-skills-pro/issues/1) 评论「购买 DEP + 中文」，24 小时内回复付款方式并发密码（¥19.9）。🎁 **前 30 个早鸟名额**：Star ⭐ 本仓库 + [开一个 Issue](../../issues/new?title=早鸟申请&body=我的使用场景是：) 写一句你的使用场景，免费换完整版，条件是使用后留一句真实反馈。

## 为什么是"技能"而不是"提示词"？

提示词用一次就丢；技能（SKILL.md）是**装进 Agent 里的标准作业程序**：AI 会在正确的时机自动调用它，并按你定下的规则执行（先诊断后动手、不编数字、结论先行）。一次配置，长期复用。

## 声明

- 本项目为独立制作，与 Anthropic / OpenAI 等公司无关联；"Claude Code" 等名称仅用于说明兼容性
- 样例内容采用 CC BY 4.0 许可：可自由使用，请注明出处
