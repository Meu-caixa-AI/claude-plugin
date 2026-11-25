<p align="center"><img src="plugins/meu-caixa-ai/.claude-plugin/icon.png" alt="Meu Caixa AI" width="160"></p>

# Meu Caixa AI plugin for Claude

Use your [Meu Caixa](https://meucaixa.ai) account from Claude.

- **Finance MCP server** (`meu-caixa`, `https://mcp.meucaixa.ai/mcp`): record, edit, search and report transactions, manage the catalog and import statements. Claude signs you in with your WhatsApp number on first use.
- **`importar-fatura` skill**: share a credit card invoice from any bank and Claude reads its lines and imports them.

## Install

```
/plugin marketplace add Meu-caixa-AI/claude-plugin
/plugin install meu-caixa-ai@meu-caixa-ai
```

## Layout

```
.claude-plugin/marketplace.json
plugins/meu-caixa-ai/
├── .claude-plugin/{plugin.json, icon.png}
├── .mcp.json
└── skills/importar-fatura/SKILL.md
```

## License

MIT, see [LICENSE](LICENSE).
