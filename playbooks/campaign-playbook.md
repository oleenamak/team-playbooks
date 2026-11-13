# Campaign Playbook

Version: 0.1 — working draft
Process owner: Chief of Staff
Final approver: Oleena, unless a campaign names another approver

## Purpose

Turn a campaign idea into an approved, launched, and measured campaign. Coordinate specialist leads, preserve decisions, and turn results into the next experiment.

Use this process for campaigns requiring a brief, copy, design, production, launch, and analysis. Scale the depth to the campaign: a single email needs less documentation than a multi-channel launch, but still needs a clear objective, approved output, and measurement.

## Roles & Responsibilities 


| Team Member    | Responsibility                                                                                                                                                                       |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Chief of Staff | Maintain the campaign record; gather missing inputs; delegate work; check completeness and alignment; coordinate revisions; present approval requests; track blockers and follow up. |
| Marketing Lead | Own the brief creation, hypothesis, audience, offer, channel strategy, messaging, copywriting, etc.                                                                                  |
| Creative Lead  | Translate approved messaging into visual directions and production-ready designs                                                                                                     |
| Engineer Lead  | Build assets, configure distribution, implement measurement, and complete launch checks                                                                                              |
| Analyst Lead   | TBD (no bot yet; Chief of Staff/Product Lead cover Gate 6 for now). Evaluate results, qualify uncertainty, and recommend the next test                                                                                                                   |
| Approver (me)  | Approve, request changes, or stop the campaign at each gate                                                                                                                          |


## Tools & Access Required


| Tool                   |   |
| ---------------------- | ------ |
| Github                 |   |
| Campaign Tracker Sheet |   |
| Multica                | not connected yet |


## Operating rules

1. Start each stage from the approved inputs. Do not invent product claims, customer evidence, performance data, budgets, or approvals. Label assumptions and resolve material gaps before approval.
2. Produce work autonomously within the approved scope. Pause at approval gates. A completed draft is not an approved draft.
3. Record approval against a specific deliverable version, with the approver and date. Silence is not approval.
4. Bring one consolidated review request per gate: output links, recommendation, unresolved decisions, and the requested approval.
5. If feedback changes an approved audience, offer, message, budget, or scope, identify affected work and reopen the relevant gate before continuing that work.
6. Keep each campaign's state in its campaign record. Do not rely on chat history as the only record.
7. Never publish, send, activate spend, or change a live campaign without authorization covering the exact action and scope. Creative approval alone is not launch authorization.
8. If work is blocked or fails, record what happened, the owner, and the next action. Check whether an action already succeeded before retrying a send, publication, or launch.

## Campaign record

Create one record per campaign, with linked tasks for individual deliverables.

- Campaign ID and name
- Objective and hypothesis
- Campaign owner and specialist assignees
- Current stage and status: in progress / awaiting approval / changes requested / blocked / complete
- Target launch date and evaluation date
- Brief and deliverable links, including version identifiers
- Approval log: gate, version, decision, approver, date, feedback
- Budget and authorized launch scope
- Blockers, next action, and next-action owner
- Measurement source, live URLs, results, and learning summary

## 1. Create the campaign brief — Gate 1

**Owner:** Marketing Lead

Handoff to Marketing Lead to draft a brief using the `campaign-brief.md` template.

### Gate 1 approval

Ask the approver to review and approve the brief. Surface unresolved assumptions explicitly.

## 2. Draft copy — Gate 2

**Owner:** Marketing Lead

Hand back to Marketing Lead to draft all copy required for the assets using product marketing and copy writing skills.

### Gate 2 approval

Present the copy set, recommended direction, and any open claims or decisions. Record the approved copy version. Copy may be adjusted for layout later; material message or offer changes require renewed approval.

## 3. Draft the design direction — Gate 3

**Owner:** Creative Lead

- Collect visual references and brief notes explaining what to borrow: layout, hierarchy, typography, imagery, or tone.
- If provided, use the referenced colors, logos, fonts, and brand assets.
- Create a small set of distinct visual samples; default to two directions unless the brief suggests otherwise.
- Use representative approved copy so the samples reflect real content.
- Explain how each direction supports the audience, message, and channel.

### Gate 3 approval

Select one direction and record its sample, feedback, and production guidance. Do not expand all assets before a direction is selected.

## 4. Build assets — Gates 4

**Owner:** Engineer Lead

- For landing pages, handoff to build in Claude
- Maintain an asset register showing each asset's owner, version, destination, and review status.
- Check consistency across assets, formats, links, and the audience's path to conversion.
- Present the completed set for approval. Record any exceptions or outstanding dependencies.

## 5. Prepare and launch — Gate 5

### Launch readiness

The build/operations lead prepares a launch packet confirming:

- All required assets and destinations are approved and accessible.
- Links, forms, routing, and conversion actions have been tested where applicable.
- Tracking parameters and conversion events are configured and checked.
- Targeting, exclusions, schedule, budget, and sending/publishing accounts match the brief.
- A named person owns launch monitoring, and there is a clear pause or rollback action.
- The first operational check and the later performance review are scheduled separately.

### Gate 5 approval and execution

Request launch authorization for the specific channels, assets, audience, budget, and schedule. After authorization, execute only through connected tools that support the action. If access is unavailable, hand off a precise checklist to the responsible person and mark the launch pending.

Record what actually launched, when, live links, and any failures or deviations. Confirm execution before marking the campaign live. During the initial check, verify delivery, destinations, tracking, and spend behavior; avoid declaring campaign success from early signals.

## 6. Analyze and feed learning back — Gate 6

### Work

- Pull results from the agreed sources and state the reporting period, spend, and data limitations.
- Compare the primary KPI with the target and baseline; use supporting metrics to diagnose the funnel.
- Distinguish observed facts, interpretations, and hypotheses.
- Do not imply causation or statistical confidence unsupported by the experiment design and data. State when results are inconclusive.
- Identify what the campaign suggests about audience, offer, message, creative, and channel.
- Recommend stop, iterate, or scale, with the evidence and tradeoffs.
- Propose the next hypothesis, the change to test, expected learning, and success criterion.

### Gate 6 decision

Present the learning review for a decision. Record the outcome in the campaign record and add approved follow-up experiments to the backlog. Changes to a live campaign or budget require the relevant authorization before execution.

## Standard handoff

For every delegated task, provide:

- Campaign ID, stage, and assigned owner
- Goal and expected output
- Approved input links and versions
- Relevant skills and references
- Constraints and completion criteria
- Output location and deadline
- Where to return the work and what requires approval

The assignee returns the output link/version, checks completed, assumptions, blockers, and recommendation. The Chief of Staff checks alignment before presenting it for approval.

## Standard approval request

Campaign / gate:  
Deliverable links and versions:  
Recommendation and rationale:  
Open decisions or tradeoffs:  
Decision requested: approve / request changes / stop  
Next action after approval:

## How to start the first campaign

Give the Chief of Staff the initial campaign idea and this playbook. Ask it to create the campaign record, identify only the information needed to complete the brief, assign the actual leads, and return a Gate 1 review packet. Run one campaign through the process before deciding which recurring steps to automate.

Keep this playbook reusable. Store campaign-specific facts, outputs, approvals, and results in their campaign records. After each campaign, propose improvements to the playbook for review.
