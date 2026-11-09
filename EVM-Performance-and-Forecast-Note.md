# Project Atlas — Month 3 EVM Performance & Forecast Note

**Performance Date:** 31 March 2026  
**Analysis Date:** 02 April 2026  
**Baseline Version:** Scope 1.0 | Schedule 1.0 | Cost 1.0  
**Status:** Monitoring & Control

> This is a synthetic Earned Value Management analysis created for the Project Atlas portfolio case study.

---

## 1. Purpose

This note formalizes Project Atlas performance measurement using Earned Value Management after the initial Month-3 execution update.

The objective is to distinguish:

- Budget scheduled
- Value actually earned
- Actual cost incurred
- Schedule efficiency
- Cost efficiency
- Statistical forecast outcomes
- Management forecast and corrective action

EVM is applied at control-account level and supported by work-package crediting rules.

---

## 2. Baseline Reconciliation

The approved financial structure remains:

**Direct Work Budget:** ₹218.00 L  
**Contingency Reserve:** ₹22.00 L  
**Cost Baseline / BAC:** ₹240.00 L  
**Management Reserve:** ₹15.00 L  
**Total Authorized Budget:** ₹255.00 L

The time-phased Cost Baseline through 31 March is **₹49.135 L**.

That amount includes **₹3.00 L of time-phased contingency reserve**.

For Month-3 earned-value measurement, unused contingency does not earn value. Therefore:

**Cumulative Cost Baseline through March:** ₹49.135 L  
**Less unconsumed time-phased contingency:** ₹3.000 L  
**EVM Planned Value (PV):** **₹46.135 L**

This distinction avoids awarding earned value merely because risk reserve was time-phased in the financial baseline.

The total approved BAC remains ₹240.00 L.

---

## 3. Work-Package Crediting Rules

Project Atlas uses different earned-value techniques based on the nature of work.

### 0 / 100

Used for discrete approval or acceptance deliverables.

No earned value is recognized until the deliverable is complete and accepted.

Examples:

- Requirements Baseline approval
- Solution Design approval
- Release Candidate acceptance
- Major stage-gate approvals

### 50 / 50

Used selectively for short-duration deliverables where starting the work represents meaningful commitment but detailed weighted milestones would add unnecessary administration.

50% is earned when the work formally starts and 50% when the deliverable is complete.

### Weighted Milestone

Used for longer technical packages such as application development, integration, migration, and test preparation.

Example weighting:

- Approved design / readiness: 20%
- Core implementation complete: 50%
- Verification / remediation complete: 20%
- Accepted handoff: 10%

The specific weighting is tailored to the work package.

### Level of Effort

Used only for support-oriented work such as ongoing project governance where output is time-dependent rather than a discrete technical product.

Earned value is limited to the value of time actually elapsed within the planned period.

---

## 4. Month-3 EVM Results

| Metric | Result |
|---|---:|
| Planned Value (PV) | ₹46.135 L |
| Earned Value (EV) | ₹45.000 L |
| Actual Cost (AC) | ₹48.200 L |
| Schedule Variance (SV = EV − PV) | **₹-1.135 L** |
| Cost Variance (CV = EV − AC) | **₹-3.200 L** |
| Schedule Performance Index (SPI) | **0.975** |
| Cost Performance Index (CPI) | **0.934** |

---

## 5. Performance Interpretation

### Schedule

**SPI = 0.975**

Project Atlas has earned approximately 97.5% of the value that was planned to be earned by the status date.

This indicates a **small but real schedule-performance shortfall**, consistent with the late Solution Design gate and early build / integration recovery activity.

The final production date remains protected, but the project has reduced schedule flexibility.

### Cost

**CPI = 0.934**

For every ₹1.00 of actual cost incurred, Project Atlas has earned approximately ₹0.934 of budgeted value.

Cost performance is therefore currently unfavorable.

This is important because the Month-3 status report showed:

**Actual spend:** ₹48.20 L  
**Cost Baseline through March:** ₹49.135 L

At first glance, the project appears ₹0.935 L under the financial baseline.

However, EVM shows a different management conclusion:

**EV = ₹45.00 L < AC = ₹48.20 L**

The project has spent less than the total time-phased Cost Baseline, but it has also completed less value than planned. Therefore, simple budget underspend should not be described as cost efficiency.

---

## 6. Forecast Analysis

Three EAC views are used.

### EAC — Remaining Work at Budgeted Rate

**EAC = AC + (BAC − EV)**

**EAC = ₹243.20 L**

This assumes the current early variance is largely non-recurring and all remaining work performs at the original budgeted rate.

### EAC — Current CPI Continues

**EAC = BAC / CPI**

**EAC ≈ ₹257.07 L**

This assumes current cost efficiency persists for the remainder of the project.

### EAC — CPI and SPI Both Influence Remaining Cost

**EAC = AC + (BAC − EV) / (CPI × SPI)**

**EAC ≈ ₹262.33 L**

This is the most conservative statistical view because it assumes both current cost and schedule inefficiency continue to affect remaining work.

---

## 7. Management Forecast

The current management forecast is:

**Management EAC: ₹243.20 L**

This is **₹3.20 L above BAC** but remains below the **₹255.00 L Total Authorized Budget**.

This forecast does **not** authorize a baseline increase.

Under the Cost Management Plan, a projected BAC overrun requires formal governance review.

The management objective remains to recover the forecast to **≤ ₹240.00 L** through corrective action before considering any baseline change or reserve draw.

---

## 8. To-Complete Performance

**TCPI to achieve BAC = (BAC − EV) / (BAC − AC)**

**TCPI ≈ 1.017**

The remaining work therefore needs to be delivered at approximately 1.017 cost efficiency to finish within BAC.

This is above 1.0 but not an extreme recovery requirement, indicating that cost recovery remains plausible if early inefficiencies are contained.

---

## 9. Corrective Actions

### Data Migration Remediation

- Complete data-quality issue assessment.
- Limit cleansing to approved in-scope records.
- Use existing migration-team capacity before external augmentation.
- Obtain approval before any contingency draw.

### Build Recovery

- Prioritize critical-path workflows.
- Use two-week detailed look-ahead planning.
- Protect developer capacity for planned build and high-priority remediation.
- Monitor Application Build Complete forecast weekly.

### Integration Dependency Recovery

- Obtain final IAM endpoint / credentials.
- Use approved stubs only where they do not create false completion credit.
- Track external dependency dates against the Integrated Project Schedule.

### Cost Control

- Separate committed cost, actual cost, and forecast.
- Review external specialist consumption against caps.
- Avoid claiming savings solely from delayed expenditure.
- Refresh ETC monthly using remaining resource and vendor demand.

### EVM Discipline

- Maintain consistent work-package crediting rules.
- Do not earn value for unapproved or incomplete deliverables.
- Do not earn value against unused contingency reserve.
- Reconcile control-account EV with physical completion evidence.

---

## 10. Management Decision

The recommended decision is:

**Continue the approved recovery plan without changing the baseline at this stage.**

The Steering Committee should review the emerging ₹243.20 L management forecast and require evidence of recovery through April.

A change request should be raised only if:

- Scope materially changes,
- Remaining forecast cannot be recovered within tolerance,
- Contingency use requires baseline redistribution,
- Or a new requirement is formally proposed.

---

## 11. Next Control Step

The next planned case-study event is the assessment of **CR-001 — Regulatory Reporting Integration**.

That change request will be evaluated against:

- Scope
- WBS
- Requirements
- Schedule
- Resources
- Cost
- Risk
- Quality / validation
- Procurement
- Benefits
- Release impact

No baseline documents will be updated until the simulated change is formally approved.

---

## Portfolio Disclaimer

Project Atlas is an independent project-management portfolio simulation.

All EVM data, progress values, forecasts, cost values, performance indices, and management decisions are synthetic and created solely to demonstrate project-management practices.
