# Test project

Node.js backend, written in TypeScript.

## Tech stack

- Runtime: Node.js
- Language: TypeScript (strict)
- Module system: ESM (`"type": "module"`)
- Package manager: npm
- Build: `tsc` via `tsconfig.json`
- Dev: `tsx` (or `ts-node`) for running TypeScript without a separate compile step during development

## Conventions

- Source in `src/`, compiled output in `dist/`
- Prefer typed APIs; avoid `any`
- Use `async`/`await` over raw callbacks
- Keep config in environment variables (`.env`), never commit secrets

## Agent notes

- Keep changes inside this folder.
- Prefer small, clear files.
- Ask before adding extra docs or tooling unless requested.
