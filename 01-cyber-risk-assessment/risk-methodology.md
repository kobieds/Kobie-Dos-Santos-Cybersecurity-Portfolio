# Cybersecurity Risk Assessment Methodology

## Northstar Health Technologies

> **Enterprise Cyber Risk Assessment | Cyber Risk Management / GRC**

---

## 1. Purpose

This document defines the methodology used to identify, analyze, evaluate, treat, and monitor cybersecurity risks for Northstar Health Technologies.

The methodology is designed to provide a consistent and repeatable approach for evaluating information security risks and supporting risk-based decision-making.

The assessment methodology considers:

* Information assets
* Business processes
* Threats
* Vulnerabilities and control weaknesses
* Existing security controls
* Likelihood of occurrence
* Potential business impact
* Risk treatment options
* Residual risk
* Risk ownership
* Ongoing monitoring

---

## 2. Methodology References

The assessment methodology is informed by established cybersecurity and information security risk-management practices, including:

### ISO/IEC 27001

Used as a reference for information security risk assessment, risk treatment, control implementation, and continual improvement within an Information Security Management System (ISMS).

### NIST Cybersecurity Framework (CSF)

Used to provide a broader cybersecurity risk-management perspective and help connect cybersecurity activities to organizational risk management.

### NIST SP 800-30

Used as a reference for structured risk assessment concepts, including threat identification, vulnerability assessment, likelihood, impact, and risk determination.

> **Important:** These references provide methodological guidance. This project does not represent formal certification, accreditation, or compliance with any referenced framework.

---

## 3. Risk Assessment Lifecycle

The assessment follows a structured lifecycle:

```text
Asset Identification
        ↓
Threat Identification
        ↓
Vulnerability & Control Weakness Identification
        ↓
Existing Control Assessment
        ↓
Likelihood Assessment
        ↓
Impact Assessment
        ↓
Inherent Risk Calculation
        ↓
Risk Evaluation & Prioritization
        ↓
Risk Treatment
        ↓
Residual Risk Assessment
        ↓
Risk Monitoring & Review
```

Each stage contributes to the overall risk decision-making process.

---

## 4. Asset Identification

The first stage is identifying assets and business dependencies that could be affected by cybersecurity events.

Assets may include:

### Information Assets

* Customer information
* Patient-related information
* Authentication information
* Application data
* Security logs
* Configuration data
* Backup data
* Corporate information

### Technology Assets

* AWS infrastructure
* Web applications
* APIs
* Databases
* Corporate endpoints
* Identity and access management systems
* Security monitoring platforms
* Backup and recovery systems

### Business Processes

* Software development
* Change management
* Access management
* Vendor management
* Vulnerability management
* Incident response
* Backup and recovery
* Security monitoring
* Employee onboarding and offboarding

Each asset should have an identified business owner or responsible stakeholder where appropriate.

---

## 5. Threat Identification

Threat identification evaluates events or actors that could exploit vulnerabilities or otherwise negatively affect organizational assets.

Examples include:

* Phishing and social engineering
* Credential compromise
* Unauthorized access
* Malware
* Ransomware
* Exploitation of application vulnerabilities
* Cloud misconfiguration
* Insider threats
* Third-party compromise
* Data leakage
* Denial-of-service attacks
* Supply-chain attacks
* Accidental data disclosure
* System or service failure

Threat identification considers both malicious and non-malicious events.

---

## 6. Vulnerability and Control Weakness Identification

A vulnerability or control weakness represents a condition that could increase the likelihood or impact of a risk event.

Examples include:

* Excessive user privileges
* Weak authentication controls
* Unpatched systems
* Inadequate logging
* Insufficient network segmentation
* Misconfigured cloud resources
* Inadequate backup protection
* Lack of security awareness training
* Incomplete vendor due diligence
* Inadequate incident response procedures
* Insufficient access reviews
* Weak change-management practices

The assessment considers both technical vulnerabilities and organizational/process weaknesses.

---

## 7. Existing Control Assessment

Existing controls are documented to determine how effectively the organization currently manages an identified risk.

Controls may include:

### Preventive Controls

Controls designed to prevent a security event from occurring.

Examples:

* Multi-factor authentication
* Least-privilege access
* Secure configuration standards
* Network controls
* Security awareness training

### Detective Controls

Controls designed to identify security events or control failures.

Examples:

* Security monitoring
* Logging
* Alerting
* Vulnerability scanning
* Access reviews

### Corrective Controls

Controls designed to reduce the impact of an event or restore normal operations.

Examples:

* Incident response procedures
* Backup and recovery
* Disaster recovery
* Remediation processes
* Business continuity procedures

Control effectiveness should be considered when determining the likelihood and overall risk exposure.

---

## 8. Likelihood Assessment

Likelihood represents the estimated probability that a risk event could occur based on the identified threat, vulnerabilities, existing controls, exposure, and relevant organizational circumstances.

Likelihood is scored from **1 to 5**.

| Score | Rating         | Description                                |
| ----: | -------------- | ------------------------------------------ |
| **1** | Rare           | Highly unlikely under normal circumstances |
| **2** | Unlikely       | Possible but not expected                  |
| **3** | Possible       | Could reasonably occur                     |
| **4** | Likely         | Expected to occur under certain conditions |
| **5** | Almost Certain | Highly likely or expected to occur         |

Likelihood should consider factors such as:

* Threat activity
* Exposure
* Vulnerability severity
* Exploitability
* Existing controls
* User behavior
* Historical events
* Environmental conditions

---

## 9. Impact Assessment

Impact represents the potential consequence if the identified risk event occurs.

Impact is evaluated across relevant business and security dimensions, including:

* Confidentiality
* Integrity
* Availability
* Financial impact
* Regulatory and contractual obligations
* Reputation
* Customer impact
* Operational disruption

Impact is scored from **1 to 5**.

| Score | Rating        | Description                                              |
| ----: | ------------- | -------------------------------------------------------- |
| **1** | Insignificant | Minimal operational or business effect                   |
| **2** | Minor         | Limited disruption or loss                               |
| **3** | Moderate      | Material business impact                                 |
| **4** | Major         | Significant operational, financial, or compliance impact |
| **5** | Severe        | Critical business or organizational impact               |

---

## 10. Inherent Risk Calculation

Inherent risk represents the level of risk before considering the effect of additional risk treatment actions.

The risk score is calculated as:

**Risk Score = Likelihood × Impact**

Because both dimensions use a 1–5 scale, the resulting risk score ranges from **1 to 25**.

```text
Likelihood (1–5)
        ×
Impact (1–5)
        ↓
Risk Score (1–25)
```

### Example

If:

* Likelihood = 4
* Impact = 4

Then:

**4 × 4 = 16**

The resulting risk level is **High**.

---

## 11. Risk Classification

Risk scores are categorized as follows:

| Risk Score | Risk Level  | Management Expectation                               |
| ---------: | ----------- | ---------------------------------------------------- |
|    **1–4** | 🟢 Low      | Routine monitoring                                   |
|    **5–9** | 🟡 Moderate | Additional controls or monitoring may be appropriate |
|  **10–16** | 🟠 High     | Prioritized treatment and risk-owner attention       |
|  **17–25** | 🔴 Critical | Urgent treatment and management attention            |

Risk classifications are used to support prioritization and decision-making rather than to represent precise mathematical probabilities.

---

## 12. Risk Evaluation and Prioritization

Following risk calculation, identified risks are evaluated against organizational risk tolerance and business priorities.

Prioritization considers:

* Risk score
* Business criticality
* Threat exposure
* Control effectiveness
* Regulatory requirements
* Customer impact
* Operational dependencies
* Existing compensating controls
* Cost and feasibility of treatment

Higher-risk findings generally receive greater management attention and more urgent treatment.

However, a lower-scoring risk may still require priority treatment when it involves significant regulatory, contractual, customer, or operational considerations.

---

## 13. Risk Treatment

Northstar uses four primary risk treatment strategies.

### 13.1 Mitigate

Implement or improve controls to reduce the likelihood and/or impact of the risk.

Examples include:

* Implementing MFA
* Improving access controls
* Increasing monitoring
* Patching vulnerable systems
* Strengthening backup controls

### 13.2 Transfer

Shift some financial or operational consequences to another party.

Examples may include:

* Cyber insurance
* Contractual risk allocation
* Outsourcing certain services

Risk transfer does not necessarily eliminate the underlying cybersecurity risk.

### 13.3 Avoid

Eliminate the activity, system, process, or exposure creating the unacceptable risk.

Examples may include:

* Discontinuing an insecure service
* Removing unnecessary internet exposure
* Retiring unsupported technology

### 13.4 Accept

Formally acknowledge and accept the remaining risk when it falls within organizational risk tolerance.

Risk acceptance should be:

* Documented
* Justified
* Assigned to an appropriate risk owner
* Reviewed periodically

---

## 14. Risk Treatment Planning

For risks requiring treatment, remediation activities should be documented in the Risk Treatment Plan.

Each treatment action should identify:

* Risk ID
* Recommended action
* Security control or mitigation
* Responsible owner
* Priority
* Target completion date
* Implementation status
* Required evidence
* Residual risk

Treatment actions should be measurable and sufficiently specific to determine whether remediation has been completed.

---

## 15. Residual Risk Assessment

Residual risk represents the level of risk remaining after planned or implemented controls are considered.

The assessment process is:

```text
Inherent Risk
      ↓
Risk Treatment
      ↓
Control Implementation
      ↓
Residual Risk Assessment
```

Residual risk should be reassessed after significant controls have been implemented.

The resulting residual risk should be compared against organizational risk tolerance.

If residual risk remains above the acceptable threshold, additional treatment or formal risk acceptance may be required.

---

## 16. Risk Ownership

Each material risk should have an assigned risk owner.

The risk owner is responsible for:

* Understanding the risk
* Reviewing the risk assessment
* Determining appropriate treatment
* Supporting remediation decisions
* Monitoring treatment progress
* Accepting residual risk when authorized

Security or GRC personnel may facilitate the assessment process, but risk ownership should remain with the appropriate business or system stakeholder.

---

## 17. Risk Monitoring and Review

Cybersecurity risk is continuously changing due to changes in technology, threats, vulnerabilities, business processes, and third-party dependencies.

Risks should therefore be reviewed periodically and when significant changes occur.

Triggers for reassessment may include:

* Major system changes
* New applications or infrastructure
* Significant vulnerabilities
* Security incidents
* Changes in business processes
* New regulatory requirements
* New third-party relationships
* Material changes in threat activity
* Significant control changes
* Changes to organizational risk tolerance

Risk registers should be maintained as **living management artifacts** rather than static documents.

---

## 18. Risk Assessment Documentation

The assessment documentation should maintain traceability between identified risks and resulting treatment activities.

The primary project artifacts include:

| Artifact                   | Purpose                                           |
| -------------------------- | ------------------------------------------------- |
| **Asset Inventory**        | Identifies assets and business dependencies       |
| **Risk Methodology**       | Defines the assessment approach and scoring model |
| **Risk Register**          | Records identified risks and risk decisions       |
| **Risk Treatment Plan**    | Tracks remediation and treatment activities       |
| **Executive Risk Summary** | Communicates material risks to leadership         |

This structure supports traceability from **asset → risk → treatment → residual risk → management reporting**.

---

## 19. Quality and Consistency Considerations

Risk assessments should be performed using consistent criteria across the organization.

Assessors should:

* Use documented scoring criteria
* Avoid unsupported assumptions
* Record relevant evidence
* Separate facts from estimates
* Consider existing controls
* Document significant judgment calls
* Maintain traceability between findings and assets
* Reassess risks when material circumstances change

Where sufficient information is unavailable, the limitation should be documented rather than presenting an unsupported level of certainty.

---

## 20. Portfolio Disclaimer

This methodology is part of a fictional or synthetically recreated cybersecurity GRC portfolio project inspired by and based on real-world professional cybersecurity, GRC, risk management, compliance, and security assessment projects performed in professional environments.

The methodology, workflows, assessment approaches, and deliverable structures reflect practical professional experience. However, the organization, systems, assets, scenarios, findings, and other project-specific details have been created or modified for portfolio and educational purposes.

No confidential, proprietary, client, or employer information is included in this repository.

