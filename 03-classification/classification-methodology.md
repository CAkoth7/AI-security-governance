# AI System Classification Methodology

## 1. Purpose

This document defines the methodology used to classify AI systems within the Laurent Technologies AI System Inventory.

The objective is to establish a consistent, evidence-based approach for assessing the potential regulatory classification of each AI system, with particular focus on the European Union Artificial Intelligence Act (EU AI Act).

The methodology is designed to support:

* Consistent AI system classification
* Identification of potentially high-risk AI systems
* Identification of systems subject to transparency obligations
* Identification of systems requiring further regulatory or legal assessment
* Clear documentation of classification reasoning
* Traceability between the AI inventory and classification decisions
* Proportionate AI governance
* Subsequent enterprise AI risk assessment
* Mapping to the NIST AI Risk Management Framework (AI RMF)

This is a portfolio governance exercise and is not intended to constitute legal advice, formal regulatory interpretation, or certification of compliance.

---

# 2. Regulatory Reference Framework

The primary regulatory reference for this classification exercise is Regulation (EU) 2024/1689, commonly referred to as the EU AI Act.

The AI Act adopts a risk-based approach to AI regulation. The regulatory framework distinguishes between different levels of risk and applies different requirements depending on the nature and intended use of an AI system.

For this project, the classification exercise considers:

1. Prohibited AI practices
2. High-risk AI systems
3. AI systems subject to transparency obligations
4. Minimal or lower-risk AI use cases

The classification should be based on the characteristics and intended purpose of the AI system rather than simply the technology used.

For example, the fact that a system uses machine learning or generative AI does not, by itself, determine whether the system is high-risk.

---

# 3. Current Regulatory Context

The EU AI Act is being implemented progressively.

As of September 2026, the transparency obligations under Article 50 apply from 2 August 2026.

The European Commission has published guidance on Article 50 transparency obligations to support practical implementation.

The rules for high-risk AI systems listed in Annex III are scheduled to apply from 2 December 2027, while high-risk AI systems integrated into regulated products are subject to a later timeline.

The classification exercise therefore distinguishes between:

* The **classification of an AI system**, and
* The **date on which particular regulatory obligations become applicable**.

An AI system should not be considered outside the scope of governance merely because a particular obligation has not yet reached its applicable date.

---

# 4. Core Classification Principle

The central principle of this methodology is:

> **Classify the AI system based on what it is intended to do, who it affects, and how its outputs influence decisions or actions — not simply on the fact that it uses AI.**

The assessment therefore begins with the system's intended purpose.

For every AI system, the assessment should establish:

1. What does the system do?
2. Why is the system being used?
3. Who is affected by its use?
4. What decision, action, or process does the system influence?
5. Does the use-case fall within a relevant AI Act category?
6. What human oversight exists?
7. Does the system involve profiling or materially influence decisions?
8. Are transparency obligations potentially applicable?
9. Is sufficient evidence available to support the classification?

---

# 5. Classification Categories

## 5.1 Potentially Prohibited

A system should be assessed for prohibited AI practices where its intended purpose or operation may fall within an AI practice prohibited under Article 5 of the EU AI Act.

The assessment should consider the specific conditions and exceptions contained in the applicable provision.

Examples of areas addressed by the prohibited-practices framework include certain forms of:

* Manipulative or deceptive AI practices
* Exploitation of vulnerabilities
* Certain forms of social scoring
* Certain biometric categorisation practices
* Certain forms of predictive policing
* Certain prohibited biometric identification practices

A system should not be classified as prohibited solely because it is considered controversial or presents a high level of risk.

The assessment must identify the relevant prohibited practice and the supporting evidence.

Where the available information is insufficient, the classification should be recorded as:

**Pending Further Assessment**

rather than assuming that the system is prohibited.

---

# 6. High-Risk Classification

## 6.1 General Principle

The EU AI Act identifies high-risk AI systems through two principal routes:

1. AI systems associated with products or safety components covered by the relevant Union harmonisation legislation and subject to the applicable conformity assessment requirements; and
2. AI systems falling within the use cases identified in Annex III.

For this portfolio, the second route is particularly relevant because several Laurent Technologies systems operate in areas such as lending and recruitment.

---

## 6.2 Annex III Assessment

Where an AI system appears to fall within an Annex III use case, the assessment should consider:

* The specific Annex III area
* The intended purpose
* The role performed by the AI system
* The individuals affected
* Whether the system materially influences decision-making
* Whether profiling is involved
* Whether an Article 6(3) exception may apply
* Whether sufficient evidence exists to support a non-high-risk conclusion

The assessment must not treat the presence of an Annex III-related business function as automatically sufficient.

The actual intended purpose and functionality of the AI system must be examined.

---

# 7. Article 6(3) Exception Assessment

An AI system falling within an Annex III area may, subject to the applicable conditions, not be considered high-risk where it does not pose a significant risk of harm to health, safety or fundamental rights, including where it does not materially influence the outcome of decision-making.

The methodology therefore requires an additional assessment where an Annex III use case is identified.

Relevant questions include:

* Is the AI performing a narrow procedural task?
* Is it improving the result of a previously completed human activity?
* Is it detecting decision-making patterns or deviations without replacing or influencing the human assessment?
* Is it performing a preparatory task?
* Does it materially influence the outcome of a decision?
* Does it perform profiling of natural persons?

Where the available information is insufficient to make this determination, the register should use:

**Pending Further Assessment**

rather than assuming that an exception applies.

---

# 8. Consequential Decision Assessment

Particular attention should be given to AI systems that influence decisions affecting individuals.

The classification assessment should document:

### Decision

What decision or action is being influenced?

Examples include:

* Lending decisions
* Recruitment decisions
* Fraud controls
* Customer access
* Eligibility decisions
* Financial crime investigations
* Service decisions

### Degree of Influence

The assessment should determine whether the AI:

* Provides information only
* Supports a human decision
* Prioritises or ranks individuals
* Recommends an action
* Materially influences a decision
* Automatically makes or triggers a decision

### Human Oversight

The existence of human review should be documented but should not automatically be treated as sufficient to remove regulatory risk.

The quality, timing and effectiveness of human oversight should be considered during the detailed assessment.

---

# 9. Profiling Assessment

Profiling should be explicitly considered where an AI system analyses or evaluates individuals.

The assessment should identify whether the system uses information relating to a person to evaluate or predict characteristics, behaviour, preferences, interests, or other attributes.

Examples within the Laurent Technologies inventory that may require closer examination include:

* Credit scoring
* Recruitment screening
* Customer segmentation
* Marketing personalisation
* Fraud risk assessment

The existence of profiling does not by itself determine the final classification.

It is an assessment factor that must be considered alongside the applicable AI Act provision and intended purpose.

---

# 10. Transparency Assessment

Some AI systems may not be high-risk but may nevertheless be subject to transparency obligations.

Article 50 includes obligations concerning certain AI systems that interact directly with natural persons.

For example, where an AI system is intended to interact directly with natural persons, the relevant persons generally need to be informed that they are interacting with an AI system unless this is obvious in the circumstances and context.

This is particularly relevant to systems such as:

* Customer chatbots
* AI assistants
* Conversational AI
* Certain generative AI systems
* Systems generating or manipulating certain synthetic content

The assessment should therefore include a separate transparency question even where the system is not classified as high-risk.

---

# 11. Minimal or Lower-Risk AI

Where an AI system does not fall within a prohibited practice, applicable high-risk category, or relevant transparency obligation, it may fall within a lower-risk or minimal-risk category.

Examples could include certain:

* Spam filters
* Recommendation functions
* Internal productivity tools
* Administrative automation
* Non-consequential analytical tools

However, a lower regulatory classification does not mean that the system has no enterprise risk.

The organisation may still identify significant:

* Cybersecurity risks
* Privacy risks
* Data quality risks
* Operational risks
* Third-party risks
* Model risks
* Reputational risks
* Business continuity risks

These risks are assessed separately through the enterprise AI risk assessment process.

---

# 12. Regulatory Classification vs Enterprise Risk

A critical principle of this project is:

> **EU AI Act classification and internal enterprise AI risk rating are separate assessments.**

The regulatory classification asks:

> **What regulatory category or obligation may apply to this AI system?**

The enterprise risk assessment asks:

> **What level of risk does this AI system present to Laurent Technologies?**

These assessments may produce different results.

For example:

```text
AI System
   │
   ├── Regulatory Classification
   │       └── Potentially High-Risk
   │
   └── Enterprise Risk Assessment
           ├── Customer Impact
           ├── Data Sensitivity
           ├── Cybersecurity Exposure
           ├── Business Criticality
           ├── Third-Party Dependency
           └── Operational Impact
```

The classification register therefore does not assign an enterprise risk rating.

Enterprise risk rating will be performed in a later stage of the project.

---

# 13. Evidence-Based Classification

Every classification decision should be supported by evidence.

Evidence may include:

* AI inventory information
* System documentation
* Business process documentation
* Intended-purpose statements
* Data-flow documentation
* Decision workflow documentation
* Human oversight procedures
* Vendor documentation
* AI provider documentation
* Product documentation
* Regulatory guidance
* Internal policies
* Legal or compliance assessments

The classification register should record the evidence used to support the decision.

---

# 14. Evidence Quality

Evidence should be considered using three principles:

### 14.1 Relevance

Does the evidence directly relate to the classification question?

### 14.2 Reliability

Is the information obtained from an authoritative or accountable source?

### 14.3 Completeness

Is there enough information to support the classification?

Where evidence is incomplete, the classification should be marked:

**Pending Further Assessment**

rather than filling the gap through assumption.

---

# 15. Classification Status

The classification register uses classification status to distinguish between an initial analytical conclusion and a formally reviewed determination.

Recommended statuses are:

### Pending Further Assessment

There is insufficient information to make a defensible classification.

### Pending Detailed Legal/Compliance Review

The initial assessment identifies a potentially relevant regulatory category, but legal or compliance review is required before the classification is treated as final.

### Transparency Review Required

The system requires a specific assessment of Article 50 or other applicable transparency requirements.

### Confirmed

The classification has undergone the required internal review and has been formally accepted.

The portfolio should avoid representing an initial assessment as a final legal determination.

---

# 16. Classification Decision Process

Each AI system should follow the following sequence.

## Step 1 — Identify the Intended Purpose

Document what the system is designed to accomplish.

Do not rely solely on the technical model description.

For example:

> "Gradient boosting model"

is not sufficient.

The assessment should instead identify:

> "Support assessment of customer creditworthiness in digital lending."

The business purpose is more relevant to regulatory classification than the algorithm name alone.

---

## Step 2 — Identify the Affected Individuals

Determine who may be affected by the AI system.

Potential groups include:

* Customers
* Loan applicants
* Employees
* Job applicants
* Payment recipients
* Suppliers
* Members of the public
* Other natural persons

The assessment should distinguish between people who use the system and people who are affected by its outputs.

---

## Step 3 — Identify the Decision or Action

Document what the AI output influences.

Examples:

* Creditworthiness assessment
* Candidate prioritisation
* Fraud controls
* Customer service
* Marketing personalisation
* AML alerts
* Document classification
* Employee productivity

---

## Step 4 — Assess Regulatory Scope

Determine whether the intended purpose corresponds to:

* A prohibited AI practice
* An Annex I/product-related high-risk route
* An Annex III high-risk use case
* A transparency obligation
* Another relevant AI Act provision
* No currently identified specific category

---

## Step 5 — Assess Exceptions

Where an Annex III use case has been identified, assess whether an applicable Article 6(3) exception may apply.

The assessment must be documented.

---

## Step 6 — Assess Transparency Requirements

Determine whether the system:

* Interacts directly with natural persons
* Generates or manipulates content
* Produces outputs requiring disclosure or labelling
* Falls within another Article 50 scenario

---

## Step 7 — Document the Reasoning

The classification register must explain:

1. What the system does
2. Who it affects
3. What it influences
4. Which provision is relevant
5. Why the proposed classification was selected
6. What evidence supports the conclusion
7. What remains uncertain

---

## Step 8 — Assign Classification Status

The reviewer should determine whether the assessment is:

* Pending Further Assessment
* Pending Detailed Legal/Compliance Review
* Transparency Review Required
* Confirmed

---

## Step 9 — Record Review Date

The classification should be date-stamped.

This supports lifecycle governance and future reassessment.

---

# 17. Classification Decision Tree

The following logical sequence should be applied to each system:

```text
                    AI SYSTEM
                        │
                        ▼
              Identify Intended Purpose
                        │
                        ▼
             Identify Affected Persons
                        │
                        ▼
            Identify Decision / Action
                        │
                        ▼
       ┌─────────────────────────────────┐
       │ Does the use potentially fall   │
       │ within a prohibited practice?   │
       └─────────────────────────────────┘
                 │                │
                YES               NO
                 │                │
                 ▼                ▼
       Assess Article 5      Assess High-Risk Scope
                                  │
                                  ▼
                       ┌─────────────────────┐
                       │ Annex I / Annex III │
                       │ use case identified?│
                       └─────────────────────┘
                            │          │
                           YES         NO
                            │          │
                            ▼          ▼
                    Assess Article 6  Assess
                       conditions      Transparency
                            │          │
                            ▼          ▼
                    Assess Article 6  Article 50 /
                         exceptions    other relevant
                            │          obligations
                            ▼          │
                    Document outcome   │
                            │          │
                            └─────┬────┘
                                  ▼
                       Document Classification
                                  │
                                  ▼
                       Record Evidence & Status
                                  │
                                  ▼
                   Separate Enterprise Risk Assessment
```

---

# 18. Classification Register

The classification register is the controlled working record for all classification assessments.

Each record should contain, at minimum:

| Field                        | Description                                  |
| ---------------------------- | -------------------------------------------- |
| AI ID                        | Unique identifier linked to the AI inventory |
| System Name                  | Name of the AI system                        |
| Intended Purpose             | Business purpose of the system               |
| Affected Individuals         | Individuals affected by the system           |
| Decision / Action Influenced | Decision or process influenced by the AI     |
| Relevant AI Act Area         | Relevant regulatory area                     |
| Potential AI Act Provision   | Relevant Article / Annex                     |
| Initial Classification       | Preliminary classification                   |
| Classification Reasoning     | Explanation supporting the classification    |
| Evidence / Inventory Basis   | Evidence supporting the assessment           |
| Classification Status        | Review status                                |
| Reviewer                     | Person responsible for review                |
| Review Date                  | Date of review                               |
| Notes / Further Assessment   | Outstanding questions or evidence            |

---

# 19. Classification of the Laurent Technologies Inventory

The current inventory provides an initial basis for classification.

The following systems require particular attention:

### Laurent CreditScore

The system supports customer creditworthiness assessment and materially influences lending decisions.

Creditworthiness assessment is specifically addressed within the Annex III high-risk framework.

The initial portfolio classification is therefore:

**Potentially High-Risk**

A detailed assessment should confirm the exact use case, decision workflow and applicability of any Article 6(3) exception.

---

### Laurent HireScreen

The system supports recruitment screening and candidate prioritisation.

Recruitment and selection systems are included within the employment-related Annex III use cases.

The initial portfolio classification is therefore:

**Potentially High-Risk**

The assessment should still document the exact intended purpose, degree of influence and human review process.

---

### Laurent SupportBot

The system directly interacts with customers and provides automated support.

It does not make an automated consequential decision based on the current inventory.

The primary classification consideration is therefore:

**Potential Transparency Obligation**

Article 50 specifically addresses AI systems intended to interact directly with natural persons.

---

### Laurent FraudGuard

The system detects potentially fraudulent payment activity and may trigger transaction controls.

The inventory alone does not establish a specific Annex III high-risk category.

The appropriate initial status is therefore:

**Pending Further Assessment**

The detailed assessment should examine the precise decision impact and applicable regulatory scope.

---

### Laurent AML Analytics

The system generates suspicious-activity risk alerts for AML investigation.

The current inventory does not establish a specific Annex III high-risk category.

The initial status is:

**Pending Further Assessment**

The impact of alerts on customers and counterparties should be examined further.

---

### Laurent MarketAI

The system performs customer segmentation and marketing personalisation.

The system involves customer data and automated selection of marketing content.

The current inventory is insufficient to establish a specific high-risk classification.

The initial status is:

**Pending Further Assessment**

Profiling, intended purpose and transparency considerations should be examined.

---

### Laurent DocAI

The system extracts and classifies information from customer documents.

The current inventory describes document processing rather than an automated consequential decision.

The initial status is:

**Pending Further Assessment**

Particular attention should be given to whether its outputs feed another system or workflow that makes a high-impact decision.

---

### Laurent Copilot

The system is an internal generative AI productivity assistant.

It does not make automated consequential decisions according to the current inventory.

The initial classification is:

**Potential Transparency / Further Assessment**

The assessment should examine the provider/model relationship, user interaction, generated outputs and any applicable transparency or GPAI-related obligations.

---

# 20. Classification Review Triggers

A classification should not be considered permanent.

Reassessment should occur when:

* The intended purpose changes
* A new use case is introduced
* The system begins making or influencing a different type of decision
* The affected population changes
* The model or provider changes materially
* New data sources are introduced
* Sensitive or personal data usage changes
* Human oversight changes
* Automation increases
* The system is deployed in a new jurisdiction
* A regulatory requirement changes
* A significant incident occurs
* A material model change occurs
* The system moves between lifecycle stages
* A new third-party dependency is introduced
* The system is repurposed for a higher-impact business process

---

# 21. Roles and Accountability

Classification should involve appropriate stakeholders depending on the system.

Potential stakeholders include:

### Business Owner

Responsible for explaining:

* Intended purpose
* Business process
* Decision impact
* Affected individuals

### Technical Owner

Responsible for explaining:

* Architecture
* Model functionality
* Deployment
* Technical dependencies
* Model changes

### Data / Analytics Team

Responsible for explaining:

* Data sources
* Model inputs
* Data processing
* Model characteristics

### Information Security

Responsible for assessing:

* Cybersecurity considerations
* Security architecture
* Third-party dependencies
* Threat exposure

### Risk

Responsible for:

* Governance coordination
* Risk assessment
* Control considerations
* Evidence and documentation

### Legal / Compliance

Responsible for:

* Regulatory interpretation
* Applicable legal requirements
* Classification review
* Regulatory uncertainty

### Data Protection / Privacy

Responsible for:

* Personal data considerations
* Privacy implications
* Data subject impacts
* Applicable data protection requirements

---

# 22. Documentation Principle

The classification process should be:

> **Understandable, traceable, reproducible and reviewable.**

A reviewer who was not involved in the original assessment should be able to understand:

* What was assessed
* Why it was assessed
* What evidence was available
* What regulatory provision was considered
* Why the classification was reached
* What assumptions were made
* What uncertainties remain
* Who reviewed the assessment
* When it was reviewed

---

# 23. Limitations

This portfolio methodology has several limitations.

It does not constitute:

* Legal advice
* Formal regulatory certification
* A complete EU AI Act compliance assessment
* A jurisdiction-by-jurisdiction legal opinion
* A formal conformity assessment
* A formal fundamental-rights impact assessment
* A detailed technical model validation
* A penetration test
* A complete data protection impact assessment
* Full third-party due diligence

Where information is unavailable, the methodology intentionally uses:

**Pending Further Assessment**

rather than making unsupported assumptions.

---

# 24. Relationship to Later Project Stages

The classification stage feeds the subsequent AI governance workflow.

The overall process is:

```text
AI Inventory
     │
     ▼
Regulatory Classification
     │
     ▼
Enterprise AI Risk Assessment
     │
     ▼
NIST AI RMF Mapping
     │
     ▼
Governance Requirements
     │
     ▼
Risk Treatment / Controls
     │
     ▼
Monitoring & Review
```

This creates a clear separation between:

**What the AI system is**

↓

**What regulatory requirements may apply**

↓

**What risk the system creates for the organisation**

↓

**What controls should be implemented**

↓

**How the system should be monitored**

---

