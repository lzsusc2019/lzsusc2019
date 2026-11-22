<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-engineer-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/banner-engineer-light.svg">
  <img src="assets/banner-engineer-light.svg" width="100%" alt="Local-first AI products">
</picture>

<br>

一个人做 AI 产品。关心的问题是：当 AI 开始替人记事、算账、下判断，它给出的每个数字能不能被核对。

所以做的东西都朝一个方向 —— 数据先可信，功能再往上长。

<br>

### Selected work

**[Daybook](https://github.com/lzsusc2019/daybook)** · 本地优先的个人数据 App。记录吃了什么、钱花到哪，日/周/月自动复盘。SwiftUI + 系统 SQLite，零第三方依赖，247 个测试。
原始采集不可变，报告里每个数字都由 SQL 聚合，数据只有一份在手机里。

**[agent-platform](https://github.com/lzsusc2019/agent-platform)** · 智能体中台 MVP。先把「可恢复、可中断、可审批」这条主路径跑通，沙箱与 MCP 留接口。

**[keyvault](https://github.com/lzsusc2019/keyvault)** · 本地 API key 台账。扫描发现、联网判活，零依赖单页界面，key 不出本机。

**[skills-watch](https://github.com/lzsusc2019/skills-watch)** · 盯着本机装的 Agent Skill，指出哪一个已经落后于上游。无后台轮询，离线时显示 `unknown` 而不误报。

<br>

### Stack

`Client` SwiftUI · Swift Concurrency · system SQLite · PWA
`Agent` Agent Loop · Tool Use · Checkpoint · HITL · 长期记忆
`LLM` Structured extraction · Citation checks · 重试与成本治理
`Server` Python · Java · Spring Boot
`Data` SQLite · MySQL · Redis

<br>

### Notes

> 先定数据模型，再写第一行代码。
> 能被 SQL 算出来的数字，不交给模型猜。

<br>

<sub>**Contact** · [15974286796@163.com](mailto:15974286796@163.com) · [English ↓](#about)</sub>

---

<a id="about"></a>

## About

I build AI products on my own. The question I keep working on: once an AI starts remembering, bookkeeping and judging for a person, can every number it gives be checked?

Everything I build points the same way — make the data trustworthy first, then grow features on top of it.

### Selected work

**[Daybook](https://github.com/lzsusc2019/daybook)** · A local-first personal data app. Log what you eat and spend; get daily, weekly and monthly reviews. SwiftUI + system SQLite, zero third-party dependencies, 247 tests. Raw captures are immutable, every number in a report is computed by SQL, and there is exactly one copy of the data — on your phone.

**[agent-platform](https://github.com/lzsusc2019/agent-platform)** · An agent middle-platform MVP. Gets the "resumable, interruptible, approvable" path working end to end first; sandboxing and MCP are left as interfaces.

**[keyvault](https://github.com/lzsusc2019/keyvault)** · A local API-key ledger. Discovery scanning, liveness checks, zero-dependency single-page UI. Keys never leave your machine.

**[skills-watch](https://github.com/lzsusc2019/skills-watch)** · Watches the agent skills installed on your machine and flags managed ones that have fallen behind upstream. No background polling; offline checks report `unknown` instead of a false alarm.

### Stack

`Client` SwiftUI · Swift Concurrency · system SQLite · PWA
`Agent` Agent Loop · Tool Use · Checkpoint · HITL · long-term memory
`LLM` Structured extraction · Citation checks · retry & cost control
`Server` Python · Java · Spring Boot
`Data` SQLite · MySQL · Redis

### Notes

> Define the data model before writing the first line of code.
> Any number SQL can compute is never left to a model to guess.

<br>

<sub>**Contact** · [15974286796@163.com](mailto:15974286796@163.com)</sub>
