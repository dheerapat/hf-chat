# Hugging Face Chat UI

Docker compose file to quickly setup ChatGPT style chat ui using [chat-ui](https://github.com/huggingface/chat-ui) project from Hugging Face

You can use any LLM provider API that support OpenAI style API endpoint (llama.cpp, openrouter, lmstudio), just make sure `/models` and `/chat/completion` endpoint is working.

Suppose you already in this repository and have Docker running

```bash
# edit api endpoint and API key in the compose file first

docker compose up -d
```