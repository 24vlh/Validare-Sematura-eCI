# ValidareSemnaturaAvansata-eCI AI Router

Use this file as the thin routing entry point for ValidareSemnaturaAvansata-eCI tasks.

The maintained router lives at:
- `@24vlh/agents/agents-repo/ValidareSemnaturaAvansata-eCI/AGENTS.md`

Load the maintained router for actual routing, source-of-truth files, and validation commands.
Do not duplicate the full router here.

## Path alias

Source of truth: `@24vlh/agents/path-roots.json`.

- `@24vlh` => WSL primary `/public_html/24vlh`
- `@24vlh` => Windows fallback `\\wsl.localhost\CentOS10\public_html\24vlh`
- `@24vlh` => legacy WSL fallback `/mnt/w/public_html/24vlh`
- `@24vlh` => legacy Windows fallback `W:/public_html/24vlh`

## Project root reference

- `@24vlh/ValidareSemnaturaAvansata-eCI`

## Command execution policy (WSL-first, mandatory)

- Run commands through WSL shell:
  - `wsl sh -lc "cd /public_html/24vlh/ValidareSemnaturaAvansata-eCI && <command>"`

## Routing

- Maintained router:
  - `@24vlh/agents/agents-repo/ValidareSemnaturaAvansata-eCI/AGENTS.md`
- Emit:
  - `Routing: ValidareSemnaturaAvansata-eCI + @24vlh/agents/agents-repo/ValidareSemnaturaAvansata-eCI/AGENTS.md [+ other routers]`
