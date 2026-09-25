# OctoAcme — Project Status Reporting

## Purpose
Provide a consistent, evidence-based update on delivery progress, upcoming work, risks, blockers, and decisions so teams and stakeholders can act quickly.

## Cadence and Ownership

- The Project Manager prepares the weekly delivery status update and coordinates input from the Product Manager, developers, QA, and dependency owners.
- Project teams review progress and blockers in daily standups and the weekly delivery sync.
- Stakeholders receive updates weekly or at milestone boundaries; the Project Manager escalates material issues outside that cadence when needed.

## Inputs

Build reports from current project artifacts:

- Project plan, roadmap, and milestone dates
- Project board and sprint or iteration backlog
- Completed work, pull requests, test results, and demos
- Success-metric dashboards
- Risk register, dependency tracker, and decision log
- Prior status report

Report verified facts. If an input is missing or stale, identify the gap instead of estimating or presenting an assumption as confirmed progress.

## Standard Status Report

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

## Status Definitions

- **Green:** delivery is on track and no material action is required.
- **Amber:** a material risk, dependency, or variance needs active management.
- **Red:** a material issue threatens agreed outcomes and requires escalation or a decision.

## Escalation and Quality Checks

Escalate blockers through the defined path: team-level triage, then the Project Manager to the Product Lead and dependent teams, then sponsor-level escalation for business-impacting issues.

Before publishing, confirm that reported progress is evidence-based, risks are distinct from confirmed blockers, commitments include owners and dates where known, and decision requests are specific and actionable. Tailor detail to the audience while retaining the current overall status and material changes.
