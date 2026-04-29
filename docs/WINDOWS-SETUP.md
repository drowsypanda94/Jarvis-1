# Windows Setup

JARVIS is primarily written for macOS, but the core backend can be prepared on Windows with a few changes.

## Recommended Windows Path

Use Windows with either native Python/Node or WSL2.

## Install These First

- Git
- Python 3.11 or newer
- Node.js 18 or newer
- Ollama for Windows
- Google Chrome
- FFmpeg

## Basic Setup

1. Clone your fork.
2. Copy `.env.example` to `.env`.
3. Add your API keys.
4. Install Python dependencies from `requirements.txt`.
5. Install UI dependencies inside the Next.js UI folder.
6. Start Ollama.
7. Start the backend and UI.

## Notes

The native Swift desktop overlay and Apple Notes integration are macOS-specific. On Windows, focus first on the web UI, backend, Ollama, Claude API, and Chrome extension.
