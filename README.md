# LegalOPC 白皮书起草小组

## 主权与角色声明（Governance Notice）

本仓库是 **LegalOPC 白皮书**的协作与发布地。为使外部读者清晰理解本仓库的归属关系，特作如下声明。

### 白皮书主权
LegalOPC 白皮书是 **LegalOPC 开放协调层**的公共品，不归任何商业实体所有、不由任何商业实体独占冠名。其定义权与标准权属于开放协调层（由白皮书起草小组代表）。

### 三方角色分工

| 角色 | 主体 | 说明 |
|------|------|------|
| **主权 / 主办** | LegalOPC 开放协调层（白皮书起草小组） | 定义权、标准权、发布决策权归开放协调层 |
| **发起 + 中文发布渠道** | 法务VC（fawuvc.com） | 白皮书发起方与主编；中文发布渠道 |
| **仓库托管 + 资助方之一** | legalVC | 本仓库当前的 GitHub 托管方与资助方之一；**非所有者、非冠名方** |

### 主权切割声明
- legalVC 作为本仓库的 GitHub 托管方与资助方之一，**不因此取得白皮书的所有权、标准权或冠名权**。
- legalVC 在 LegalOPC 生态中的定位为"楔子而非天花板"（wedge, not the ceiling）：参与生态经济、不占有行业公共品。
- 任何实现层（包括但不限于各类法律 AI 配置包、评测基准、参考实现）均可自由 adopt 本白皮书定义的标准，无需经 legalVC 授权。

### 迁移注记
本仓库当前托管于 `github.com/legalvc/legalopc-whitepaper`，系 v0.1 阶段因 `legalopc` 开放协调层 org 尚未创建的过渡安排。待 `legalopc` org 就绪，白皮书主仓库将迁移至 `github.com/legalopc/whitepaper`，届时本声明中的托管方关系相应更新，主权归属不变。

> *本声明仅用于仓库治理透明度（GitHub 层），不影响白皮书正文内容。白皮书正文遵循其独立叙事纪律。*

---

> LegalOPC（Legal One Person Company）中文称**「法律超级个体」（法务一人公司）**——一个人 + 法律专业能力 + AI 智能体，构成一个完整、可担责的法律交付单元。**AI 做执行，法律人担责。**

本仓库是 LegalOPC 白皮书的**开放共建仓库**：白皮书正文、一页纸、起草小组治理文件与公开物料，全部在此沉淀、迭代与讨论。

> 📖 在线浏览入口：[仓库导航页](https://legalvc.github.io/legalopc-whitepaper/)（GitHub Pages 开启后生效）

---

## 状态

| 版本 | 状态 | 说明 |
|---|---|---|
| v0.1 概念版 | ✅ 已完成 | 线上概念版 |
| v0.2 起草稿 | 🔨 进行中 | 本仓库 `docs/white-paper.html`：当前起草版本，欢迎共建 |
| v1.0 正式版 | ⏳ 目标 | 正文扩写完成并定稿后方可称为 v1.0 |

> ⚠️ 命名纪律：仅加序 / 净化术语 / 排版调整只能记为 v0.x，不得称 v1.0。

---

## 仓库结构

```
legalopc-whitepaper
├── README.md                          ← 仓库门面（本文件）
├── LICENSE                            ← CC BY 4.0
├── CONTRIBUTING.md                    ← 贡献指南：如何参与共建
├── docs/
│   ├── white-paper.html              ← 白皮书起草稿（当前正文基底）
│   └── one-pager.html                 ← 一页纸介绍（零内部叙事，对外可用）
├── governance/
│   ├── charter.md                     ← 起草小组工作章程（治理方式）
│   ├── writing-guide.md               ← 写作指南（红线 / 术语 / 分章要求）
│   └── ai-participation-guide.md      ← AI 参与起草指南（碳基担责 / 披露 / 核验）
└── community/
    ├── co-build-handbook.html         ← 共建发起手册（0–30 天第一步动作与话术）
    ├── invitation.html                ← 定向邀请函（模板）
    ├── recruitment.html               ← 招募公众号文章
    ├── announcement-drafting-group.html ← 起草小组公众号文章
    └── editor-note.html               ← 法务VC 主编说明（发起方视角）
```

---

## 核心主张（一句话）

LLM 把法律执行成本压到趋近于零，稀缺的不再是"能不能做完"，而是"谁来对结果负责"。LegalOPC 把**责任不可委托**做成可操作的职业与组织形态：

- **生产层**（合同起草 / 检索 / 文书）→ AI 自动覆盖
- **控制层**（风险判断 / 审批 / 质量把关）→ 人带 AI 下场
- **责任层**（签字 / 执业背书 / 合法性来源）→ 不可自动化、不可外包，**人担责**

---

## 如何参与

1. 阅读 `CONTRIBUTING.md` 了解共建方式与写作红线；使用 AI 辅助起草者，另见 `governance/ai-participation-guide.md`。
2. 对白皮书正文的反馈：提交 Issue（标 `[白皮书]`）。
3. 想成为章节主笔 / 评审 / 数据顾问：按 `community/invitation.html` 联系方式与主编沟通。

---

## 许可

本仓库内容以 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) 授权（署名即可使用）。
