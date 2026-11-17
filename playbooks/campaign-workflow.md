# Campaign workflow

```text
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│                  CAMPAIGN WORKFLOW  ·  how Oleena's team runs a campaign today                   │
├─ WORKSPACE · where Oleena and the agents work ───────────────────────────────────────────────────┤
│                                                                                                  │
│  Chief of Staff        routes work to leads; owns the review queue                               │
│  Marketing Lead        Gate 1 brief, Gate 2 copy                                                 │
│  Creative Lead         Gate 3 design · architecture.md                                           │
│  Engineer Lead         Gate 4 build · preview only                                               │
│  Production            Claude Code on Mac · Sonnet · per-run yes                                 │
│  Playbooks             github.com/oleenamak/team-playbooks                                       │
│  Campaign state        campaign-record.md on the box                                             │
│                                                                                                  │
├─ CONTEXT · internal / external ──────────────────────────────────────────────────────────────────┤
│                                                                                                  │
│  INTERNAL                                     │ EXTERNAL                                         │
│  Obsidian LLM wiki + playbooks                │ research sources                                 │
│  brand, positioning, campaign files           │ Meta Ads Manager · not yet in use                │
│                                                                                                  │
│  Company brain       Obsidian LLM wiki + playbooks                                               │
│  CRM                 Attio                                                                       │
│  Sign-ups            Airtable · automation off                                                   │
│  Data warehouse      not yet                                                                     │
│                                                                                                  │
├─ CAMPAIGN WORKFLOW · from objective to results ──────────────────────────────────────────────────┤
│                                                                                                  │
│                     ┌─────────────────────────────────────────────────────┐                      │
│                     │ 1  OBJECTIVE                                        │                      │
│                     │ Gate 1 Brief · Marketing Lead                       │                      │
│                     └─────────────────────────────────────────────────────┘                      │
│                                                │                                                 │
│                                                ▼                                                 │
│                     ┌─────────────────────────────────────────────────────┐                      │
│                     │ 2  RESEARCH                                         │                      │
│                     │ inputs to the brief · stored with the campaign      │                      │
│                     └─────────────────────────────────────────────────────┘                      │
│                                                │                                                 │
│                                                ▼                                                 │
│                     ┌─────────────────────────────────────────────────────┐                      │
│                     │ 3  PLAN + APPROVE                                   │                      │
│                     │ one packet per gate · Oleena's yes                  │                      │
│                     └─────────────────────────────────────────────────────┘                      │
│                                                │                                                 │
│                                                ▼                                                 │
│                     ┌─────────────────────────────────────────────────────┐                      │
│                     │ 4  RUN                                              │                      │
│                     │ sequential gates · parallel channel tracks: not yet │                      │
│                     └──────────────────────────┬──────────────────────────┘                      │
│                                                │                                                 │
│                               ┌────────────────┴────────────────┐                                │
│                               │                                 │                                │
│                               ▼                                 ▼                                │
│                 ┌───────────────────────────┐     ┌───────────────────────────┐                  │
│                 │ META · only channel       │     │ OTHER CHANNELS            │                  │
│                 │                           │     │                           │                  │
│                 │ Gate 2 COPY · Marketing   │     │ not yet                   │                  │
│                 │             ▼             │     │                           │                  │
│                 │ Gate 3 DESIGN · Creative  │     │                           │                  │
│                 │ architecture.md           │     │                           │                  │
│                 │             ▼             │     │                           │                  │
│                 │ Gate 4 BUILD · Engineer   │     │                           │                  │
│                 │ preview only              │     │                           │                  │
│                 └─────────────┬─────────────┘     └─────────────┬─────────────┘                  │
│                               │                                 │                                │
│                               └────────────────┬────────────────┘                                │
│                                                │                                                 │
│                                                ▼                                                 │
│                     ┌─────────────────────────────────────────────────────┐                      │
│                     │ 5  CHECK + REVIEW                                   │                      │
│                     │ CoS review queue                                    │                      │
│                     │ changes → back to that gate   ·   approve → next    │                      │
│                     └──────────────────────────┬──────────────────────────┘                      │
│                                                │                                                 │
│                                                ▼                                                 │
│                     ┌─────────────────────────────────────────────────────┐                      │
│                     │ 6  LAUNCH  ·  Gate 5                                │                      │
│                     │ needs yes: hosting, domain, Pixel,                  │                      │
│                     │ Airtable automation, spend                          │                      │
│                     └─────────────────────────────────────────────────────┘                      │
│                                                │                                                 │
│                                                ▼                                                 │
│                     ┌─────────────────────────────────────────────────────┐                      │
│                     │ 7  RESULTS  ·  Gate 6                               │                      │
│                     │ Airtable rows vs target  ·  not yet run             │                      │
│                     └─────────────────────────────────────────────────────┘                      │
│                                                                                                  │
├─ CHECK + REVISE · inside each lead, before her review ───────────────────────────────────────────┤
│                                                                                                  │
│  create  →  check against brief / copy  →  pass  →  CoS queue  →  Oleena                         │
│             └── fail → name issue → revise  →  check again                                       │
│                                                                                                  │
│  Checks    taste loop: no beige/AI backgrounds, no photorealism, brand-sheet style,              │
│            verbatim copy, 5-sec test at 375px, ad promise match                                  │
│  Stop      any gate · missing input · no yes for the exact action                                │
│                                                                                                  │
│  CBO-001 now:  Gates 1–2 approved  ·  Gate 3 in progress  ·  no launch, no spend                 │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```
