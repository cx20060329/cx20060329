
Gemini
发起新对话
搜索对话内容
视频
库
根据简历生成GitHub README
Customizing Agent Behavior in Loops
Hermes Agent: 架构与实现
DeepAgent 集成 Langfuse 指南
LangGraph 本地服务器与 LangSmith
API 接口文档规范化
Git 克隆与切换分支
Novel Analysis Pipeline Design
Docker 端口映射访问失败排查
Langchain-Core 消息类型详解
`make dev` to `uv` Migration Guide
文件输出路径确认
设计合理性与完整性评估
Deepagents Backend Explained
Hermes 提示词：内容与格式
简历评估与逻辑漏洞澄清
多智能体系统设计与实现
长文本解析与多智能体系统
Skill vs. Tool in AI
分析小说所需Token量
开源 Agent 框架选型指南
开源 Agent 框架选型指南
Transformer 架构、公式与原理
AI 演化世界设计讨论
简历技术栈总结
VS Code Git 分支拉取合并
JupyterLab 连接问题排查
间接注入：数据中的安全陷阱
FastAPI 快速入门指南
LeetCode 128: Longest Consecutive Sequence
如何查看显示屏刷新率
Agent 热重载的工程实现方案
TypeScript 方法详解与应用
List Slicing Index Offset Explanation
与 Gemini 对话
根据简写一个github的rademe文件根据简历写啊

Your Markdown file (README.md) is ready.
MD 图标
README
 MD 
打开

I have generated a professional GitHub profile README tailored to your AI Application Development background based on the resume details provided. It includes styled badges for your tech stack, a clean layout for your project and internship experience, and highlights your key achievements in Multi-Agent and RAG engineering.  
PDF




Gemini 是一款 AI 工具，其回答未必正确无误。

<h1 align="center">Hi there, I'm 陈茜 👋</h1>

<h3 align="center">AI应用开发工程师 | 专注于 Multi-Agent 与 RAG 落地应用</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/LangChain-121212?style=flat-square&logo=chainlink&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
</p>

---

## 👨‍💻 关于我

- 🎓 坐标 **安徽宿州**，目前就读于 **安徽信息工程学院** (数据科学与大数据技术专业，本科，2023级)。
- 💼 现任芜湖埃泰克汽车电子有限公司 **AI应用开发实习生**。
- 🧠 专注方向：大模型（LLM）应用落地、长文本上下文管理、RAG 工程、多智能体（Multi-Agent）架构编排及 MCP 协议集成。
- 📫 联系方式：[chenxi20060329@163.com](mailto:chenxi20060329@163.com) | 📞 18725579526

## 🛠️ 技术栈

- **大模型生态:** LangChain, LangGraph (StateGraph), DeepAgent, MCP (Model Context Protocol)
- **RAG & 知识工程:** Milvus, GraphRAG, Query 路由与重写, 意图识别, 长文本高精召回
- **后端开发:** Python (FastAPI, Pydantic, 异步协程), TypeScript (NestJS, 依赖注入, 泛型编程)
- **中间件 & 数据:** PostgreSQL (pgvector), Redis, RabbitMQ, Hadoop

## 🚀 项目经历

### 📚 长文本解析与多智能体推演沙盒系统 (项目负责人)
*2026.06 - 至今*
- **技术栈:** Python | PostgreSQL+pgvector | Redis | RabbitMQ | RAG | MCP | LangChain/LangGraph
- **业务场景:** 针对小说的“结构化解析与动态剧情仿真”系统。通过离线RAG管线将原著降维拆解为知识底表，支撑多 Agent 在沙盒中进行交互推演。
- **核心贡献:**
  - **多智能体架构:** 采用“中心化调度+事件驱动”机制替代轮询，实现 Agent 的稀疏激活，降低 70% 无效 Token 消耗。
  - **知识工程:** 构建分布式长文本 ETL 管线，启发式实体消歧算法跨文档对齐准确率达 85%+。
  - **高可用优化:** 落地 Prompt Caching 与混合检索架构，依托消息队列实现节点弹性扩容，单次响应<2秒，推理成本下降30%-50%。
  - **状态与工具管理:** 基于 MCP 协议规范化工具调用；采用差集存储优化状态管理，实现低成本沙箱回滚。

## 💼 实习经历

### 🚗 芜湖埃泰克汽车电子有限公司 | AI应用开发实习生
*2026.05 - 至今*
- **项目背景:** 解决车身控制器研发中 FRS (客户功能规范) 到 SCRS (软件需求规范) 的人工转换痛点，开发集离线结构化解析与在线智能体协同的高可靠系统。
- **核心贡献:**
  - **Multi-Agent 工作流:** 搭建 “StateGraph+多智能体” 确定性工作流，结合 HITL (Human-in-the-loop) 机制实现高可控推理。
  - **防幻觉 RAG:** 构建自适应切片与降噪管线，强制生成内容绑定溯源 ID (Chunk ID)，实现 100% 来源可溯。
  - **分布式与性能:** 引入消息队列支持 ReAct 智能体水平扩展，结合 Redis 轻量级缓存降低上下文膨胀，优化高并发延迟。
  - **安全与可观测性:** 部署自动化评估与拦截框架，剥离模型自检权限，通过确定性逻辑接管确保行为安全。

## 🏆 荣誉奖项
- 安徽省计算机设计大赛 **省级二等奖**
- 分布式比赛 **省级三等奖**
- 安徽省 **金汇奖学金**

---
<p align="center"> <i>Let's build something amazing together!</i> </p>
README.md
目前显示的是“README.md”。
