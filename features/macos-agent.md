# MacOS‑Agent

The **MacOS‑Agent** project is a lightweight assistant for automating tasks on macOS. Key elements to reuse include:

- **Mac automation layer** – uses AppleScript and system commands to control applications, open files, search Spotlight, and manage system settings.
- **Natural‑language interface** – interprets user instructions via an LLM and maps them to corresponding Mac actions.
- **Tool wrappers** – exposes common actions (open app, search web, play media) as reusable functions for the agent.
- **Extensible command set** – allows adding new AppleScript or shell commands to support additional macOS features.
- **Safety mechanisms** – includes confirmation prompts or permission checks to prevent unintended system changes.
