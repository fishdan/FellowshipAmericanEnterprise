# Nonprofit Constitution — Fellowship for American Enterprise

## Purpose & Mission Alignment
- Mission adherence: All activities must advance the mission defined in `mission.txt` and documented specs; no unrelated programs or private benefit.
- Community-first focus: Prioritize town-scale digital economic infrastructure deployments modeled on Andrews, NC results.
- Public benefit: Deliver measurable, broad community benefit with no partisan activity and no inurement or private advantage.
- Scope guardrails: Programs, funding, and partnerships must be evaluated for alignment before approval by the Board.

## Ethical Principles
- Integrity & honesty in all filings, communications, and fundraising.
- Equity & inclusion in program access, hiring/volunteer opportunities, and beneficiary selection.
- Nonpartisanship: No direct or indirect political campaign intervention; limited, non-partisan advocacy only within IRS boundaries.
- Stewardship: Prudent, transparent use of funds; avoid conflicts and appearances of impropriety.
- Data responsibility: Protect constituent and donor data; use only for mission purposes.

## Transparency & Accountability
- Public-facing transparency: Publish governing documents, policies, and annual reports in `documents/` with version history in Git.
- Financial transparency: Track budgets, grants, and expenditures with audit-ready records; provide donor acknowledgments and receipts.
- Decision traceability: Board actions recorded in minutes and stored under `documents/board/`.
- Compliance logging: Maintain checklists and filings history in `documents/compliance/`.

## Governance & Decision Documentation
- Board authority: Board governs strategy, compliance, budgets, major contracts, and policy adoption.
- Meeting cadence: At least quarterly board meetings with quorum defined in bylaws; emergency meetings allowed per bylaws.
- Minutes: Capture agenda, attendees, motions, votes, recusals, and resolutions; store as `documents/board/minutes/<YYYY-MM-DD>.md`.
- Resolutions: Numbered and stored as `documents/board/resolutions/RES-<seq>.md`.
- Approvals: Governing docs (bylaws, policies) require board approval and recorded vote; PR-based review with two board reviewers before merge.
- Delegation: Operational tasks may be delegated; fiduciary duties remain with the board.

## Volunteers & Contributors
- Expectations: Follow mission, ethics, data responsibility, and Git contribution standards; disclose conflicts; respect confidentiality.
- Onboarding: Volunteers must read this constitution, applicable policies, and the contributor guide; sign acknowledgment if required.
- Conduct: Professional, respectful collaboration; incidents escalated to the Board or delegated officer.
- Access: Grant least-privilege access; revoke when no longer needed.

## Document Governance (Git-Based)
- Single source of truth: All official artifacts live in this repository; no shadow copies.
- Versioning: Use semantic, dated naming (e.g., `bylaws-v1.0.md` or `bylaws-2024-12-09.md`) and Git history for auditability.
- Amendments: Proposed via PR with rationale, redlines, and approval evidence; Board approval recorded in minutes/resolution before merge.
- Records retention: Retain governing documents, policies, financial statements, filings, and minutes permanently; operational records per retention policy once drafted.
- Reviews: Annual governance/policy review logged in compliance calendar; assign owners in tasks.

## Compliance Posture
- IRS §501(c)(3): Charitable purpose and dissolution clauses in organizing documents; no private inurement; limit lobbying; no campaign activity.
- EIN: Obtain EIN before banking or filings requiring it.
- Form 1023/1023-EZ: Prepare eligibility checklists, narratives, budgets, and schedules; keep copies of all submissions and IRS correspondence.
- State: Incorporate in North Carolina (per user request), appoint registered agent, and file charitable solicitation registration/renewals as required.
- Conflicts: Maintain Conflict of Interest policy; annual disclosures for board/officers; recusals documented in minutes.
- Whistleblower & Document Retention: Adopt policies and enforce retention and safe reporting.
- Donations: Issue receipts with required IRS elements; track restricted funds separately.

## Repository Conventions
- Structure: Use `documents/` for official artifacts, `documents/templates/` for reusable forms, `documents/board/` for board records, and `.specify/` for specs, plans, and tasks.
- Metadata: Each document includes front-matter (title, version, status, approvers, approval date, references).
- Workflows: Use PRs for all governing docs; require two approvals (including one board member) and link to relevant spec/task IDs.
- Controls: Protect main branch; require status checks once automation is added.
- Access & secrets: No credentials in repo; use `.gitignore` for any local secrets; consider adding `.codex/` to `.gitignore` if tokens are present.

## Amendments & Maintenance
- Change control: Amend via PR referencing this constitution; Board approval required and logged in minutes/resolution.
- Periodic review: Annual review scheduled in compliance calendar; capture decisions in minutes.
- Custody: Secretary (or designated officer) maintains repository governance and ensures records completeness.

## Open Questions
- Board composition specifics (number, initial directors, officers, staggered terms).
- Fiscal year end (e.g., Dec 31 vs. June 30).
- Registered agent selection and mailing address in North Carolina.
- Banking institution and signatory policy.
- Choice of Form 1023 vs. 1023-EZ based on projected revenue and activities.
