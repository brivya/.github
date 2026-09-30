# brivya/.github Bootstrap

**Target repository:** `brivya/.github`  
**Visibility:** Public  
**Default branch:** `main`

## Purpose

This repository provides the public Brivya organization profile and default community health files.

## Required layout

```text
.github/
├── profile/
│   └── README.md
├── SECURITY.md
├── CONTRIBUTING.md
└── CODE_OF_CONDUCT.md
```

## Source mapping

| Target | Prepared source |
|---|---|
| `profile/README.md` | `bootstrap/github/profile/README.md` |
| `SECURITY.md` | `bootstrap/github/SECURITY.md` |
| `CONTRIBUTING.md` | `bootstrap/github/CONTRIBUTING.md` |
| `CODE_OF_CONDUCT.md` | `bootstrap/github/CODE_OF_CONDUCT.md` |

## Repository settings

Recommended:

- Public
- Default branch: `main`
- No license required for this metadata/community repository
- No Cortex `.agent` required unless this repository later develops an independent lifecycle
- Prefer PR-based updates after initial bootstrap

## Sequence

1. Owner manually creates `brivya/.github` as Public.
2. ChatGPT/GitHub connector writes the prepared files.
3. Verify organization profile renders correctly.
4. Keep organization-level community files here as the default fallback for public repositories.
