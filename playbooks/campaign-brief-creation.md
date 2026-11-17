# Campaign brief creation

Scope: rough idea through approved Gate 1 brief. This expands Gate 1; later production gates remain unchanged.

```text
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│                    CAMPAIGN BRIEF CREATION · voice dump to approved direction                    │
├─ WORKSPACE · roles and tools ────────────────────────────────────────────────────────────────────┤
│                                                                                                  │
│  Chief of Staff   GrokBot on Mac · conversation, coordination, review queue                      │
│  Marketing Lead   Research synthesis and final brief · CoS may cover this role                   │
│  Research worker  Assigned internal / external evidence gathering                                │
│  T3 Code          Optional worker environment · connection not yet verified                      │
│  GitHub           Shared methods, templates and version history                                  │
│  Campaign state   campaign-record.md · status, approvals, blockers, worker links                 │
│                                                                                                  │
├─ CONTEXT · use what exists; unknown stays unknown ───────────────────────────────────────────────┤
│                                                                                                  │
│  INTERNAL                                      │ EXTERNAL                                        │
│  Brand, audience, offer, positioning           │ Customer discussions and reviews                │
│  Previous campaigns and results                │ Competitor offers, pages and campaigns          │
│  Existing decisions and constraints            │ Market evidence relevant to the decision        │
│                                                                                                  │
│  Private campaign data stays in approved private storage; this repo is public.                   │
│                                                                                                  │
├─ GATE 1 WORKFLOW · three human checkpoints ──────────────────────────────────────────────────────┤
│                                                                                                  │
│           ┌──────────────────────────────────────────────────────────────────────────┐           │
│           │ 1  CAPTURE THE IDEA                                                      │           │
│           │ Chief of Staff · voice dump                                              │           │
│           │ Preserve rough thoughts; inspect relevant existing context.              │           │
│           │ Output: intake.md                                                        │           │
│           └──────────────────────────────────────────────────────────────────────────┘           │
│                                                 │                                                │
│                                                 ▼                                                │
│           ┌──────────────────────────────────────────────────────────────────────────┐           │
│           │ 2  CLARIFY + PRESSURE-TEST                                               │           │
│           │ Chief of Staff + Oleena · campaign-discovery                             │           │
│           │ Question goals, assumptions and gaps; recommend options.                 │           │
│           │ Output: intent.md + decisions.md                                         │           │
│           └──────────────────────────────────────────────────────────────────────────┘           │
│                                                 │                                                │
│                                                 ▼                                                │
│           ┌──────────────────────────────────────────────────────────────────────────┐           │
│           │ 3  CONFIRM INITIAL INTENT                                                │           │
│           │ Oleena · checkpoint 1                                                    │           │
│           │ Confirm goal, why, hypotheses, boundaries and open questions.            │           │
│           │ Record: exact version + confirmation in campaign-record.md               │           │
│           └──────────────────────────────────────────────────────────────────────────┘           │
│                                                 │                                                │
│                                                 ▼                                                │
│           ┌──────────────────────────────────────────────────────────────────────────┐           │
│           │ 4  SCOPE THE RESEARCH                                                    │           │
│           │ Research worker + Chief of Staff · campaign-research                     │           │
│           │ Propose questions, methods, sources, time and cost limits.               │           │
│           │ Output: research/plan.md                                                 │           │
│           │ Oleena · checkpoint 2: approve scope before research starts              │           │
│           └──────────────────────────────────────────────────────────────────────────┘           │
│                                                 │                                                │
│                                                 ▼                                                │
│           ┌──────────────────────────────────────────────────────────────────────────┐           │
│           │ 5  GATHER + SYNTHESIZE EVIDENCE                                          │           │
│           │ Research worker · campaign-research                                      │           │
│           │ Review internal context and external sources; obey approved limits.      │           │
│           │ Output: research/findings.md + research/summary.md                       │           │
│           └──────────────────────────────────────────────────────────────────────────┘           │
│                                                 │                                                │
│                                                 ▼                                                │
│           ┌──────────────────────────────────────────────────────────────────────────┐           │
│           │ 6  RESOLVE THE DIRECTION                                                 │           │
│           │ Marketing Lead / Chief of Staff + Oleena                                 │           │
│           │ Recommend options and tradeoffs; choose a bounded campaign or test.      │           │
│           │ Output: decisions.md · retain explicit testable assumptions              │           │
│           └──────────────────────────────────────────────────────────────────────────┘           │
│                                                 │                                                │
│                                                 ▼                                                │
│           ┌──────────────────────────────────────────────────────────────────────────┐           │
│           │ 7  DRAFT + CHECK THE BRIEF                                               │           │
│           │ Marketing Lead · campaign-brief                                          │           │
│           │ Define audience, offer, messages, channels, budget and measurement.      │           │
│           │ Output: brief.md + completed review checklist                            │           │
│           └──────────────────────────────────────────────────────────────────────────┘           │
│                                                 │                                                │
│                                                 ▼                                                │
│           ┌──────────────────────────────────────────────────────────────────────────┐           │
│           │ 8  APPROVE + HAND OFF                                                    │           │
│           │ Oleena · checkpoint 3: Gate 1 approval                                   │           │
│           │ Review recommendation, evidence, unresolved choices and exact version.   │           │
│           │ Record: approved brief version + next action / owner                     │           │
│           └──────────────────────────────────────────────────────────────────────────┘           │
│                                                                                                  │
├─ PROTOTYPE + REVISE · throughout the planning conversation ──────────────────────────────────────┤
│                                                                                                  │
│  Unclear choice → small offer card, sample, outline or mock → Oleena reacts                      │
│  Save in prototypes/; record what the reaction clarified in decisions.md.                        │
│  Reaction shows preference, not customer demand. Respect per-run build approvals.                │
│  New evidence changes intent → return to clarification and reconfirm.                            │
│  Research gap → propose targeted scope → approval → additional research.                         │
│  Brief changes requested → revise → check → return for approval.                                 │
│                                                                                                  │
├─ COMPLETION · approved brief, not production ────────────────────────────────────────────────────┤
│                                                                                                  │
│  Check   coherent objective / audience / offer; evidence; feasible test; owners;                 │
│          measurement window; decision rules; time / budget; explicit uncertainty.                │
│  Stop    research limits reached; missing access; material decision; approval needed.            │
│  Handoff approved direction + deliverables + dependencies + exact input versions.                │
│  Next    production workflows are separate; existing approvals still apply.                      │
│                                                                                                  │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```

## Owners and outputs

| Stage | Owner | Output / completion |
| --- | --- | --- |
| Capture | Chief of Staff | intake.md preserves the voice transcript; unclear names/numbers are confirmed |
| Clarify | Chief of Staff with Oleena | intent.md captures goal, why, hypotheses, commitments, constraints and questions; Oleena confirms it |
| Prototype | Assigned worker | prototypes/ contains the smallest useful offer card, sample, outline or mock; reaction is logged |
| Research scope | Research worker, coordinated by Chief of Staff | research/plan.md states decision questions, methods, sources, time and cost limits; Oleena approves |
| Research | Research worker | research/findings.md records sourced observations and limitations; research/summary.md explains implications |
| Decide and draft | Marketing Lead with Oleena | decisions.md records choices; brief.md uses the campaign brief template |
| Review | Chief of Staff and Oleena | Completed checklist, recommendation and version-specific approval in campaign-record.md |

Use the discovery, research and brief skills in skills/README.md. Assign actual workers, not just role names. Start with the existing Chief of Staff and one research worker; Marketing Lead may be the same agent.

## Key rules

- Prototype-maxxing: when further discussion is unlikely to clarify a choice, propose or build a small reversible internal example. Respect existing per-run heavy-production rules; ask for that specific run if needed. Never publish a prototype implicitly.
- No knowledge base is required. Inspect what exists, record gaps, and create only useful campaign context. Do not fill blanks with invented customers, results or brand rules.
- Scope an initiative into a bounded campaign. If the offer is uncertain, define an offer hypothesis and the decision the experiment should unlock.
- Research is decision-led. Approve the approach, estimated active/elapsed time, model/API/tool budget and enforceable limits before starting. Stop at limits; return partial findings and options. Research approval is not media-spend approval.
- Record available usage honestly. When hard dollar enforcement is unavailable, disclose that and agree enforceable run/tool limits instead.
- Bring evidence back before settling the direction. Recommend alternatives and tradeoffs. Material changes to confirmed intent require reconfirmation; new research requires a revised approved scope.
- Save internal links instead of copying canonical documents. Separate observations, inferences and assumptions. Public competitor activity does not prove campaign performance.
- Questions can remain as explicit experiment hypotheses. Blocking gaps in offer, measurement or ownership must be settled before approval.
- Use decisions.md for simple campaigns. Introduce Wayfinder decision tickets only when session length and dependencies warrant them. Keep the map campaign-scoped.

## Campaign folder

Use campaigns/<id>-<slug>/ with intake.md, intent.md, decisions.md, campaign-record.md, brief.md, research/{plan,findings,summary}.md and prototypes/ as needed. Create from templates only when the stage requires them; do not create blank placeholders unnecessarily. One parent issue can link this folder; it is an index, not a competing status record.

## Approval packet

Present exact output paths/revisions, recommendation, evidence, unresolved choices, checks, and the next action. Record person, date, decision, scope and version in campaign-record.md. Approval of intent is not approval of the offer; approval of research is not approval of production; Gate 1 approval does not waive the existing per-run production or launch rules.

## Brief review checklist

- Objective and learning decision are clear.
- Audience, problem, offer, CTA and channel form a coherent journey.
- Claims have evidence; uncertainty is labelled.
- Experiment specifies what changes and what stays stable.
- Primary metric, qualification, data source, evaluation window and decision rules are explicit.
- Clicks/signups/purchases are interpreted at their actual evidentiary strength.
- Deliverables, owners, dependencies, time and budget are feasible.
- Sources, major decisions and prototype feedback are linked.
- Approval references the reviewed version; no production starts prematurely.
