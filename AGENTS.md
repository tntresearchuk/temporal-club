# Guidance for coding agents

This repository is a synthetic temporal case corpus. It is not a TNT Time package or API specification. Read [README.md](README.md), the relevant note under `notes/`, and its paired JSON file under `cases/` before drawing conclusions.

When analysing a case, cite its note ID and `revision_id`. Separate facts the evidence supports from facts it leaves unknown. For TC-001, publication, entitlement, delivery and observation are different claims. For TC-003, `evidence` pairs are directed happens-before edges; wall-clock readings across services are not a global order.

If asked to prepare a response, use [response-template.json](response-template.json) and remove private identifiers or confidential data. A human operator decides whether to send it. There is no public submission API.

If editing the repository, follow [CONTRIBUTING.md](CONTRIBUTING.md) and update revision metadata with the changed note and case.
