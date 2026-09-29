# Rules for this session
- Python 3.11+, packages: httpx, pydantic, python-dotenv, typer, rich, pillow, pytest. Ask before adding
others.
- Read PLAN.md for the goal. Keep changes small: one function or one file per request unless I ask for more.
- Small typed functions; no classes unless state is needed; no frameworks beyond the list.
- API: OpenRouter, base URL https://openrouter.ai/api/v1, key from env OPENROUTER_API_KEY via python-dotenv.
Never print or hard-code the key.
- Never swallow exceptions silently; record errors per item.
- Do NOT run commands that call paid APIs (image generation, batches) without asking me first.
- Model IDs are CLI options, never constants buried in code.