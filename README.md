# South Neuhof Skills

Agent skills for Carta-based projects. Each folder under `skills/` is one installable skill with a `SKILL.md` contract plus optional `references/`, `scripts/`, and `agents/` support files.

## Skills

| Skill | Use when |
|---|---|
| `api-conventions` | Adding, changing, or reviewing anything in `apps/api` |
| `build-resource-form` | Adding or repairing a schema-bound resource form in `apps/web` |
| `carta-module-development` | Routing one application module from intent through verification |
| `implement-schema-first-zod` | Applying schema-first Zod type inference |
| `migrate-web-resource` | Migrating one web module to the schema-bound resource API |
| `verify-carta-module` | Read-only acceptance verification of a complete feature |
| `web-ui-surfaces` | Building or reviewing `apps/web` routes with framework surfaces |

## Install one skill

```sh
npx skills@latest add southneuhof/skills --skill <name>
```

## Install all skills

```sh
npx skills@latest add southneuhof/skills
```
