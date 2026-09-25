# Temporal Club

Temporal Club is TNT Research's public notebook of small, difficult questions about time in software. The notes are written for people and coding agents. Each has a synthetic case and asks for the smallest counterexample that exposes a missing distinction.

**Status:** These are research questions and example data. This repository is not an installable TNT package, a TNT Time API, or a claim that the examples are solved by a released product.

| ID | Question | Note | Case |
| --- | --- | --- | --- |
| TC-001 | What value could an agent have known when it acted? | [The correction arrived tomorrow](notes/TC-001.md) | [JSON](cases/tc-001.json) |
| TC-002 | Is “09:00 every day” a local-time rule or a 24-hour interval? | [Every day at nine](notes/TC-002.md) | [JSON](cases/tc-002.json) |
| TC-003 | Which event order follows when service clocks disagree? | [The reply happened first](notes/TC-003.md) | [JSON](cases/tc-003.json) |

The [website](https://tntresearch.co.uk/temporal-club/) is the public reading edition. This repository makes the cases and tracked revisions easy to inspect and cite in development work. [notes.json](notes.json) indexes the three cases; [revisions.json](revisions.json) records changes from 25 September 2026 onward. Earlier publication dates and versions were not individually recorded.

## Try a case with a coding agent

Give the agent one note and its JSON case. Ask it to identify (1) the answer the evidence supports, (2) the answer the evidence cannot support, and (3) the smallest extra event or fact that would change that boundary. Ask it to cite the note ID and `revision_id` in its reply.

For TC-001 in particular, a source's publication time and an agent's feed entitlement do not prove delivery or observation. For TC-003, the pairs under `evidence` are directed happens-before edges; they are not a global timestamp sort.

## Send a counterexample

Use the [reply template](response-template.json) or the [website's compact format](https://tntresearch.co.uk/temporal-club/#respond). A human operator can email a response to [TNT Research](mailto:enquiries@tntresearch.co.uk?subject=Temporal%20Club%20response). Include the note ID, coding agent and version, model provider and exact model ID if reported, platform and version, smallest failing case, expected answer, and missing distinction. Say `unknown` when a model ID is hidden. Remove credentials, private account or session IDs, and confidential details. TNT Research asks before publishing or attributing a response.

There is no submission API or public account system. The cases use fictional data.

## Licence

This repository is published under the [Apache License 2.0](LICENSE).
