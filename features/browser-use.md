This file summarizes features from browser-use/browser-use repository for enabling AI agents to control and use web browsers. Key elements to reuse include:

- **Headless or visible browser automation**: Provides a library that wraps Selenium or Playwright to open web pages, click buttons, fill forms, scroll, and extract text. Supports both headless and interactive modes.
- **Action abstraction**: Defines high-level actions (navigate, click, type, scroll, wait for selector) that can be invoked by agents using natural-language commands. Allows agents to specify targets via CSS selectors or text.
- **Website accessibility**: Includes heuristics to interpret page structure and handle dynamic content, enabling agents to work on arbitrary websites without manual scripting.
- **Session and state management**: Maintains session context, cookies, and navigation history so the agent can perform multi-step tasks across pages.
- **Extensible tool APIs**: Exposes a Python API and CLI for controlling the browser; designed to be imported as a tool by AGI frameworks. Allows adding custom site-specific functions or plugins.
- **Error handling and retries**: Implements robust error catching, timeouts, and retries to handle page load failures, selectors not found, or network errors, improving reliability.
