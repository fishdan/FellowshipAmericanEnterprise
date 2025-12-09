# Feature Spec: 001-nonprofit-formation

## Overview
- Purpose: Produce all legal and operational artifacts required to form and maintain a U.S. 501(c)(3) nonprofit for Fellowship for American Enterprise (North Carolina incorporation).
- Outcome: A complete, reviewable, and board-approved formation package with repository-based governance, ready for filing and ongoing compliance.

## Goals & Success Criteria
- All mandatory formation documents drafted, reviewed, and stored under `documents/` with metadata and versioning.
- Board-ready packet including Articles, bylaws, COI policy, initial resolutions, and organizational minutes.
- EIN application information compiled and ready to submit (SS-4 flow).
- IRS exemption packet prepared (1023-EZ eligibility or full 1023 requirements, narratives, budgets, schedules).
- State-level charity/solicitation registration steps documented for North Carolina.
- Compliance calendar, donor acknowledgment procedure, and document retention policy in place.
- Open questions captured with owners and blocking items resolved before filing.

## Users & Stakeholders
- Board of Directors (approvers and fiduciaries).
- Secretary/Compliance lead (records, filings, calendars).
- Treasurer/Finance lead (budgets, donor receipts).
- Volunteers drafting documents and templates.
- External reviewers (legal/accounting) if engaged.

## Scope
- In-scope: Formation documents, policies required for 501(c)(3) compliance, EIN, IRS exemption filing prep, state incorporation and solicitation registration, governance workflows, repository structure.
- Out-of-scope: Program delivery specifics, fundraising campaign materials, detailed technology platform build-out beyond compliance records, HR hiring processes.

## Requirements
- Mission statement aligned to `mission.txt`.
- Articles of Incorporation (NC) including charitable-purpose and dissolution clauses compliant with IRS language.
- Bylaws covering board composition, meetings, voting, officers, committees, indemnification, conflicts, records, fiscal year.
- Conflict of Interest policy and annual disclosure process.
- Initial Board Resolution(s) approving Articles, bylaws, officers, banking, and filings.
- Organizational Meeting Minutes documenting approvals and appointments.
- EIN application steps (SS-4 details, responsible party, submission flow).
- IRS Form 1023-EZ eligibility checklist or full 1023 requirements (narratives, activities, 3-year budget, schedules, public charity status).
- State-level charity registration steps for NC (and foreign if needed).
- Recordkeeping requirements and retention policy aligned to IRS/state needs.
- Donor acknowledgment procedure with IRS-compliant receipt language.
- Compliance calendar (federal/state filings, board cadence, annual reviews).
- Repository conventions for storing and approving documents via Git/PRs.

## Success Metrics
- 100% of required documents present with metadata and version labels.
- Board approvals recorded in minutes/resolutions for governing docs.
- Eligibility determination (EZ vs. full) documented with rationale.
- Compliance calendar populated with at least one-year horizon of deadlines.

## Constraints
- IRS-required organizing language for purpose and dissolution.
- North Carolina nonprofit corporation statute requirements (e.g., registered agent, incorporator, minimum directors).
- IRS 1023-EZ eligibility thresholds (gross receipts, assets, activity limits).
- Nonpartisan activity and private inurement prohibitions.
- Document naming/versioning per repository conventions.

## Assumptions
- Organization will incorporate in North Carolina and solicit donations nationally only after required registrations.
- Board will review/approve via Git-based workflow.
- Volunteers can draft from templates; legal review may be limited unless arranged.

## Open Questions
- Final NC registered agent and principal office address.
- Initial directors and officers (names, roles, staggered terms).
- Fiscal year end.
- Banking institution and signatory policy specifics.
- Whether projected revenue/activities keep us eligible for 1023-EZ.
- Whether we will register for charitable solicitations outside NC in year one.

## Deliverables (Files)
- `documents/mission-statement.md`
- `documents/articles-of-incorporation-nc.md`
- `documents/bylaws.md`
- `documents/conflict-of-interest-policy.md`
- `documents/board/resolutions/RES-001-initial-board-actions.md`
- `documents/board/minutes/organizational-meeting.md`
- `documents/ein/ss-4-workup.md`
- `documents/irs/1023-ez-eligibility-checklist.md` (or `1023-full-requirements.md` if not eligible)
- `documents/irs/activities-narrative.md`
- `documents/finance/three-year-budget-template.xlsx` (or `.md` table if no spreadsheet use)
- `documents/compliance/charity-registration-nc.md`
- `documents/compliance/compliance-calendar.md`
- `documents/compliance/donor-acknowledgment-procedure.md`
- `documents/compliance/document-retention-policy.md`

## Out of Scope
- Program implementation manuals and technology build-outs.
- Detailed fundraising campaign plans and marketing materials.
- HR employment policies beyond board/volunteer governance.
