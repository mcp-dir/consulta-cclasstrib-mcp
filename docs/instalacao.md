# Instalação detalhada

Consulta cClassTrib é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_consulta-cclasstrib`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_consulta-cclasstrib` | nenhuma (grátis) |
| Cursor | `https://api.mcp.ai/p_consulta-cclasstrib` | nenhuma |
| VS Code (Copilot) | `https://api.mcp.ai/p_consulta-cclasstrib` | nenhuma |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.consultacclasstrib` (ou `servers.consultacclasstrib` no VS Code) do config do cliente e reinicie.
