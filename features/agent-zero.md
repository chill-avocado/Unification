# Agent Zero

The **Agent Zero** project by mikekelly implements a minimalist autonomous agent for large language models. Key components to extract include:

- **Minimal agent loop** – a simple stateful loop that iteratively calls an LLM to reason about the next action, executes the action using tools, and updates the context and memory.
- **Tool interface** – defines a small API for adding tools (functions) that the agent can call; allows easy extension with new skills.
- **Conversation memory** – stores the chat history and tool outputs so the LLM can take actions based on context.
- **Plan and execution structure** – the agent generates a plan, executes tasks sequentially, and updates the plan based on outcomes and new information.
- **Extensibility** – despite being minimal, the architecture is modular enough to integrate additional tools, memory stores, or reasoning strategies.
