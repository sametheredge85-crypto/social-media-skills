# Ministry Content Archive

Token-efficient, long-term home for sermons, pulpit notes, studies, helps, and related ministry material generated in conversations with Grok.

## Purpose
Keep the valuable output from study, preaching preparation, and packet creation without bloating conversation threads or burning tokens on repeated retrieval.

## Structure
- `sermons/` — Full sermon manuscripts, outlines, or series (one file per sermon or series).
- `pulpit-notes/` — 5x8-style notes, cards, and delivery aids.
- `studies/` — Deeper exegetical work, harmony studies, and doctrinal deep dives.
- `helps/` — Practical tools, checklists, workflows, and assistance documents.
- `packets/` — Complete teaching packets, Facebook essays, posters descriptions, or multi-part deliverables.
- `index.md` — Running catalog of what has been archived (update when adding).

## Economy Rules (to keep token cost low)
1. One clear topic per file. Prefer clean markdown over full conversation dumps.
2. Use short YAML-style front matter only when useful (title, date, text, status).
3. Store final polished output, not intermediate drafts, unless the draft itself is valuable.
4. Keep KJV citations exact. Do not restate the same harmony repeatedly across files.
5. Update `index.md` with a one-line entry when a new file is added.
6. Prefer linking to an existing file rather than duplicating content.

## How to Add
- Place new files directly in the appropriate subfolder.
- Or tell Grok “add this to ministry/sermons/” (or the relevant folder) and provide the content or point to a prior output.
- For bulk history, prioritize high-value finished pieces first; raw threads can be summarized into studies later.

This folder lives alongside the social-media skills so the repository remains useful for both content creation workflows and long-term ministry archive.

Last updated: 2026-11-23
