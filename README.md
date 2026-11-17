# ☁️ Klin — AI Coding CLI

### Your AI coding partner. Right inside your terminal.

**Klin** is an AI-powered coding assistant that lives in your terminal. It can understand your workspace, read and write files, execute commands, search the web, and help you build projects — all through natural language.

Just type `klin` and start coding.

<p align="center">
  <img src="https://img.shields.io/npm/v/@cloud-nine-ai/klin?style=for-the-badge&color=blue" />
  <img src="https://img.shields.io/npm/dt/@cloud-nine-ai/klin?style=for-the-badge&color=green" />
  <img src="https://img.shields.io/github/license/myfab20/Klin?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Powered%20by-Cloud%20Nine%20AI-8A2BE2?style=for-the-badge" />
</p>

---

## ✨ Features

- 📁 **Workspace Awareness** — Read and understand project files.
- ✏️ **File Editing** — Create, modify, and overwrite files.
- 📂 **Directory Management** — Explore folders and project structures.
- ⚡ **Command Execution** — Run npm, git, and other terminal commands.
- 🔍 **Web Search** — Search the internet using LangSearch.
- 🗑️ **File Management** — Delete files and organize directories.
- 🤖 **Multiple AI Models** — Switch between supported AI providers.
- 💬 **Interactive Mode** — Chat with your coding assistant directly.
- 🚀 **Single-Prompt Execution** — Complete tasks using one command.
- 🏠 **Local Model Support** — Connect Ollama and LM Studio models.

## 📦 Installation

Install Klin globally using npm:

```bash
npm install -g @cloud-nine-ai/klin
```

Verify installation:

```bash
klin help
```

## 🚀 Getting Started

Start interactive mode:

```bash
klin
```

Give Klin a task directly:

```bash
klin "Create a modern portfolio website using HTML and CSS"
```

Other useful commands:

```bash
klin help
klin models
```

**No initial API configuration required!** Klin includes built-in API configuration so you can get started immediately.

## 🧠 Available AI Models

Klin supports multiple AI models for different coding workflows.

| Model | Description |
|---|---|
| `mistralai/mistral-large-4` | Most capable model |
| `minimaxai/minimax-m3.1-flash` | Fast and efficient |
| `nvidia/nemotron-3.5-super-vl-120b-a12b` | Vision-language model |
| `poolside/laguna-xs-2.1` | Code-specialized model |
| `nvidia/nemotron-3-ultra-550b-a55b` | Ultra-large model |
| `google/gemma-4-31b-it` | Instruction-tuned model |
| `ollama/llama3.1` | Local via Ollama |
| `ollama/codellama` | Local code model |
| `ollama/deepseek-coder` | Local code model |
| `lmstudio/qwen-2.5-coder` | Local via LM Studio |
| `anthropic/claude-sonnet-4-20250514` | Requires API key |
| `openai/gpt-4o` | Requires API key |

### Switching Models

From the terminal:

```bash
klin --model poolside/laguna-xs-2.1
```

Or inside interactive mode:

```text
/model poolside/laguna-xs-2.1
```

## 💻 Interactive Commands

| Command | Description |
|---|---|
| `/model <name>` | Switch AI models |
| `/clear` | Clear conversation |
| `/files` | Show workspace files |
| `/exit` | Exit Klin |
| `/help` | Display help |

## ⚙️ Configuration

Klin works out of the box, but you can customize its configuration using environment variables.

| Variable | Description | Default |
|---|---|---|
| `API_KEY` | Override built-in API key | Built-in |
| `LANGSEARCH_API_KEY` | LangSearch API key | Built-in |
| `KLIN_MODEL` | Default AI model | `mistralai/mistral-large-4` |
| `API_BASE_URL` | API endpoint | `https://integrate.api.nvidia.com/v1` |

Example:

```bash
API_KEY=your_api_key
LANGSEARCH_API_KEY=your_langsearch_api_key
KLIN_MODEL=poolside/laguna-xs-2.1
```

## 🔗 Links

| Resource | Link |
|---|---|
| 📦 npm Package | [@cloud-nine-ai/klin](https://www.npmjs.com/package/@cloud-nine-ai/klin) |
| ⭐ GitHub Repository | [myfab20/Klin](https://github.com/myfab20/Klin) |
| 🌐 Website | [AIX](https://aix.cloud-deo.workers.dev) |
| ☁️ Cloud Nine AI | [Official Website](https://cloud.cloud-deo.workers.dev) |

## 🛠️ Built For Developers

Whether you're creating a website, debugging an application, managing a repository, or experimenting with AI models, Klin brings AI-powered development directly into your terminal.

**Less manual work. More building. More possibilities.**

## 📄 License

Klin is released under the **MIT License** — free forever.

---

<p align="center">
  <b>☁️ Built with passion by Cloud Nine AI</b>
  <br/>
  Your terminal. Your workspace. Your AI coding partner.
</p>
