# AI Personal Profile
跨 AI 共享的个人档案入口。各 AI / Agent 读取本仓库以了解我；请用 Issues 跟踪待填充项，用 commit 记录每次修改以便追溯与回退。
## 个人简介与背景
- 陈之恒（Joson Chen）；时区 Asia/Shanghai（UTC+8）。
- 上市公司跨境电商公司（深圳市永联科技有限公司）合伙人、产品研发 VP、首席 AI 官；主导建设「企业 Ai 大脑」与 AI 数字员工矩阵。
- 将 AI 视为企业底层操作系统，而非仅降本工具；团队手把手 AI / LLM 实践累计 3000+ 小时；重视系统架构、极致执行、极客精神与终身学习。
- 曾打造 Koogeek（苹果智能家居，获 Apple 专题报道 19 次）、iHaper（43 项 Apple PPID 认证）、dodocool（28 项 MFi 认证）；在两家上市跨境电商公司带过百人级研发团队。
- 完成深圳磨房 100km 徒步 9 次；得到重度用户（936 学分）。
- 对外公开信息以本仓库为准，隐私细节不写入此处。
## 工作与学习习惯
- 默认先给结论再给证据；交付物要求可执行、可回退。
- 重度使用 AI 助手与自动化例行（晨间邮件简报、周报、清单等）处理信息流。
- 学习与落地偏好「最小可验证实验 → 笔记 → 复盘」；对可复用玩法倾向沉淀成 bot / skill / 例行任务。
- 明确要求「不要跟业务有关」时，助手应改走通用玩法，不把公司业务细节带进泛化建议。
## 沟通风格偏好
- 默认中文；技术名词可保留英文。
- 回复宜短、直接，先答案后细节；少用客套、少用标题堆砌。
- 不确定时先说明证据边界，不要编造数字、来源或结论。
- 与助手协作：可直接下短指令（如「接到」「写入」）；期望对方先做再报结果。
## 常用工具与技术栈
- 协作与日常：GitHub（账号 gdjoson-dev）、Gmail、Google Drive、Grok Bot 矩阵（含额度雷达、VOC、跨境电商选品、学习流等）。
- 自动化：Grok Bot 例行任务（晨间邮件简报、周一本周提醒、周五 AI 工具周报、每周新玩法、本仓每日档案同步）。
- 开发与代理：Cursor / Cloud Agent、浏览器自动化、微信中继（限定入口）。
- 技术栈按项目再补；本仓本身为 Markdown + Issues / Projects 管理。
## 项目经验与成果
- 企业 Ai 大脑 + AI 数字员工矩阵 — 永联科技 — 主导建设（角色：产品研发 VP / 首席 AI 官）。
- Koogeek — Apple 智能家居品牌 — 获 Apple 专题报道 19 次。
- iHaper — 智能硬件 — 43 项 Apple PPID 认证。
- dodocool — 配件品牌 — 28 项 MFi 认证。
- 本仓库 [ai-personal-profile](https://github.com/gdjoson-dev/ai-personal-profile) — 跨 AI 共享个人档案 — 进行中。
## 长期目标
- 持续把 AI 做成企业级操作系统能力（架构、数字员工矩阵、可复用流程）。
- 希望 AI 助手优先协助：个人档案维护、信息流精简、可验证的调研与工具编排、可回退的自动化。
- 刻意边界：泛化玩法中不夹带公司业务细节；公开仓不写隐私与密钥。
## 如何更新
1. 改对应章节后直接 commit 到 `main`（或开 PR）。
2. 用 Issues 勾选/关闭已填完的待办。
3. 需要回退时用 GitHub 的 commit / history 恢复到任意版本。

## 每日自动同步

[Daily profile sync](https://github.com/gdjoson-dev/ai-personal-profile/actions/workflows/main.yml) 每天北京时间 16:00 检查待同步条目。仓库所有者可从 [Issues](https://github.com/gdjoson-dev/ai-personal-profile/issues/new) 新建空白 Issue，标题以 `[SYNC] ` 开头。正文第一行写 README 的完整章节名，下面每行写一个以 `- ` 开头的公开条目。例如：

```text
沟通风格偏好
- 对比方案时优先使用表格，并注明决策依据。
```

工作流只读取仓库所有者创建的开放同步 Issue，有新增时才提交到 `main`。同步后可关闭对应 Issue。若要回退同步提交，请先关闭对应 Issue，再用 Git revert 恢复。普通档案待办继续使用 Issues 模板。
