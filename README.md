# video-edit

> Edit videos locally using ffmpeg — trim, concat, resize, speed, overlay, extract audio, compress, and convert.

**Free. Apache 2.0. Bring-your-own-Claude.**

## What this is

A Claude skill bundle — a sanitized, attributed, downloadable subject-matter expert that runs inside Claude Code, Claude Desktop, or any Claude-API workflow. Drop it in, invoke it, get answers grounded in real practitioner content rather than generic LLM consensus.

Use for trimming or cutting video segments, concatenating clips, resizing video, adjusting speed, extracting audio, compressing files, or converting between formats.

## Install

```bash
# Claude Code plugin install (one-line)
claude plugin install video-edit --from https://fadaly.net/downloads/skills/video-edit.zip
```

Or clone this repo into your Claude skills directory:

```bash
git clone https://github.com/MomoFadaly/video-edit.git ~/.claude/skills/video-edit
```

Or download the zip from [fadaly.net/skills/video-edit](https://fadaly.net/skills/video-edit) (the per-skill landing page on fadaly.net) and extract into `~/.claude/skills/`.

## What's in the bundle

| File | Size |
|---|---|
| `references/operations.md` | 9KB |
| `SKILL.md` | 3KB |
| `thumb.png` | 1.77MB |

Total: 1.78MB

## Sources

This SME's canon was built from these practitioners. Every claim in the canon is attributed.

- ffmpeg (ffmpeg.org) — primary

Primary sources (official documentation, peer-reviewed research) take priority over practitioner consensus, which takes priority over single-source claims. Confidence tiers are tagged inline.

## How it works

Claude reads `SKILL.md` as the system instructions for the skill. Supporting files (`canon.md`, `mental-models.md`, etc.) are loaded as reference material when the skill needs to answer off the cuff or cite a specific source.

When you ask a question this SME covers, Claude pulls the relevant canon entry, names its source, tags its confidence level, and pushes back if your question contradicts canon.

## Confidence levels

- **Verified** — primary source + practitioner corroboration. Treat as fact.
- **Confirmed** — practitioner consensus across credible voices, no primary contradiction. Defended best-practice.
- **Plausible** — single-source or thin evidence. Working hypothesis until validated.
- **Disputed** — credible voices disagree. The SME names the camps and gives you the lens to decide.
- **Stale** — once true, contradicted by current docs/data. Flagged for refresh.

## License

Apache License 2.0. See [LICENSE](LICENSE).

You are free to use, modify, redistribute, and build on this skill. Attribution to the original practitioners (named in `sources.md` or `SKILL.md`) is morally required even if not legally; their work made the canon possible.

## Built by

[Mo Fadaly](https://fadaly.net) — AI intrapreneur, runs Claude skills in production.

This is one of a series. See the [full catalog at fadaly.net/work](https://fadaly.net/work).
