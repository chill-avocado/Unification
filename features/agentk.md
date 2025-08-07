# AgentK

The **AgentK** project introduces a modular AGI framework where autonomous agents can reason, plan and act. Important elements to reuse include:

- **Modular agent architecture** – multiple agent modules coordinate through a central planner, allowing specialized behaviours (e.g. coder, planner, critic) to collaborate on tasks.
- **Self‑improvement loop** – agents evaluate their own outputs and refine plans, enabling iterative improvement and error correction.
- **Plugin-based tools** – tasks are executed via pluggable tools that encapsulate capabilities like web search, file operations, code execution, etc.
- **Memory and context management** – shared memory stores context, goals and intermediate results so agents can access and update the task state.
- **Extensible design** – adding new agent roles or tools is straightforward, making it easy to expand the system’s abilities.
