# AI Governance Control Matrix

## 1. Purpose

This control matrix identifies key organizational controls required to support responsible AI governance. It provides a structured method to assess control objectives, ownership, evidence requirements and implementation status.

The matrix is designed for a hypothetical organization using AI-based recruitment software.

Framework references are indicative mappings to ISO/IEC 42001 and the NIST AI Risk Management Framework (AI RMF 1.0).

## 2. Control Assessment Status

| Status | Meaning |
|---|---|
| Implemented | Control is established and supported by evidence |
| Partially Implemented | Control exists but has identified gaps |
| Not Implemented | Control has not been established |
| Not Verified | Sufficient evidence is unavailable |
| Not Applicable | Control does not apply, with justification |

**Important:** A documented control does not automatically prove that it operates effectively. Design and operating effectiveness must be assessed separately.

## 3. AI Governance Control Matrix

| Control ID | Control Area | Control Objective | Key Control Activity | Indicative Framework Mapping | Control Owner | Expected Evidence | Status |
|---|---|---|---|---|---|---|---|
| AIG-01 | AI Policy | Establish organizational AI governance | Maintain an approved AI governance policy | ISO 42001 Clauses 5, 7; NIST GOVERN | AI Governance Lead | Approved policy, review records | Not Verified |
| AIG-02 | Accountability | Define responsibilities | Assign accountable owners for AI systems and risks | ISO 42001 Clauses 5, 7; NIST GOVERN | Senior Management | RACI matrix, role assignments | Not Verified |
| AIG-03 | AI Inventory | Maintain visibility of AI systems | Maintain an updated inventory of deployed AI systems | ISO 42001 Clauses 4, 8; NIST MAP | AI Governance Team | AI inventory, system register | Not Verified |
| AIG-04 | Risk Assessment | Identify potential AI-related harms | Conduct documented AI risk assessments before deployment | ISO 42001 Clauses 6, 8; NIST MAP | Risk Manager | Risk assessment reports | Not Verified |
| AIG-05 | Data Governance | Ensure appropriate data quality and use | Review data sources, quality, relevance and permissions | ISO 42001 Clauses 8; NIST MAP, MEASURE | Data Protection/Data Team | Data quality reports, data lineage | Not Verified |
| AIG-06 | Fairness | Identify discriminatory outcomes | Conduct bias and fairness testing across relevant groups | ISO 42001 Clauses 6, 8; NIST MEASURE | Model Risk Team | Bias testing reports | Not Verified |
| AIG-07 | Privacy | Protect personal information | Apply privacy safeguards and access restrictions | ISO 42001 Clauses 8; NIST MAP, MANAGE | Privacy Officer | Privacy assessments, access records | Not Verified |
| AIG-08 | Transparency | Support understandable AI decisions | Document system limitations and communicate AI involvement | ISO 42001 Clauses 7, 8; NIST MAP, MEASURE | AI Product Owner | User disclosures, system documentation | Not Verified |
| AIG-09 | Human Oversight | Prevent inappropriate reliance on AI | Establish meaningful human review and escalation procedures | ISO 42001 Clauses 8; NIST GOVERN, MANAGE | Business Owner | Review records, override logs | Not Verified |
| AIG-10 | Security | Protect AI systems from unauthorized access | Apply role-based access controls and security monitoring | ISO 42001 Clauses 8; NIST MANAGE | Information Security Team | RBAC records, security logs | Not Verified |
| AIG-11 | Third-Party Risk | Manage external AI provider risks | Assess vendors and review contractual safeguards | ISO 42001 Clauses 8; NIST GOVERN, MAP | Vendor Risk Manager | Vendor assessments, contracts | Not Verified |
| AIG-12 | Monitoring | Detect changes in AI performance and risk | Monitor accuracy, bias, drift and control effectiveness | ISO 42001 Clauses 9; NIST MEASURE, MANAGE | Model Owner | Monitoring dashboards, review reports | Not Verified |
| AIG-13 | Incident Management | Manage AI-related incidents | Record, investigate and escalate AI incidents | ISO 42001 Clauses 8, 10; NIST MANAGE | Incident Manager | Incident register, investigation reports | Not Verified |
| AIG-14 | Change Management | Control significant AI system changes | Reassess risks following material model, data or deployment changes | ISO 42001 Clauses 8, 10; NIST MAP, MANAGE | Model Owner | Change approvals, reassessment records | Not Verified |
| AIG-15 | Internal Audit | Evaluate governance control effectiveness | Conduct periodic independent control assessments | ISO 42001 Clauses 9, 10; NIST GOVERN | Internal Audit | Audit reports, testing evidence | Not Verified |
| AIG-16 | Corrective Action | Address identified control weaknesses | Assign owners, deadlines and verify corrective actions | ISO 42001 Clause 10; NIST MANAGE | Control Owners | Action plans, closure evidence | Not Verified |

## 4. Control Assessment Methodology

Each control should be evaluated through the following steps:

1. **Design Review:** Determine whether the control is appropriately designed to address the identified risk.
2. **Implementation Review:** Confirm whether the control has been established.
3. **Evidence Collection:** Obtain relevant policies, logs, reports, approvals and records.
4. **Operating Effectiveness:** Test whether the control operates consistently.
5. **Finding Classification:** Record gaps, weaknesses and exceptions.
6. **Corrective Action:** Assign an accountable owner and target completion date.
7. **Closure Validation:** Verify evidence before closing the finding.

## 5. Key Assessment Principles

- Missing evidence should be recorded as Not Verified rather than automatically classified as ineffective.
- High-risk controls should receive appropriate assessment priority.
- Control owners must be accountable for implementation and remediation.
- Risk reduction should only be recognized when supported by sufficient evidence.
- Independent reviewers should evaluate control effectiveness objectively.

## 6. Expected Deliverables

- Documented AI governance control inventory.
- Framework-aligned control assessment.
- Evidence requirements for each control.
- Identified compliance and operational gaps.
- Input for the compliance gap assessment and action plan.

## 7. Disclaimer

This is an educational portfolio assessment using a hypothetical AI recruitment environment. Framework mappings are indicative and do not constitute a formal certification audit, legal opinion or complete assessment of ISO/IEC 42001 requirements.
