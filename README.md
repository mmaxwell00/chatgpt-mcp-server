# ChatGPT MCP Server

A minimal MCP server that connects to your ChatGPT account via OpenAI API.

## Setup

1. Install dependencies:
```bash
npm install
```

2. Set your OpenAI API key:
```bash
export OPENAI_API_KEY="your-api-key-here"
```

3. Add to Kiro CLI:
```bash
/mcp add chatgpt-server node /Users/mmaxwell/chatgpt-mcp-server/index.js
```

## Usage

Once added, you can use the `@chatgpt-server/chat_with_gpt` tool to send messages to ChatGPT.

## Tools

- `chat_with_gpt`: Send a message to ChatGPT and get a response
  - `message` (required): The message to send
  - `model` (optional): GPT model to use (default: gpt-4)