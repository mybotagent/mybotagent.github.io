# mybotagent.github.io

Personal portfolio entry point for @mybotagent. Lightweight static site
hosted on GitHub Pages — designed as a single redirect page into the
deeper technical portfolio.

## About

A redirect-only landing page that routes visitors to the active
architecture deck site. Kept intentionally minimal — no bundler, no
runtime, only HTML and CSS.

## Stack

- Pure HTML + CSS (Apple-style, SF Pro)
- Hosted via GitHub Pages (legacy mode)
- `http-equiv="refresh"` for instant redirect + canonical link for SEO

## Structure

```
mybotagent.github.io/
├── index.html      # Redirect to hermes-architecture-deck
├── README.md       # This file
├── CHANGELOG.md    # Change history
├── LICENSE         # MIT
└── scripts/
    └── review_pr.py  # PR review helper (mirrored from hermes-wiki-super)
```

## Related repositories

| Repo | Visibility | Purpose |
|:-----|:----------:|:--------|
| `mybotagent/hermes-architecture-deck` | public | Active portfolio — Reveal.js decks |
| `mybotagent/hermes-wiki-super` | public | Super repo — all wikis as submodules |
| `mybotagent/memory-map` | public | Memory <-> wiki lazy indexing map |
| `mybotagent/hermes-agent` | public | Hermes Agent (upstream fork) |

## Maintenance

This repo is part of the mybotagent mirror set. Updates follow the same
convention as the other public mirrors — auto-managed by hermes-bot with
human review for content changes.

## License

MIT
