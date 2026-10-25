<div align="center">

# Hi, I'm 庄书珺 👋

**Java 后端开发 · AI Agent 全栈**

成都信息工程大学 · 计算机科学与技术 · 2028 届

🔍 正在寻找 **Agent 全栈开发 / Java 后端** 实习机会

[![GitHub](https://img.shields.io/badge/GitHub-buleSkyBe-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/buleSkyBe)
[![Open to Work](https://img.shields.io/badge/Open%20to%20Work-Internship-2ea44f?style=flat-square)](https://github.com/buleSkyBe)

</div>

---

## 🧭 关于我

我是庄书珺（GitHub: **buleSkyBe**），成都信息工程大学计算机科学与技术专业 2024 级本科生。

- 🎯 **方向**：Agent 全栈开发 / Java 后端
- 🧠 **在做**：把 LLM 接进真实场景 —— QQ 群 AI 角色机器人、RAG 知识库、Agent 工作流
- 🛠️ **能落地**：Spring Boot 后端、MySQL / Redis、Vue 前端，到 Linux + Nginx 部署上线
- 📚 **在补**：JVM、并发、MySQL 调优、分布式基础
- ✍️ **习惯**：用「30 天复习笔记 + LeetCode」把零散知识沉淀成体系

> 把「能跑」写成「写好」，把「刷过」变成「掌握」。

## 🛠️ 技术栈

**后端开发**

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Spring MVC](https://img.shields.io/badge/Spring_MVC-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![MyBatis-Plus](https://img.shields.io/badge/MyBatis--Plus-1E90FF?style=for-the-badge)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)

**AI / Agent**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NoneBot2](https://img.shields.io/badge/NoneBot2-4B8BBE?style=for-the-badge)
![LLM API](https://img.shields.io/badge/LLM_API-412991?style=for-the-badge&logo=openai&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-FF6F61?style=for-the-badge)

**前端与工程化**

![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)

## 🚀 代表项目

> 项目代码正在整理开源，对某个项目感兴趣欢迎开 Issue 交流。

### 🤖 QQ AI Agent 角色机器人

`NoneBot2` `OneBot V11` `NapCat` `Python` `LLM API` `APScheduler`

一个接入真实 QQ 群运行的 AI 角色机器人，不只是「问答」，而是像群成员一样参与聊天。

- 基于 **NoneBot2 + OneBot V11** 对接 NapCat 协议端，通过 WebSocket 收发消息，支持 @触发、引用续聊与私聊
- 设计**分层上下文注入**：人设 System Prompt + 群聊近期记录 + 对话历史 + 被 @ 成员的个人发言，让回复贴合语境、减少编造
- 按群隔离的**滑动窗口记忆**（deque + JSON 持久化），重启不丢上下文
- 实现**主动插话**机制：概率触发 + 冷却时间 + 冷场保护，避免刷屏
- 接入 **Tavily 搜索**，按关键词把实时信息注入 Prompt
- 用 **APScheduler** 定时生成每日群聊总结，以角色口吻播报

### 📝 个人博客系统

`Spring` `SpringMVC` `MyBatis-Plus` `MySQL` `Redis` `Vue` `Nginx` `Linux`

独立开发并部署上线的全栈博客平台，支持文章发布、分类标签、评论互动与搜索。

- 基于 **SSM + Maven 多模块**搭建后端，MyBatis-Plus 负责数据访问
- 引入 **Redis** 缓存热门文章与评论，页面平均响应时间降低约 **40%**
- 编写动态 SQL 支持分类检索、多条件组合查询与分页
- 完成 Vue 前端开发与前后端联调，部署至 Linux 云服务器并配置 **Nginx 反向代理**

### ♟️ 五子棋 AI

`Python` `Tkinter` `Minimax` `Alpha-Beta 剪枝` `启发式估值`

带博弈搜索能力的五子棋人机对战程序，三档难度可调。

- **Minimax + Alpha-Beta 剪枝**：在同等搜索深度下大幅减少无效分支
- **棋型启发式估值**：识别五连、活四、冲四、活三、眠三等棋型并赋分
- **候选点裁剪**：只评估已有棋子邻近的空位，避免全盘枚举
- 棋局逻辑（`Game`）与 Tkinter UI 完全解耦，支持无界面自检

### 📚 学习沉淀

- **30 天后端面试笔记**：30 篇 Markdown + PDF，覆盖 Java 基础、集合、并发、JVM、Spring、MySQL、Redis、RabbitMQ、网络、操作系统、项目复盘与模拟面试
- **LeetCode Java 题解**：按算法类型整理，含题目描述与思路注释，目前覆盖动态规划（279 / 322）等题型

## 📈 GitHub

<p align="center">
  <img height="150" src="https://github-readme-stats.vercel.app/api?username=buleSkyBe&show_icons=true&theme=tokyonight&hide_title=true&hide_border=true" alt="GitHub Stats" />
  <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=buleSkyBe&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=buleSkyBe&theme=tokyonight&hide_border=true" alt="GitHub Streak" height="150" />
</p>

## 🌱 最近在学

- 🧠 大模型应用：RAG、Tool Use、Agent Memory 与工作流编排
- ☕ Java 后端进阶：JVM 调优、并发编程、MySQL 索引与事务
- 🧱 工程化：Linux 运维、Nginx、项目部署与性能优化

## 📫 联系我

- GitHub：[github.com/buleSkyBe](https://github.com/buleSkyBe)
- 对项目感兴趣、想交流或内推，欢迎直接开 **Issue** 或 **Pull Request**
- 目前开放 **Agent 全栈开发 / Java 后端** 实习机会

---

<div align="center">

**Thanks for visiting! ⭐**

</div>
