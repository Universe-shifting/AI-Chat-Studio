# <img src="https://raw.githubusercontent.com/Universe-shifting/AI-Chat-Studio/refs/heads/main/ai_icon.png" width="30" height="30" />  AI Chat Studio <img src="https://raw.githubusercontent.com/Universe-shifting/AI-Chat-Studio/refs/heads/main/ai_icon.png" width="30" height="30" />

**A powerful, local desktop AI chat application powered by Pollinations.AI**

![AI Chat Studio Screenshot](https://raw.githubusercontent.com/Universe-shifting/AI-Chat-Studio/refs/heads/main/AIChatExample.png)

AI Chat Studio is a feature-rich, offline-first desktop application built with PyQt6 that lets you chat with advanced AI models from Pollinations.AI. It supports **text generation**, **image generation**, **vision/multimodal chats** (attach images/PDFs/docs), and even **local file management** — all in a beautiful, dark-themed interface.

This app works entirely locally (your chats and files stay on your machine) while leveraging the free, open Pollinations.AI API for powerful AI capabilities.

# <img src="https://raw.githubusercontent.com/Universe-shifting/AI-Chat-Studio/refs/heads/main/ai_icon.png" width="30" height="30" />  Key Features <img src="https://raw.githubusercontent.com/Universe-shifting/AI-Chat-Studio/refs/heads/main/ai_icon.png" width="30" height="30" />

- **Multi-model support**: Choose from top text models (Gemini, Claude, Grok, Mistral, Llama, etc.) and image models (Flux, Turbo, etc.)
- **Multimodal conversations**: Attach images, PDFs, DOCX, PPTX, or text files — the AI can "see" and discuss them
- **Image generation**: Switch to image mode and generate high-quality images directly in the chat
- **Local workspace**: Create, edit, view, and delete files right from the chat (AI can help write code/files)
- **Chat management**: Multiple chats, search, rename, export (JSON/Markdown), delete
- **Custom system prompts**: Edit the system prompt per chat for specialized assistants
- **Streaming responses**: Real-time typing effect with smooth scrolling
- **Attachment preview**: See thumbnails of attached images/files before sending
- **Drag & drop / paste support**: Easily add files or images from clipboard
- **No data leaves your device**: All files and chats stored locally

## Installation & Requirements

1. **Python 3.8+** required
2. Install dependencies:

```bash
pip install PyQt6 requests pypdf python-docx python-pptx
