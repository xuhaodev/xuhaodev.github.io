---
title: "Vibe Coding Tips and Tricks"
date: 2025-04-02 12:00:00 +0000
categories: 
  - Tips and Tricks
tags: 
  - Tips and Tricks
---
Reflections after 30 days of using GitHub Copilot Agent.

My vibe coding project: [Agentic AI Apps](https://haxu.dev/) live App. And code is here -> [GitHub Repo](https://github.com/xuhaodev/agentic-ai-app)
This project is a modern demonstration and experimental application of AI agents. It features a variety of agent types, including Instruction Agents, Function Call Agents, Workflow Agents, and MCP Agents.
The project contains over 60 code files and uses a distributed deployment approach. The entire application development process was driven by me providing requirements in natural language, while GitHub Copilot Agent handled the coding.

**Technology Stack**:
**Framework**: Next.js, Typescript, Python, Tailwind CSS， Copilotkit, Langchain
**AI Models**: GPT-4o, GPT-4o-mini, GPT-o3-mini, Deepseek v3, Deepseek-r1 from GitHub Models and Azure OpenAI
**Deployment**: Azure Web Apps, Azure Function, Azure container registry, GitHub Action

### Transformations We Must Embrace Today:

- Embrace abstraction rather than getting lost in details.
- Focus on solving problems rather than controlling every aspect.
- Pursue continuous iteration rather than achieve success in one go.
- Achieve rapid usability rather than striving for flawless polish.

### Learn from the journey

- Precise requirement descriptions and industry-specific terminology remain crucial.
- Use modern frameworks following the principles of low coupling and high cohesion; aim to keep each file under 1,000 lines.
- As projects grow, focus on editing individual files rather than having an agent process the entire codebase.
- Consistency can be challenging, so implementing an effective undo mechanism and rollback strategy is essential.
- Version control is vital—always maintain a stable version before iterating.
- In AI agent programming, every element (file names, comments, strings, variable names, function names) provides important context.
- When runtime failures occur, the model might generate extensive check outputs; however, the root cause could lie elsewhere.
- Providing models with references and examples is equally important.
- Be cautious when requiring an agent to perform refactoring; ensure the scope is well-defined.
- Sometimes, knowing when to abandon a nonproductive approach is more important than persisting indefinitely.
- Allow agents to run tests, including unit tests and UI tests.
- AI agent development should avoid any human path dependencies.
- Embrace a "vibe coding" approach and continuous deployment—prioritize practical, functional solutions over excessive detail orientation.

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
- Agent的世界来不得半点路径依赖。
- Vibe coding，持续部署，能用就是好的。
- 克制自己深入细节。
