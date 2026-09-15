# AGENTS.md

## Purpose

This repository publishes Amit's public engineering knowledge portal at `https://amitkarpe.github.io/`.

The portal curates sanitized, reusable technical knowledge and public portfolio content across AWS, GitHub/OIDC, agentic AI, AgentCore, MCP, DevSecOps, security, automation, troubleshooting, and related engineering work.

## Read Order

1. `AGENTS.md`
2. `CONTEXT.md`
3. the owning GitHub Issue/PR and latest relevant handoff
4. site configuration and content needed for the active milestone

## Repository Role

Keep ownership boundaries clear:

- `amitkarpe.github.io` owns curated public technical knowledge, case studies, and portfolio content.
- `amitkarpe/agent-os` owns reusable agent operating policies, playbooks, and the knowledge-promotion lifecycle.
- `amitkarpe/repo-starter` owns only the smallest universal repository defaults.
- dotfiles / `.agent` own machine-, runtime-, and tool-specific defaults.
- source project repositories remain authoritative for their implementation, current context, evidence, approvals, and runtime truth.

When a reusable lesson is primarily an agent operating rule, promote it through Agent OS instead of duplicating it here.

## Public-Safety Gate

This repository is public. Before publishing or copying material from another project:

- remove credentials, tokens, keys, authentication state, and secrets;
- remove or generalize private/customer/internal infrastructure identifiers;
- avoid private account IDs, ARNs, hostnames, IPs, endpoints, and work-specific names unless they are already intentionally public and safe;
- do not publish raw logs, private chat transcripts, proprietary/internal documents, or copied customer/work material;
- rewrite learning into general, reusable technical guidance and cite/link public source repositories when useful.

If public safety is uncertain, stop publication and keep the candidate in the source project until reviewed.

## Working Rules

- Follow KISS: optimize for one useful portal milestone, not a broad migration.
- Preserve `https://amitkarpe.github.io/` and existing useful content while improving structure incrementally.
- Keep `CONTEXT.md` current-only; completed history belongs in Git history and closed Issues/PRs.
- Reuse the owning Issue/PR for corrections and directly related work.
- Do not bulk-copy repositories or documentation. Curate and deduplicate.
- Prefer Markdown and simple GitHub-native publishing. Add framework/dependency complexity only when it materially improves maintainability, navigation, or search.
- Validate the actual GitHub Pages result before declaring a publishing milestone complete.

## Canonical Guidance

For reusable agent collaboration and promotion rules, use Agent OS:

- https://github.com/amitkarpe/agent-os

Project-specific instructions in this repository and Amit's current instruction remain authoritative for this site.