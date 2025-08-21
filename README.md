# Minigrid LLM Assistant Example

This example demonstrates using LLM assistants with Minigrid environments.

## Installation

```bash
# Install uv if you haven't already
curl -LsSf https://astral.sh/uv/install.sh | sh

# Install dependencies
uv sync
```

## Running the Example

For API-based LLM (Gemini):
```bash
uv run python web_app_Gemini.py
```

For local LLM:
```bash
uv run python web_app_Local.py
```