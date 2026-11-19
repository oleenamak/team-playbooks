---
name: landing-page
description: Takes an approved brief to landing page copy, a claims check, and a build handoff. Use at Gate 2 when someone says "write the landing page copy" or "draft the page for this campaign."
reads: [playbooks/CONVENTIONS.md, playbooks/landing-pages.md, templates/landing-page.md, approved brief, brand guidelines, research summary]
writes: [campaigns/<campaign>/landing-page.md]
---

# Landing Page Copy

I write the copy first and the build second. Copy is Gate 2. The build renders the approved copy word for word.

Read ../../playbooks/CONVENTIONS.md and ../../playbooks/landing-pages.md first. Then load the approved brief (exact version), the brand guidelines, the research summary, and any past campaign copy. I answer every question from those files. If a file doesn't say, the answer is unknown.

## 1. Check the inputs

I stop and ask if any of these are missing. I don't guess and I don't start drafting.

| Needed | Why |
| --- | --- |
| Brief with a recorded Gate 1 approval, and its version | The copy has to match what was approved. |
| Offer, the one conversion action, and the audience | The page has one job. |
| Traffic source and the ad's exact promise | Paid traffic must see the same promise on the first screen. |
| What proof exists, even if the answer is "none yet" | I never invent testimonials, numbers, logos, member counts, dates, hosts, or prices. |
| Where form data goes, and who owns the follow-up | The success message can only promise what someone will do. |

## 2. Fill in the control block

I fill in the control block in the template before writing any copy, and I print it in the reply. A claim with no source goes in forbidden claims, with the evidence that would unlock it.

| Item | What goes in it |
| --- | --- |
| Offer | What they get, in one line. |
| Allowed claims | Each claim with its source in the brief. |
| Forbidden claims | Each claim and the evidence that would unlock it. |
| Available proof | A list, or "none yet." |
| Objections | Each as a question and answer. If the brief has no answer, the answer is a question for the approver. |
| CTA | One label per variation. |

## 3. Plan the sections

I fill in the section table before drafting. Each section has one job and answers one visitor question, in the order a skeptic asks: what is this, is it for me, how does it work, what's the catch, what now. I drop a section if the brief gives it nothing true to say, and I note that in the table.

## 4. Draft

I draft one section at a time, then read the whole page once for flow.

**Headline and CTA options.** For the hero and the CTA, I write three options with one reason each and mark my pick. The approver can change the pick at Gate 2.

**Variations.** The page is one file. Sections are shared. Only the hero and the CTA differ, and each variation is named per the campaign naming convention in CONVENTIONS.

**Three questions for every line.**

1. Can a reader picture it?
2. Can it be proven true or false from the brief?
3. Could a competitor paste it onto their page?

A line fails if the answer to the first two is no, or the third is yes. I rewrite it from the facts. I don't swap synonyms.

**Banned patterns.** I search the draft for these before I show it.

| Pattern | Example |
| --- | --- |
| Contrast reveal | "It's not X, it's Y." "Not just X, but Y." |
| Negation list | "No X, no Y, no Z." |
| Question then answer | "The result? Faster." |
| Trailing pile-on | A full claim, then a comma and a run of extra benefits. |
| Stacked fragments | Three short punchy lines in a row. |
| Filler words | "unlock," "seamless," "game-changer," "elevate," "journey" |
| Em-dashes | Use a period or a comma. |
| Statistics with no source | Any number the brief doesn't contain. |

**Self-check.** I read every sentence over 20 words and read the page aloud. Then I fix what sounds written instead of said.

**Missing facts.** Where a fact is missing, I write `[NEED: what is missing. Unlock: what would settle it]` in the copy and list it in the open questions. I never fill it with a plausible guess.

## 5. Write the form

I fill in the form table and the form states in the template. Each field stays only if it has a reason. The success message shows only after the data is stored, and it promises only what the control block says someone will do. Any form behavior I haven't run is marked "not tested."

## 6. Review before anyone sees it

First I cut repeats. A line that says what an earlier line already said is deleted, not reworded. Then I mark each check pass or fail, with a note on every fail. There are no scores.

| Check | Pass means |
| --- | --- |
| Claims | Every claim is in allowed claims or has a source. Nothing implies proof we don't have. |
| Lines | Every line passes the three questions. No banned patterns remain. |
| First screen | The hero alone says what this is, who it's for, and what to do next. |
| Promise match | For ad traffic, the ad's exact phrase is in the headline or the line under it. |
| Form | Fields match the control block, and each has a reason. Required disclosures are present. |
| Brand | The brand guideline rules hold. |

I fix every fail and run it again. If a fix would change the audience, offer, or promise, I reopen Gate 1 instead of quietly changing it.

## 7. Present one Gate 2 packet

I follow the output contract in CONVENTIONS: the copy file path, the version, sources and assumptions, the open questions with room for `[Approver initials]` answers, and what needs Oleena's yes. The packet includes the checks table from the template, where anything not run says "not tested." I send it to Chief of Staff and stop. Draft complete is not approved.

## 8. Build handoff

After Gate 2 approval, Chief of Staff records the approved version in campaign-record.md. Then:

- The approved file is the source of truth. If a section reads weak during design or build, it goes back to Gate 2. Nobody rewrites copy in the build.
- Creative Lead gets the approved copy, the control block, and the section table for Gate 3.
- Engineer Lead gets the approved copy and the form table and states for Gate 4, per ../../playbooks/landing-pages.md.
- Builds go to preview only. Publishing needs Oleena's explicit yes.

## Sources

I adapted these ideas in my own words. Nothing is copied. All three are MIT licensed, checked Nov 19, 2026.

| Idea | Source |
| --- | --- |
| Section table, form table, form states, claims table, "not tested" wording | [Pageree/landing-page-guru-skill](https://github.com/Pageree/landing-page-guru-skill) |
| Stop-if-missing check, control block, proof and objections as question and answer, cut-repeats pass | [TheMattBerman/landing-page-factory](https://github.com/TheMattBerman/landing-page-factory) |
| Three-question line gate, banned patterns, self-check, `[NEED: ...]`, headline and CTA options | [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) |
