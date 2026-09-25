---
name: project-status-reporting
description: Create concise, evidence-based project status reports that communicate progress, upcoming work, risks, blockers, and decisions needed. Use when asked to prepare a weekly, sprint, milestone, or stakeholder project update.
---

# Project Status Reporting

Create an accurate report that gives each audience the information needed to act without duplicating project artifacts.

## Gather evidence

Use the project plan, board, milestone, recent pull requests, risk register, decision log, and prior status report where available. Distinguish confirmed facts from assumptions, and never imply that incomplete work is complete.

If information is unavailable, identify the gap in the report rather than inventing a status. Confirm the reporting period, audience, and delivery format when they materially affect the report.

## Produce the report

Use this structure unless the user supplies another format:

```markdown
# Project Status — <project name>

**Reporting period:** <start date>–<end date>
**Overall status:** Green | Amber | Red

## Progress this period
- <completed outcome or measurable progress>

## Next period
- <planned work, owner, or milestone>

## Risks and blockers
- **<risk or blocker>:** <impact>; <owner>; <mitigation or escalation>

## Decisions or support needed
- <specific decision, accountable person, and needed-by date>
```

Set the overall status based on delivery confidence, scope, schedule, dependencies, quality, and unresolved risks:

- **Green:** delivery is on track and no material action is required.
- **Amber:** a material risk, dependency, or variance needs active management.
- **Red:** a material issue threatens agreed outcomes and requires escalation or a decision.

Keep updates outcome-focused, specific, and concise. Include owners and dates for commitments, mitigations, and decisions when known. Escalate blockers through the documented project path: team triage, then Project Manager and Product Lead, then sponsor-level escalation for business-impacting issues.

## Review before sharing

- Ensure each reported item is supported by project evidence.
- Separate risks from confirmed blockers.
- State changes since the prior report.
- Ensure decisions requested are actionable and assigned.
- Remove internal detail that is not appropriate for the audience.
