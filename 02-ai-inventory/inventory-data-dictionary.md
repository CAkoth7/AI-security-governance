# AI System Inventory — Data Dictionary

## 1. Purpose

This data dictionary defines the fields used in the Laurent Technologies AI System Inventory.

The inventory is intended to provide a structured view of AI systems across the organization and capture information required for subsequent regulatory classification, enterprise AI risk assessment, NIST AI RMF mapping, and governance decisions.

---

## 2. Inventory Fields

### A. System Identification

| Field            | Description                                                                     | Example               |
| ---------------- | ------------------------------------------------------------------------------- | --------------------- |
| AI-ID            | Unique identifier assigned to an AI system.                                     | AI-001                |
| System Name      | Name assigned to the AI system.                                                 | Laurent CreditScore   |
| Business Unit    | Business function responsible for the system's use.                             | Lending               |
| Business Owner   | Person or function accountable for the business use and outcomes of the system. | Chief Lending Officer |
| Technical Owner  | Person or function responsible for the technical operation of the system.       | Head of Data Science  |
| Lifecycle Status | Current stage of the AI system lifecycle.                                       | Production            |

### B. Business Context

| Field            | Description                                                                                            | Example                             |
| ---------------- | ------------------------------------------------------------------------------------------------------ | ----------------------------------- |
| Purpose          | The primary business objective of the AI system.                                                       | Support creditworthiness assessment |
| Use Case         | Specific activity for which the AI system is used.                                                     | Credit scoring                      |
| Business Process | Business process in which the AI system operates.                                                      | Digital lending                     |
| Business Impact  | Potential impact on Laurent Technologies if the system fails or produces materially incorrect results. | High                                |

### C. Technology

| Field                  | Description                                                                      | Example              |
| ---------------------- | -------------------------------------------------------------------------------- | -------------------- |
| AI Technology          | General AI technique used by the system.                                         | Machine Learning     |
| Model Type             | Type or architecture of model used.                                              | Gradient Boosting    |
| Model Provider         | Organization that developed or provides the model or AI capability.              | Laurent Technologies |
| Deployment Environment | Environment in which the AI system operates.                                     | Cloud                |
| Third-Party Dependency | External provider, service, model, or technology on which the AI system depends. | Cloud AI Platform    |

### D. Data

| Field          | Description                                                                          | Example                                |
| -------------- | ------------------------------------------------------------------------------------ | -------------------------------------- |
| Data Sources   | Primary sources from which data is obtained.                                         | Loan applications, transaction history |
| Personal Data  | Indicates whether the system processes personal data.                                | Yes                                    |
| Sensitive Data | Indicates whether the system processes sensitive or specially protected information. | Yes                                    |
| Customer Data  | Indicates whether customer information is processed.                                 | Yes                                    |
| Employee Data  | Indicates whether employee information is processed.                                 | No                                     |

### E. Decision-Making and Human Oversight

| Field                | Description                                                                                        | Example                     |
| -------------------- | -------------------------------------------------------------------------------------------------- | --------------------------- |
| Automated Decision   | Indicates whether the system makes or materially influences a decision without human intervention. | Yes                         |
| Decision Type        | Type of decision influenced or produced by the system.                                             | Creditworthiness assessment |
| Human Oversight      | Describes the level and nature of human involvement in the AI-supported process.                   | Human review required       |
| Affected Individuals | Individuals or groups potentially affected by the system's output.                                 | Loan applicants             |
| External Users       | Indicates whether customers or other external parties directly interact with the system.           | No                          |
| Internal Users       | Indicates whether Laurent Technologies employees use the system.                                   | Yes                         |

### F. Risk and Governance

| Field                | Description                                                                                               | Example    |
| -------------------- | --------------------------------------------------------------------------------------------------------- | ---------- |
| Business Criticality | Importance of the AI system to a critical business process.                                               | High       |
| Regulatory Relevance | Indicates whether the system may have significant regulatory considerations requiring further assessment. | High       |
| Review Frequency     | Planned frequency for formal review of the AI system.                                                     | Annual     |
| Last Review          | Date on which the system was most recently reviewed.                                                      | 2026-09-01 |
| Next Review          | Date on which the next formal review is scheduled.                                                        | 2027-09-01 |

---

## 3. Data Entry Conventions

To improve consistency, the inventory should use standardized values where practical.

### Boolean Fields

The following fields should use:

* Yes
* No
* Unknown
* Pending Assessment

### Lifecycle Status

Use the following lifecycle values:

* Proposed
* Under Assessment
* Development
* Testing
* Approved
* Production
* Suspended
* Retired

### Business Impact

Use:

* Low
* Medium
* High
* Critical
* Pending Assessment

### Business Criticality

Use:

* Low
* Medium
* High
* Critical
* Pending Assessment

### Human Oversight

Use:

* No Human Oversight
* Human-in-the-Loop
* Human-on-the-Loop
* Human Review Required
* Pending Assessment

### Regulatory Relevance

Use:

* Low
* Medium
* High
* Critical
* Pending Assessment

---

## 4. Inventory Design Principle

The inventory should capture **factual characteristics of each AI system before regulatory classification or enterprise risk scoring is performed**.

For example, the inventory should document:

> "The system assesses customer creditworthiness using customer financial information."

It should not initially record:

> "The system is a high-risk AI system."

The regulatory classification will be performed separately using the information captured in the inventory.

This separation helps maintain a clear distinction between:

**System Facts → Regulatory Classification → Enterprise Risk Assessment → Governance Requirements**

---

## 5. Data Quality Expectations

Each inventory record should be sufficiently complete to support subsequent governance activities.

Where information is unavailable, the inventory should use:

**Unknown** or **Pending Assessment**

rather than making unsupported assumptions.

Inventory records should also have an identifiable business owner and technical owner wherever possible.

The inventory should be reviewed periodically and updated when:

* A new AI system is introduced
* An existing system changes materially
* The system changes purpose
* New data sources are introduced
* The model or provider changes
* The system moves to a different lifecycle stage
* Regulatory requirements change
* A material AI incident occurs
* A scheduled review is completed

