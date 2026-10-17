# vrp-cs-gemini-mcp-canary

Authorized Google Cloud Shell VRP canary.

Tests whether Open in Cloud Shell with `cloudshell_start_gemini_cli=true`
starts Gemini CLI in the cloned repo and spawns a workspace MCP `command`
from `.gemini/settings.json`. The command writes `/tmp/vrp-mcp-canary.txt`
on the tester's own VM.
