# Plan: 001-nonprofit-formation

## Objective
Operational blueprint to produce, review, and approve all artifacts required to form and maintain the Fellowship for American Enterprise as a North Carolina 501(c)(3), using repository-based governance.

## Scope & Outputs
- Draft and approve governing documents: Articles (NC), bylaws, Conflict of Interest policy.
- Board records: Initial resolutions and organizational meeting minutes.
- Compliance prep: EIN workup, IRS exemption (1023-EZ eligibility or full 1023 packet), state charity registration steps.
- Policies and procedures: Donor acknowledgments, document retention, compliance calendar, budgets.
- Repository outputs saved under `documents/` with metadata and PR-based approvals.

## Work Breakdown (Artifacts & Paths)
- Mission statement: `documents/mission-statement.md`
- Articles of Incorporation (NC): `documents/articles-of-incorporation-nc.md`
- Bylaws: `documents/bylaws.md`
- Conflict of Interest policy: `documents/conflict-of-interest-policy.md`
- Board resolutions: `documents/board/resolutions/RES-001-initial-board-actions.md`
- Organizational meeting minutes: `documents/board/minutes/organizational-meeting.md`
- EIN workup (SS-4 data, steps): `documents/ein/ss-4-workup.md`
- IRS exemption: `documents/irs/1023-ez-eligibility-checklist.md` or `documents/irs/1023-full-requirements.md`; supporting `documents/irs/activities-narrative.md`; `documents/finance/three-year-budget-template.md`
- State charity registration (NC): `documents/compliance/charity-registration-nc.md`
- Compliance calendar: `documents/compliance/compliance-calendar.md`
- Donor acknowledgment procedure: `documents/compliance/donor-acknowledgment-procedure.md`
- Document retention policy: `documents/compliance/document-retention-policy.md`

## Sequencing & Flow
1) Foundation: mission statement -> Articles draft (with IRS language) -> bylaws -> COI policy.
2) Governance approvals: initial resolutions + organizational minutes to adopt Articles/bylaws/COI and appoint officers.
3) EIN: capture SS-4 data and filing steps.
4) IRS exemption: check EZ eligibility; if eligible, prep EZ attachments (narrative, budget). If not, prepare full 1023 requirements.
5) State: NC charity registration steps and timelines.
6) Operational controls: donor acknowledgment procedure, retention policy, compliance calendar, file naming/versioning.

## Review & Approval Workflow (GitHub)
- All governing docs and policies go through PRs.
- Required approvals: two reviewers including at least one board member/officer; link to spec/tasks in PR description.
- Evidence: PR description includes checklist, references to minutes/resolutions; approvals recorded in `documents/board/minutes` and `documents/board/resolutions`.
- Branch protection: require PR review before merge; no direct pushes to main.

## Standards & Templates
- Metadata front-matter per document: title, version/date, status (draft/approved), approvers, approval date, source spec/task IDs.
- Naming: use descriptive filenames; add version suffix when superseded (keep prior versions).
- Redlines: capture substantive changes in PR; keep prior versions in Git history or archived copies if required.
- Records retention: governing docs, minutes, resolutions retained permanently; operational records per retention policy once adopted.

## Dependencies & Inputs
- Mission clarity from `mission.txt`.
- North Carolina incorporation requirements (registered agent, address, incorporator, director minimum).
- IRS required clauses for purpose and dissolution.
- Board/officer roster, fiscal year end, banking/signatory decisions (open questions).
- EZ eligibility factors: projected receipts/assets, activity types.

## Risks & Mitigations
- Missing IRS language in Articles -> use vetted clause text and checklist.
- EZ ineligibility discovered late -> run EZ checklist early and branch to full 1023 path.
- Unsettled governance choices (directors/officers/fiscal year) -> track as open questions with owners.
- File/version confusion -> enforce metadata and PR workflow.
- Deadlines: track filings in compliance calendar; assign owners.

## Acceptance Criteria
- All listed artifacts exist in `documents/` with metadata and status.
- Board approvals captured in minutes/resolutions and referenced in PRs.
- EZ eligibility determination documented; if ineligible, full 1023 requirements documented.
- Compliance calendar populated and linked to filing instructions.
- Open questions resolved or explicitly tracked with owners in tasks.
