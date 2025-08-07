# Unification

This repository aggregates various autonomous‑agent frameworks and tools.  The `features` directory (from the original repository) contains descriptions and analyses of different frameworks, while the root now includes compressed archives of several open‑source projects.  Each archive was created on **August 7 2025** and, where necessary, split into chunks under 100 MB to comply with GitHub’s upload limits.

## Compressed packages

The following archives are included in this repository:

- `AGI-Samantha.tar.gz` – Archive of the AGI‑Samantha framework
- `AgentForge.tar.gz` – Archive of the AgentForge framework
- `AgentGPT.tar.gz` – Archive of the AgentGPT project
- `Auto-GPT-MetaTrader-Plugin.tar.gz` – Archive of the Auto‑GPT MetaTrader Plugin
- `Free-Auto-GPT.tar.gz` – Archive of the Free‑Auto‑GPT project
- `LocalAGI.tar.gz` – Archive of the LocalAGI project
- `SuperCoder.tar.gz` – Archive of the SuperCoder toolkit
- `agent-zero.tar.gz` – Archive of the agent‑zero project
- `babyagi.tar.gz` – Archive of the BabyAGI project
- `browser-use.tar.gz` – Archive of the browser‑use project
- `open-interpreter.tar.gz` – Archive of the Open‑Interpreter project
- `open-webui.tar.gz.part000`, `open-webui.tar.gz.part001` – Split archive of the Open WebUI project. Download all parts before extracting.
- `pyCodeAGI.tar.gz` – Archive of the pyCodeAGI project
- `senpai.tar.gz` – Archive of the Senpai project
- `web-ui.tar.gz` – Archive of the Web‑UI project
 - `automata-full-automata.tar.gz` – Archive of the Automata project (full‑automata branch)

## Extracting split archives

To extract a split archive such as `open-webui.tar.gz`, first concatenate the parts and then decompress:

```bash
cat open-webui.tar.gz.part* > open-webui.tar.gz
mkdir open-webui && tar -xzf open-webui.tar.gz -C open-webui
```