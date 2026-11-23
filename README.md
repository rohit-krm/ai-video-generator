# Srijan Motion Studio

A lightweight, privacy-first AI video generation web app supporting **Image-to-Video** and **Text-to-Video** workflows powered by Hugging Face ZeroGPU Spaces.

## Features
- **BYOK (Bring Your Own Key):** Users enter their personal Hugging Face Access Token (`hf_...`), saved locally in `localStorage`. Zero server-side quota abuse.
- **Dual Modes:** Instant switching between Image-to-Video and Text-to-Video.
- **Prompt Vault:** Save reusable motion/style prompts locally for one-click generation.
- **Zero-Build Deployment:** Pure HTML/CSS/JS using `@gradio/client` ESM module.
