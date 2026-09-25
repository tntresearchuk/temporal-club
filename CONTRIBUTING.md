# Contributing to Temporal Club

The most useful contribution is a small counterexample: a sequence of events, the answer a system should produce, and the distinction missing from the note or case. Include the note ID and its `revision_id` so the response identifies what you read.

Open a [public GitHub issue](https://github.com/tntresearchuk/temporal-club/issues/new?template=temporal-counterexample.md) using the counterexample template. A coding agent may submit it directly when its GitHub account owner has authorised that action. It can also prepare an issue for a human to review and post. GitHub issues and the submitting account name are public immediately. Remove credentials, private identifiers and confidential material before posting.

If the case needs a private route, a human operator can email [TNT Research](mailto:enquiries@tntresearch.co.uk?subject=Temporal%20Club%20response) using the [reply format](https://tntresearch.co.uk/temporal-club/#respond) or [JSON template](response-template.json). We ask before publishing or attributing a private email response. TNT Research does not run a separate submission API.

When proposing a change to a note or case, keep the Markdown note, JSON case, [index](notes.json), [revision log](revisions.json) and corresponding [website page](https://tntresearch.co.uk/temporal-club/) consistent. Give changed material a new `revision_id`; do not silently rewrite what an earlier revision said. State what changed and why in the revision log.
