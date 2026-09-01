# Jurisprudência TST

### Brazilian labour court (TST) case law for Claude, Cursor and AI agents

Search labour case law from the **TST**, the last word on employment matters in Brazil. Beyond rulings, the TST guides through binding summaries and jurisprudential orientations, which is what actually steers the lower instances, and the search covers all three. Free, no login, hosted by the platform.

- ⚖️ **TST** plus 16 other Brazilian courts on the same connection
- 🎯 **The snippet that actually MATCHED**, not the boilerplate opening every ruling shares
- 🔗 **Link to the official court site** on every result
- 📄 **Full text on demand** where the ruling allows it
- 🚦 **Says when it does not know**: an unavailable source becomes an explicit notice, never an unexplained blank
- 🔒 **Read-only**
- ⚡ **Free, no login, no credentials**
- 💬 **Works with any MCP client**: Claude Desktop, Cursor, VS Code, Cline, Continue

[Versão em português](README.md) · [Full docs (PT-BR)](docs/) · [Agent skill](skills/)

---

## One-click install

### Claude (Web and Desktop)

Anthropic unified MCP installation at `claude.ai/customize/connectors`. **The same link works for Claude Web and Claude Desktop** (just be logged in):

[➕ Open in Claude and connect](https://claude.ai/new?modal=add-custom-connector#settings/customize-connectors)

**Manual** (if the deeplink does not open): [claude.ai/customize/connectors](https://claude.ai/customize/connectors?surface=cowork) → **+** → **Add custom connector** → paste **Name** `Jurisprudência TST` and **URL** `https://api.mcp.ai/p_tst`.

### Cursor

[➕ Install Jurisprudência TST in Cursor](cursor://anysphere.cursor-deeplink/mcp/install?name=tst&config=eyJ1cmwiOiJodHRwczovL2FwaS5tY3AuYWkvcF90c3QifQ==)

### VS Code (Copilot Chat)

[➕ Install Jurisprudência TST in VS Code](vscode:mcp/install?name=tst&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fapi.mcp.ai%2Fp_tst%22%7D)

### ChatGPT, Manus, OpenClaw and 40+ other clients

Works with any MCP client that speaks **MCP over HTTP**. The server URL is always:

```
https://api.mcp.ai/p_tst
```

Per-client details: [INSTALL.md](INSTALL.md).

---

## Example prompts

```
What does the TST hold on dismissal for job abandonment?
Is there a TST summary or orientation on commuting hours?
TST case law on role accumulation and salary differences
```

---

## 3 tools available

| Tool | Description |
|---|---|
| `jurisprudencia_buscar` | Busca jurisprudência (acórdãos, súmulas, orientações jurisprudenciais, temas) por termo ou tese. |
| `jurisprudencia_sumulas` | Busca SÚMULAS (incluindo vinculantes) por termo. |
| `jurisprudencia_documento` | Lê o INTEIRO TEOR de uma decisão (texto completo do acórdão, não o resumo). |

Details for each tool: [docs/ferramentas.md](docs/ferramentas.md) (PT-BR)

---

## Pricing

Free.

---

## Privacy & data protection

- **Read-only**, no tool changes data at the source.
- **Sub-processors**: Serper (Google Search), the LLM host you choose (Claude, ChatGPT, Cursor, your own agent). Full list in [docs/privacidade-lgpd.md](docs/privacidade-lgpd.md).
- Data returned by the tools is sent to **the LLM host you choose**, a sub-processor outside our control. We recommend plans with training opt-out.

---

## FAQ

**Cobre súmulas e OJs, não só acórdãos?**
Sim, e isso importa no trabalhista: boa parte do que orienta a instância inferior está em súmula e orientação jurisprudencial, não em acórdão isolado.

**Precisa de login ou cadastro?**
Não. É grátis e sem credencial, e você não precisa de conta em nenhum tribunal.

**Serve para citar em petição?**
Serve para encontrar e ler. Todo resultado traz o link no site oficial, e a conferência lá é obrigatória antes de citar.

**Por que uma busca voltou vazia?**
Quase sempre é vocabulário: o tribunal nomeia a tese de um jeito diferente do coloquial, e a resposta sugere o que tentar. Se a fonte estiver indisponível no momento, ela diz isso explicitamente, o que é diferente de a decisão não existir.

**O servidor é open source?**
O servidor é proprietário (hosted). Este repositório é o wrapper público com manifestos, docs e skills, tudo MIT.


---

## Support

- 📧 [tst@mcp.ai](mailto:tst@mcp.ai)
- 🐛 [GitHub Issues](https://github.com/mcp-dir/tst-mcp/issues)
- 📄 [docs/](docs/)

---

## License

MIT — see [LICENSE](LICENSE). The MCP server at `api.mcp.ai/p_tst` is proprietary (hosted); this repo (manifests, docs, skills) is MIT.
