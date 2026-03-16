# rt-translator-desktop

![Rust](https://img.shields.io/badge/Rust-000?style=flat-square&logo=rust&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-24C8D8?style=flat-square&logo=tauri&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

Desktop application for real-time multilingual meeting translation. Runs entirely offline using local AI models.

## Features

- Real-time speech-to-text with Whisper.cpp
- Multilingual translation via Ollama LLM
- Live caption overlay during meetings
- Transcript export (text/markdown)
- Fully offline — no data leaves your machine

## Tech Stack

- **Desktop**: Tauri (Rust backend)
- **Frontend**: React + TypeScript
- **Speech-to-Text**: Whisper.cpp (local)
- **Translation**: Ollama LLM (local)

## Prerequisites

- [Whisper.cpp](https://github.com/ggerganov/whisper.cpp) installed
- [Ollama](https://ollama.ai) with a translation-capable model

## Getting Started

```bash
npm install
npm run tauri dev
```

### Build

```bash
npm run tauri build
```

## License

See [LICENSE](./LICENSE) for details.
