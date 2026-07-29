# Glossary

Definitions of key terms used throughout the Execution Governance Model (EGM) specification.

---

**Admissibility**
Whether a proposed AI action has standing to proceed, evaluated at the moment of execution rather than in advance. The central question EGM's runtime layer answers.

**Adversarial Test**
A test designed to defeat a specific governance guarantee before the corresponding fix is implemented, used to verify that a guarantee actually holds under deliberate attempts to break it, rather than only under expected conditions.

**Bind Point**
The point at which a governance decision becomes final and enforcement is applied. Once a decision is bound, it is non-bypassable.

**Binding Consistency**
One of EGM's six verified guarantees: governance decisions bind execution consistently regardless of how or when execution is attempted.

**Bounded Fail-Closed Evaluation**
One of EGM's six verified guarantees: when a governance evaluation cannot complete within defined time or resource bounds, the system fails closed rather than defaulting to allow.

**Complete Mediation**
One of EGM's six verified guarantees: every AI action passes through the governance enforcement boundary without exception.

**Conformance Check**
A structural verification confirming that an implementation of the specification is complete and internally consistent, distinct from an adversarial test, which verifies that a guarantee resists deliberate attack.

**Decision State Awareness (DSA)**
The state under which a given AI decision was produced, including the assumptions, policy and constraints, risk exposure, model state, and operational tolerance in effect at that time.

**Deterministic Adjudication**
One of EGM's six verified guarantees: given the same governance state and the same proposed action, the enforcement decision is always the same.

**Environmental State Awareness (ESA)**
The current state of the environment at the point of execution, including telemetry and signals, system condition, operational context, external constraints, and current risk and exposure.

**Escalation Integrity**
One of EGM's six verified guarantees: escalation pathways are tamper-resistant and cannot be modified or suppressed.

**Evidence Continuity**
One of EGM's six verified guarantees: every governance decision generates tamper-evident evidence with no gaps in the audit trail.

**Fail-Closed**
A design principle in which a system defaults to blocking or refusing an action when it cannot complete its evaluation, rather than defaulting to allow.

**Runtime Governance**
Governance enforcement applied at the moment an AI system takes action, as distinct from governance expressed only as policy documentation or verified only through periodic audit.

---

*Maintained by Grace Adjeli, BridgeCore AI LLC.*
