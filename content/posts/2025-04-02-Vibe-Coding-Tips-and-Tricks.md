---
title: "Vibe Coding Tips and Tricks"
date: 2025-04-02 12:00:00 +0000
categories: 
  - Tips and Tricks
tags: 
  - Tips and Tricks
---
Reflections after 30 days of using **GitHub Copilot Agent**.

My vibe coding project: live App **[Agentic AI Apps](https://haxu.dev/)**. And code repo -> **[Agentic AI Apps Repo](https://github.com/xuhaodev/agentic-ai-app)**

This project is a demonstration and experimental modern application of AI agents. It features a variety of agent types, including **Instruction Agents**, **Function Call Agents**, **Workflow Agents**, and **MCP Agents**.

The project contains **over 60 code files** and uses a **distributed deployment approach**. The entire application development process was driven by me providing requirements in **natural language**, while **GitHub Copilot Agent** handled the coding.

#### **Technology Stack**:

- **Framework**: Next.js, Typescript, Python, Tailwind CSS, Copilotkit, Langchain
- **AI Models**: GPT-4o, GPT-4o-mini, GPT-o3-mini, Deepseek v3, Deepseek-r1 from GitHub Models and Azure OpenAI
- **Deployment**: Azure Web Apps, Azure Function, Azure container registry, GitHub Action, Supabase

### Transformations We Must Embrace Today:

- Embrace abstraction rather than getting lost in details.
- Focus on solving problems rather than controlling every aspect.
- Pursue continuous iteration rather than achieve success in one go.
- Achieve rapid usability rather than striving for flawless polish.

### Learn from the journey

- **Precise Descriptions**: Clear and accurate prompts are essential, as is dev framework terminology.
- **Adopt Modern Frameworks**: Prioritize modern frameworks and adhere to the principles of low coupling and high cohesion. Limit each file to no more than 1,000 lines.
- **Agent or Edits**: As the project gets larger, it is actually the selection file that carries the Edits more than the Agent for the entire codebase.
- **Consistency with Rollback Strategies**: Inconsistencies may arise in larger projects, making 'undo' functionality and strong rollback strategies indispensable.
- **Start from Workable**: Version control is important, keep a workable version before iterating.
- **Context Matters for AI Agents**: File names, comments, strings, variables, and function names all serve as critical context for AI-driven programming.
- **Agent Wrong or Human Wrong?**: The model keeps increasing the check output when the run fails, but it is possible that the problem lies elsewhere.
- **Provide Sufficient and Useful Example**: Providing Agent with well-designed examples and meaningful references greatly improves their performance.
- **Controlled Refactoring by Agents**: Be cautious when assigning refactoring tasks to agents. Clearly define and limit the scope of changes.
- **Know When to Let Go**: Recognize when abandoning an unproductive approach is more efficient than persisting with repeated attempts.
- **Use AI to Test AI**: Let the agent do the testing, unit test yes, UI test also.
- **"It Works" is Top Priority**: Prioritize continuous deployment and functional utility over well prepare. If it works, it’s good enough.
- **Avoid Path Dependency**: Vibe Coder to try to avoid path dependency in thinking and methodology.
- **Free Yourself**: Vibe Coder should avoid getting caught up in unnecessary details or overly dwelling on insignificant matters.

===

### 今天我们需要做出改变：

- 理解抽象，而不是沉溺细节
- 解决问题，而不是掌控全程
- 不断迭代，而不是一蹴而就
- 快速可用，而不是完美打磨

### Vibe coding 心得体会

- 精准描述需求的提示词仍然很重要，开发和框架术语也很重要。
- 尽量使用现代的框架，低耦合高内聚原则，每个文件不要超过1000行。
- 项目规模变大后，实际是选择文件进行Edits要多于整个codebase的Agent。
- 一致性可能会出现问题，undo很重要，做好roll back策略。
- 版本控制很重要，保持一个可用版本，再进行迭代。
- 面向AI Agent 编程，文件名，注释，字符串，变量名，函数名皆是上下文。
- 运行失败时，模型会不断增加check输出，但有可能问题出在其他方面。
- 给模型提供参考和示例也同样重要。
- 要求Agent重构需谨慎，范围需要控制。
- 及时放弃有时候比不断尝试更重要。
- 让agent来做测试，unit test是，UI test也是。
- Vibe coding，持续部署，能用就是好的。
- Vibe Coder要尽量避免思维和方法论上的路径依赖。
- Vibe Coder要克制自己陷入细节和计较无所谓的东西。
