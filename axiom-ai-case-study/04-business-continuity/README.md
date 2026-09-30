# Business Continuity & Disaster Recovery

## Overview

This project demonstrates the development of a Business Continuity and Disaster Recovery (BCP/DR) framework for **Axiom AI Technologies**, a fictional B2B cloud AI/ML SaaS organization.

The project builds on the risk management, controls assessment, ISMS implementation, policies, and Statement of Applicability developed in the previous stages of the case study.

The objective is to demonstrate how an organization can translate identified business risks and critical processes into practical continuity, recovery, testing, and improvement activities.

> **Portfolio Disclaimer:** Axiom AI Technologies is a fictional organization created for cybersecurity/GRC portfolio purposes. The artifacts in this project are modeled examples and do not represent an actual organization's certification, audit opinion, operational capability, or confidential information.

---

## Objectives

This project demonstrates the ability to:

* Perform a Business Impact Analysis (BIA).
* Identify critical business processes and dependencies.
* Define Maximum Tolerable Periods of Disruption (MTPD).
* Establish Recovery Time Objectives (RTO).
* Establish Recovery Point Objectives (RPO).
* Prioritize business activities for recovery.
* Develop a Business Continuity and Disaster Recovery strategy.
* Define continuity and recovery approaches for critical capabilities.
* Establish backup and recovery expectations.
* Address people, technology, communications, and supplier continuity.
* Develop business continuity and disaster recovery plans.
* Design tabletop exercises and recovery tests.
* Track lessons learned and continual-improvement actions.

---

# Project Structure

## 01 — Business Impact Analysis

The Business Impact Analysis establishes the business requirements that drive continuity and recovery planning.

### Key activities

The BIA identifies:

* Business processes and activities.
* Process owners.
* Business criticality.
* Potential impact from disruption.
* MTPD.
* RTO.
* RPO.
* Recovery priorities.
* Internal and external dependencies.
* Minimum resources.
* Manual workarounds.
* Recovery considerations.

### Primary Artifact

`Axiom-AI-Business-Impact-Analysis.xlsx`

The workbook contains:

* BIA
* Summary
* Recovery Requirements
* Assumptions

The BIA serves as the foundation for the remaining BCP/DR artifacts.

---

## 02 — BCP/DR Strategy

The BCP/DR Strategy translates the BIA findings into an organization-wide recovery approach.

### Key areas covered

* Recovery principles.
* Recovery priorities.
* BIA-derived recovery requirements.
* Continuity strategies.
* Technology recovery.
* People and organizational continuity.
* Communications.
* Supplier and dependency resilience.
* Manual workarounds.
* Backup and data restoration.
* Exercise and testing strategy.
* Governance and responsibilities.
* Implementation roadmap.
* Continual improvement.

### Primary Artifact

`Axiom-AI-BCP-DR-Strategy.docx`

The document is designed to be converted to PDF for portfolio publication.

---

# Planned Future Artifacts

The BCP/DR framework will be expanded with additional artifacts.

## 03 — Business Continuity Plan

The Business Continuity Plan will translate the strategy into business-level continuity procedures.

Planned content includes:

* Business continuity roles.
* Activation criteria.
* Escalation procedures.
* Emergency communications.
* Business process continuity.
* Manual workarounds.
* Critical personnel requirements.
* Supplier continuity.
* Stakeholder communications.
* Return-to-normal operations.
* Plan maintenance.

---

## 04 — Disaster Recovery Plan

The Disaster Recovery Plan will provide the technical recovery framework supporting critical technology services.

Planned content includes:

* Disaster recovery roles.
* Recovery activation.
* Technology dependencies.
* Recovery sequence.
* Backup and restoration.
* Cloud infrastructure recovery.
* Database recovery.
* Application recovery.
* Identity and access recovery.
* Security monitoring recovery.
* Validation and service restoration.
* Recovery completion criteria.

---

## 05 — Tabletop Exercise

A tabletop exercise will be used to validate the BCP/DR framework through a simulated disruption scenario.

The exercise will evaluate:

* Roles and responsibilities.
* Incident escalation.
* Decision-making.
* Communications.
* Recovery priorities.
* RTO/RPO assumptions.
* Business continuity procedures.
* Technical recovery coordination.
* Third-party dependencies.

---

## 06 — Testing & Lessons Learned

Testing artifacts will document recovery exercises and identify opportunities for improvement.

Planned evidence includes:

* Exercise objectives.
* Scenario.
* Participants.
* Decisions.
* Recovery actions.
* RTO/RPO observations.
* Identified gaps.
* Corrective actions.
* Action owners.
* Target dates.
* Lessons learned.
* Follow-up validation.

---

# Relationship to Previous Projects

Project 4 builds directly on the earlier Axiom AI case-study work.

### Project 1 — Risk Management

Identified organizational risks and established risk treatment requirements.

↓

### Project 2 — Controls Assessment

Assessed security controls and identified control gaps requiring remediation.

↓

### Project 3 — ISMS Implementation

Established the ISMS foundation through:

* ISMS Scope.
* Information Security Policy.
* Access Control Policy.
* Incident Response Policy.
* Asset Management Policy.
* Third-Party Security Policy.
* Statement of Applicability.
* Supporting governance documentation.

↓

### Project 4 — Business Continuity & Disaster Recovery

Uses the outputs above to determine:

**What needs to be protected → What happens if it is unavailable → How quickly it must be recovered → How it will be recovered → How recovery will be tested.**

---

# Framework Alignment

The project is designed to demonstrate concepts relevant to:

* **ISO/IEC 27001:2022**
* **ISO 22301 — Business Continuity Management**
* **NIST Cybersecurity Framework**
* **NIST SP 800-34 — Contingency Planning Guide**
* General cybersecurity business continuity and disaster recovery practices.

The artifacts are educational portfolio demonstrations and should not be interpreted as claiming formal compliance or certification.

---

# Key Recovery Concepts

### Maximum Tolerable Period of Disruption — MTPD

The maximum period a business activity can remain unavailable before the resulting impact becomes unacceptable.

### Recovery Time Objective — RTO

The target time within which a service or business activity should be restored following disruption.

### Recovery Point Objective — RPO

The target maximum amount of data loss measured in time.

### Recovery Priority

The order in which business activities should be restored during a significant disruption.

For this project:

* **P1** — Critical recovery priority
* **P2** — High recovery priority
* **P3** — Moderate recovery priority

These priorities are portfolio assumptions and would require business-owner validation in a real organization.

---

# Current Status

| Artifact                  | Status      |
| ------------------------- | ----------- |
| Business Impact Analysis  | Complete    |
| BIA README                | Complete    |
| BCP/DR Strategy           | Complete    |
| BCP/DR Strategy README    | In progress |
| Business Continuity Plan  | Planned     |
| Disaster Recovery Plan    | Planned     |
| Tabletop Exercise         | Planned     |
| Testing & Lessons Learned | Planned     |

---

# Portfolio Value

This project demonstrates practical experience in connecting:

**Business Impact → Risk → Recovery Requirements → Continuity Strategy → Recovery Planning → Testing → Continual Improvement**

Rather than treating business continuity as a standalone documentation exercise, the project demonstrates how recovery requirements can be derived from business impact and integrated with an organization's broader ISMS and risk-management processes.
