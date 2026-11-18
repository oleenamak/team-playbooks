---
name: landing-page
description: Takes an approved brief to landing page copy, a review pass, and a build handoff. Use at Gate 2 when someone says "write the landing page copy" or "draft the page for this campaign."
reads: [playbooks/CONVENTIONS.md, playbooks/landing-pages.md, templates/landing-page.md, approved brief, brand guidelines, research summary]
writes: [campaigns/<campaign>/landing-page.md]
---

# Landing Page Copy

I write the copy first and the build second. Copy is Gate 2. The build renders the approved copy word for word.

Read ../../playbooks/CONVENTIONS.md and ../../playbooks/landing-pages.md first. Then load the approved brief (exact version), the brand guidelines, the research summary, and any past campaign copy.

## 1. Check the inputs

I stop and ask if any of these are missing.

- A brief with a recorded Gate 1 approval, and its version.
- The offer, the one conversion action, and the target audience.
- Where traffic comes from. Paid traffic means the first screen must repeat the ad's promise, so I need that promise from the brief's key messages.
- What proof exists. "None yet" is a valid answer. I never invent testimonials, numbers, logos, member counts, or dates.

## 2. Fill in the control block

Before any copy, I fill in the control block at the top of the template: offer, audience, allowed claims, forbidden claims, available proof, top objections, CTA, and form fields. A claim with no evidence goes in forbidden claims, with the evidence that would unlock it.

## 3. Draft from the template

I copy ../../templates/landing-page.md to `campaigns/<campaign>/landing-page.md` and draft one section at a time. For each section I write two or three candidates, keep the best, and lock it. Then I read the whole page once for flow.

- Every section has one job and answers one visitor question, in the order a skeptic asks: what is this, is it for me, how does it work, what's the catch, what now.
- One conversion action. One CTA label, repeated.
- With more than one variation, sections are shared. Only the hero, the offer line, and the CTA differ, and each variant is named per the campaign naming convention.
- Use the audience's own words from research when I have them. Plain, specific, and short beats clever.

## 4. Review before anyone sees it

I run this pass and fix what fails. Usually it takes two rounds.

| Check | Pass means |
| --- | --- |
| Three-question gate | Every line can be pictured, can be proven true or false, and could not be pasted onto a competitor's page. |
| Claim audit | Every claim is in allowed claims or backed by a source. Nothing implies proof we don't have. |
| 5-second test | The hero alone says what this is, who it's for, and what to do next. |
| Promise match | For ad traffic, the ad's exact phrase appears in the headline or the line under it. |
| Friction count | Form fields and exit links match the control block. Each field has a reason. |
| Brand and compliance | Brand guideline rules hold. Required disclosures and consent text are present. |
| AI tells | No filler phrases ("unlock", "seamless", "game-changer"), no "it's not X, it's Y" patterns, no stacked punchy lines. |

I record the result in the template's review block. If a fix would change the audience, offer, or promise, I reopen Gate 1 instead of quietly changing it.

## 5. Present one Gate 2 packet

I follow the output contract in CONVENTIONS: the copy file path, the version, sources and assumptions, the open questions in the template with room for `[Approver initials]` answers, and what needs Oleena's yes. I send it to Chief of Staff, not to anyone else, and stop. Draft complete is not approved.

## 6. Build handoff

After Gate 2 approval, Chief of Staff records the approved version in campaign-record.md. Then:

- The approved file is the source of truth. If a section reads weak during design or build, it goes back to Gate 2. Nobody rewrites copy in the build.
- Creative Lead gets the approved copy, the control block, and the section list for Gate 3.
- Engineer Lead gets the approved copy plus `architecture.md` (page job, section plan, friction budget) for Gate 4, per ../../playbooks/landing-pages.md.
- Builds go to preview only. Publishing needs Oleena's explicit yes.

## Borrowed ideas

I adapted these in my own words, and nothing is copied. All are MIT licensed, checked Nov 18, 2026.

| Idea | Source |
| --- | --- |
| Diagnose the input first, the three-question gate, claims must be supportable | [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills), copywriting skill |
| Every form field has a cost | [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills), cro skill, form reference |
| Control block of allowed and forbidden claims before drafting | [TheMattBerman/landing-page-factory](https://github.com/TheMattBerman/landing-page-factory), page-copy skill |
| Human approval gates, hero checklist, never invent proof | [joychetry/landing-page-system](https://github.com/joychetry/landing-page-system) |
| Glance test: a stranger gets it in a few seconds | [lodar/caveman-marketing](https://github.com/lodar/caveman-marketing) |
