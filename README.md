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

## 🚀 项目矩阵

### 🤖 AI Agent 工程

| 项目 | 定位 | 核心证据 |
|---|---|---|
| [AgentX](https://github.com/conversition/AgentX) | Agent 构建平台(Java 17 · Spring Boot · DDD) | 753 Java 类 · 自研状态机工作流 · [二开证据](https://github.com/conversition/AgentX/blob/master/docs/REFACTOR-NOTES.md) |
| [酒馆提示词 Agent](https://github.com/conversition/jiuguan) | SillyTavern 剧本引擎(Typescript · pnpm Monorepo) | 100+ commits · 世界书语义激活 · 记忆衰减 |
| [ComfyUI LLM 节点](https://github.com/conversition/comfyui-llm-chat-node) | ComfyUI LLM 对话节点二次开发(Python · MCP) | 三合一 Direct Chat · OpenCode 网关 · [CHANGELOG](https://github.com/conversition/comfyui-llm-chat-node/blob/master/CHANGELOG.md) |
| AI 叙事对话 Agent | 端到端叙事引擎(Python · TS · RAG) | 单回合 1 次模型往返 · 混合检索 ·【整理中,待开源】 |

### 🗄 数据治理与解决方案

| 项目 | 定位 | 状态 |
|---|---|---|
| 主数据治理 Agent | 制造业主数据实习延伸 POC(规则引擎 + LLM 映射) | 【规划中】 |
| 解决方案案例库 | 政府/组织级交付方法论案例(脱敏) | 【规划中】 |

### ⚡ 数据分析与竞赛

| 项目 | 定位 | 核心证据 |
|---|---|---|
| [电力负荷预测](https://github.com/conversition/energy-load-forecast) | 竞赛:96 点电价预测 + 储能策略 | 收益导向评估 · 分位数回归 · [RESULTS](https://github.com/conversition/energy-load-forecast/blob/master/docs/RESULTS.md) |

### 📊 求职市场分析

| 项目 | 定位 | 核心证据 |
|---|---|---|
| [Boss 直聘分析](https://github.com/conversition/boss-job-analyzer) | 采集 → 清洗 → 技能基准 → LLM 简历 | 55 组任务 · 4,234 条职位 · 98.8% 可统计薪资 |
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