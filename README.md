# Research

Captured sources for content production. See `sources.md` for the index.

## Subfolders

- `sources.md` — master index, one row per source
- `linkedin-posts/` — LinkedIn posts to repurpose or react to
- `youtube-transcripts/` — YouTube transcripts (frontmatter: title, url, captured, type, lang)
- `other/` — articles, podcasts, X posts, anything else

## Fetching a new YouTube transcript

From the project root:

```bash
python supadata.py "https://youtu.be/<VIDEO_ID>" > research/youtube-transcripts/<slug>.md
```

Or use the helper directly in Python — see `readme1.md` for the full API.

## Source file conventions

- **Filename:** `<index>-<slug>.md` where index is the next `#` in `sources.md`.
- **Frontmatter:** `title`, `url`, `captured` (YYYY-MM-DD), `type`, plus type-specific fields (e.g. `lang` for YouTube).
- **Status:** update the `sources.md` row from `captured` → `distilled` → `repurposed` as you work through it.
