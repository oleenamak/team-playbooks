# Landing Page Conventions

Landing page work at gates 3-4: section architecture, build standards, and the pre-ship checklist.

## Copy is source of truth

Approved copy lives in its own file (typically `landing-page.md` or `copy.md` in the campaign folder). The build renders that copy verbatim — word for word, including headline, subhead, CTA labels, and offer details.

If a section reads weak during the build, it goes back to gate 2 (copy) for revision and re-approval. The build does not quietly rewrite copy to "fix" it. Copy changes require the copy gate; the build gate implements approved copy exactly as written.

## Section architecture before building

Before starting the build, write a short section plan to `architecture.md` in the campaign folder. This documents:

1. **The page's one job** — what action the page exists to drive (email capture, booking, call, quote request, purchase)
2. **One job per section** — what visitor question each section answers, in the order a skeptic would ask (what is this → is it for me → does it work → what's the catch → what now)
3. **The section list** — named sections in reading order, with each section's purpose
4. **Friction budget** — number of form fields, steps, decisions, and exit links the page will have

The section list determines what gets built and in what order. It also sets the baseline for future optimization: when the page is later evaluated or torn down, the architecture file shows what was intentional.

## The 5-second phone test (ship bar)

Before a page ships, it must pass this test at 375px width:

**Can a visitor tell in 5 seconds:**
1. What this is
2. Who it's for
3. What to do next

Test method: show someone only the first screen (above the fold) on a phone for 5 seconds. They should be able to answer all three questions. If they can't, the page is not ready.

### Promise match for ad traffic

When the page receives paid ad traffic, the first screen repeats the ad's promise word for word. Not paraphrased, not summarized — the exact phrase from the ad appears in the headline or the line directly under it.

Example: if the ad says "Free for teams under 10," the hero says "Free for teams under 10," not "Affordable plans for growing teams." A visitor arriving from an ad is scanning for the phrase they clicked. A paraphrase reads as a different offer, and they leave.

Write the ad's exact text into `architecture.md` next to the planned headline so the pre-ship check can verify the match.

## Preview deploys only

Builds deploy to preview/staging environments by default. A production deploy — the version that receives live traffic, replaces the current live page, or goes on the domain visitors see — happens only on Oleena's explicit yes.

The distinction:
- **Preview deploy:** safe to run. Used for review, testing, and approval. Can be rebuilt and redeployed freely.
- **Production deploy:** requires authorization. This is a "ship" action covered by the hard rules.

If the build is handed off rather than deployed directly (for example, a single-file HTML page sent to someone else to host), note clearly in the handoff that it is not yet live and requires Oleena's approval before publishing.

## Pre-ship checklist

Run these checks before presenting a landing page for ship approval. Fix and recheck (usually takes 2 passes). Show only the passing page; note anything still off in one line in Sources and assumptions.

- [ ] **Copy match:** Diff the rendered page text against the approved copy file. Headline, subhead, price, CTA labels, and offer details match verbatim.
- [ ] **5-second test passes** at 375px width: a visitor can tell what it is, who it's for, and what to do next from the first screen alone.
- [ ] **Promise match (ad traffic only):** The ad's exact promise from `architecture.md` appears word for word on the first screen.
- [ ] **Section plan executed:** The built page matches the approved section list in `architecture.md` (no sections quietly added or cut during build).
- [ ] **Friction budget:** Form fields, steps, and exit links match the counts documented in `architecture.md`.
- [ ] **Preview deploy only:** The build is in a staging or preview environment, not production.
- [ ] **Next action clear:** The deliverable states what needs Oleena's yes before the page goes live.

## Files produced

Landing page work typically produces:

```
./campaigns/{campaign-name}/
├── copy.md or landing-page.md    # approved copy (gate 2)
├── architecture.md                # page job, section plan, friction budget (gate 3)
├── page/                          # built page files (gate 4)
│   ├── index.html                 # or Next.js component files
│   └── variants/                  # A/B variant files if applicable
└── notes.md                       # working notes, diff results, check outcomes
```

Copy lives separately from the build so it can be diffed, versioned, and re-approved without touching code.
