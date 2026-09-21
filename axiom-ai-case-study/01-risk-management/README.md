# Axiom AI — Risk Management

## Overview

This workstream establishes the cybersecurity risk management foundation for the Axiom AI case study.

Axiom AI Technologies is a fictional B2B AI/ML SaaS organization with approximately 180 employees. The organization operates primarily in a cloud-based AWS environment and supports customer-facing AI/ML services, APIs, proprietary models, application source code, and sensitive customer information.

The risk assessment identifies key information security and cybersecurity risks affecting Axiom's business operations, technology environment, information assets, and third-party dependencies. The results are used to inform subsequent security control assessment, ISO/IEC 27001 ISMS implementation, business continuity planning, and vulnerability management activities within the case study.

> **Portfolio Disclaimer:** Axiom AI Technologies is a fictional organization created for portfolio demonstration purposes. The assessment methodology and artifacts are inspired by and based on real professional projects performed in cybersecurity, GRC, risk management, and ISO/IEC 27001 environments.

---

## Objectives

The objectives of this risk management workstream are to:

* Establish an inventory of key information assets and technology resources.
* Identify cybersecurity and information security risks affecting Axiom AI.
* Evaluate risks based on likelihood and potential business impact.
* Identify existing controls and risk treatment considerations.
* Determine inherent and residual risk levels.
* Prioritize risks requiring additional treatment or remediation.
* Establish a documented risk treatment approach aligned with organizational priorities.
* Provide risk-based inputs for subsequent case study workstreams.

---

## Scope

The assessment considers risks associated with Axiom AI's:

* Cloud infrastructure and AWS environment
* Customer-facing SaaS applications
* APIs and application interfaces
* Customer and business data
* AI/ML models and intellectual property
* Application source code
* Identity and access management
* Employee endpoints and remote work
* Logging and security monitoring
* Software development and CI/CD processes
* Third-party and SaaS service providers
* Business-critical technology services
* Incident response and security operations
* Availability, integrity, confidentiality, and resilience of information assets

The assessment is focused on cybersecurity and information security risk management and does not constitute a live penetration test, vulnerability scan, or technical security assessment of an actual production environment.

---

## Risk Management Methodology

The assessment uses a qualitative risk methodology informed by:

* ISO/IEC 27001:2022
* ISO/IEC 27005 risk management principles
* NIST Cybersecurity Framework (CSF) 2.0
* NIST SP 800-30 risk assessment concepts

Risks are evaluated using a likelihood and impact model.

### Likelihood

Likelihood represents the estimated probability that a threat or adverse event could occur.

| Score | Rating         |
| ----- | -------------- |
| 1     | Rare           |
| 2     | Unlikely       |
| 3     | Possible       |
| 4     | Likely         |
| 5     | Almost Certain |

### Impact

Impact represents the potential effect of a risk on Axiom's operations, customers, information, technology, regulatory obligations, and business objectives.

| Score | Rating        |
| ----- | ------------- |
| 1     | Insignificant |
| 2     | Minor         |
| 3     | Moderate      |
| 4     | Major         |
| 5     | Severe        |

### Risk Score

**Risk Score = Likelihood × Impact**

The resulting score is used to categorize risk severity and prioritize treatment activities.

| Score Range | Risk Level |
| ----------- | ---------- |
| 1–4         | Low        |
| 5–9         | Moderate   |
| 10–16       | High       |
| 17–25       | Critical   |

---

## Risk Treatment

Identified risks are evaluated to determine an appropriate treatment strategy.

Treatment options include:

* **Mitigate** — Implement or strengthen controls to reduce likelihood and/or impact.
* **Avoid** — Eliminate the activity, process, or condition creating the risk.
* **Transfer** — Shift a portion of the risk through contractual, insurance, or third-party arrangements.
* **Accept** — Formally accept the remaining risk when it falls within the organization's risk tolerance.

Risk treatment decisions consider business impact, existing controls, residual risk, resource requirements, and organizational priorities.

---

## Key Assessment Artifacts

| Artifact                                | Purpose                                                                                                     |
| --------------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| `Axiom-AI-Asset-Inventory.xlsx`         | Identifies key information, technology, and business assets within the assessment scope.                    |
| `Axiom-AI-Risk-Register.xlsx`           | Documents identified risks, risk ratings, existing controls, treatment decisions, and residual risk.        |
| `Axiom-AI-Risk-Assessment-Summary.docx` | Provides an executive-level summary of the assessment results, major risk themes, and treatment priorities. |

---

## Relationship to the Axiom AI Case Study

This workstream is the first stage of the broader Axiom AI security and compliance case study.

The risk assessment establishes the risk landscape that informs subsequent workstreams:

```text
01 Risk Management
        ↓
02 Security Controls Assessment
        ↓
03 ISO/IEC 27001 ISMS Implementation
        ↓
04 Business Continuity & Resilience
        ↓
05 Vulnerability Management,
   Security Remediation & Malware Analysis
```

The previously completed Security Controls Assessment evaluates Axiom's control environment against ISO/IEC 27001:2022, NIST CSF 2.0, and NIST SP 800-53.

Findings from that assessment will be considered when evaluating existing controls and determining residual risk within this broader case study.

---

## Assessment Boundaries

This portfolio assessment is a simulated GRC exercise.

It does not involve:

* Live testing of Axiom AI systems
* Exploitation of vulnerabilities
* Access to production environments
* Collection of real customer information
* Real credentials, secrets, or authentication material
* Actual incident investigation
* Unauthorized security testing

All organizational, asset, risk, and control information is fictional or generalized for portfolio demonstration purposes.

---

## Expected Outcomes

The completed risk management workstream will provide:

1. A documented inventory of relevant information and technology assets.
2. A structured cybersecurity risk register.
3. Inherent and residual risk evaluations.
4. Risk treatment recommendations.
5. Prioritized risks for remediation and management attention.
6. A documented foundation for the subsequent ISO/IEC 27001 ISMS implementation.

---

## Framework Alignment

| Framework / Standard | Application                                           |
| -------------------- | ----------------------------------------------------- |
| ISO/IEC 27001:2022   | Information security risk management and ISMS context |
| ISO/IEC 27005        | Information security risk management principles       |
| NIST CSF 2.0         | Cybersecurity risk identification and management      |
| NIST SP 800-30       | Risk assessment methodology and analysis concepts     |

