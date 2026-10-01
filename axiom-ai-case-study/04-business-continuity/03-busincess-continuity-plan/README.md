# Business Continuity Plan

## Overview

This folder contains the **Business Continuity Plan (BCP)** developed for **Axiom AI Technologies**, a fictional B2B cloud AI/ML SaaS organization.

The BCP translates the requirements established in the Business Impact Analysis (BIA) and the BCP/DR Strategy into practical procedures for maintaining critical business activities during a disruptive event.

The plan establishes continuity responsibilities, activation criteria, escalation thresholds, recovery priorities, communication procedures, manual workarounds, and return-to-normal procedures.

> **Portfolio Disclaimer:** Axiom AI Technologies is a fictional organization created for cybersecurity/GRC portfolio purposes. The information contained within this project is modeled for demonstration and does not represent an assessment, certification, audit opinion, or operational capability of a real organization.

---

## Purpose

The purpose of the BCP is to provide a structured framework for maintaining critical business operations when normal operating conditions are disrupted.

The plan addresses:

* Business continuity activation.
* Incident and continuity levels.
* Decision-making and escalation.
* Critical business activity continuity.
* Recovery priorities.
* RTO and RPO requirements.
* Manual workarounds.
* Personnel continuity.
* Supplier continuity.
* Communications.
* Information protection.
* Return to normal operations.
* Post-event review.
* Testing and continual improvement.

---

## Relationship to the BIA and BCP/DR Strategy

The BCP is built from the recovery requirements identified in the BIA and the strategic approach established in the BCP/DR Strategy.

The relationship is:

**Business Impact Analysis**

Identifies critical activities, impacts, dependencies, MTPD, RTO, and RPO.

↓

**BCP/DR Strategy**

Defines the strategic approach to continuity and recovery.

↓

**Business Continuity Plan**

Defines how critical business activities continue during disruption.

↓

**Disaster Recovery Plan**

Defines how technology and infrastructure are technically recovered.

↓

**Testing & Exercises**

Validate the plans and recovery assumptions.

↓

**Lessons Learned & Continual Improvement**

Drive updates to the continuity program.

---

## Recovery Concepts

### Maximum Tolerable Period of Disruption (MTPD)

The **MTPD** is the maximum period that a business activity can remain unavailable before the resulting impact becomes unacceptable to the organization.

### Recovery Time Objective (RTO)

The **RTO** is the **target amount of time within which a business activity, system, or service should be restored following a disruption**.

RTO represents a **time-to-recovery requirement**.

### Recovery Point Objective (RPO)

The **RPO** is the **target maximum amount of data loss, measured in time, that the organization can tolerate following a disruption**.

RPO represents a **data-loss tolerance requirement**.

### RTO vs. RPO

| Concept  | What it measures               | Example                                           |
| -------- | ------------------------------ | ------------------------------------------------- |
| **MTPD** | Maximum acceptable disruption  | Activity cannot remain unavailable beyond 4 hours |
| **RTO**  | Target time to restore service | Restore service within 2 hours                    |
| **RPO**  | Maximum acceptable data loss   | Recover data to within 4 hours of disruption      |

In simple terms:

**MTPD = How long can we tolerate the disruption?**

**RTO = How quickly do we need to restore the service?**

**RPO = How much recent data can we afford to lose?**

---

## Business Continuity Activation

The BCP may be activated when a disruption has the potential to:

* Affect a critical business activity.
* Cause recovery objectives to be missed.
* Affect multiple business functions.
* Cause significant customer impact.
* Disrupt critical technology or cloud services.
* Create significant supplier or third-party impact.
* Require coordinated response across multiple functions.
* Exceed the capability of normal operational procedures.

Activation should be proportional to the severity and expected duration of the disruption.

---

## Decision and Escalation Thresholds

The BCP establishes objective thresholds to support timely escalation and decision-making.

Escalation may be triggered by:

* A P1 activity being materially disrupted.
* Recovery approaching or exceeding approximately 75% of the applicable RTO without sufficient progress.
* Recovery approaching approximately 90% of the RTO without validated restoration.
* An RTO breach.
* An MTPD being at risk.
* An RPO breach or inability to validate an appropriate recovery point.
* Multiple critical business functions being affected.
* A critical supplier disruption.
* Significant security concerns.
* Material customer impact.
* A requirement for decisions beyond delegated authority.

The thresholds are intended as early-warning and decision-support criteria rather than replacements for approved RTO, RPO, or MTPD requirements.

---

## Critical Business Activities

The BCP addresses continuity requirements for:

* Customer Support & Service Operations
* SaaS Platform Operations
* Identity & Access Administration
* Security Monitoring & Incident Response
* Software Development & Release Management
* Vulnerability Management & Security Remediation
* Third-Party & Supplier Security Management
* ISMS Governance & Compliance
* Customer & Business Communications
* Backup, Recovery & Data Restoration

Recovery priorities are based on the BIA.

---

## Recovery Priorities

| Priority          | Description                                                                                            |
| ----------------- | ------------------------------------------------------------------------------------------------------ |
| **P1 — Critical** | Activities requiring the shortest recovery timeframe and receiving priority during a major disruption. |
| **P2 — High**     | Important activities restored after P1 capabilities have been stabilized.                              |
| **P3 — Moderate** | Supporting activities that can be restored after higher-priority services.                             |

---

## Key BCP Components

The BCP contains procedures and guidance covering:

### Activation

Criteria and procedures for determining when continuity measures should be initiated.

### Roles and Responsibilities

Responsibilities for Executive Management, Incident Leadership, GRC, Security, Engineering/IT, Communications, Process Owners, and personnel.

### Continuity Procedures

Business-specific procedures for maintaining critical activities during disruption.

### Manual Workarounds

Temporary operating methods for situations where primary systems or services are unavailable.

### Communications

Primary and alternate communication methods for employees, customers, suppliers, management, and other stakeholders.

### Supplier Continuity

Procedures for managing disruptions involving critical third-party providers.

### Personnel Continuity

Requirements for backup personnel, cross-training, responsibilities, and critical knowledge.

### Return to Normal Operations

Criteria for transitioning from continuity operations back to normal business operations.

### Post-Event Review

Requirements for documenting lessons learned and identifying corrective actions.

---

## Testing and Validation

The BCP should be validated through periodic exercises and testing.

Testing activities may include:

* Tabletop exercises.
* Technical recovery testing.
* Backup restoration testing.
* Plan reviews.
* Supplier continuity reviews.
* Post-incident reviews.

Testing should evaluate whether:

* Roles and responsibilities are understood.
* Escalation procedures work as intended.
* Communications are effective.
* Recovery priorities are appropriate.
* RTO and RPO assumptions remain achievable.
* Manual workarounds are practical.
* Dependencies are accurately documented.

Testing results should feed into corrective actions and continual improvement.

---

## Framework Alignment

The BCP demonstrates concepts relevant to:

* **ISO/IEC 27001:2022**
* **ISO 22301 — Business Continuity Management**
* **NIST Cybersecurity Framework**
* **NIST SP 800-34 — Contingency Planning Guide**
* General business continuity and disaster recovery practices

The artifact is a portfolio demonstration and does not claim formal compliance or certification.

---

## Artifact

**Primary Artifact:**

`Axiom-AI-Business-Continuity-Plan.docx`

**Format:** Microsoft Word Document

**Classification:** Internal Use

The document can also be exported to PDF for portfolio presentation.

---

## Related Artifacts

* `../01-business-impact-analysis/Axiom-AI-Business-Impact-Analysis.xlsx`
* `../02-bcp-dr-strategy/Axiom-AI-BCP-DR-Strategy.docx`

### Related ISMS Artifacts

* Risk Register
* Statement of Applicability
* Information Security Policy
* Incident Response Policy
* Asset Management Policy
* Access Control Policy
* Third-Party Security Policy

### Planned Project 4 Artifacts

* Disaster Recovery Plan
* BCP/DR Tabletop Exercise
* Testing & Lessons Learned

---

## Portfolio Value

This artifact demonstrates the ability to translate:

**Business Impact → Recovery Requirements → Strategic Approach → Operational Continuity Procedures**

It demonstrates practical understanding of how a GRC professional can connect business continuity requirements with risk management, security governance, incident response, technology recovery, and continual improvement.

---

## Portfolio Disclaimer

This Business Continuity Plan is a fictional cybersecurity/GRC portfolio artifact created to demonstrate practical application of business continuity and disaster recovery principles.

The recovery objectives, roles, procedures, dependencies, thresholds, and assumptions are modeled examples and would require validation, approval, testing, and ongoing maintenance by appropriate business, technical, security, and executive stakeholders in a real organization.
