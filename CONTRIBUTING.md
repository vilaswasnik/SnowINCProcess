# Contributing to SnowINCProcess

Thanks for looking. This repository is a **process design**, not software: a ServiceNow incident monitoring and assignment process, maintained as a README plus a flow diagram. Contributions are improvements to the process — clearer phases, better SLA targets, extra templates, real-world corrections — and they are very welcome from anyone who runs an incident queue.

## The one rule that matters most

**Keep the diagram and the text in sync.** The process lives in two files that must agree:

- `INC-Monitoring-Assignment.drawio` — the editable diagram source
- `INC-Monitoring-Assignment.png` — the rendered diagram the README embeds

If your change alters the flow, edit the `.drawio`, re-export the PNG (same filename), and include **both** files plus the README text in the same pull request. A PR that changes only the text or only the diagram will be asked to complete the set.

## Proposing a change

1. Open an issue first for anything substantive: which phase or SLA you're changing, what problem it solves in a real queue, and what you'd change it to. War stories (anonymised) are persuasive.
2. Fork, branch from `main`, and make the change in the README, the `.drawio`, and the PNG together.
3. Keep the README's structure: problems → workflow → SLA matrix → implementation → metrics. Version-footer the change ("Updated: <month year>") if it alters the process itself.
4. One approval from the maintainer merges.

## What makes a good contribution here

- **Templates** — work-notes, customer-notification, and escalation templates that match the phases.
- **Worked examples** — an anonymised incident walked through all 5 phases with timings.
- **Adaptations** — how the process changes for follow-the-sun teams, smaller teams, or non-ServiceNow tooling (Jira Service Management, etc.), clearly marked as variants.
- **Metric definitions** — precise definitions for the success metrics so two teams measure the same thing.

## Filing issues

Use GitHub Issues for gaps, ambiguities ("what happens when the whole team is at capacity in Phase 3?"), and real-world reports of running the process. There is no code to break, so there are no bad questions — ambiguity in a process document *is* a bug.
