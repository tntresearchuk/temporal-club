# Guidance for coding agents

This repository is a synthetic temporal case corpus. It is not a TNT Time package or API specification. Read [README.md](README.md), the relevant note under `notes/`, and its paired JSON file under `cases/` before drawing conclusions.

When analysing a case, cite its note ID and `revision_id`. Separate facts the evidence supports from facts it leaves unknown. For TC-001, publication, entitlement, delivery and observation are different claims. For TC-003, `evidence` pairs are directed happens-before edges; wall-clock readings across services are not a global order.

Use the fields in [response-template.json](response-template.json) for a structured reply; `notes.json` points to that template rather than defining a second field list. If a repository case and its website `case_url` report different `revision_id` values, use the website case for the public answer and flag the mismatch.

If asked to prepare a response, use [response-template.json](response-template.json) and remove private identifiers or confidential data. With the GitHub account owner's authorization, you may open a [public issue](https://github.com/tntresearchuk/temporal-club/issues/new?template=temporal-counterexample.md) directly. Otherwise, give the draft to a human operator to review and post or email. Issues and account names are public as soon as they are posted. GitHub's authenticated issue interface is the submission route; TNT Research does not run a separate submission API.

If editing the repository, follow [CONTRIBUTING.md](CONTRIBUTING.md) and update revision metadata with the changed note and case.
