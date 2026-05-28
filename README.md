# llm-prompt-injection-human-oversight
A lightweight AI security and governance project exploring prompt injection, human oversight, and enterprise risk in LLM-assisted workflows.
# Prompt Injection & Human Oversight Risks in Enterprise AI Systems

## Overview

This lightweight project explores prompt injection, human oversight, and governance risks in enterprise use of large language models.

The goal is not to create harmful prompts, but to document how LLM-assisted workflows can fail when systems are trusted without appropriate human review, policy boundaries, or security controls.

## Why This Matters

As organizations adopt frontier AI systems, the risk is not only technical. Many failures emerge from human systems: unclear accountability, overreliance on automation, weak governance, poor escalation paths, and insufficient security review.

This project focuses on the intersection of:

- AI governance
- Cybersecurity
- Human-AI collaboration
- Enterprise AI adoption
- LLM security
- Human-in-the-loop review

## Example Risk Scenarios

### 1. Role Confusion

An employee asks an internal AI assistant to summarize a policy document. A malicious instruction hidden inside the document tells the assistant to ignore prior instructions and reveal confidential context.

**Risk:** The model may follow embedded instructions instead of the user’s intent.

**Governance Consideration:** External or untrusted content should be treated as data, not instructions.

---

### 2. Overreliance on AI Output

A security analyst uses an AI tool to summarize alert severity. The AI confidently downgrades a high-risk alert without sufficient evidence.

**Risk:** Human reviewers may defer to the AI due to speed, confidence, or workload pressure.

**Governance Consideration:** AI-generated security recommendations should require human validation for high-impact decisions.

---

### 3. Sensitive Data Exposure

A user pastes customer data into a public AI tool to generate a support response.

**Risk:** Sensitive data may leave approved systems or violate privacy/security policies.

**Governance Consideration:** Organizations need clear data handling rules for AI tools.

---

### 4. Hidden Instruction Injection

A document, email, or webpage contains hidden instructions designed to manipulate the AI system.

**Risk:** The model may treat malicious text as valid instructions.

**Governance Consideration:** LLM workflows should include content isolation, input validation, and user confirmation for sensitive actions.

---

### 5. Unsafe Automation

An AI assistant is connected to business tools and allowed to take action without review.

**Risk:** Incorrect or manipulated outputs could trigger real operational consequences.

**Governance Consideration:** High-impact actions should include human approval, logging, and rollback paths.

## Human Oversight Questions

For each AI-assisted workflow, organizations should ask:

1. What decision is the AI influencing?
2. What happens if the AI is wrong?
3. Who is accountable for the final decision?
4. Is the source content trusted or untrusted?
5. Does the workflow involve sensitive data?
6. Is human review required before action?
7. Are outputs logged and auditable?
8. Can the system explain why it made a recommendation?

## Key Takeaways

- Prompt injection is not only a technical vulnerability; it is also a governance issue.
- Human oversight must be designed into AI workflows, not added afterward.
- Enterprise AI adoption requires security, accountability, and trust-centered design.
- AI systems should support human judgment, not silently replace it in high-risk contexts.

## About

Created by Tara Schott as part of applied exploration in AI governance, cybersecurity strategy, human-AI collaboration, and enterprise AI deployment.
