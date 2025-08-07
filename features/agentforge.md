# AgentForge

The **AgentForge** project is an extensible AGI framework designed for building autonomous agents. Key components include:

- **Core agent engine** – orchestrates planning, tool invocation and memory updates while interacting with LLMs.
- **Plugin architecture** – allows adding tools (APIs, browsers, filesystems) via a simple interface; includes built-in connectors for web search, code execution and database access.
- **Memory and vector stores** – persists task context, conversation history and embeddings to support long-term reasoning.
- **Multi-agent support** – can coordinate multiple agents with different roles and shared memory to tackle complex tasks.
- **User interface** – provides CLI and web interfaces for configuring agents, tracking progress and managing credentials.
