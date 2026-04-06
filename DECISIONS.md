# Decisions

## Purpose of This Document

This document records major architectural decisions for the constitutional framework.

It prevents institutional drift across drafting sessions and ensures consistency between constitutional text and supporting documents.

Decisions are labeled with one of the following statuses:

PROPOSED — under discussion
TENTATIVE — preliminary but not final
STABLE — confirmed and should not change casually
REVISABLE — may be reconsidered if necessary
FOUNDATIONAL — core structural assumption; changing requires major redesign

---

# Decision Status Rules

Decisions marked STABLE or FOUNDATIONAL are considered locked.

To modify a locked decision:

1. Declare "Reconsidering Decision"
2. Provide justification
3. Update status accordingly

---

# Foundational Decisions

## Rights Appear as Article I

Human rights are the first article of the constitution rather than amendments.

Rationale:
Rights define the purpose and limits of institutions.

Status: FOUNDATIONAL

---

## Constitutional Minimalism with Structural Redundancy

The constitution itself defines structure, authority relationships, and rights,
while operational detail appears in supporting documents.

Critical protections must rely on multiple institutional safeguards rather than
a single mechanism.

Status: FOUNDATIONAL

---

## Legislature as Primary Democratic Authority

The legislature holds authority over:

• lawmaking
• expenditures
• war authorization
• executive oversight

Rationale:
Representative authority must remain the central democratic mechanism.

Status: FOUNDATIONAL

---

## Executive as Administrative Authority

The executive administers laws but does not create them.

The executive:

• has no veto authority
• answers to the legislature
• cannot independently declare war
• may deploy defensive force only in emergencies subject to immediate legislative review

Rationale:
Prevents executive dominance and preserves legislative supremacy.

Status: FOUNDATIONAL

---

## Highest Court Holds Final Constitutional Review Authority

A highest court interprets constitutional meaning and ensures legal compliance
with constitutional structure and rights protections.

Rationale:
Maintains consistency and protects institutional boundaries.

Status: FOUNDATIONAL

---

## Civic Lottery as a Representation Mechanism

Civic lotteries should be used where appropriate to reduce:

• career political classes
• party capture
• elite gatekeeping
• electoral distortion

Terms should be staggered to preserve institutional continuity.

Status: FOUNDATIONAL

---

## Unicameral Legislature

The legislature consists of a single representative chamber.

Representation is geographically distributed using districts with approximately
equal population.

Rationale:
Improves representational equality and reduces structural gridlock.

Status: FOUNDATIONAL

---

## Transparency as the Default Government Condition

Government processes should be transparent unless limited by:

• personal privacy
• personnel matters
• legitimate national security requirements

Rationale:
Transparency reduces corruption and institutional capture risk.

Status: FOUNDATIONAL

---

## Prevention of Bureaucratic Entrenchment

The constitutional structure should prevent the emergence of a permanent,
unaccountable administrative class insulated from democratic oversight.

Rationale:
Maintains legitimacy and preserves representative authority.

Status: FOUNDATIONAL

---

## Supporting Documents Are Structural Components of the Framework

Supporting documents such as:

PROJECT_CONTEXT.md
PROJECT_RULES.md
COMMENTARY.md
POWER_MAP.md
SYSTEM_GUARDRAILS.md
CROSS_REFERENCE_MAP.md

are considered part of the constitutional design environment.

They guide interpretation and maintain architectural consistency.

Status: FOUNDATIONAL

---

## COMMENTARY.md Serves as Official Interpretive Companion

COMMENTARY.md explains:

• article intent
• interpretation boundaries
• institutional reasoning

Courts may reference commentary when evaluating constitutionality.

Amendments to commentary must remain consistent with original intent.

Status: FOUNDATIONAL

---

## Institutional Risk Monitoring Maintained in SYSTEM_GUARDRAILS.md

Design proposals must be evaluated against systemic risks including:

• executive consolidation
• party capture
• bureaucratic autonomy
• judicial overreach
• oligarchic influence

Rationale:
Prevents predictable democratic failure paths through structured guardrail evaluation.

Status: FOUNDATIONAL

---

## Institutional Stress Testing Is Part of Structural Evaluation

Institutional changes should be evaluated against scenarios described in:

INSTITUTIONAL_STRESS_TESTS.md

Rationale:
Ensures constitutional resilience under crisis conditions and prevents structural drift during emergency interpretation.

Status: FOUNDATIONAL

---

# Structural Decisions

## Defined Terminology Maintained in GLOSSARY.md

Technical constitutional terms must be defined centrally and used consistently.

Rationale:
Prevents ambiguity and interpretive drift.

Status: STABLE

---

## Cross-Document Dependency Tracking Is Required

Institutional relationships must be maintained in CROSS_REFERENCE_MAP.md.

Changes affecting authority relationships require updates across dependent documents.

Status: STABLE

---

## Authority Flow Tracking Maintained in POWER_MAP.md

Institutional authority relationships must be explicitly mapped and reviewed
when structural changes occur.

Status: STABLE

---

## Emergency Authority Does Not Alter Constitutional Hierarchy

Emergency defensive authority permits temporary executive response to immediate threats but does not suspend or modify the constitutional hierarchy between representative, administrative, and judicial institutions.

Emergency authority does not:

• transfer sovereign authority to the executive
• suspend legislative oversight authority
• suspend judicial review authority
• authorize permanent emergency governance structures
• alter the constitutional distribution of powers between branches

Legislative review and judicial compliance review remain continuously operative during emergency conditions.

Rationale:
Historical democratic failure frequently occurs when temporary crisis powers are interpreted as permitting structural authority transfer. This rule preserves constitutional continuity during emergencies and prevents normalization of executive supremacy.

Status: STABLE

---

# Open Structural Questions

## Scope of Civic Lottery Implementation

Which representative bodies should use civic lottery selection mechanisms
remains under evaluation.

Status: TENTATIVE

---

## Legislative Term Length and Rotation Structure

Exact duration and staggering schedule of legislative terms remain undecided.

Status: PROPOSED

---

## Judicial Appointment Method

The selection process for members of the highest court remains under consideration.

Status: PROPOSED

---

## Amendment Procedure Design

The mechanism for constitutional amendment remains to be defined.

Status: PROPOSED
