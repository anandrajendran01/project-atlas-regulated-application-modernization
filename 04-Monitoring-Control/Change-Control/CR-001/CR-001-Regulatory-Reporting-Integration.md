[CR-001-Regulatory-Reporting-Integration.md](https://github.com/user-attachments/files/34724344/CR-001-Regulatory-Reporting-Integration.md)
# Project Atlas — Change Request CR-001

## Regulatory Reporting Integration

**Change Request ID:** CR-001  
**Status:** Proposed — Pending Steering Committee Decision  
**Assessment Date:** 17 April 2026  
**Requested By:** Business Owner / Quality & Compliance Lead  
**Change Owner:** Project Manager  
**Affected Baseline:** Scope, Requirements, WBS, Schedule, Cost, Risk, Validation, Procurement  
**Current Baseline Versions:** Scope 1.0 | Schedule 1.0 | Cost 1.0  
**Change Branch:** `change/cr-001-integration-scope`

> This change request is part of the synthetic Project Atlas portfolio case study. No approved baseline is modified by this assessment.

---

## 1. Change Summary

CR-001 proposes adding a **fifth enterprise integration** between Project Atlas and the enterprise Regulatory Reporting platform.

The approved Scope Baseline currently contains four enterprise integrations:

1. Enterprise Identity & Access Management
2. Enterprise Master Data
3. Enterprise Records Management
4. Enterprise Notification Service

CR-001 would add:

**5. Enterprise Regulatory Reporting Integration**

The requested interface would automate transmission of designated approved reporting data from Project Atlas to the enterprise reporting platform and retain traceable transmission / acknowledgement evidence.

---

## 2. Business Rationale

The change request was raised after the original Scope Baseline was approved.

A new enterprise compliance-control requirement was identified requiring designated reporting information generated within Project Atlas to be transferred to the enterprise Regulatory Reporting platform with auditable transmission status.

Without the integration, the business would require an interim manual reporting and reconciliation process.

The proposed integration is intended to:

- Reduce manual reporting effort.
- Improve reporting timeliness.
- Reduce reconciliation effort.
- Improve auditability and control evidence.
- Reduce operational dependency on spreadsheet / manual transfer.
- Align the application with the enterprise reporting architecture.

This case study does not claim that the change is required by any real-world law or regulator.

---

## 3. Proposed Scope Change

### In Scope

CR-001 would add:

- Regulatory reporting interface requirements.
- Reporting-data mapping and transformation.
- Secure interface design.
- Automated transmission from Project Atlas to the enterprise Regulatory Reporting platform.
- Transmission acknowledgement / error handling.
- Audit evidence for reporting events.
- Integration monitoring and support procedures.
- System / integration testing.
- Security review.
- Regulated validation evidence where designated.
- Operational handover.

### Out of Scope

CR-001 does not include:

- Redesign of the enterprise Regulatory Reporting platform.
- New regulatory-report authoring functionality within Project Atlas.
- Replacement of enterprise reporting governance.
- New regions or business processes unrelated to the reporting interface.
- Historical-report reconstruction beyond the approved migration / reporting requirement.

---

## 4. Requirement Impact

If approved, the following requirements would be added.

### INT-005 — Regulatory Reporting Integration

Project Atlas shall securely transmit designated approved reporting data to the enterprise Regulatory Reporting platform and process transmission acknowledgement / error status.

### REG-003 — Regulatory Reporting Traceability

Project Atlas shall retain traceable evidence of designated reporting transmissions, acknowledgements, exceptions, and approved reprocessing actions according to the defined control requirements.

Existing security, audit, availability, and operational requirements will also apply to the new interface.

No requirement is added to the approved RTM until CR-001 is approved.

---

## 5. WBS Impact

If approved, the WBS would be revised to include:

**4.1.5 Regulatory Reporting Integration**

The existing integration-testing, security, validation, release, and operational-handover work packages would also be updated to include the fifth interface.

The WBS Dictionary would be revised accordingly.

---

## 6. Schedule Impact

The current Month-3 forecast remains:

**Go / No-Go:** 17 August 2026  
**Production Go-Live:** 21 August 2026  
**Project Closure:** 30 September 2026

If CR-001 is approved, the recommended schedule impact is:

| Milestone | Current Forecast | Proposed Forecast | Impact |
|---|---|---|---:|
| Application Build Complete | 13-May-2026 | 13-May-2026 | 0 WD |
| Integration Build Complete | 12-May-2026 | 20-May-2026 | +6 WD |
| Technical Testing Complete | 23-Jun-2026 | 26-Jun-2026 | +3 WD |
| Validation & UAT Complete | 03-Aug-2026 | 07-Aug-2026 | +4 WD |
| Production Readiness | 14-Aug-2026 | 21-Aug-2026 | +5 WD |
| Go / No-Go | 17-Aug-2026 | 24-Aug-2026 | +5 WD |
| Production Go-Live | 21-Aug-2026 | 28-Aug-2026 | +5 WD |
| Hypercare Exit | 18-Sep-2026 | 25-Sep-2026 | +5 WD |
| Project Closure | 30-Sep-2026 | 30-Sep-2026 | 0 WD |

The five-working-day release movement preserves approximately four weeks of hypercare before final closure.

---

## 7. Resource Impact

CR-001 is expected to require additional effort primarily from:

- Integration & Data Migration Lead
- Integration / Data Engineers
- Solution Architect
- Validation & Deployment Lead
- QA / Validation Analysts
- DevOps / Release Engineer
- Project Manager
- Information Security Lead
- Quality / Compliance Lead
- Enterprise Regulatory Reporting platform owner
- Specialist integration / validation supplier support

The change can reuse the mobilized project team, reducing remobilization cost relative to a post-project implementation.

No permanent increase to core headcount is proposed.

---

## 8. Cost Impact

The estimated incremental Cost Baseline impact is:

| Cost Category | Increment |
|---|---:|
| Internal & Contract Delivery Resources | ₹3.60 L |
| External / Specialist Vendor Services | ₹1.60 L |
| Cloud & Infrastructure | ₹0.60 L |
| Software & Licensing | ₹0.40 L |
| Validation & Security Services | ₹0.80 L |
| Training & Change Readiness | ₹0.20 L |
| Travel & Operational Costs | ₹0.00 L |
| Change-Specific Contingency | ₹1.60 L |
| **Incremental BAC** | **₹8.80 L** |

If approved:

**Current BAC:** ₹240.00 L  
**Proposed Revised BAC:** **₹248.80 L**

The existing ₹15.00 L Management Reserve would remain unchanged and outside BAC.

**Current Total Authorized Budget:** ₹255.00 L  
**Proposed Total Authorized Budget:** **₹263.80 L**

The incremental scope is not proposed to be funded by silently consuming the existing Management Reserve.

A scope increase requires explicit funding authorization through change control.

---

## 9. Forecast Impact

Month-3 performance analysis produced a current Management EAC of **₹243.20 L** before CR-001.

If CR-001 is approved and the change work is delivered at its approved budget:

**Provisional Management EAC:** ₹243.20 L + ₹8.80 L = **₹252.00 L**

Against the proposed revised BAC of ₹248.80 L, the existing ₹3.20 L performance gap would remain visible rather than being hidden by the change.

Corrective actions therefore remain necessary even if CR-001 is approved.

---

## 10. Risk Impact

CR-001 introduces additional risks including:

- Regulatory Reporting interface specification / endpoint availability.
- Mapping accuracy for reportable data.
- Additional validation and evidence workload.
- Compressed integration / test capacity.
- Security / authentication configuration.
- Enterprise reporting-platform dependency.
- Cutover coordination for the fifth interface.

These risks would be added to the Risk Register after approval.

---

## 11. Quality & Validation Impact

If approved, CR-001 would require:

- Updated validation / test strategy.
- New integration-test scenarios.
- New negative / error-handling scenarios.
- Security review.
- Updated traceability.
- Reporting-transmission evidence.
- Updated production-readiness criteria.
- Operational monitoring / support validation.
- Updated final validation summary.

No existing quality acceptance criterion is proposed to be reduced.

---

## 12. Procurement Impact

CR-001 is expected to require approximately:

- **₹1.60 L** additional specialist integration support.
- **₹0.80 L** additional validation / security support.

Existing procurement packages would be amended where commercially appropriate rather than creating unnecessary new suppliers.

Any supplier amendment remains subject to Procurement approval and existing package controls.

---

## 13. Benefits Impact

The original recurring annual project benefit assumption is approximately:

**₹130.00 L per year**

CR-001 is estimated to add approximately:

**₹6.00 L per year**

through reduced manual reporting / reconciliation effort and improved operational control.

Proposed revised recurring annual benefit:

**₹136.00 L per year**

Using the proposed Total Authorized Budget of ₹263.80 L:

**Indicative simple payback ≈ 23.3 months**

The primary rationale remains compliance-control improvement and automation rather than financial benefit alone.

---

## 14. Options Considered

### Option 1 — Reject CR-001

**Advantages**
- No baseline cost increase.
- No release movement.

**Disadvantages**
- Manual reporting / reconciliation process required.
- Lower automation and auditability.
- Compliance-control gap must be managed operationally.

### Option 2 — Defer to a Post-Go-Live Follow-On

**Advantages**
- Protects the current August release.
- Separates delivery risk from Project Atlas.

**Disadvantages**
- Requires team / vendor remobilization.
- Duplicates some design, testing, validation, and release effort.
- Manual process remains until follow-on delivery.
- Estimated follow-on implementation would likely cost more than integrating while the current team is mobilized.

### Option 3 — Approve CR-001 Within Project Atlas

**Advantages**
- Uses the currently mobilized team.
- Avoids a separate future release / validation cycle.
- Improves automation, traceability, and operational control.
- Incremental annual benefit is realized earlier.

**Disadvantages**
- Adds ₹8.80 L to BAC.
- Moves production Go-Live by five working days.
- Adds integration, validation, and dependency risk.

---

## 15. Recommendation

**Recommended Option: Option 3 — Approve CR-001 within Project Atlas**

The recommendation is conditional on:

1. Explicit Steering Committee approval.
2. Approval of the ₹8.80 L incremental Cost Baseline.
3. Approval of the revised 28 August production release.
4. Regulatory Reporting platform endpoint / specification confirmation.
5. Updated resource and procurement commitments.
6. Updated validation and security plan.
7. Continued corrective action on the existing ₹3.20 L performance forecast gap.

---

## 16. Approval Status

At Commit #15:

**CR-001 is NOT approved.**

The change remains:

**Proposed — Pending Steering Committee Decision**

Therefore:

- Scope Statement remains Version 1.0.
- RTM remains unchanged.
- WBS remains unchanged.
- Integrated Project Schedule remains unchanged.
- Cost Baseline remains ₹240.00 L.
- Total Authorized Budget remains ₹255.00 L.
- Existing four-integration scope remains the approved baseline.

No baseline document should be edited until formal approval is recorded.

---

## 17. Git / Change-Control Principle

The Git branch is used to isolate the proposed change artifacts.

It does **not** itself constitute project approval.

Formal approval is represented by the documented Steering Committee decision.

Only after approval will affected baseline documents be updated and the approved change merged.

---

## Portfolio Disclaimer

Project Atlas is an independent project-management portfolio simulation.

All change-request details, requirements, financial impacts, timelines, benefits, risks, supplier impacts, and approval data are fictional / synthetic and are used solely to demonstrate integrated project change control.
