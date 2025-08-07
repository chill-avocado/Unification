# Feature: open-webui

This file outlines the pieces of the `open-webui` project to extract for our unified AI agent framework.

## Source Repository
`open-webui/open-webui`

## Key Components to Reuse

- **Web-based UI** – User-friendly interface built with modern JavaScript/TypeScript frameworks to interact with local or remote language models.
- **Chat interface** – Clean chat and prompt inputs that support streaming model responses and conversation history.
- **Model management** – Infrastructure to select and configure different back-end providers (Ollama, OpenAI, local LLMs).
- **Session handling** – Support for multiple sessions, conversation state, and persistent history.

These components will inform the UI layer of the unified project. We will reuse UI elements, layouts, and state management patterns, adapting them to our modular architecture.
