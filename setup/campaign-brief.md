# Set up campaign brief creation

1. Read the root agent instructions, conventions and brief-creation playbook. Assign the existing GrokBot Chief of Staff as coordinator and identify the actual Marketing Lead/research worker; one agent may cover several roles.
2. Open a local checkout on the Mac. Verify read, edit, commit and push separately; read access alone is insufficient. Read back one harmless test output from another agent, then remove the test artifact before committing.
3. Configure the Chief of Staff to load skills/campaign-discovery/SKILL.md for new campaign ideas. Explicit loading works before runtime skill auto-discovery is configured.
4. Create a campaign folder and campaign-record.md from its template. Preserve the dump in intake.md; run the conversation to confirmed intent. Leave shared business context absent rather than invent it.
5. Have the research worker propose the scope, methods, time and cost; obtain approval. Start one assignment manually, then verify its evidence and output readback.
6. Use campaign-brief to synthesize findings and decisions into brief.md. Obtain Gate 1 approval. Do not change production workflows or prior campaign approvals.
7. Only after a successful handoff, automate GrokBot-to-T3 if useful. Confirm installed-version support and the GrokBot host's capabilities first.

## T3 connection options

T3's current docs describe remote MCP over HTTP with OAuth for outside bots, or t3 thread commands on the host. Hosted bots need a reachable T3 Connect endpoint. Outside bots can launch/message/read/wait for threads; internal-only subagent and browser tools require a worker inside T3. The host must remain available. Do not assume GrokBot supports OAuth/MCP merely because it runs locally.

https://github.com/pingdotgg/t3code/blob/main/docs/user/outside-agents.md

If direct connection is unavailable, Chief of Staff saves an assignment; Oleena starts a T3 thread using the repository paths; the worker saves and commits results; Chief of Staff resumes from them. Do not create another coordinator in T3.

## Assignment contract

Campaign ID; question/outcome; input paths and revisions; methods; time/cost/retry limits; writable paths; checks; return location; escalation conditions. Record thread links and collect committed outputs before dependent work. Refresh existing worker state on resume to avoid duplicate launches.

## Public repository boundary

Store reusable methods and templates here. If campaign details, transcripts or research contain confidential material, use a private campaign repository/storage and pass its approved paths to the same skills. Never commit tokens or private customer records. No external connection or runtime agent is activated by these files.

## First-run acceptance

A voice dump produces confirmed intent, an approved research scope, sourced findings and a reviewed brief with explicit version-specific approval. Test an unclear-offer case with a prototype and a missing-context case. Check that an exhausted research limit returns partial findings and a blocker rather than expanding work.
