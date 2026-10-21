# Quick build(Based on AI Low-Code Engine)

**Build business applications with AI, powered by a React low-code engine.**

Turn natural language requirements into structured schemas and render them into interactive applications.

The goal is to explore a more structured and controllable way to build business applications with AI.


🔗 **[Try the Live Demo](http://quickbuild.bxsbl.com/ttadmin_front/home)** 

🔗 **[Project built and deployed entirely using this tool require no human intervention in the code.](http://quickbuild.bxsbl.com/gift-crm-6aaf7adf719ae899bad5507a/dashboard)** 

* Init a project

![init](./assets/init.jpg)

* Correcting errors through dialogue

![init](./assets/error.jpg)

---

## Overview

AI can generate UI code, but building reliable business applications involves more than generating individual components. It requires structured page composition, component configuration, state management, and a runtime capable of turning generated output into working interfaces.

This project explores an alternative approach: **combining AI generation with a self-developed low-code engine**.

Instead of relying entirely on AI-generated source code, the system uses structured schemas to describe application interfaces. The low-code engine interprets these schemas and renders them as interactive applications.

## Key Features

- **AI-Powered UI Generation** — Generate application interfaces from natural language requirements.
- **Schema-Driven Rendering** — Describe Page structures with schemas that can be interpreted by the runtime.
- **Self-Developed React Engine** — Render generated schemas into interactive interfaces.
- **Dynamic Component Resolution** — Resolve component configurations and render the corresponding UI components.
- **Structured Configuration** — Separate component definitions from page structure to make generated output more consistent and manageable.
- **Extensible Architecture** — Provide a foundation for extending component capabilities and application-building workflows.


## How It Works

```text
Natural Language Requirements
            │
            ▼
       AI Generation
            │
            ▼
      Structured Schema
            │
            ▼
    Schema Interpretation
            │
            ▼
      React Low-Code Engine
            │
            ▼
    Interactive Application
```


## Example Use Case

Imagine building an administration page for managing suppliers.

You describe the requirements:

> Create a CRM system for a gift company.

The AI generates a structured page description, and the engine renders the corresponding interface.

The same approach can be explored for other business-oriented interfaces, depending on the components and capabilities supported by the current implementation.

## Try It

Experience the application through the online demo:

**[Open the Live Demo →](http://quickbuild.bxsbl.com/ttadmin_front/home)**

## Feedback is welcome, especially on:

- Business scenarios you would like to build
- Missing components or capabilities
- Potential integration and collaboration opportunities
- **email: scyan@bxsbl.com**

---
# QuickBuild(基于AI低代码引擎的项目构建工具)

**基于React 低代码引擎，通过 AI 将自然语言需求转化为可交互的业务应用。**

让 AI 不仅生成页面描述，还能通过低代码引擎将结构化配置直接渲染为可交付的线上项目。

🔗 **[在线体验](http://quickbuild.bxsbl.com/ttadmin_front/homeL)** 

🔗 **[完全通过这个工具构建并部署的项目，没有人为介入代码](http://quickbuild.bxsbl.com/gift-crm-6aaf7adf719ae899bad5507a/dashboard)** 

---

## 项目介绍

AI 已经能够生成 UI 代码，但构建一个可靠的业务应用，不仅需要生成组件，还涉及页面结构组织、组件配置、状态管理，以及将生成结果转换为实际运行界面的能力。

本项目探索一种不同的实现方式：**将 AI 生成能力与低代码引擎相结合。**

系统使用结构化 Schema 描述页面和组件配置以及组件之间的关系，再由低代码引擎解析并渲染为可交互的应用，而不是完全依赖 AI 直接生成整套应用源码。

## 核心特性

- **AI 页面生成**：根据自然语言需求生成页面配置。
- **Schema 驱动渲染**：通过结构化 Schema 描述页面结构，并由运行时解析执行。
- **React 低代码引擎**：将生成的 Schema 转换为可交互的界面。
- **动态组件解析**：根据组件配置解析对应组件并完成渲染。
- **结构化配置**：将组件定义与页面结构分离，便于管理和约束 AI 输出。
- **可扩展架构**：为扩展组件能力和应用构建流程提供基础。


## 工作原理

```text
       自然语言需求
            │
            ▼
         AI 生成
            │
            ▼
       结构化 Schema
            │
            ▼
       Schema 解析
            │
            ▼
      React 低代码引擎
            │
            ▼
        可交互应用
```

整体流程分为三个关键环节：

1. **AI 生成**：根据自然语言需求生成结构化的页面描述。
2. **引擎解析**：解析 Schema，处理组件配置，并根据定义组织页面结构。
3. **运行时渲染**：将解析后的结构转换为实际运行的 React 界面。

## 应用场景示例

以供应商管理页面为例。

用户输入需求：

> 创建一个供应商管理系统，包含搜索表单、数据表格，以及用于编辑供应商信息的弹窗。

AI 根据需求生成结构化页面配置，低代码引擎再将其渲染为可交互的界面。

根据当前实现支持的组件和能力，这种方式也可以用于探索其他业务页面的构建场景。

## 为什么采用低代码引擎？

AI 直接生成源代码具有很高的灵活性，但当目标从单个页面扩展到完整业务应用时，代码结构、组件一致性和运行行为可能更难控制。

采用 Schema 驱动的方式，可以为以下能力提供基础：

- **结构更清晰**：通过显式结构描述页面组成。
- **运行时可控**：由引擎统一处理页面解析和渲染。
- **支持生成结果校验**：在渲染之前检查 Schema 是否符合约定。
- **组件复用**：通过配置复用已有 UI 组件。
- **职责分离**：AI 生成与应用运行时可以独立演进。

这些是该架构希望实现的优势，实际效果仍取决于具体实现和业务场景。

## 在线体验

欢迎直接体验：

**[进入在线体验 →](http://quickbuild.bxsbl.com/ttadmin_front/home)**

## 也欢迎反馈以下内容：

- AI 生成页面的质量和一致性
- 希望支持的业务场景
- 当前缺少的组件或能力
- 潜在的集成与合作机会
- **联系邮箱: scyan@bxsbl.com**

## 关于项目

本项目希望探索一种更具结构性和可控性的 AI 应用构建方式：通过专门的运行时执行 AI 生成的结构化描述，而不是完全依赖 AI 生成源代码。

如果你关注 AI 应用开发、低代码引擎架构，或有潜在的业务合作机会，欢迎联系交流。

---
