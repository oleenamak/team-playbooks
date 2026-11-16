# Lead Conventions

Rules every lead skill and playbook follows. Read this first before running any lead work.

## Hard rules (never break)

1. **Drafts only.** Nothing is sent, published, merged, shipped, or spent without Oleena's explicit yes. An approved deliverable is still a draft until she authorizes the actual action.
2. **No credentials in chat.** API keys, passwords, tokens, and secrets never appear in messages or files committed to git.
3. **Read back before confirming.** Don't claim a write succeeded until you've read the destination and confirmed the content matches what you intended.
4. **Never invent facts or numbers.** Cite sources. Write "unknown" or "not yet determined" rather than guess. Mark assumptions clearly.

## Gate order

Every campaign moves through these gates in sequence:

1. **Brief** — campaign objective, audience, hypothesis, channels, budget, and success metrics
2. **Copy** — ad copy and landing page copy
3. **Design/mockups** — visual direction and production-ready designs
4. **Build** — via Engineer Lead

Don't skip ahead. Each gate needs Oleena's approval before the next one starts. If feedback at a later gate changes an earlier decision (audience, offer, message, budget, or scope), reopen the relevant earlier gate.

## Routing

- **Chief of Staff** is the front door. Route campaign ideas, new requests, and cross-functional work there first.
- **Heavy production work** goes to Claude Code on Oleena's Mac. Requires per-run approval. Defaults to `--model sonnet`.
- **Builds** (landing pages, web assets, implementation) go to Engineer Lead.

## Defaults

These are sensible defaults. A lead may deviate with a one-line stated reason.

- **Model:** sonnet for production work unless specified otherwise
- **Drafts only:** see hard rules above
- **Keep usage lean:** prefer smaller tasks and targeted research over exhaustive scans
- **Files first:** write deliverables to disk before summarizing in chat
- **One approval request per gate:** consolidate review requests rather than multiple back-and-forths

## Skill format

When writing or updating a lead skill:

**Frontmatter:**

```yaml
---
name: skill-name
description: What it does (one sentence). When to use it (one sentence with trigger phrases).
reads: [files this skill loads]
writes: [files this skill creates or updates]
---
```

**Size:** Cap each skill at ~300-500 lines. Move depth (methodology, examples, calibration anchors) into `references/` files and load them only when needed. State explicitly when to load each reference.

**Example frontmatter:**

```yaml
---
name: campaign-brief
description: Creates a structured campaign brief with objective, audience, hypothesis, channels, and success metrics. Use when starting a new campaign or when someone says "let's run a campaign" or "I have a campaign idea."
reads: [brand-sheet.html, past campaign records]
writes: [templates/campaign-brief.md]
---
```

## Standard output contract

Every deliverable follows this structure:

1. **Result first** — the work itself (brief, copy, design direction, analysis)
2. **Files saved** — exact paths with (new) or (updated) markers
3. **Sources and assumptions** — what this rests on: data sources, research conducted, stated assumptions, and any gaps or limitations. Cap at 10 lines.
4. **Next steps** — what happens next and what needs Oleena's approval before proceeding

Keep the deliverable clean. Don't include process notes, skill names, self-scores, or capability tiers in the final output. Those go in working notes if needed.
