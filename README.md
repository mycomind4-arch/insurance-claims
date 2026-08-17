# Insurance Claims

**Status: Planned vertical — do not build yet.**

## Product thesis

Turn a confusing insurance claim into an evidence-backed case record: understand the claim position, organize supporting documents, track events and deadlines, and prepare a clear response or appeal.

Core journey:

**Claim → Coverage/Documents → Evidence → Timeline → Gaps → Response/Appeal → Review → Mail/Proof**

## Primary search intent

- insurance claim response
- denied insurance claim appeal
- underpaid insurance claim
- insurance demand/response letter
- homeowners claim dispute
- property damage claim
- insurance documentation

## MVP

1. Upload claim correspondence, policy excerpts, estimates, photos, and other documents.
2. Extract claim numbers, dates, parties, amounts, stated reasons, and requested information.
3. Build a source-linked claim timeline.
4. Compare asserted facts against supporting evidence.
5. Identify missing documents/questions for human review.
6. Draft a factual response or appeal for review.
7. Hand off the approved document to MailMyPDF.

## Reuse

Use shared evidence, provenance, timeline, deadline, and document infrastructure. FairProcess should supply procedural reasoning where appropriate; FairProcessMaps patterns may inform evidence/property context. Avoid creating a parallel intelligence stack.

## Guardrails

Never invent coverage, policy interpretation, claim entitlement, or legal conclusions. Distinguish policy text, insurer statements, user-provided facts, extracted facts, and generated suggestions.

## Future

Jurisdiction/insurance-type playbooks, estimate comparison, correspondence tracking, and advanced contradiction analysis should follow a working MVP.
