# 👋 Hi, I'm Conversition

> 全栈工程师 · AI Agent / LLM 工程化 · 数据工程
> 从主数据平台落地到智能体应用,用工程化的方式把大模型能力变成可上线的产品。

---

## 🧭 当前专注

- 🤖 **LLM Agent 工程化**:MCP 工具编排 / RAG 检索增强 / 上下文管理 / 提示词架构
- 🗄 **主数据 & 数据迁移**:国产化 Oracle → 达梦迁移、ESB 集成、数据清洗治理
- 📈 **数据采集与预测**:爬虫工程、时序清洗、GBDT / LightGBM 建模

## 🛠 技术栈

**后端 & AI**

![Java 17](https://img.shields.io/badge/Java-17-orange?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Python](https://img.shields.io/badge/Python-3-3776AB?style=flat-square&logo=python&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/MCP%20Protocol-4B32C3?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-8A2BE2?style=flat-square)
![LightGBM](https://img.shields.io/badge/LightGBM-00BFFF?style=flat-square)

**前端**

![Next.js](https://img.shields.io/badge/Next.js-15-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=flat-square&logo=typescript&logoColor=white)

**数据 & 工程化**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![达梦](https://img.shields.io/badge/达梦%20DM-2E77BC?style=flat-square)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Kettle](https://img.shields.io/badge/Kettle%20ETL-FF6600?style=flat-square)
![ESB](https://img.shields.io/badge/ESB%20集成-7A5CFA?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

## 🚀 项目

### 🤖 [AgentX 智能体应用平台](https://github.com/conversition/AgentX)
**基于大模型 + MCP 协议的 Agent 构建与对话运行平台** · Java 17 · Spring Boot · LangChain · PostgreSQL · Next.js · Docker

- DDD 四层架构(基础设施 / 应用 / 核心业务 / 领域),保障高可维护性
- 落地计费、任务、会话、记忆、RAG 核心模块,打通完整 Agent 开发闭环
- 解决上下文爆炸、子 Agent 无限递归、Tool 调用逻辑冲突等智能体工程难题

### 🎭 AI 叙事对话 Agent
**端到端 Agent 系统,CLI / Web 双端** · Python · TypeScript · Monorepo · Node.js · React

- 7 大 Tool 模块 + Zod 契约(OpenAI Tools Schema + 运行校验),单回合最多 1 次模型往返
- RAG 增强:BM25 + 向量检索 + RRF 融合 + 置信度门限 + 快照恢复,缓解幻觉
- 提示词分层缓存(L0-L6)+ 1024 token 前缀缓存,降低推理成本
- node vm 沙箱隔离 + 钩子化扩展 API,插件热接入无需重启

### 📊 Boss 直聘数据采集与智能简历生成
**岗位数据爬虫 + BI 分析 + LLM 简历生成** · Python · Playwright · MySQL · Redis

- 采集管线:代理切换、断点续爬、内存/Redis 双队列去重
- ECharts 交互式 BI 报表,量化招聘市场感知
- 「采集 → 清洗 → 分析 → 报告 → 生成 → 导出」完整工作流

### ⚡ 电力负荷预测(全国竞赛)
**D+1 全天 96 点电价预测 + 充放电计划优化** · Python · LightGBM · GBDT

- 十万级多源时序数据清洗、特征工程与剪枝
- GBDT + LightGBM 融合模型,以真实业务收益而非 RMSE 选优

## 💼 经历

**美林数据** — 主数据实施实习生 / 解决方案支持(驻场项目)

- 面向制造企业搭建 7 大类主数据统一主数据源:集团报送标准对齐、历史数据清洗、**Oracle → 达梦**国产化迁移
- ESB 接口分发,完成 PDM / ERP / MES 等下游系统集成;Kettle 表对表迁移生产落地
- Python pandas 批量清洗:空值、重复、格式、符号、大小写、日期、单位标准化
- 深入"双写保同步、双读做校验、灰切控风险、回切做兜底"不停机迁移机制

## 📊 GitHub 数据

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=conversition&show_icons=true&theme=vue&count_private=true" alt="GitHub Stats" width="48%"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=conversition&layout=compact&theme=vue" alt="Top Languages" width="48%"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=conversition" alt="GitHub Streak"/>
</div>

## 🏆 成就

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=conversition&theme=flat&column=4" alt="GitHub Trophy"/>
</div>

## 📫 联系我

- GitHub: [conversition](https://github.com/conversition)
- 欢迎交流 **AI Agent 工程化 / 数据治理** 相关话题 ✨

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=conversition&style=flat-square&color=blue" alt="Profile Views"/>
</p>
