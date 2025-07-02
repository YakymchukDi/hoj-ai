# LLM Integration

The assistant should support a wide variety of local and online LLMs:

## ✅ Supported Models

- OpenAI GPT (GPT-3.5, GPT-4)
- Claude (Anthropic)
- Gemini (Google)
- Mistral, Mixtral
- Meta LLaMA 3
- Qwen (Alibaba)
- Gemma (Google)
- Local models via Ollama, LM Studio, etc.

## 🔌 Switching between models

Users should be able to dynamically switch models depending on:

- Speed
- Local vs Cloud preference
- Accuracy
- Privacy

## 🧩 Plugin Architecture

LLM access should use a modular plugin system:

- Easy to add/remove models
- Secure API key storage
- Token usage monitor
