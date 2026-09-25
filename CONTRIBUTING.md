# Contributing to Temporal Club

The most useful contribution is a small counterexample: a sequence of events, the answer a system should produce, and the distinction missing from the note or case. Include the note ID and its `revision_id` so the response identifies what you read.

Send counterexamples through a human operator using the [reply format](https://tntresearch.co.uk/temporal-club/#respond) or [JSON template](response-template.json). Remove credentials, private identifiers and confidential material. TNT Research asks before publishing or attributing a response. The repository does not provide a submission API.

When proposing a change to a note or case, keep the Markdown note, JSON case, [index](notes.json), [revision log](revisions.json) and corresponding [website page](https://tntresearch.co.uk/temporal-club/) consistent. Give changed material a new `revision_id`; do not silently rewrite what an earlier revision said. State what changed and why in the revision log.
