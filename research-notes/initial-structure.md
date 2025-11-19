# Initial Structure — Research Notes (v0.1)

本文件是研究区（research-notes）的初始草图，用于：  
- 明确未来研究路线  
- 梳理初始问题空间  
- 确定需要拆解的方向  
- 记录从直觉 → 理论 → formalization 的早期阶段

内容本身会在 v0.2–v0.3 中进一步被迁移到 formal-docs 或拆分成更细的结构。

---

## 1. The Three Core Problems（核心研究问题）

### **1.1 如何让 LLM 的推理更稳？**
- 多阶段推理（multi-pass）
- 任务分解（task decomposition）
- 错误定位（self-reflection）
- 不确定性识别（uncertainty detection）

### **1.2 如何让 LLM 输出更“工程化”？**
- 输入规范（input sanitation）
- 工作流协议（workflow protocols）
- 结构化输出（structured generation rules）
- 多步反思（critique + rewrite）

### **1.3 如何 formalize 自己的直觉？**
- 把经验拆成步骤  
- 把流程变成 protocol  
- 把 protocol 变成 reproducible pattern  
- 把 pattern 写成 methodology  

---

## 2. Draft Structure（草稿结构）

未来可能拆解为十几个正式模块，这里是草图：

### **A. Cognitive Protocols**
- CoT vs ReAct 的选择条件  
- Multi-pass decision pipeline  
- Uncertainty-first prompting  
- Critique → verify → rewrite pipeline  

### **B. Workflow Patterns**
- General task template  
- Ill-defined task clarification pattern  
- Input sanitation rules  
- Thought-visibility protocols （让模型展示推理链路）  

### **C. Error Framework**
- 常见 hallucination 模式  
- 诱因分类  
- 任务复杂度 × 模型错误概率 mapping  
- 自检 prompts 的结构  

### **D. Human-AI Collaboration**
- 人类在 loop 中的角色  
- 分工边界  
- “当人何时介入”  
- 如何利用模型生成 meta-instructions  

---

## 3. Future Branches（未来方向）

这些将成为后续版本的新增目录或 pattern：

- LLM 推理行为的分类学（taxonomy）
- 任务类型体系（task typology）
- Prompt-engineering 理论化映射
- 专家模式的协议（expertise emulation protocols）
- 安全边界（safety-aware workflow）

每个部分都会经历：  
**idea → notes → insights → protocol → formal-docs**

---

## 4. Current TODO（下一步行动）

- [ ] 按照 weekly 模板开始记录  
- [ ] 整理碎片桶窗口的初始内容  
- [ ] 建立 paper-mapping 目录（等读论文后自动填充）  
- [ ] 初步草拟 “Task Decomposition Framework v0.1”  
- [ ] 为 uncertainty protocol 写第一个草图  
- [ ] 形成 v0.2 的路线图  

---

## 5. Philosophy（理念）

这里保留一些早期思想：

- 结构比灵感更重要  
- 模型的错误其实可以预测  
- 任务拆解是一种 cognitive engineering  
- prompt 不是命令，而是协议（protocol）  
- “LLM 不是工具，而是协作者”  

这些想法将在未来 formalize。

---

## 6. Notes（零散想法）

- 人类推理的 uncertainty 感应比模型强得多  
- 模型的缺点全都能通过 workflow 修补  
- Prompt engineering 本质是“控制信息流”  
- 所谓“人类直觉”其实能转换成 protocol  
- 不同任务需要不同 chain-of-thought 结构  

这些会在后续版本拆解。

---

*This file is expected to evolve quickly. Many sections will migrate to formal-docs when stabilized.*
