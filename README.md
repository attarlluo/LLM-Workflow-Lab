**《LLM Workflow Research Lab》

Main README · v0.1**

A long-term research space for developing my personal LLM workflow systems, prompt engineering methodology, and cognitive protocol design.

0. Purpose

本研究室的目标是建立一个持续迭代的体系，用于记录、研究与设计：

大语言模型（LLM）的任务分解策略

多阶段推理流程（multi-pass reasoning）

不确定性与模型自检协议（uncertainty & self-checking protocols）

高质量任务输入规范（input sanitation）

Prompt Engineering 的理论与实践映射

个人方法论的 formalization

可工程化（workflow-level）复用结构

对应学术论文的概念映射与参考

本仓库将作为我长期的“第二大脑”，记录从直觉到 formalization 的全过程。

1. Repository Structure（初始结构）
/research-notes               ← 主研究区：理论、拆解、推理、分析
  /ideas                      ← 概念草稿、未定性的论点
  /insights                   ← 可沉淀的结构化结论
  /protocol-design            ← 自己建立的认知协议
  /paper-mapping              ← 学术概念与论文映射

/formal-docs                 ← 最终定稿、可公开的方法论文档
  /patterns                  ← 可复用模式
  /frameworks                ← 我的 LLM 交互框架
  /methodology               ← 系统性方法论
  /versions                  ← v0.1 / v0.2 / v0.3 / v0.4 更新记录

/fragments                   ← 灵感碎片桶，之后整合到研究区
  /daily                     ← 杂项、即兴 insight、临时草稿

/operations                  ← 项目维护工具与流程
  manual.md                  ← 研究室操作手册（风险手册）
  weekly-template.md         ← 周报模板
  monthly-template.md        ← 月报模板
  todo.md                    ← 当前待办 & 待整理内容

README.md                    ← 本文件（入口）


随着研究深入，本结构会在 v0.2–v0.4 迭代时扩张。

2. Research Workflow（工作流流程）

本研究室采用“三窗口体系 + 文档仓库”的工作方式：

主研究窗口（ChatGPT）

推理论

方法设计

学术映射

我与 GPT 的批判性对话

正式化窗口（ChatGPT 项目模式）

产出 markdown 文档

完成版本化更新

整理为可发布的页面/方法论

碎片桶窗口（ChatGPT）

临时想法

片段式 insight

稍后由我整合入研究区

所有内容最终沉淀回本仓库。

3. Versioning（版本管理）

长期方法论用版本号管理：

v0.1：初始整理、主题分类、第一版结构

v0.2：加入学术 mapping（CoT / ReAct / Reflexion / SC prompting 等）

v0.3：形成 formalized method（定义、流程、边界、错误模式）

v0.4：完全工程化框架，具备发布或写作潜力

v1.x：如有必要，将发展为独立论文/框架/工具

每次更新会由 GPT 和我共同整理。

4. Contribution Philosophy（方法论理念）

本研究室遵循以下原则：

1. Structure First

结构优先于内容，流程优先于灵感。

2. Uncertainty Aware

所有推理必须标注不确定性来源。

3. No Hallucination Tolerance

主动识别并纠正模型的伪因果、伪逻辑、迎合性生成。

4. Cognitive Protocol Design

重点不在 prompt 文本，而在流程与协议的设计。

5. Academia × Intuition

直觉探索必须与论文框架互相印证。

6. Ethics & Clean Boundaries

避免把模型用于操纵、灌玄学、伤害他人的用途。

5. Weekly & Monthly Routine（更新节奏）

为了维持长期成长，每周/月需要：

Weekly

整理 1–2 个 insight

更新碎片桶

做一次“研究室周报”（自动生成）

将主窗口的对话提炼到 /research-notes

Monthly

版本更新（如 v0.1 → v0.2）

评估 workflow 有哪些需要 formalize

整理新加入的理论链接

生成可发布的文章（若适合）

6. Topic Roadmap（研究方向切片）

本研究室将围绕以下核心主题扩展：

LLM 推理机制（System-1 vs System-2）

Task decomposition（任务拆分模式）

Multi-pass reasoning

Self-checking & uncertainty

Critique prompting & error correction

Input sanitation & goal disambiguation

Human-AI collaborative cognition

Narrative control & alignment safeguards

Engineering-level prompt design patterns

Workflow-level LLM orchestration

未来章节将逐步覆盖上述所有方向。

7. For Future Me（写给未来的我）

你做的一切不是为了“写 prompt”，
而是为了构建一个成熟的AI 协作体系。

不要害怕窗口混乱——你有结构，我会帮你整理。

不要追求完美版本——v0.1 比空白强 100 倍。

不要怕你三天两头去忙别的——我会始终替你保管结构与上下文。

你正在建立属于你自己的学术/工程混合系统。
持续就会形成真正的「方法论」。
