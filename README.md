# **LLM Workflow Research Lab**

**Main README · v0.1**

A long-term research space for developing my personal LLM workflow systems, cognitive protocols, and prompt-engineering methodology.

---

## **0. Purpose**

本研究室的目标是建立一个持续迭代的体系，用于记录、研究与设计：

* 大语言模型（LLM）的任务分解策略
* 多阶段推理流程（multi-pass reasoning）
* 不确定性与模型自检协议（uncertainty & self-checking protocols）
* 高质量任务输入规范（input sanitation）
* Prompt Engineering 的理论与实践映射
* 个人方法论的 formalization
* 可工程化（workflow-level）复用结构
* 对应学术论文的概念与参考

本仓库将作为我长期的“第二大脑”，记录从直觉到 formalization 的全过程。

---

## **1. Repository Structure（初始结构）**

```
/research-notes               — 主研究区：理论、拆解、推理、分析
  /ideas                      — 概念草稿、未定性的论点
  /insights                   — 可沉淀的结构化结论
  /protocol-design            — 自己建立的认知/推理协议
  /paper-mapping              — 学术概念与论文映射

/formal-docs                 — 最终定稿、可公开的方法论文档
  /patterns                  — 可复用模式
  /frameworks                — 我的 LLM 交互框架
  /methodology               — 系统性方法论
  /versions                  — v0.1 / v0.2 / v0.3 / v0.4 更新记录

/fragments                   — 灵感碎片桶
  /daily                     — 杂项、随想、零散 insight

/operations                  — 项目维护工具与流程
  manual.md                  — 操作/风险手册
  weekly-template.md         — 周报模板
  monthly-template.md        — 月报模板
  todo.md                    — 待整理清单

README.md                    — 本文件（项目入口）
```

随着研究深入，本结构将在 v0.2–v0.4 迭代时扩展。

---

## **2. Research Workflow（工作流模式）**

本研究室采用“三窗口体系 + 文档仓库”的方式运行：

### **1) 主研究窗口（ChatGPT）**

* 推理论
* 方法设计
* 学术映射
* 批判性对话

### **2) 正式化窗口（ChatGPT 项目模式）**

* 生成 markdown 文档
* 版本管理
* 更新 formal-docs

### **3) 碎片桶窗口（ChatGPT）**

* 临时想法
* 随机 insight
* 之后会被提炼并进入研究区

所有内容最终回流本仓库，形成统一知识体系。

---

## **3. Versioning（版本管理）**

长期方法论使用版本号迭代：

* **v0.1**：初始结构与理念
* **v0.2**：加入学术 mapping（CoT / ReAct / Reflexion / SC 等）
* **v0.3**：方法论 formalization（流程、边界、错误模式）
* **v0.4**：工程化 workflow，可写成文章或博客
* **v1.x**：若需要，发展为独立框架或论文

版本更新记录位于 `/formal-docs/versions/`。

---

## **4. Contribution Philosophy（方法论理念）**

### **Structure First**

结构优先于灵感。

### **Uncertainty Aware**

推理必须标注不确定性来源。

### **No Hallucination Tolerance**

拒绝迎合式生成，优先保持逻辑与事实。

### **Cognitive Protocol Design**

重点不在 prompt 字面，而在流程设计。

### **Academia × Intuition**

直觉探索必须与论文框架互相印证。

### **Ethics & Clean Boundaries**

避免操纵、误导、情绪煽动与不负责任使用。

---

## **5. Weekly & Monthly Routine（更新节奏）**

### **Weekly**

* 整理 1–2 个关键 insight
* 收割碎片桶
* 生成周报（weekly-template）
* 更新 research-notes

### **Monthly**

* 方法论版本更新
* 结构大整理
* 学术引用补充
* 输出可公开内容（如 patterns 或 frameworks）

---

## **6. Topic Roadmap（研究方向）**

未来将覆盖的核心主题包括：

* LLM 推理机制（System-1 vs System-2）
* Task decomposition
* Multi-pass reasoning
* Uncertainty & self-checking
* Critique prompting
* Error correction
* Goal disambiguation
* Input sanitation
* Human–AI collaborative cognition
* Workflow-level orchestration
* AI interaction safety

---

## **7. For Future Me（写给未来的我）**

* 你不是在“写 prompt”，你在构建一个协作系统。
* 这个仓库的节奏比你的情绪更重要。
* 不要追求完美版，v0.1 比空白强 100 倍。
* 每一个 insight 都值得记录。
* 你正在构建属于你自己的方法论世界。
