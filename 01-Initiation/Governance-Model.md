# Project Atlas — Governance Model

**Document ID:** ATL-GOV-001  
**Version:** 1.0 (initial governance baseline)  
**Project phase:** M1 — Initiation, following simulated charter authorization  
**Document owner:** Project Manager  
**Delivery model:** Predictive / Waterfall  
**Classification:** Public, synthetic portfolio case study

> **Portfolio notice:** All governance assignments, approval outcomes, project values, schedules, risks and roles are simulated. This document is not an actual employer or client policy, and GitHub commits/pull requests do not replace organizational approval.

## 1. Purpose and governing references

Define how Project Atlas will be directed, controlled and escalated through a nine-month modernization of a regulated enterprise application. This model supports the approved [Project Charter](Project-Charter.md), [Business Case](Business-Case.md) and [Stakeholder Register](Stakeholder-Register.xlsx).

Governance is designed to:

- maintain clear accountability for scope, schedule, cost, quality and business outcomes;
- bring risks and cross-workstream dependencies to the right decision maker early;
- obtain mandatory business, technical and compliance approvals before stage transitions;
- control changes to approved baselines and preserve decision evidence; and
- coordinate production cutover, four-week hypercare and formal closure.

**Planning reference:** Project Atlas has three workstreams, approximately 14 core delivery resources, four integrations, a nine-month duration, a ₹2.40 crore cost baseline (BAC), ₹15 lakh management reserve and a ₹2.55 crore total authorized budget.

## 2. Governance structure

```text
Executive Sponsor
       │
Steering Committee (monthly; extraordinary meetings as required)
       │
Project Manager (integrated delivery, controls and reporting)
       ├── Application Development Lead
       ├── Integration & Migration Lead
       └── Validation & QA Lead
                 │
      Cross-functional delivery teams and specialist vendors
```

**Cross-cutting decision partners:** Business Owner, Technology Director, Quality & Compliance Lead, Information Security Lead, Finance Business Partner and Operations & Service Transition Lead. They join the relevant forums and approval gates; they are not assumed to report to the Project Manager.

### Accountability

| Role / forum | Primary accountability |
|---|---|
| Executive Sponsor | Strategic alignment, overall sponsorship, approved funding, management-reserve release, material baseline-change approval and final go/no-go decision. |
| Steering Committee | Executive oversight, trade-off review and recommendations on material changes, cross-functional conflicts and stage-gate readiness. For this simulation, the Steering Committee also serves as the change-control board (CCB). |
| Business Owner | Business outcomes, requirements ownership, UAT/business acceptance and post-project benefits ownership. |
| Project Manager | Integrated plan, baseline control, forecasting, RAID, change-impact assessment, decision records, reporting, escalation and stage-gate coordination. |
| Technology Director | Technical resources, architecture/design approval, technical readiness and operational technology dependencies. |
| Quality & Compliance Lead | Validation strategy, required quality evidence, compliant release criteria and formal validation approval. |
| Workstream Leads | Delivery of approved work packages, local forecasting, quality, dependencies and early escalation. |
| Finance Business Partner | Cost validation, monthly actuals, forecasts, funding reconciliation and financial impact advice. |
| Security / Data Governance / Operations | Required specialist assessments and sign-offs relevant to security, privacy, migration and operational handover. |

The **Project Manager coordinates** decisions and makes recommendations; the role does not independently authorize a new cost baseline, material scope changes or management-reserve release.

## 3. Operating cadence and records

| Forum | Frequency | Owner / participants | Primary input and output |
|---|---|---|---|
| Workstream coordination | Twice weekly during build and test; otherwise as needed | Workstream Leads + PM | Task progress, critical dependencies, defects and actions; updated workstream plans. |
| Integrated delivery review | Weekly | PM + Workstream Leads + relevant SMEs | Schedule, near-term milestones, capacity, RAID and decisions; integrated status/action log. |
| Risk & change review | Fortnightly; urgent cases ad hoc | PM + affected leads + risk/control owners | Risk responses, issue resolution, change-impact assessments and recommendations. |
| Financial performance review | Monthly, ahead of steering | PM + Finance Business Partner + workstream estimates | Actual cost, committed cost, PV/EV/AC when available, EAC, reserve usage and variance commentary. |
| Steering Committee | Monthly; extraordinary session for urgent material matters | Sponsor, Business Owner, Technology Director, Compliance, PM; Finance as needed | Executive status pack; direction, approvals and recorded decisions. |
| Stage-gate / release readiness | At planned gates | Named gate approver, PM and mandatory control owners | Evidence checklist, accepted exceptions, approval/hold decision and follow-up actions. |
| Hypercare command review | Daily during initial stabilization; taper as agreed | PM, Operations, technical leads, business SMEs | Incident/defect trend, ownership, escalation and hypercare exit readiness. |

**Reporting standard:** The PM publishes a concise weekly status and a monthly executive summary. Both must reference the approved baseline and distinguish *actual results*, *current forecast* and *proposed changes*. Project status is not changed to “green” solely because a recovery action has been proposed.

**Required records:** Integrated Schedule; RAID Register; Decision Log; Change Register; Budget/EVM Workbook; Requirements Traceability Matrix; Validation and UAT evidence; Stage-Gate Checklist; Cutover Plan; Hypercare Tracker; Closure Report.

## 4. Decision rights

| Decision | Responsible for recommendation / evidence | Accountable approval | Mandatory input or prerequisite |
|---|---|---|---|
| Project authorization / original funding | PM and Business Owner | Executive Sponsor | Business Case and charter endorsement. |
| Requirements baseline | Business Analyst / PM | Business Owner | Quality/Compliance and technical review. |
| Solution design approval | Solution Architect / PM | Technology Director | Integration, Security and Compliance input as applicable. |
| Initial cost and schedule baselines | PM + Finance Business Partner | Executive Sponsor | Reviewed estimates, resource plan and Steering Committee recommendation. |
| Validation completion | Validation & QA Lead | Quality & Compliance Lead | Traceability, required test evidence and disposition of deviations. |
| UAT/business acceptance | Business SME / UAT Lead | Business Owner | Accepted scenarios, test evidence and documented defects. |
| Minor execution decisions inside the approved baseline | Workstream Lead | Project Manager | No change to approved scope, stage-gate date, cost baseline or mandatory quality controls. |
| Material scope/schedule/cost change | PM after integrated impact analysis | Executive Sponsor | Steering Committee acting as CCB; Finance/Business/Technology/Compliance as affected. |
| Management-reserve release | PM + Finance Business Partner | Executive Sponsor | Documented justification and authorized budget adjustment. |
| Production go/no-go | PM / release-readiness forum | Executive Sponsor | Recorded Business, Technology, Quality/Compliance, Security and Operations sign-offs where applicable. |
| Project closure | PM | Executive Sponsor | Business acceptance, operational handover, financial close and benefits ownership transfer. |

**Control independence:** A sponsor's final go/no-go decision cannot substitute for missing mandatory compliance, security or business acceptance. An unresolved mandatory control is a **hold** until appropriately resolved through the applicable authority.

## 5. Escalation and decision timing

The following numerical thresholds are **illustrative controls created for this case study**, not company policies or permission to exceed a baseline.

| Condition | Initial route | Escalation target / timing |
|---|---|---|
| Forecast delay of **5 or more working days** to an approved stage gate or critical milestone | Workstream Lead → PM | Notify Sponsor and affected gate owners within one working day; Steering Committee decides on material corrective action. |
| Forecast total cost above BAC or cost-performance variance requiring recovery | PM + Finance | Escalate to Sponsor; obtain CCB review if a baseline change or reserve request is proposed. |
| Adverse EAC movement of **more than 3% of BAC** (₹7.2 lakh) versus approved cost baseline | PM + Finance | Explain in monthly steering pack; escalate earlier if the movement threatens available contingency or a gate. |
| Unresolved Severity-1 defect; critical compliance, privacy or security finding | QA / control owner → PM | Same-day notification to Sponsor and responsible control owner; block the relevant release gate until disposition. |
| Missing UAT, validation or operations acceptance evidence | Gate owner → PM | Hold the gate and escalate to Sponsor; do not infer approval from silence. |
| Cross-team dependency blocks a critical-path activity for **more than 2 working days** | Workstream Lead → PM | PM convenes owners; seek Technology Director / Steering decision if unresolved. |
| Material supplier non-performance or contractual exposure | Procurement Lead + PM | Notify Sponsor and Finance as affected; evaluate recovery and contractual remedies. |

A material decision or approval that remains open for **more than two working days beyond its agreed due date** is highlighted in the Decision Log and escalated by the PM.

### Standard escalation path

1. **Workstream Lead:** records the matter, assesses impact and attempts a local resolution.
2. **Project Manager:** integrates schedule, cost, scope, resource, quality and dependency impacts; appoints an action owner.
3. **Functional control owner:** makes the applicable technical, security, compliance, financial or business determination.
4. **Steering Committee / Sponsor:** resolves cross-functional trade-offs and authorizes material baseline or funding decisions.

Urgent regulatory, security or Severity-1 issues bypass routine meeting cadence.

## 6. Change-control workflow

Changes to an approved scope, schedule or cost baseline require formal evaluation. Once a change is proposed:

1. **Log:** assign an ID (`CR-001`, etc.), requester, business reason and date.
2. **Screen:** PM determines whether it is an operational action within the baseline or a formal change.
3. **Analyze:** relevant workstreams assess scope, requirements/RTM, WBS, schedule, critical path, resource loading, cost, contingency, quality, validation, vendor and release effects.
4. **Recommend:** PM compiles options, benefit/risk trade-offs, mitigation and an explicit recommendation.
5. **Decide:** Steering Committee acting as CCB reviews; Sponsor approves or rejects material changes to the authorized baseline/funding, subject to mandatory control-owner concurrence where required.
6. **Implement:** only after approval, update affected baselines and registers; communicate changes to owners and record the new version.
7. **Verify:** confirm implementation and trace the change through testing, release and closure evidence.

**Illustrative future change:** `CR-001 — Additional regulatory reporting integration` would expand the original four-integration scope to five **only if formally approved**. Until then, the fifth integration is *proposed*, not part of the approved baseline.

**GitHub demonstration:** A branch and pull request may show the proposed and approved artifact revisions, but the simulated approval decision must be separately recorded in the Change Register/Decision Log. A merged pull request is not, by itself, a compliance or funding approval.

## 7. Financial governance

- **BAC / cost baseline:** ₹2.40 crore, including contingency for identified risk.
- **Management reserve:** ₹15 lakh, held outside BAC until formally released and incorporated into an authorized revision where applicable.
- **Total authorized project budget:** ₹2.55 crore.
- **Reporting:** monthly planned vs actual/committed cost; earned value metrics only against the relevant approved performance-measurement baseline and verified progress rules.
- **Forecast ownership:** workstream leads provide estimate-to-complete inputs; PM consolidates; Finance validates cost assumptions, actuals and commitments.
- **Change authority:** a tolerance trigger initiates review; it is not an automatic authorization for overspend or rebaselining.
- **Benefits:** the Business Owner owns post-project measurement of the simulated ₹1.30 crore annual recurring benefit expectation after stabilization.

## 8. Stage gates and minimum evidence

| Gate | Target | Approval / decision owner | Minimum evidence |
|---|---|---|---|
| G0 — Initiation authorization | Month 1 | Executive Sponsor | Business Case, approved Charter and initial governance. |
| G1 — Requirements baseline | Month 2 | Business Owner | Reviewed requirements, scope boundary, RTM approach, known assumptions and acceptance criteria. |
| G2 — Solution design | Month 3 | Technology Director | Approved architecture, integration/data-migration design, quality/security input and estimates. |
| G3 — Build completion | Month 5 | Technology Director | Build evidence, peer review, unit-test results and readiness for integration testing. |
| G4 — SIT completion | Month 6 | Validation & QA Lead | SIT evidence, requirement coverage, defect disposition and migration-test results. |
| G5 — Validation and UAT completion | Month 7 | Quality & Compliance Lead for validation; Business Owner for UAT | Signed validation evidence and separate business acceptance; no unresolved mandatory findings. |
| G6 — Production go/no-go | Month 8 | Executive Sponsor | Required functional sign-offs, readiness checklist, cutover/rollback plan, operational support readiness and no unresolved Severity-1 defects. |
| G7 — Hypercare exit and closure | Month 9 | Executive Sponsor | Hypercare exit evidence, business/operations acceptance, closure report, lessons learned and benefits handover. |

A gate can be **approved, conditionally approved where permissible, or held**. Mandatory compliance or security conditions cannot be waived by the PM or by an informal meeting decision.

## 9. Stakeholder engagement controls

The [Stakeholder Register](Stakeholder-Register.xlsx) identifies 18 synthetic, role-based stakeholders; power–interest priority; current and target engagement; engagement owner; principal concern; and gate touchpoints.

Review stakeholder engagement:
- at the weekly integrated delivery review for active issues;
- at requirements, design, validation, go-live and closure gates;
- whenever funding, scope, role ownership, regional impacts or risk exposure materially changes.

Keep personal names, contact data and candid assessments out of this public portfolio. In an actual project, that information would be held in an access-controlled system.

## 10. Document control and portfolio use

**Initial version:** 1.0, established with Stakeholder Register under Commit #5.  
**Change history:** Future governance changes must identify the reason, impacted decision rights or cadence, approver and effective version.

The portfolio README and GitHub history are *demonstrations* of PM practice. Actual approval in this simulated case is represented through the documented decision and named approval role, never through an unverified signature or a claim of real corporate authorization.
