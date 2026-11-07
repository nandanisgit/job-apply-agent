# Job Apply Agent

An agent that finds relevant jobs every night, ranks them against your profile,
prepares tailored applications (résumé, cover letter, screening answers, pre-filled
form saved as a draft) and lets you **review and approve** each one in the morning
before it submits.

Everything user-specific (target roles, portals, scoring, prompts, templates, LLM,
schedule, notifications) is **configuration**, so a new user can adapt it without
changing code.

## Design (read in order)

1. [Architecture](docs/01-architecture.md): goals, principles, building blocks, tech choices, risks
2. [High-level design](docs/02-hld.md): daily flow, pipeline stages, state machine, config model, phases
3. [Low-level design](docs/03-lld.md): package layout, models, plugin interfaces, config schemas with examples, DB schema, algorithms, CLI, UI routes, tests

Status: **design review**. Code starts after the design is approved.
