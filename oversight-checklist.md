# Human Oversight Checklist for LLM-Assisted Workflows

Use this checklist before deploying or relying on an AI-assisted workflow.

## Workflow Risk

- [ ] What task is the AI supporting?
- [ ] Is the AI making a recommendation or taking action?
- [ ] Could the output affect security, privacy, money, access, safety, or reputation?
- [ ] Is the workflow internal, customer-facing, or public?

## Data Risk

- [ ] Does the workflow involve sensitive, regulated, or confidential data?
- [ ] Could users paste data into unauthorized tools?
- [ ] Are there rules for what data can and cannot be used?
- [ ] Is data retained, logged, or shared with third parties?

## Prompt Injection Risk

- [ ] Does the AI process emails, documents, webpages, tickets, or other untrusted content?
- [ ] Could external text include hidden or malicious instructions?
- [ ] Are instructions separated from retrieved content?
- [ ] Does the system require confirmation before acting on external content?

## Human Review

- [ ] Who reviews the AI output?
- [ ] What decisions require human approval?
- [ ] Are reviewers trained to challenge AI confidence?
- [ ] Is there an escalation path for uncertainty?

## Accountability

- [ ] Who owns the workflow?
- [ ] Who is accountable if the AI output causes harm?
- [ ] Are outputs auditable?
- [ ] Can decisions be explained after the fact?

## Controls

- [ ] Are access controls in place?
- [ ] Are high-risk actions gated?
- [ ] Are logs monitored?
- [ ] Is there a rollback or correction process?

## Deployment Decision

Proceed only if:

- The workflow has a clear owner.
- Sensitive data handling is defined.
- Human review exists for high-impact decisions.
- Prompt injection risk has been considered.
- Outputs are logged and auditable.
