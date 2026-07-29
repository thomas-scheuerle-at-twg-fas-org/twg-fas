# Decision-Making Policy

This document defines how TWG-FAS makes decisions in the founding phase.

## 1. Principles

Decision-making is guided by:

- consensus before voting
- technical merit over organizational power
- transparent rationale and traceability
- fair handling of objections
- practical forward progress

## 2. Decision Types

TWG-FAS uses three decision classes.

1. Editorial
Changes that do not alter technical meaning (formatting, wording clarity, typo fixes, cross-reference cleanup).

2. Technical
Changes that alter requirements, semantics, interfaces, conformance expectations, or interoperability behavior.

3. Governance/Process
Changes to roles, workflow rules, voting criteria, publication status, and governance documents.

## 3. Consensus Workflow

Default workflow:

1. Open discussion in issue, pull request, or meeting record.
2. State the specific decision text.
3. Capture objections with technical rationale.
4. Propose revisions to address objections.
5. Call for consensus with a clear response window.

Recommended default response windows:

- Editorial: 5 calendar days
- Technical: 10 calendar days
- Governance/Process: 14 calendar days

A consensus call is successful when no unresolved, technically grounded objection remains at close.

## 4. Escalation to Vote

If consensus is not reached in reasonable time, the decision may move to a vote.

Vote thresholds in founding phase:

- Technical decisions: at least 2/3 yes from valid votes cast
- Governance/process decisions: at least 3/4 yes from valid votes cast

Abstentions are recorded but do not count as yes or no.

## 5. Eligibility and Participation

In the founding phase, valid votes are cast by recognized active participants in the affected scope (maintainers, editors, and designated working group participants).

Eligibility should be listed in the decision record before the vote opens.

## 6. Quorum and Validity

TWG-FAS prefers explicit participation evidence over strict quorum formulas in early stages.

A vote should only close if there is sufficient participation to justify legitimacy, and maintainers should document why participation is sufficient.

## 7. Conflict of Interest

Participants must disclose conflicts when they may materially influence neutrality.

Examples:

- direct commercial dependency on a proposed requirement
- proprietary control over an interface under discussion
- financial or organizational influence on decision outcome

Disclosure does not automatically remove participation, but unresolved high-risk conflicts may require recusal from final vote.

## 8. Appeals

A recorded decision may be appealed when there is evidence of:

- process violation
- material information omitted during decision
- conflict-of-interest handling failure

Appeals should be filed within 21 calendar days from decision publication.

Appeal outcomes:

- uphold decision
- reopen decision with targeted scope
- invalidate and rerun decision process

## 9. Decision Records

Every non-trivial technical or governance decision should include:

- context and decision question
- options considered
- rationale for final outcome
- objection summary and resolution status
- vote results (if voting occurred)
- links to supporting issues and pull requests

Record location should be stable and discoverable in the repository.
