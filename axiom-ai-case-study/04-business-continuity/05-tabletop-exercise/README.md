# BCP/DR Tabletop Exercise

## Overview

This folder contains the documented tabletop exercise used to evaluate the practical effectiveness of Axiom AI Technologies' Business Continuity Plan (BCP) and Disaster Recovery Plan (DRP).

The exercise uses a scenario-based discussion format to evaluate organizational response to a significant technology disruption without performing destructive actions against production systems.

The exercise is designed to validate:

* Incident recognition and escalation
* Business impact assessment
* Continuity and recovery decision-making
* RTO, RPO, and MTPD awareness
* Technical recovery coordination
* Internal and stakeholder communications
* Executive decision-making
* Recovery validation
* Evidence and documentation requirements
* Corrective-action identification

---

## Exercise Scenario

The primary exercise scenario involves a simulated failure of the production PostgreSQL database hosted on AWS RDS.

The failure causes customer-facing application functionality to become unavailable or degraded. Participants must determine how the organization would identify, escalate, communicate, recover from, and ultimately close the disruption.

The scenario is intentionally structured to introduce increasing operational pressure through timed injects.

---

## Exercise Objectives

The exercise is intended to determine whether participants can:

1. Recognize and appropriately classify a significant service disruption.
2. Activate the appropriate incident, continuity, and recovery processes.
3. Identify affected business activities and dependencies.
4. Apply established RTO, RPO, and MTPD requirements.
5. Escalate decisions at appropriate thresholds.
6. Select and authorize an appropriate recovery approach.
7. Coordinate technical and business recovery activities.
8. Establish appropriate communication and notification requirements.
9. Validate service restoration before returning to normal operations.
10. Identify gaps that require corrective action.

---

## Exercise Type

**Type:** Scenario-based tabletop exercise
**Duration:** Approximately 90 minutes
**Environment:** Simulated / non-production
**Classification:** Internal / Portfolio Case Study

No destructive testing, production changes, live exploitation, or actual database recovery actions are performed as part of this exercise.

---

## Exercise Participants

The exercise may include the following roles:

| Role                                 | Responsibility                                                    |
| ------------------------------------ | ----------------------------------------------------------------- |
| Exercise Facilitator                 | Controls the scenario, provides injects, and records observations |
| Incident Lead                        | Coordinates technical response and recovery                       |
| Executive Approver / Escalation Lead | Provides business decisions and authorization                     |
| Operations / Communications Lead     | Coordinates internal and stakeholder communications               |
| Scribe / Evidence Owner              | Records decisions, timestamps, actions, and findings              |

Participant names may be populated when the exercise is actually conducted.

---

## Exercise Structure

The exercise progresses through a series of scenario injects:

1. **Detection** — Production RDS becomes unavailable.
2. **Initial Triage** — Technical investigation begins while root cause remains uncertain.
3. **Business Impact** — Customer workflows and critical business activities are affected.
4. **Escalation** — Recovery uncertainty creates pressure against established recovery thresholds.
5. **Recovery Choice** — Participants evaluate available recovery options and potential data loss.
6. **Communications** — Participants determine appropriate internal and external communication considerations.
7. **Restoration** — Service is restored and requires validation.
8. **Transition** — Participants determine incident closure and post-incident requirements.

---

## Recovery Objectives

The exercise references the organization's established:

* **RTO — Recovery Time Objective**
* **RPO — Recovery Point Objective**
* **MTPD — Maximum Tolerable Period of Disruption**

Participants are expected to use the values established in the approved BIA, BCP/DR Strategy, BCP, and DRP.

The exercise should not introduce arbitrary recovery targets that conflict with those documents.

If participants discover that a recovery target is unclear, unavailable, inconsistent, or impractical, the issue should be recorded as a finding.

---

## Decision and Escalation

The exercise evaluates whether participants understand when to:

* Declare an incident
* Activate continuity procedures
* Escalate to management
* Escalate when an RTO or MTPD threshold is threatened
* Obtain authorization for material risk acceptance
* Evaluate potential data loss against the RPO
* Consider customer, vendor, contractual, legal, or regulatory notification requirements
* Authorize recovery completion
* Close the incident

The exercise does not assume that every service disruption creates an external reporting obligation. Notification decisions should be based on the facts of the simulated incident and applicable requirements.

---

## Evidence and Exercise Records

The following evidence should be retained where applicable:

* Participant attendance
* Exercise timeline
* Scenario injects and responses
* Incident declaration
* Decision log
* Escalation decisions
* Recovery actions
* Communication decisions
* RTO/RPO/MTPD observations
* Facilitator observations
* Identified gaps
* Corrective actions
* Assigned owners
* Target completion dates

These records provide evidence that the continuity and recovery arrangements were exercised rather than merely documented.

---

## Success Criteria

The exercise is considered effective when participants are able to demonstrate that they can:

* Identify the appropriate response process
* Understand their assigned responsibilities
* Identify critical business impacts
* Apply documented recovery objectives
* Escalate decisions appropriately
* Make and document recovery decisions
* Coordinate communications
* Validate recovery before declaring the incident resolved
* Identify weaknesses in the BCP/DRP
* Convert significant findings into corrective actions

The exercise is not considered unsuccessful merely because gaps are identified. Discovering and documenting gaps is an intended outcome of the exercise.

---

## Post-Exercise Activities

Following the exercise, the facilitator should conduct a short **hotwash** with participants.

The hotwash should capture:

* What worked well
* What was unclear
* What assumptions were incorrect
* Which procedures were difficult to follow
* Which dependencies were overlooked
* Whether RTO/RPO expectations were realistic
* Whether escalation paths were clear
* Whether communication responsibilities were understood
* Which documents require revision

Formal findings and corrective actions should be documented in:

`06-testing-lessons-learned/`

---

## Related Documents

This exercise should be considered together with the following Project 4 artifacts:

```text
01-business-impact-analysis/
02-bcp-dr-strategy/
03-business-continuity-plan/
04-disaster-recovery-plan/
05-tabletop-exercise/
06-testing-lessons-learned/
```

The relationship between these artifacts is:

**BIA → Strategy → BCP → DRP → Exercise → Lessons Learned & Improvement**

---

## Document Ownership and Review

**Document Owner:** Business Continuity / Information Security Lead

**Approver:** Executive Management

**Review Frequency:** At least annually and following:

* A major business or technology change
* Changes to critical systems or dependencies
* Changes to RTO/RPO/MTPD requirements
* A significant incident
* A material change to the BCP or DRP
* Completion of a major continuity or disaster recovery exercise

Exercise findings should be reviewed after each exercise and incorporated into the organization's corrective-action and continual-improvement process.

---

## Document Status

| Field            | Value                                           |
| ---------------- | ----------------------------------------------- |
| Document         | BCP/DR Tabletop Exercise                        |
| Version          | 1.0                                             |
| Status           | Portfolio Case Study                            |
| Exercise Type    | Scenario-Based Tabletop                         |
| Scenario         | AWS RDS PostgreSQL Database Failure             |
| Owner            | Business Continuity / Information Security Lead |
| Review Frequency | Annual / After Material Change or Exercise      |
