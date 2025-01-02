# Curiso.ai

Curiso.ai is an infinite canvas for your thoughts—a platform that seamlessly connects nodes and AI services to explore ideas in depth without repeating yourself. By guiding the direction of each conversation, Curiso.ai empowers advanced users to unlock richer, more accurate AI interactions. Created by Carsen Klock.

## Donate

If you find Curiso.ai useful, please consider donating to support its development.

Bitcoin (BTC) Address: bc1qgamupnnd2v0uj8a5cffyn8d25atahwq3wexue8

Solana (SOL) Address: FLXQhZgyNGgNzE7MEniiHkrh3bs8kfHjd4J1L7KgBWso

## Features

- **Infinite Canvas**: Create and organize your thoughts visually on an unlimited workspace
- **Multiple AI Provider Integration**:
  - OpenAI
  - Anthropic
  - Google
  - xAI
  - Groq
  - OpenRouter
  - Ollama
- **Custom Model Support**: Add and configure custom AI models
- **Multiple Boards**: Create and manage multiple workspaces
- **Vision Model Support**: Add images to your chats for vision models
- **Customizable Interface**:
  - Theme color selection
  - Grid snapping
  - Pan and zoom controls
  - Double-click zoom functionality
- **Node-Based Conversations**: Connect ideas and conversations through an intuitive node system
- **Secure**: Local encrypted storage of API keys and sensitive chat data

![screenshot](screenshot.png)
![screenshot2](screenshot2.png)

## Getting Started

### Prerequisites

- [Bun](https://bun.sh/) runtime installed on your system
- API keys for the AI services you plan to use or Ollama installed locally

### Installation

1. Clone the repository:

```bash
git clone https://github.com/metaspartan/curiso.git
```

2. Navigate to the project directory:

```bash
cd curiso
```

3. Install dependencies:

```bash
bun install
```

4. Run the development server:

```bash
bun run desktop
```

## Known Issues

- On Windows, you will get CORS errors when trying to connect to a local running Ollama instance. Run the command below in command prompt and restart Ollama to resolve this issue.

```bash
set OLLAMA_ORIGINS=*
```
