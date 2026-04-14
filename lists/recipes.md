# Stack Recipes

Recipes combine server patterns and workflows into something closer to a publishable product direction or internal-tool package.

Every recipe here is intentionally framed as a pattern bundle, not as proof that a market or vendor already validated it.

## Release Operations Cockpit

- Status: `Pattern seed`
- Primary user: platform team, OSS maintainer, or developer tools founder
- Core workflow: release notes, changelog assembly, pre-ship docs checks
- Server mix: repository server + docs index + communication or approval server
- Why it looks launch-worthy: clear buyers, visible pain, and easy before-after demos
- Honest risks: hard to move from drafting to trusted automation without strong review loops

## Support Copilot with Internal Context

- Status: `Pattern seed`
- Primary user: support lead or technical success team
- Core workflow: ticket enrichment, suggested replies, escalation prep
- Server mix: ticketing bridge + docs index + status or incident context
- Why it looks launch-worthy: measurable time savings and a strong need for grounded answers
- Honest risks: private customer data and hallucinated certainty can damage trust quickly

## Customer Onboarding Verifier

- Status: `Pattern seed`
- Primary user: implementation and customer success teams
- Core workflow: browser-assisted onboarding QA with follow-up task creation
- Server mix: browser bridge + CRM bridge + communication server
- Why it looks launch-worthy: turns messy operational work into a trackable checklist product
- Honest risks: browser reliability, authentication drift, and exception-heavy edge cases

## Internal Knowledge Desk

- Status: `Pattern seed`
- Primary user: fast-growing startup or internal enablement team
- Core workflow: onboarding, meeting prep, policy lookup, docs freshness support
- Server mix: docs index + calendar server + repository or task tools
- Why it looks launch-worthy: broad internal demand with an understandable first deployment path
- Honest risks: stale knowledge quickly erodes trust unless freshness is part of the product

## Incident Coordination Assistant

- Status: `Pattern seed`
- Primary user: SRE, platform ops, or reliability tooling team
- Core workflow: incident briefs, stakeholder updates, runbook retrieval
- Server mix: monitoring server + docs index + communication tools
- Why it looks launch-worthy: high urgency makes small productivity gains valuable
- Honest risks: high-blast-radius environment requires strong approval and audit controls

## Governance Review Lane

- Status: `Pattern seed`
- Primary user: AI platform owner, compliance lead, or internal tooling team
- Core workflow: prompt review, policy checks, approval routing, release blocking
- Server mix: local workspace tools + docs index + approval or communication server
- Why it looks launch-worthy: governance is painful, repetitive, and increasingly cross-functional
- Honest risks: easy to overpromise unless the system is explicit about what it can and cannot approve automatically
