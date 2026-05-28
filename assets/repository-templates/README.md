# Repository README templates

Templates for standardizing public repository READMEs across Mark1708 projects.

## How to choose a template

1. Start from `README_BASE.md` for the shared public-facing contract.
2. Pick one type-specific template by repository role:

| Repository type | Template |
|---|---|
| CLI tool / developer utility | `README_TOOLS.md` |
| Host plugin / OpenCode extension | `README_PLUGIN.md` |
| Full-stack demo / app | `README_FULLSTACK.md` |
| Backend service / backend demo | `README_BACKEND.md` |
| Frontend / static site / web app | `README_FRONTEND.md` |
| Research / benchmark / ML experiment | `README_RESEARCH.md` |
| Library / package | `README_LIBRARY.md` |

## Required shared contract

Every public README should include:

- one-line value proposition;
- consistent dark/purple badge style;
- summary table with status, type, primary stack, quick verification, and verification level;
- exact install/run/validation commands;
- limitations or security caveats;
- explicit status vocabulary.

## Guidance levels

Use these labels consistently:

- **Documented**: command or claim is written in README only.
- **Manifest-backed**: claim matches package, Gradle, Maven, Go, Python, or other manifest files.
- **Run-confirmed**: command was run and passed during a documented maintenance pass.

## Bilingual policy

Write the English README first. After its structure stabilizes, mirror the same section order in `README.ru.md`.
