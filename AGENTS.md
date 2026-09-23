# Agent instructions

This repository is one person's curated list. The rules it follows live in the
engine at <https://github.com/olitreadwell/awesome-list-template>, and
`README.md` is the only source of truth for entries.

## Before you change anything

```bash
uv sync --group dev
make hooks-install
make check
```

## Rules

- Every entry is `- [Name](https://example.com/) - What it is.` with a capital
  and a closing period. This list does not use tags.
- Do not write entry text with a model. Every description here came from
  upstream, and rewording one is not a revival.
- Run `make toc` after moving a heading, and never hand-edit Contents lines.
- Give every GitHub link its stars and last-push date with `make stats`. Never
  hand-write a stars number. `make stats-check` verifies the snapshot offline.
- Two hosts serve no TLS certificate, so those entries stay on http and
  `awesome.toml` records the exceptions.
- A heading that a body line points at is already linked from the Contents
  list. Linking the same anchor twice in one readme is a duplicate link.

## Layout

- `README.md` holds the list, the Contents section, and the prose.
- `tests/test_readme.py` holds the invariants for this particular list.
- `docs/revival.md` records what the engine changed and what it left alone.
