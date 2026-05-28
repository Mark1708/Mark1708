# Plugin / Host Extension

> One-line value proposition for users of the host application.

![Package](https://img.shields.io/badge/package-name-111827?style=for-the-badge&labelColor=111827&color=5b5ef4)
![Runtime](https://img.shields.io/badge/runtime-bun-111827?style=for-the-badge&logo=bun&logoColor=5b5ef4)
![License](https://img.shields.io/badge/license-MIT-111827?style=for-the-badge&labelColor=111827&color=5b5ef4)

[Русская версия](README.ru.md)

| Field | Value |
|---|---|
| Status | Active / Maintained / Finished demo / Archived |
| Type | Plugin / host extension |
| Host app | Name and supported host version |
| Package | Package registry name and version |
| Runtime | Bun / Node.js / other runtime |
| Maintenance command | `command` or short note |
| Notes | Maintenance or reproducibility context |

## Screenshots

Show the plugin UI early. Keep screenshots local and current.

![Screenshot](assets/screenshot.png)

## Quick start

```sh
# install package or clone locally

# install dependencies

# build plugin

# verify plugin output
```

## Installation

### Package install

```sh
# package-manager add package-name
```

### Local checkout

```sh
git clone https://github.com/owner/repo.git
cd repo
# install/build commands
```

## Compatibility

| Component | Supported version | Source |
|---|---|---|
| Host app | `>=...` | README / package peer dependency / release note |
| Plugin API | `>=...` | `package.json` peer dependency |
| Runtime | `>=...` | `package.json` engines or README |

Separate host-application version from plugin API peer dependency when they differ.

## Configuration

Document the smallest useful config first, then the full schema.

```json
{
  "enabled": true
}
```

## Usage

- How the user enables the plugin.
- What UI appears and where.
- Main interactions and keybindings.
- Cache, refresh, or persistence behavior.

## Quality notes

| Area | Command | Notes |
|---|---|---|
| Build | `command` | Documented maintenance guidance |
| Typecheck | `command` | Documented maintenance guidance |
| Test | `command` | Documented maintenance guidance |

## Troubleshooting

- Plugin not loading:
- Configuration not found:
- UI width/layout issues:
- Missing credentials or host data:

## Limitations / Security

- Document credentials discovery and redaction behavior when relevant.
- Never include real tokens, personal config, or internal paths in examples.
- State polling, API, width detection, or host API limitations.

## Status

State maintenance expectations and host compatibility policy.

## Links / License

- Package:
- Host app docs:
- License:
