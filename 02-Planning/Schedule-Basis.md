# Project Atlas — Schedule Basis

## 1. Purpose

This document explains the planning assumptions and control logic used to develop the Project Atlas Integrated Project Schedule.

The schedule translates the approved Scope Baseline into a time-phased delivery plan and provides the basis for milestone management, dependency control, resource planning, cost phasing, schedule performance measurement, and future Earned Value Management.

---

## 2. Baseline Period

**Baseline Start:** 05 January 2026  
**Baseline Finish:** 30 September 2026  
**Planned Duration:** Approximately 9 months

All dates are synthetic and are used solely for portfolio demonstration.

---

## 3. Scheduling Approach

Project Atlas uses a predominantly predictive scheduling approach.

The schedule is developed using:

- Approved WBS work packages
- Logical activity sequencing
- Finish-to-start dependencies unless otherwise noted
- Selected parallel work where technically and operationally feasible
- Formal milestone and stage-gate reviews
- Controlled release and cutover windows
- Explicit testing, validation, UAT, and hypercare periods

The Integrated Project Schedule is more detailed than the WBS. A single WBS work package may contain multiple executable schedule activities.

---

## 4. Working Calendar

Unless explicitly identified otherwise, the baseline assumes:

- Monday to Friday working week
- Standard business-day calendar
- Weekends treated as non-working days
- Public holidays and regional leave impacts managed through detailed resource planning
- Production cutover activities may occur during an approved release window outside standard working hours

Durations in the schedule are expressed primarily in working days.

---

## 5. Key Stage Gates & Milestones

The baseline includes the following major milestones:

1. Project Charter Approved
2. Requirements Baseline Approved
3. Solution Design Approved
4. Application & Integration Build Complete
5. System & Integration Testing Complete
6. Validation & UAT Complete
7. Production Readiness Approved
8. Go / No-Go Approved
9. Production Go-Live
10. Hypercare Complete
11. Project Closure Approved

These milestones are used for executive governance and release decision-making.

---

## 6. Dependency Logic

The schedule is designed around several major dependency chains.

### Requirements to Build
Requirements baseline must be sufficiently approved before final solution design and controlled build completion.

### Design to Development
Application, integration, migration, security, and operational designs drive downstream implementation.

### Build to Testing
A controlled application release candidate and completed integration components are required before formal system and integration testing.

### Data Migration
Data profiling and mapping precede migration development, which precedes trial migration and final production migration.

### Testing to Validation / UAT
Technical verification provides entry conditions for regulated validation and business acceptance.

### Validation to Release
Traceability, validation approval, business readiness, security approval, and operational readiness feed the production-readiness decision.

### Release to Hypercare
Go / No-Go authorization precedes production migration and deployment. Production verification initiates the structured hypercare period.

### Hypercare to Closure
Operational handover and hypercare exit must be achieved before final project closure.

---

## 7. Critical Path Approach

The baseline identifies the current critical path through the longest zero-float sequence of activities leading to project completion.

The initial critical chain runs broadly through:

**Requirements → Solution Design → Core Build → Technical Testing → Validation / UAT → Defect Resolution → Final Traceability Approval → Production Readiness → Go / No-Go → Deployment → Production Verification → Hypercare → Closure**

Critical-path status may change as actual performance, approved changes, resource constraints, or revised dependencies are introduced.

The schedule therefore treats critical-path analysis as an ongoing control activity rather than a one-time planning exercise.

---

## 8. Schedule Control

Schedule performance will later be monitored using:

- Baseline Start / Finish
- Current Forecast Start / Finish
- Actual Start / Finish
- Milestone variance
- Critical-path status
- Total float
- Schedule Performance Index (once EVM is established)
- Look-ahead planning
- Dependency and blocker reviews
- Corrective-action tracking

A material change to the approved schedule baseline requires integrated change control.

---

## 9. Schedule Tolerances

For this case study, the following management thresholds are assumed:

- **Work-package variance ≤ 5 working days:** Manage within delivery team where no downstream milestone impact exists
- **Milestone variance > 5 working days:** Escalate to Project Manager and impacted workstream leads
- **Critical milestone impact:** Escalate through formal governance regardless of days
- **Projected project completion delay:** Steering Committee review required
- **Baseline change:** Requires approved change request when schedule impact exceeds delegated tolerance

These thresholds are synthetic and are used to demonstrate schedule governance.

---

## 10. Relationship to Other Artifacts

The Integrated Project Schedule will provide timing inputs to:

- Resource Plan
- RACI / responsibility planning
- Procurement lead-time planning
- Cost estimating and time-phased Cost Baseline
- RAID Register
- Release-readiness planning
- EVM and forecast reporting
- Change-control impact analysis

The WBS ID is retained as the principal traceability key across these artifacts.

---

## Portfolio Disclaimer

Project Atlas is an independent project-management portfolio simulation. All dates, durations, dependencies, milestones, float values, and other project information are synthetic and do not represent confidential information from any employer, client, or customer.
