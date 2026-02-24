# scoop-charly

Scoop bucket for [charly-vibes](https://github.com/charly-vibes) tools.

## Setup

```powershell
scoop bucket add charly https://github.com/charly-vibes/scoop-charly
```

## Tools

| Manifest | Description |
|----------|-------------|
| `wai` | Workflow manager for AI-driven development |
| `fabbro` | Local-first code review annotation tool |
| `fotos-mcp` | MCP server for the Fotos screenshot tool |
| `fotos` | AI-powered screenshot capture and analysis app |

## Install

```powershell
scoop install wai
scoop install fabbro
scoop install fotos-mcp
scoop install fotos
```

## Update

```powershell
scoop update *
```

---

Manifests are auto-updated on each release via [GoReleaser](https://goreleaser.com) and GitHub Actions.
