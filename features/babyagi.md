# BabyAGI

The `BabyAGI` repository implements a minimal task-driven autonomous agent. Key features include:

- **Task creation and prioritization** – generates new tasks based on the result of previous tasks and a main objective, and prioritizes them using a simple algorithm.
- **Loop architecture** – cycles through tasks, executes them using an LLM and optionally a vector store for memory, and creates more tasks until the objective is met.
- **Memory integration** – can store and retrieve context from a vector database such as Pinecone or Chroma to maintain continuity.
- **Modular components** – designed to be simple and extensible, enabling developers to swap the LLM, memory backend, or task prioritization method.
- **Example usage** – includes sample scripts and instructions for running the agent with different LLMs and vector stores.
