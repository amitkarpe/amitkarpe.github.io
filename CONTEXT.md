# Context

Status: ACTIVE
Updated: 2026-09-17

> `CONTEXT.md` is current-only restart state. Keep completed history in Git history and closed Issues/PRs.

## Project Identity

- Project: Amit Engineering Knowledge Portal
- Primary Repository: `amitkarpe/amitkarpe.github.io`
- Live Site: `https://amitkarpe.github.io/`
- Default Branch: `master`

## Current Truth

- The repository already publishes Amit's GitHub Pages site.
- Current site configuration uses `jekyll-theme-midnight`.
- Existing root content is small: `README.md`, `_config.yml`, and `k8s.md`.
- The objective is to evolve this existing site into a sanitized, searchable engineering knowledge portal and portfolio rather than create another repository.
- Agent OS remains the canonical home for reusable agent operating policy; this repository owns curated public technical knowledge and case studies.
- The separate `mytestlab123/mytestlab123.github.io` Astro/Starlight site is a prototype/learning surface; its success does not automatically change this portal's framework or publishing path.

## Active Work

- Issue: `#1` — Knowledge Portal v1
- PR: `#2` — bootstrap Knowledge Portal collaboration context
- Current milestone: establish durable repository guidance and handoff so the owning G can continue Knowledge Portal v1 from GitHub truth.
- Blocker: none.

## Next Action

Continue Issue #1 / PR #2 by inspecting the existing live site and implementing the smallest maintainable knowledge-portal structure without breaking the public URL.

The first implementation milestone should preserve useful existing content, define navigation/taxonomy, and publish a small set of sanitized seed articles from intentionally public source material. Framework migration remains a separate explicit decision if needed.

## Continuation

Normal continuation:

`@GitHub Continue PR #2 from its latest relevant authorized handoff/comment and current HEAD.`

Use `AGENTS.md` plus this file for cold start/recovery, materially changed governing context, ambiguous objective/repository identity, or stale/incomplete/contradictory state. Do not force a full context reread on every handoff.
