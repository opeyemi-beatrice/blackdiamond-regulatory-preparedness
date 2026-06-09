# Blackdiamond Financial Ltd — AI Governance Framework
## 01-Governance | CRISC 8th Edition Aligned | DORA + EU AI Act 2026

> **Built by:** Beatrice Opeyemi Aiyeobasan, MSc, CAMS — CRISC Candidate  
> **Last updated:** June 2026  
> **Status:** Work in progress — updated as CRISC studies and practitioner research develops  
> **Regulatory scope:** DORA (in force Jan 2025) · EU AI Act (high-risk obligations Aug 2026)

---

## 1. About Blackdiamond Financial Ltd

Blackdiamond Financial Ltd is a UK-headquartered challenger bank providing retail and SME banking services. It operates on a cloud-native, mobile-first architecture and competes directly with firms such as Monzo, Starling, and Revolut.

| Attribute | Detail |
|-----------|--------|
| Employees | 2,000 |
| Headquarters | London, UK |
| EU presence | Lithuanian-licensed subsidiary passporting into Spain, France, and Portugal |
| Annual revenue | ~£350 million |
| UK regulator | FCA (conduct) and PRA (prudential) |
| EU regulator | Bank of Lithuania (EU subsidiary) |
| Core banking platform | Third-party provider (critical ICT dependency under DORA) |
| Cloud infrastructure | AWS and Google Cloud (concentration risk — formally assessed) |

### Context: Why Governance Matters Now

Blackdiamond has recently emerged from a significant regulatory enforcement action — an FCA fine for failings in its financial crime prevention systems, mirroring the £29 million fine issued to Starling Bank in 2024. This event has fundamentally reset the firm's risk culture and governance posture. The board has committed to a period of reduced risk appetite, strengthened internal controls, and enhanced oversight across all risk categories.

Simultaneously, two major regulatory deadlines are approaching:

- **DORA** — in force since January 2025, requiring ICT risk management, resilience testing, and third-party oversight
- **EU AI Act** — high-risk AI system obligations enforceable **August 2, 2026** (53 days away)

This governance framework is Blackdiamond's response to both.

---

## 2. Governance Structure

### 2.1 Definition

A governance structure is the system of rules, accountability mechanisms, and decision-making authority that directs and controls an organisation. It defines who has the power to make which decisions, who is accountable when things go wrong, and how oversight is exercised at every level of the firm.

For Blackdiamond, governance is not just an operational requirement — it is a regulatory one. DORA Article 5 requires the management body to define, approve, and oversee the ICT risk management framework. The EU AI Act Article 26 places accountability for AI system deployment squarely on the deployer organisation. Without a clearly defined governance structure, neither obligation can be met.

### 2.2 Board Composition

Blackdiamond's board includes both Executive Directors and Non-Executive Directors (NEDs). The NEDs provide independent oversight and challenge. For a firm of Blackdiamond's regulatory profile, the following board composition is required:

| Role | Type | Primary accountability |
|------|------|----------------------|
| Chair | Non-Executive | Board leadership and independence |
| CEO | Executive | Overall firm strategy and performance |
| CFO | Executive | Financial performance and capital adequacy |
| CRO | Executive | Enterprise risk management framework |
| Chief AI Officer | Executive | AI governance and EU AI Act compliance |
| Chief Compliance Officer | Executive | Regulatory compliance — FCA, PRA, EU |
| Chief Engineering Officer | Executive | Technology, DORA ICT resilience |
| CISO | Executive | Cybersecurity and information security |
| CLO | Executive | Legal obligations, contracts, EU AI Act liability |
| Independent NED (Risk) | Non-Executive | Chair of Board Risk Committee |
| Independent NED (Audit) | Non-Executive | Chair of Audit Committee |
| Independent NED (Technology) | Non-Executive | Technology and resilience oversight |

### 2.3 Governance Committees

Four committees provide structured oversight of Blackdiamond's regulatory obligations. Each committee has a defined mandate, chair, membership, and reporting line to the board.

#### Board Risk Committee
**Chair:** Independent NED (Risk)  
**Members:** CRO (Secretary), CEO, CFO, Chief AI Officer, Chief Compliance Officer  
**Mandate:** Approves and monitors the enterprise risk appetite statement. Receives quarterly risk reports across all risk categories. Reviews and challenges residual risk positions. Escalates material risks to the full board. Specifically reviews DORA and EU AI Act compliance status quarterly.  
**Meeting frequency:** Quarterly minimum; monthly during regulatory remediation periods  

#### Audit Committee
**Chair:** Independent NED (Audit)  
**Members:** CFO, Chief Compliance Officer, Head of Internal Audit (Secretary)  
**Mandate:** Oversees internal and external audit programmes. Reviews audit findings and remediation tracking. Provides independent assurance that controls are operating effectively — not just designed correctly. Reviews AI audit programme results.  
**Meeting frequency:** Quarterly  

#### AI Governance Committee
**Chair:** Chief AI Officer  
**Members:** CRO, CISO, CLO, Chief Engineering Officer, Chief Compliance Officer  
**Mandate:** Reviews and approves all new AI system deployments. Monitors performance of high-risk AI systems under EU AI Act obligations. Ensures human oversight mechanisms are functioning. Reviews model drift, bias testing results, and explainability standards. Reports to the Board Risk Committee quarterly.  
**Meeting frequency:** Monthly  

#### Technology and Operational Resilience Committee
**Chair:** Chief Engineering Officer  
**Members:** CISO, CRO, Chief AI Officer, Head of IT Operations  
**Mandate:** Oversees DORA compliance across all five pillars. Manages the ICT third-party register and vendor risk assessments. Reviews resilience testing results. Owns the incident reporting process and major incident classification. Monitors cloud concentration risk (AWS and Google Cloud).  
**Meeting frequency:** Monthly  

---

## 3. Risk Appetite Statement

### 3.1 Definition

A risk appetite statement is a formal, board-approved document that defines the amount and type of risk Blackdiamond is willing to accept in pursuit of its strategic objectives. It is not a description of risks that exist — it is a declaration of risks the firm chooses to take.

Risk appetite is distinct from risk tolerance. **Risk appetite** defines how much risk the board wants to accept. **Risk tolerance** defines the acceptable variation around that appetite — the boundary within which residual risk must remain before escalating to board level.

### 3.2 Blackdiamond's Post-Enforcement Risk Appetite

Following the FCA enforcement action, Blackdiamond's board has reset its risk appetite across all categories. The previous culture of accepting elevated risk in pursuit of rapid growth is no longer consistent with the firm's regulatory standing or strategic direction.

The board has adopted the following formal positions:

#### Regulatory Compliance Risk
**Appetite: Zero tolerance**

Blackdiamond will not knowingly operate in breach of any applicable regulation. Following the FCA enforcement action, any activity that creates material regulatory compliance risk must be escalated to the Board Risk Committee before proceeding. The cost of compliance is treated as a non-negotiable cost of doing business — not a variable to be optimised.

*This means:* All DORA obligations must be met in full. All EU AI Act high-risk system obligations must be met before August 2, 2026. Any identified compliance gap triggers immediate remediation with a board-level owner and a fixed deadline.

#### AI and Model Risk
**Appetite: Low**

Blackdiamond accepts that AI creates both opportunity and significant risk. The firm will continue to use AI systems where they deliver clear customer or operational benefit — but only where those systems are properly governed, tested, explainable, and subject to human oversight. No AI system will be deployed in a customer-facing or high-stakes decision context without passing the AI Governance Committee's review process.

*This means:* All four high-risk AI systems must comply fully with EU AI Act Articles 9–15 before August 2, 2026. Model drift must be monitored continuously. Any AI system generating unexplainable outputs for regulated decisions must be suspended pending remediation.

#### Operational and ICT Risk
**Appetite: Low**

Blackdiamond's customers depend on continuous platform availability. ICT failures are reputational and regulatory events, not just operational ones. The firm will invest in resilience, redundancy, and tested business continuity capabilities. Third-party ICT dependencies — particularly AWS and Google Cloud — will be formally risk-assessed and managed as critical relationships.

*This means:* DORA five-pillar obligations are treated as minimum standards, not aspirational targets. ICT incidents will be classified and reported within DORA's mandatory timelines. DR tests will be conducted and documented annually.

#### Financial Crime Risk
**Appetite: Zero tolerance**

Given the FCA enforcement action specifically related to financial crime controls, Blackdiamond adopts zero tolerance for financial crime risk failures. AML, KYC, and sanctions controls will be treated as the firm's highest operational priority. Investment in financial crime prevention systems — including AI-powered transaction monitoring — will not be subject to cost reduction pressures.

#### Strategic and Financial Risk
**Appetite: Moderate**

Blackdiamond accepts moderate strategic and financial risk in pursuit of sustainable growth. The firm will pursue new products and markets where risk has been properly assessed and where the expected return justifies the exposure. However, no strategic initiative will proceed where it creates material regulatory compliance risk.

### 3.3 Risk Appetite Thresholds

| Risk Score | Level | Blackdiamond Appetite | Action Required |
|------------|-------|----------------------|-----------------|
| ≥20 | Critical | Never acceptable as residual risk | Immediate board escalation and treatment |
| 12–16 | High | Acceptable only with active treatment plan | CRO review and monthly monitoring |
| 6–10 | Medium | Acceptable with standard controls | Quarterly review |
| ≤5 | Low | Acceptable — monitor only | Annual review |

---

## 4. Roles and Responsibilities Matrix (RACI)

### 4.1 Definition

A RACI matrix defines, for each governance activity, who is:
- **Responsible (R)** — does the work and makes it happen
- **Accountable (A)** — has ultimate authority and sign-off (one person only per activity)
- **Consulted (C)** — provides input before the decision is made
- **Informed (I)** — told after the decision is made

The critical rule: only **one person** can be Accountable for any activity. Multiple people can be Responsible or Consulted. This ensures clarity when things go wrong.

### 4.2 CRISC Note on RACI

The RACI matrix is a risk governance tool, not just an HR document. In ISACA's framework, unclear accountability is itself a risk — specifically an operational risk and a governance gap. The Starling FCA fine identified unclear ownership of financial crime controls as a contributing factor. Blackdiamond's RACI is designed to eliminate that ambiguity.

### 4.3 Blackdiamond RACI Matrix

| Governance Activity | CEO | CRO | Chief AI Officer | CISO | CLO | CFO | Chief Eng. Officer | Chief Compliance Officer | Board Risk Committee |
|--------------------|-----|-----|-----------------|------|-----|-----|-------------------|------------------------|---------------------|
| Approve risk appetite statement | A | R | C | C | C | C | C | C | I |
| Deploy new AI system | A | C | R | C | C | I | C | C | I |
| Classify AI system (EU AI Act) | I | C | R/A | C | C | I | C | C | I |
| Declare major ICT incident (DORA) | I | C | C | R | C | I | A | C | I |
| Submit Register of Information | I | C | I | C | C | I | A | C | I |
| Approve risk treatment plan | A | R | C | C | C | C | C | C | I |
| Report risk to board | I | R/A | C | C | C | I | C | C | R |
| Approve new vendor contract | C | C | C | C | A | C | R | C | I |
| Conduct AI conformity assessment | I | C | A | C | R | I | C | C | I |
| Review and approve KRIs | I | A | R | C | C | C | C | C | I |
| Oversee financial crime controls | I | C | C | C | C | I | I | A | I |
| Manage DORA resilience testing | I | C | C | A | C | I | R | C | I |

---

## 5. Governance Principles

Blackdiamond's governance is built on five principles drawn from ISACA CRISC methodology and DORA requirements:

**1. Accountability without ambiguity.** Every risk has a named owner. Every decision has a named accountable person. Shared accountability means no accountability.

**2. Risk-informed decision making.** No material business decision is made without a risk assessment. The risk function is consulted before, not informed after.

**3. Independence of oversight.** The Audit Committee and Board Risk Committee include independent NEDs who can challenge executive decisions without fear of consequence.

**4. Proportionate response.** Controls are proportionate to risk level. Critical and high risks receive active treatment and monthly monitoring. Low risks receive annual review.

**5. Continuous improvement.** The governance framework is a living document. It is reviewed following every significant risk event, every regulatory change, and every material change to Blackdiamond's business model.

---

## 6. Regulatory Mapping

| Governance Element | DORA Article | EU AI Act Article | CRISC Domain |
|-------------------|-------------|------------------|--------------|
| Board accountability for ICT risk | Article 5 | Article 26 | D1 — Risk Identification |
| Risk appetite statement | Article 9 | Article 9 | D2 — Risk Assessment |
| AI Governance Committee | Article 6 | Articles 26, 27 | D1 — Risk Identification |
| RACI for AI deployment | Article 28 | Article 26 | D3 — Risk Response |
| Technology and Resilience Committee | Articles 6–16 | Article 15 | D4 — Risk Monitoring |

---

## 7. Next Sections

This governance framework is Section 01 of the Blackdiamond Regulatory Preparedness Framework. Subsequent sections build directly on the accountability structures defined here:

- **02-Risk-Identification** — risk universe for a UK challenger bank
- **03-Risk-Register** — 60+ risks with inherent and residual scoring
- **04-DORA-Mapping** — five pillars mapped to Blackdiamond's obligations
- **05-EU-AI-Act-Mapping** — AI system inventory and classification
- **06-AI-Audit-Programme** — audit controls and test scripts
- **07-Gap-Analysis** — current state vs required state, with remediation roadmap

---

*Document owner: Chief Risk Officer*  
*Approved by: Board Risk Committee*  
*Review cycle: Quarterly*  
*CRISC alignment: Domain 1 (IT Risk Identification) + Domain 3 (Risk Response)*  
*Regulatory reference: DORA Articles 5–9; EU AI Act Articles 9, 26–27*  
*MITRE ATLAS reference: Governance and oversight controls mapped to AML.TA0000*
