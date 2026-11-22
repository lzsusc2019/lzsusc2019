<p align="center">
  <b>中文</b> · <a href="#about">English</a>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-engineer-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/banner-engineer-light.svg">
    <img src="assets/banner-engineer-light.svg" width="100%" alt="AI Products · Local-first" />
  </picture>
</p>

<p align="center">
  <a href="https://github.com/lzsusc2019"><img src="https://visitor-badge.laobi.icu/badge?page_id=lzsusc2019.lzsusc2019&left_text=Visitors&left_color=7C3AED" alt="Visitors" /></a>
  <a href="https://github.com/lzsusc2019"><img src="https://img.shields.io/badge/GitHub-lzsusc2019-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="mailto:15974286796@163.com"><img src="https://img.shields.io/badge/Email-联系我-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

## 关于

一个人做 AI 产品。关心的问题很具体：当 AI 开始替人记事、算账、下判断，它给出的每个数字能不能被核对。

所以做的东西都朝一个方向 —— **数据先可信，功能再往上长。**

**现在在做**

📓 **日知 Daybook** — 本地优先的个人数据 App：记下吃了什么、喝了什么、钱花到哪、学了什么，日/周/月自动复盘。SwiftUI + 系统 SQLite，零第三方依赖。三条写进代码的硬约束：原始采集不可变、报告里每个数字都由 SQL 聚合、数据只有一份在手机里。
`Swift` · `SwiftUI` · `SQLite` · `本地优先` · 247 tests

🧭 **[agent-platform](https://github.com/lzsusc2019/agent-platform)** — 灵枢智能体中台 MVP：先把「可恢复、可中断、可审批」这条主路径跑通（Agent Loop + Checkpoint + HITL），沙箱 / 热加载 / MCP 留接口
`Python` · `Agent Runtime` · `HITL`

🔑 **[keyvault](https://github.com/lzsusc2019/keyvault)** — 本地 API key 台账：扫描发现、联网判活，零依赖单页界面，key 不出本机
`Python` · `零依赖`

🛰️ **[skills-watch](https://github.com/lzsusc2019/skills-watch)** — 盯着本机装的 Agent Skill，指出哪一个已经落后于它的上游仓库。Host/Client 双半边架构，无后台轮询，远端 SHA 缓存 24h，离线时显示 `unknown` 而不误报
`Cordis` · `React 18` · `Node.js` · `zod` · MIT

**技术栈**

<p>
  <img src="https://skillicons.dev/icons?i=swift,python,java,ts,sqlite,mysql,redis,docker" alt="Tech Stack" />
</p>

| 方向 | 技术 |
|---|---|
| 产品与客户端 | SwiftUI · Swift Concurrency · 系统 SQLite（零依赖）· PWA |
| Agent | Agent Loop · Tool Use 编排 · Checkpoint · HITL · 长期记忆 |
| LLM 应用 | Function Calling · 结构化抽取 · 引用校验 · 重试与成本治理 |
| 服务端 | Python（asyncio）· Java · Spring Boot · MyBatis |
| 数据 | SQLite（schema 迁移 / 聚合口径）· MySQL · Redis |
| 工程 | 本地优先架构 · 可观测性 · CI 编译签名流水线 · Docker/K8s |

**两条写码习惯**

1. 先定数据模型，再写第一行代码。
2. 能被 SQL 算出来的数字，不交给模型猜。

**联系**

- 邮件：见上方 Email 按钮

---

<p align="center">
  <img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=lzsusc2019&theme=github" alt="Profile Details" />
</p>

<p align="center">
  <img height="165" src="https://github-readme-stats-eight-theta.vercel.app/api?username=lzsusc2019&show_icons=true&title_color=7C3AED&icon_color=7C3AED&text_color=434d58&bg_color=00000000&hide_border=true&include_all_commits=true" alt="GitHub Stats" />
  <img height="165" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=lzsusc2019&layout=compact&title_color=7C3AED&text_color=434d58&bg_color=00000000&hide_border=true&langs_count=6" alt="Top Languages" />
</p>

---

## About

I build AI products on my own. The question I keep working on is concrete: once an AI starts remembering, bookkeeping and judging for a person, can every number it gives be checked?

So everything I build points the same way — **make the data trustworthy first, then grow features on top of it.**

**What I'm building**

📓 **Daybook** — a local-first personal data app: log what you eat, drink, spend and learn; get daily, weekly and monthly reviews. SwiftUI + system SQLite, zero third-party dependencies. Three rules enforced in code: raw captures are immutable, every number in a report is computed by SQL, and there is exactly one copy of the data, on your phone.
`Swift` · `SwiftUI` · `SQLite` · `local-first` · 247 tests

🧭 **[agent-platform](https://github.com/lzsusc2019/agent-platform)** — An agent middle-platform MVP: get the "resumable, interruptible, approvable" path working end to end first (Agent Loop + Checkpoint + HITL), with sandboxing / hot reload / MCP left as interfaces
`Python` · `Agent Runtime` · `HITL`

🔑 **[keyvault](https://github.com/lzsusc2019/keyvault)** — A local API-key ledger: discovery scanning, liveness checks, and a zero-dependency single-page UI. Keys never leave your machine
`Python` · `zero-dependency`

🛰️ **[skills-watch](https://github.com/lzsusc2019/skills-watch)** — Watches the agent skills installed on your machine and flags the managed ones that have fallen behind their upstream repository. Host/Client halves, no background polling, 24h remote-SHA cache, and offline checks report `unknown` instead of a false alarm
`Cordis` · `React 18` · `Node.js` · `zod` · MIT

**Tech Stack**

| Area | Technologies |
|---|---|
| Product & Client | SwiftUI · Swift Concurrency · system SQLite (zero dependencies) · PWA |
| Agent | Agent Loop · Tool Use orchestration · Checkpoint · HITL · long-term memory |
| LLM Applications | Function Calling · structured extraction · citation checks · retry & cost control |
| Server | Python (asyncio) · Java · Spring Boot · MyBatis |
| Data | SQLite (schema migrations / aggregate semantics) · MySQL · Redis |
| Engineering | Local-first architecture · observability · CI build & signing · Docker/K8s |

**Two habits**

1. Define the data model before writing the first line of code.
2. Any number that SQL can compute is never left to a model to guess.

**Contact**

- Email: see the Email button above
