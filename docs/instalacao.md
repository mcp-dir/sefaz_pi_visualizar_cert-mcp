# Instalação detalhada

SEFAZ PI Visualizar certidões CNDA: CND é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_sefaz_pi_visualizar_cert`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_sefaz_pi_visualizar_cert` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_sefaz_pi_visualizar_cert` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_sefaz_pi_visualizar_cert` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.sefaz_pi_visualizar_cert` (ou `servers.sefaz_pi_visualizar_cert` no VS Code) do config do cliente e reinicie.
