# Project Atlas — Risk Management Plan

## 1. Purpose

This Risk Management Plan defines how Project Atlas will identify, analyze, respond to, monitor, escalate, and close project risks.

The plan also defines how assumptions, issues, and dependencies will be managed through the RAID process.

Project Atlas uses a structured risk approach because delivery includes regulated validation, four enterprise integrations, data migration, multi-region business participation, controlled production release, vendor dependencies, and a fixed nine-month delivery window.

All risks, values, owners, dates, and financial exposures in this case study are synthetic.

---

## 2. Objectives

Risk management will:

- Identify threats and opportunities early.
- Assign clear ownership.
- Assess probability and impact consistently.
- Prioritize management attention using risk scores.
- Define preventive and contingent responses.
- Track risk triggers and response actions.
- Escalate exposure that exceeds agreed thresholds.
- Connect risk exposure to schedule, cost, quality, scope, and release decisions.
- Provide an evidence-based input to contingency-reserve planning.
- Convert realized risks into issues when they occur.

---

## 3. RAID Definitions

### Risk
An uncertain event or condition that may affect project objectives if it occurs.

### Assumption
A planning factor treated as true for the purpose of developing the project plan and requiring validation where appropriate.

### Issue
A current event, condition, or problem that has already occurred and requires action or resolution.

### Dependency
An internal or external relationship where delivery depends on an action, output, decision, system, or resource outside the immediate control of the responsible work package.

---

## 4. Risk Identification

Risks may be identified through:

- Requirements and design reviews
- WBS and schedule development
- Architecture and integration planning
- Data profiling
- Security and compliance reviews
- Resource planning
- Procurement planning
- Test and validation planning
- Weekly delivery reviews
- Risk and change reviews
- Steering Committee discussions
- Lessons learned
- Vendor and dependency reviews

Risks are recorded in the Risk Register with a unique ID.

---

## 5. Risk Categories

Project Atlas uses the following categories:

- Technical / Architecture
- Integration
- Data / Migration
- Quality / Validation
- Security
- Business / Stakeholder
- Resource
- Vendor / Procurement
- Performance
- Release / Deployment
- Scope / Change
- Environment / Infrastructure
- External / Enterprise Dependency

Categories support aggregation and trend analysis but do not replace individual risk ownership.

---

## 6. Probability Scale

| Score | Probability | Guide |
|---|---:|---|
| 1 | 10% | Unlikely |
| 2 | 30% | Possible but not expected |
| 3 | 50% | Reasonably possible |
| 4 | 70% | Likely |
| 5 | 90% | Highly likely |

Probability percentages are synthetic planning assumptions used for quantitative exposure analysis.

---

## 7. Impact Scale

Impact is assessed using the highest material impact across schedule, cost, scope, quality, compliance, security, operations, or benefits.

| Score | Impact | Typical Interpretation |
|---|---|---|
| 1 | Very Low | Limited local impact; absorbed within normal workstream control |
| 2 | Low | Minor corrective action; no major milestone impact |
| 3 | Moderate | Noticeable workstream impact or management attention required |
| 4 | High | Major deliverable / milestone, cost, quality, or stakeholder impact |
| 5 | Very High | Project objective, release, regulatory, or critical business impact |

---

## 8. Risk Score & Rating

**Risk Score = Probability Score × Impact Score**

| Score | Rating | Governance Expectation |
|---:|---|---|
| 1–4 | Low | Monitor through routine workstream governance |
| 5–9 | Medium | Owner response and regular review required |
| 10–15 | High | Project Manager visibility and active response plan required |
| 16–25 | Critical | Executive / Steering Committee visibility and active escalation required |

---

## 9. Risk Response Strategies

Threat-response strategies may include:

- **Avoid** — change the plan to remove the threat.
- **Mitigate** — reduce probability and/or impact.
- **Transfer** — shift ownership or financial consequence to an appropriate third party where practical.
- **Accept** — acknowledge the exposure and define monitoring / contingency where required.
- **Escalate** — move the risk to the organizational level that can manage the underlying cause or decision.

Opportunities, if identified, may use exploit, enhance, share, accept, or escalate strategies.

---

## 10. Risk Ownership

Every active risk must have:

- Risk Owner
- Response Owner where different
- Trigger / early-warning indicator
- Preventive response
- Contingency action
- Target review date
- Current status
- Residual-risk assessment

The Risk Owner is accountable for monitoring exposure and ensuring agreed response actions are progressed.

---

## 11. Quantitative Cost Exposure

For selected cost-relevant risks, Project Atlas uses a simplified Expected Monetary Value approach:

**Initial Cost Exposure = Probability % × Estimated Cost Impact**

This is not intended to imply that all risks are independent or that reserve should equal the simple mathematical sum without management judgment.

The initial portfolio model produces approximately **₹20.75 lakh of quantified expected cost exposure**.

The Project Atlas Cost Baseline includes **₹22.00 lakh of contingency reserve**, providing a modest management allowance above the quantified initial exposure.

Management reserve remains separate and is not used for identified risk exposure.

---

## 12. Contingency Reserve Linkage

The ₹22.00 lakh contingency reserve is intended to address identified uncertainty such as:

- Integration delays / rework
- Data remediation
- Additional validation effort
- Security remediation
- Defect resolution
- Specialist support
- Release and cutover uncertainty

Risk responses are expected to reduce residual exposure before contingency is consumed.

Contingency usage must be linked to an approved project need, risk, issue, or corrective action where practical.

---

## 13. Risk Triggers

Triggers are observable conditions indicating that:

- Probability is increasing
- Impact may be increasing
- A planned response should begin
- A risk has materialized and should become an issue

Examples include:

- Interface specification approval missed
- Data-quality threshold exceeded
- Critical vulnerability identified
- UAT participation below plan
- Production release slot not confirmed
- Required vendor resource not onboarded
- Test environment unavailable by required date

---

## 14. Risk Reviews

### Weekly Delivery Review
Review new / changed delivery risks, dependencies, and immediate response actions.

### Fortnightly Risk & Change Review
Review high / critical risks, assumptions requiring validation, open issues, dependencies, response effectiveness, contingency implications, and change requests.

### Monthly Steering Committee
Review:

- Critical and selected high risks
- Risk trend
- Material cost / schedule exposure
- Contingency consumption
- Risks requiring executive decisions
- Risks threatening major milestones or release

---

## 15. Escalation Thresholds

A risk is escalated when one or more of the following apply:

- Risk score reaches **16 or above**
- A critical project milestone is threatened
- Forecast cost impact exceeds delegated tolerance
- Regulatory / compliance acceptance may be affected
- Critical security or production risk exists
- Resolution requires executive or enterprise-level authority
- The response requires management-reserve consideration
- A dependency outside project control is not being resolved within required lead time

---

## 16. Assumption Management

Assumptions will be:

1. Recorded with an owner.
2. Given a validation date.
3. Reviewed when related planning information becomes available.
4. Converted to a risk or issue when evidence indicates the assumption may not hold.
5. Closed when validated or superseded.

---

## 17. Issue Management

Issues will include:

- Clear problem statement
- Impact
- Owner
- Required action
- Target resolution date
- Escalation status
- Closure evidence

A realized risk will be cross-referenced to the corresponding issue where applicable.

---

## 18. Dependency Management

Dependencies will record:

- Dependency description
- Provider / external owner
- Required-by date
- Dependent WBS / activity
- Current status
- Escalation trigger
- Recovery / workaround where available

Critical external dependencies are reviewed alongside the Integrated Project Schedule.

---

## 19. Residual & Secondary Risk

After planned responses are defined, the Risk Owner will assess residual probability and impact.

Where a response creates a new material exposure, a secondary risk will be entered separately rather than hidden within the original risk.

---

## 20. Risk Closure

A risk may be closed when:

- The risk event can no longer occur.
- The relevant milestone / exposure window has passed.
- The underlying cause has been eliminated.
- The risk has occurred and is now managed as an issue.
- The project formally accepts that no further response is required.

Closed risks remain in the register for traceability and lessons learned.

---

## Portfolio Disclaimer

Project Atlas is an independent project-management portfolio simulation.

All risks, assumptions, issues, dependencies, financial exposures, probability estimates, response plans, owners, and dates are fictional / synthetic and are used solely to demonstrate project-management practices.
