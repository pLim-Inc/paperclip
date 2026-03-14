# Claude Code — pLimLab Project Config

## Plugins ativos

Este repositorio esta configurado com plugins Claude Code (escopo project via `.claude/settings.json`):

| Plugin | Funcao |
|--------|--------|
| `github` | Issues, PRs, code search, releases |
| `playwright` | Testes E2E e automacao de browser |
| `firecrawl` | Web scraping e crawling |
| `stripe` | Integracoes Stripe API |
| `typescript-lsp` | TypeScript Language Server |
| `code-review` | Review automatico de diffs/PRs |
| `security-guidance` | Analise de seguranca no codigo |
| `superpowers` | Capacidades avancadas |
| `commit-commands` | `/commit`, `/push` padronizados |
| `claude-md-management` | Gestao do CLAUDE.md |
| `claude-code-setup` | Setup automatico de projetos |
| `data` | Analise e manipulacao de dados |
| `playground` | Sandbox para testes rapidos |
| `adspirer-ads-agent` | Gestao de campanhas |
| `chrome-devtools-mcp` | Chrome DevTools via MCP |
| `amazon-location-service` | AWS Location Service |
| `clangd-lsp` | C/C++ Language Server |

## Convencoes pLimLab

**Branch Claude:** `claude/setup-dev-plugins-22mO1` — nunca push direto para `main`.

**Commit style** (Conventional Commits):
```
feat:     nova funcionalidade
fix:      correcao de bug
chore:    manutencao/config
docs:     documentacao
test:     testes
refactor: sem mudanca de comportamento
```

**Stack:** TypeScript / Python / FastAPI / Express / React / Next.js / Docker / PostgreSQL / Prisma

## Config central

Global config e skills: [pLim-Inc/plimlab-claude-config](https://github.com/pLim-Inc/plimlab-claude-config)
