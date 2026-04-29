# Windows Polish Plan

This plan turns the WSL text-mode setup into a polished local JARVIS experience.

## Goal

- working text backend
- local Ollama model backend
- web graphics interface
- voice output
- desktop shortcut
- optional Chrome extension bridge

## Phase 1: Voice Output

Install the lightweight text-to-speech fallback packages inside the active Python virtual environment.

Recommended first target: Edge TTS, because it is easier to run on WSL than local neural TTS.

## Phase 2: Web Graphics

Run the backend/server mode and the Next.js UI. The cinematic interface should be available from Windows Chrome at localhost port 3000 once the UI is running.

## Phase 3: Shortcut

Create a Windows desktop shortcut that opens the local JARVIS web UI in Chrome.

## Phase 4: Voice Input

Voice input is harder on WSL because microphone passthrough may need Windows audio routing. Treat this as a second-pass improvement after UI and voice output are stable.

## Phase 5: Chrome Extension

Install the extension from the repository's extension folder using Chrome developer mode, then verify that it connects to the backend websocket.
