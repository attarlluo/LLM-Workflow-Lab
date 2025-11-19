# Protocol Design — 认知协议设计区（v0.1）

本目录用于构建 LLM 协作方法的核心“协议（protocols）”。  
协议是比 prompt 更高层级的结构化交互设计。

典型协议包括：

### 1. 推理协议（Reasoning Protocols）
- 多阶段推理（multi-pass reasoning）  
- 思维可见性协议（thought-visibility）  
- 推理链结构（chain-of-thought variants）  

### 2. 不确定性协议（Uncertainty Protocols）
- 置信度评分  
- 不确定性优先（uncertainty-first prompting）  
- critique → verify → rewrite 链路  

### 3. 任务澄清协议（Task Disambiguation）
- 明确输入需求、目标、上下文  
- 任务类型识别（task typing）  

### 4. 专家模拟协议（Expertise Emulation）
- 多专家协作（multi-expert structure）  
- 风格/知识域模拟  

### 5. 工作流级协议（Workflow Protocols）
- 输入规范（input sanitation）  
- 分层架构（layered orchestration）  
- 模型自检与循环校验（self-checking loops）  

随着研究深入，这里的文件将从 idea → draft → stable → formal-docs 逐步迁移。

该目录是整个研究体系的核心。
