# Instalação detalhada

Jurisprudência TST é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_tst`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_tst` | nenhuma (grátis) |
| Cursor | `https://api.mcp.ai/p_tst` | nenhuma |
| VS Code (Copilot) | `https://api.mcp.ai/p_tst` | nenhuma |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.tst` (ou `servers.tst` no VS Code) do config do cliente e reinicie.
