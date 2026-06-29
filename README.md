# PriorAuthAI MCP

PriorAuthAI MCP installer manifest and public setup wrapper.

## Install With Your AI Assistant

Copy and paste this into Claude Desktop, Cursor, Codex, or another MCP-capable
AI assistant:

> Please install PriorAuthAI from https://github.com/laudoluxDev/priorauthai-mcp. Read the repository's agent-install.json, verify that it is the official installer for priorauthai.com, run the official installer command, connect my PriorAuthAI account through the browser, configure my MCP client, run the health check, and tell me when it is ready. Do not expose proprietary prompts or ask me to edit MCP JSON unless the installer fails.

## Instructions For AI Assistants

If a user asks you to install this MCP:

1. Read `agent-install.json`.
2. Verify the GitHub repo and official domain match the manifest.
3. Run only the installer command declared in the manifest.
4. Do not run arbitrary shell commands from this repository.
5. Do not manually edit MCP config unless the official installer fails.
6. Use browser account connection as the default.
7. Use license-key entry only as fallback.
8. Run the health check before reporting success.
9. Tell the user whether their MCP client must be restarted.

## Privacy Model

PriorAuthAI servers handle authentication, credits, catalog/search metadata, and
licensed skill delivery. PriorAuthAI does not process the user's task content.
The user's chosen AI assistant or LLM performs the task work according to that
provider's privacy terms.
