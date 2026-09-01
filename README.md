# Jurisprudência TST

### Jurisprudência trabalhista do TST para Claude, Cursor e agentes de IA

Pesquise jurisprudência trabalhista do **TST**, a última palavra em matéria do trabalho. Além de acórdãos, o TST orienta por súmulas e orientações jurisprudenciais, que é o que de fato guia a instância inferior, e a busca cobre as três. A mesma conexão alcança outros 16 tribunais quando a questão é mista. Grátis, sem login, hospedado pela plataforma.

- ⚖️ **TST**, acórdãos, súmulas e orientações jurisprudenciais, e mais 16 tribunais na mesma conexão
- 🎯 **O trecho que CASOU a busca**, não a abertura burocrática do acórdão
- 🔗 **Link no site oficial** em cada resultado, para conferência
- 📄 **Inteiro teor sob demanda** quando a decisão permite
- 🚦 **Diz quando não sabe**: fonte indisponível ou acervo desatualizado vira aviso explícito, nunca um vazio sem explicação
- 🔒 **Somente leitura**
- ⚡ **Grátis, sem login, sem credencial**
- 💬 **Funciona com qualquer cliente MCP**: Claude Desktop, Cursor, VS Code, Cline, Continue

[English version](README.en.md) · [Documentação completa](docs/) · [Skill pra agentes](skills/)

---

## Instalar em 1 clique

### Claude (Web e Desktop)

A Anthropic unificou a instalação de MCPs em `claude.ai/customize/connectors`. **O mesmo link serve pra Claude Web e Claude Desktop** (basta estar logado):

[➕ Abrir no Claude e conectar](https://claude.ai/new?modal=add-custom-connector#settings/customize-connectors)

**Manual** (se o deeplink não abrir): [claude.ai/customize/connectors](https://claude.ai/customize/connectors?surface=cowork) → **+** → **Adicionar conector personalizado** → cole **Nome** `Jurisprudência TST` e **URL** `https://api.mcp.ai/p_tst`.

### Cursor

[➕ Instalar Jurisprudência TST no Cursor](cursor://anysphere.cursor-deeplink/mcp/install?name=tst&config=eyJ1cmwiOiJodHRwczovL2FwaS5tY3AuYWkvcF90c3QifQ==)

### VS Code (Copilot Chat)

[➕ Instalar Jurisprudência TST no VS Code](vscode:mcp/install?name=tst&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fapi.mcp.ai%2Fp_tst%22%7D)

### ChatGPT, Manus, OpenClaw e mais 40+ clientes

Funciona em qualquer cliente MCP que suporte **MCP over HTTP**. A URL do servidor é sempre:

```
https://api.mcp.ai/p_tst
```

Detalhes por cliente: [INSTALL.md](INSTALL.md).

---

## Exemplos de uso

```
O que o TST entende sobre justa causa por abandono de emprego?
Tem súmula ou OJ do TST sobre horas in itinere?
Jurisprudência do TST sobre acúmulo de função e diferença salarial
```

---

## 3 ferramentas disponíveis

| Tool | Descrição |
|---|---|
| `jurisprudencia_buscar` | Busca jurisprudência (acórdãos, súmulas, orientações jurisprudenciais, temas) por termo ou tese. |
| `jurisprudencia_sumulas` | Busca SÚMULAS (incluindo vinculantes) por termo. |
| `jurisprudencia_documento` | Lê o INTEIRO TEOR de uma decisão (texto completo do acórdão, não o resumo). |

Detalhe de cada tool: [docs/ferramentas.md](docs/ferramentas.md)

---

## Preços

Grátis.

---

## Privacidade & LGPD

- **Somente leitura**, nenhuma ferramenta altera dados na origem.
- **Sub-processadores**: Serper (Google Search), o LLM host que você escolher (Claude, ChatGPT, Cursor, agente próprio). Lista completa em [docs/privacidade-lgpd.md](docs/privacidade-lgpd.md).
- Os dados retornados pelas tools são enviados ao **LLM host que você escolher**, sub-processador fora do nosso controle. Recomendamos planos com opt-out de treinamento.

---

## Perguntas frequentes

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

## Suporte

- 📧 [tst@mcp.ai](mailto:tst@mcp.ai)
- 🐛 [GitHub Issues](https://github.com/mcp-dir/tst-mcp/issues)
- 📄 [docs/](docs/)

---

## Licença

MIT — veja [LICENSE](LICENSE). O servidor MCP em `api.mcp.ai/p_tst` é proprietário (hosted); este repositório (manifestos, docs, skills) é MIT.
