# Cyber Risk Assessment & Risk Register

## Northstar Health Technologies

> **Enterprise Cyber Risk Assessment | Cyber Risk Management / GRC**

|                          |                                           |
| ------------------------ | ----------------------------------------- |
| **Assessment Type**      | Enterprise Cyber Risk Assessment          |
| **Environment**          | Cloud-Based SaaS                          |
| **Organization**         | Fictional Healthcare Technology Company   |
| **Framework References** | ISO/IEC 27001 · NIST CSF · NIST SP 800-30 |
| **Project Status**       | Completed Portfolio Demonstration         |

---

## 1. Project Overview

This project demonstrates the design and execution of a structured **enterprise cybersecurity risk assessment** for a fictional cloud-based healthcare technology organization.

**Northstar Health Technologies** is a mid-sized SaaS provider supporting healthcare organizations through cloud-hosted patient management and healthcare workflow applications.

The assessment evaluates cybersecurity risks affecting Northstar's:

* Information assets
* Cloud environment
* Business operations
* Employees and endpoints
* Third-party dependencies

The project demonstrates a practical risk-management lifecycle:

```text
Asset Identification
        ↓
Threat & Vulnerability Identification
        ↓
Risk Analysis
        ↓
Risk Evaluation
        ↓
Risk Treatment
        ↓
Residual Risk Assessment
        ↓
Risk Monitoring
```

The resulting risk register and treatment plan are designed to provide both operational teams and executive leadership with a structured view of the organization's cybersecurity risk exposure.

---

## 2. Organization Profile

### Northstar Health Technologies

Northstar Health Technologies is a fictional healthcare technology company with approximately **250 employees**.

The organization provides cloud-based software used by healthcare customers to manage workflows and patient-related information.

### Business Characteristics

* Approximately 250 employees
* Cloud-first operating model
* AWS-hosted production environment
* Remote and hybrid workforce
* Healthcare-sector customers
* Sensitive customer and patient-related information
* Multiple third-party technology and service providers
* Formal information security and compliance program
* Security governance aligned with ISO/IEC 27001 and NIST practices
* Preparing for a future SOC 2 examination

### Key Technology Areas

The fictional environment includes:

* AWS production infrastructure
* Web and API applications
* Relational databases
* Corporate endpoints
* Identity and access management
* Security monitoring and logging
* Backup and recovery systems
* Collaboration and productivity platforms
* Third-party SaaS applications

---

## 3. Assessment Objectives

The primary objectives of this assessment are to:

1. Identify critical information assets and business dependencies.
2. Identify relevant cybersecurity threats and vulnerabilities.
3. Evaluate the likelihood and potential impact of identified risks.
4. Determine inherent risk levels before additional treatment.
5. Identify existing security controls and control gaps.
6. Prioritize risks according to organizational impact.
7. Develop appropriate risk treatment recommendations.
8. Assign ownership and target actions for risk remediation.
9. Provide executive leadership with a clear summary of significant cybersecurity risks.
10. Establish a repeatable methodology for ongoing risk monitoring.

---

## 4. Assessment Scope

The assessment covers cybersecurity risks associated with Northstar's:

### Information Assets

* Customer and patient-related information
* Corporate information
* Authentication credentials
* Security logs
* Application data
* Configuration data
* Backup data

### Technology

* AWS cloud infrastructure
* Web applications
* APIs
* Databases
* Corporate endpoints
* Identity and access management systems
* Security monitoring infrastructure
* Backup and recovery systems

### Business Processes

* Software development
* Change management
* User access management
* Vendor management
* Vulnerability management
* Incident response
* Backup and recovery
* Security monitoring
* Employee onboarding and offboarding

### Third Parties

The assessment considers risks introduced by:

* Cloud service providers
* SaaS vendors
* Managed service providers
* Software and technology suppliers
* External service providers with access to organizational information

---

## 5. Out of Scope

The following areas are excluded from this assessment:

* Physical penetration testing
* Live vulnerability scanning
* Malware execution or analysis
* Production system exploitation
* Actual customer data
* Real employee information
* Real credentials or authentication secrets
* Real cloud infrastructure
* Real third-party contractual information

All assessment activities are based on fictional or synthetically generated information.

---

## 6. Risk Assessment Methodology

The assessment methodology combines concepts from **ISO/IEC 27001**, the **NIST Cybersecurity Framework (CSF)**, and **NIST SP 800-30**.

The methodology is designed to demonstrate how cybersecurity risks can be consistently:

**Identified → Analyzed → Evaluated → Treated → Monitored**

### Risk Assessment Process

```text
Asset Identification
        ↓
Threat Identification
        ↓
Vulnerability Identification
        ↓
Existing Control Review
        ↓
Likelihood Assessment
        ↓
Impact Assessment
        ↓
Risk Calculation
        ↓
Risk Evaluation & Prioritization
        ↓
Risk Treatment
        ↓
Residual Risk Assessment
        ↓
Risk Monitoring
```

---

## 7. Risk Scoring Methodology

Each identified risk is evaluated using **two scoring dimensions**:

1. **Likelihood — 1 to 5**
2. **Impact — 1 to 5**

These two scores are then multiplied to produce the overall **Risk Score — 1 to 25**.

### How the Scoring Works

```text
Likelihood Score (1–5)
          ×
Impact Score (1–5)
          ↓
Risk Score (1–25)
          ↓
Risk Level
```

For example:

> **Likelihood = 4**
> **Impact = 4**
> **Risk Score = 4 × 4 = 16**
> **Risk Level = 🟠 High**

The 1–5 scales therefore represent the **individual dimensions of risk**, while the 1–25 scale represents the **calculated overall risk score**.

### Likelihood

Likelihood represents the estimated probability that a threat could successfully exploit a vulnerability or otherwise cause the identified risk event.

| Score | Rating         | Description                                |
| ----: | -------------- | ------------------------------------------ |
| **1** | Rare           | Highly unlikely under normal circumstances |
| **2** | Unlikely       | Possible but not expected                  |
| **3** | Possible       | Could reasonably occur                     |
| **4** | Likely         | Expected to occur under certain conditions |
| **5** | Almost Certain | Highly likely or expected to occur         |

### Impact

Impact represents the potential effect on the organization's:

* Confidentiality
* Integrity
* Availability
* Financial position
* Regulatory/compliance obligations
* Reputation
* Business operations

| Score | Rating        | Description                                              |
| ----: | ------------- | -------------------------------------------------------- |
| **1** | Insignificant | Minimal operational or business effect                   |
| **2** | Minor         | Limited disruption or loss                               |
| **3** | Moderate      | Material business impact                                 |
| **4** | Major         | Significant operational, financial, or compliance impact |
| **5** | Severe        | Critical business or organizational impact               |

### Risk Score

**Risk Score = Likelihood × Impact**

This produces a score between **1 and 25**.

|     Score | Risk Level      | Status                                                  |
| --------: | --------------- | ------------------------------------------------------- |
|   **1–4** | 🟢 **Low**      | Generally acceptable with routine monitoring            |
|   **5–9** | 🟡 **Moderate** | Additional controls or monitoring may be appropriate    |
| **10–16** | 🟠 **High**     | Requires prioritized treatment and risk-owner attention |
| **17–25** | 🔴 **Critical** | Requires urgent treatment and management attention      |

> **Note:** Risk ratings support prioritization and treatment decisions. They should not be interpreted as precise mathematical probabilities of occurrence.

### Example Risk Calculations

| Likelihood | Impact | Calculation | Risk Score | Risk Level  |
| ---------: | -----: | ----------: | ---------: | ----------- |
|          1 |      2 |       1 × 2 |      **2** | 🟢 Low      |
|          2 |      3 |       2 × 3 |      **6** | 🟡 Moderate |
|          4 |      4 |       4 × 4 |     **16** | 🟠 High     |
|          5 |      5 |       5 × 5 |     **25** | 🔴 Critical |

---

## 8. Risk Treatment

Identified risks will be evaluated against four primary treatment options.

### Mitigate

Implement or improve security controls to reduce likelihood and/or impact.

### Transfer

Shift some financial or operational consequences to another party through mechanisms such as contractual arrangements or insurance.

### Avoid

Discontinue or modify the activity creating unacceptable risk.

### Accept

Formally accept the remaining risk when the risk is within organizational tolerance and additional treatment is not justified.

Risk acceptance decisions should be documented and approved by an appropriate risk owner.

---

## 9. Risk Register

The risk register will document identified cybersecurity risks and their associated treatment activities.

Key fields include:

* Risk ID
* Asset
* Business Process
* Risk Description
* Threat
* Vulnerability
* Existing Controls
* Likelihood
* Impact
* Inherent Risk
* Risk Owner
* Treatment Strategy
* Recommended Controls
* Target Date
* Residual Risk
* Status

The register is intended to function as a **living risk-management artifact** rather than a one-time assessment.

Risk status will use the following visual classification:

* 🟢 **Low**
* 🟡 **Moderate**
* 🟠 **High**
* 🔴 **Critical**

---

## Executive Risk Summary

The executive risk summary provides a management-level overview of the cybersecurity assessment and translates the detailed risk analysis into an executive-focused view of organizational risk exposure.

The summary highlights:

* Overall inherent and residual risk exposure
* Highest-priority cybersecurity risks
* Key cybersecurity risk themes
* Risk treatment priorities
* Residual risk considerations
* Recommended monitoring activities
* Management-level actions and priorities

### Executive Summary Deliverable

**01-cyber-risk-assessment/Northstar Health Technologies — Executive Cyber Risk Summary.pdf**

The executive summary is intended to demonstrate how detailed cybersecurity risk assessment results can be communicated to executive leadership and other business stakeholders in a concise, decision-oriented format.

### Assessment Results

The completed assessment evaluated:

* **20** organizational assets
* **15** cybersecurity risks
* **6** Critical inherent risks
* **9** High inherent risks
* **10** High residual risks
* **5** Moderate residual risks

The assessment identified significant risk exposure across areas including identity and access management, application and API security, cloud configuration, credential and secrets management, operational resilience, vulnerability management, and third-party risk.

The assessment applies a structured risk treatment process to demonstrate how identified risks can be reduced through security controls, remediation activities, monitoring, and ongoing risk-owner oversight.

---

## 10. Risk Treatment Plan

The treatment plan will translate prioritized risks into actionable remediation activities.

Each treatment activity will include:

* Recommended action
* Control or mitigation
* Responsible owner
* Priority
* Target completion date
* Implementation status
* Residual risk
* Evidence requirements

Treatment activities will prioritize risks based on:

**Business Impact + Threat Exposure + Control Weakness + Organizational Risk Tolerance**

---

## 11. Key Deliverables

This project contains the following deliverables:

### Risk Methodology

Documentation describing the assessment approach, scoring model, risk criteria, and treatment methodology.

### Asset Inventory

A structured inventory of fictional organizational assets and business dependencies used as the foundation for the assessment.

### Risk Register

A detailed register documenting identified cybersecurity risks, risk scores, existing controls, owners, and treatment decisions.

### Risk Treatment Plan

A prioritized remediation plan showing how identified risks will be addressed.

### Executive Risk Summary

A management-level summary highlighting significant risks, risk trends, treatment priorities, and recommended actions.

---

## 12. Expected Assessment Outcomes

The completed assessment is intended to demonstrate the organization's ability to:

* Establish a repeatable cybersecurity risk assessment process
* Identify and prioritize material cyber risks
* Connect technical vulnerabilities to business impact
* Evaluate existing security controls
* Document risk ownership
* Develop actionable remediation plans
* Track residual risk
* Communicate cybersecurity risk to executive leadership

---

## 13. Professional Relevance

This project is a fictional portfolio demonstration inspired by real-world cybersecurity GRC activities and professional experience.

The assessment structure reflects practical approaches used in areas including:

* Cyber risk assessments
* Risk register management
* Security control evaluation
* Risk treatment and remediation
* Executive risk reporting
* ISO/IEC 27001 information security management
* NIST-aligned security risk management
* Third-party risk management
* Vulnerability management
* Business continuity and operational resilience

The purpose of the project is to demonstrate the ability to translate cybersecurity requirements and identified technical risks into structured, business-oriented risk management activities.

---

## 14. Framework Alignment

### ISO/IEC 27001

Used as a reference for information security risk management, organizational controls, risk treatment, and continual improvement.

### NIST Cybersecurity Framework (CSF)

Used to provide a broader cybersecurity governance and risk-management perspective.

### NIST SP 800-30

Used as a reference for structured risk assessment concepts, including threat, vulnerability, likelihood, impact, and risk determination.

> **Important:** This project does not claim formal certification or compliance with any of these frameworks.

---

## 15. Portfolio Disclaimer

This project is a **fictional or synthetically recreated demonstration** inspired by real-world cybersecurity, GRC, risk management, compliance, and security assessment work performed in professional environments.

The methodologies, workflows, assessment approaches, and deliverable structures reflect practical experience, while the organization, systems, data, scenarios, findings, and other project-specific details have been created or modified for portfolio and educational purposes.

**No confidential, proprietary, client, or employer information is included in this repository.**
