# AI-Agentic-Design-Patterns-with-AutoGen

Welcome to **[AI Agentic Design Patterns with AutoGen](https://www.deeplearning.ai/short-courses/ai-agentic-design-patterns-with-autogen/)**, a course designed to teach you how to build and customize sophisticated multi-agent systems. Using AutoGen, a powerful open-source framework from Microsoft, you will move beyond single large language models (LLMs) and learn to create collaborative teams of AI agents. Each agent can be assigned a unique role, enabling them to work together to solve complex problems, from generating creative content to performing detailed financial analysis. This course provides a hands-on journey through the most effective design patterns for orchestrating these agentic workflows, empowering you to build more capable and autonomous AI applications.

## 📚 Course Topics Explained

### **1. Multi-Agent Conversation with Stand-Up Comedy**

This introductory module presents the foundational concept of multi-agent systems using AutoGen’s `ConversableAgent`. You will learn how to:

* Instantiate multiple agents with unique personalities and roles
* Define system messages to guide agent behavior
* Initiate and manage interactive conversations between agents

To make learning engaging, the practical exercise involves two AI agents acting as stand-up comedians. Each agent will generate jokes, react to punchlines, and engage in a collaborative, turn-based dialogue. This example highlights the core mechanics of agent-to-agent communication and demonstrates how specialized agents can work together to achieve a creative goal.

---

### **2. Sequential Chats for Customer Onboarding**

This section introduces the *sequential collaboration* design pattern, where agents operate in a predefined order rather than a free-form conversation.

You will build a playful customer onboarding flow for a fictional product, using a series of specialized agents:

* **Welcomer Agent** – greets the user
* **Feature Explainer Agent** – introduces product benefits
* **Setup Guide Agent** – provides initial steps to get started

This structured approach teaches you how to orchestrate agent interactions to follow a specific workflow, ensuring consistency and control throughout the user experience.

---

### **3. Agent Reflection and Blog Post Writing**

This module explores the *reflection-based* design pattern using a nested chat structure. You will build a collaborative writing system involving multiple agents:

* A `WriterAgent` generates an initial blog post draft.
* A `CriticAgent` coordinates a team of `ReviewerAgents` focused on specific aspects (e.g., technical accuracy, tone, grammar).
* Feedback is synthesized by the `CriticAgent` and returned to the `WriterAgent` for revision.

This iterative process models high-quality content generation through feedback and self-correction, demonstrating how agents can collaborate to improve output over multiple cycles.

---

### **4. Tool Use with Conversational Chess**

In this section, you will learn how to extend agent capabilities through *tool use*—allowing agents to execute external functions or code.

You’ll implement a conversational chess game where:

* Two agents play chess by communicating their moves
* Moves are validated via a registered Python function ("chess tool")
* Game state is updated in real time based on valid moves

This hands-on exercise demonstrates how to register user-defined functions with agents, enabling them to make grounded, rule-based decisions in dynamic environments.

---

### **5. Coding Assistance and Financial Analysis**

This topic focuses on applying agents as intelligent coding assistants for data analysis tasks. You will build a system in which an agent:

* Solves a financial problem by analyzing and visualizing stock data
* Writes and executes Python code using libraries like `matplotlib` and `yfinance`
* Debugs its own code when errors occur
* Incorporates pre-written functions into its workflow

The key takeaway is understanding how to empower agents with programmatic capabilities, making them valuable in solving technical problems efficiently and accurately.

---

### **6. Planning and Collaborative Stock Report Generation**

In this advanced module, you’ll orchestrate a team of agents to complete a multi-step task: generating a comprehensive stock performance report.

The agent team includes:

* A `PlanningAgent` that breaks down the request (e.g., "Analyze MSFT stock") into logical steps
* A `CoderAgent` and `DataAnalystAgent` that carry out specific tasks (e.g., fetch data, calculate metrics, generate visuals)
* Customized transition logic to manage the conversational flow efficiently

This section demonstrates how to build a fully coordinated, multi-agent system capable of solving complex, structured problems through planning, task delegation, and cooperative execution.

---

## Acknowledgement

This course, **[AI Agentic Design Patterns with AutoGen](https://www.deeplearning.ai/short-courses/ai-agentic-design-patterns-with-autogen/)**, is provided by **[DeepLearning.AI](https://www.deeplearning.ai/)** in collaboration with **[Microsoft](https://www.microsoft.com/en-us/research/)** and **Penn State University**.
