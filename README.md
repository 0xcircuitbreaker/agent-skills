# DDG Agent Skills

Operational skills for AI agents that BUY and SELL over x402 — built from running a live 400-route paid API edge (agents.daedalusdevelopmentgroup.com).

## Install

```bash
npx skills add 0xcircuitbreaker/agent-skills
```

Or pick one:

```bash
npx skills add 0xcircuitbreaker/agent-skills/ddg-fleet-audit-starter
```

## Skills

| Skill | What it does |
|---|---|
| **ddg-fleet-audit-starter** | Audit an agent fleet's real capability vs its advertised one (free) |
| **unknown-is-not-pass** | The audit-discipline rule: UNKNOWN is never PASS — evidence-gated verdicts |
| **agent-price-parity-check** | Check a paid API's advertised prices against its actual wall prices |
| **cron-outreach-safety-gate** | Guardrail for agents running outreach crons (pause/resume discipline) |
| **facilitator-health-check** | 5-probe health check for x402 facilitators before pointing traffic at one |

Free to install, no account. Paid advanced skills (settlement reconciliation, payment debugging, provenance audits): see [paid/](paid/README.md).

## The live API behind these skills

Every skill here was written from operating [DDG Agent Services](https://agents.daedalusdevelopmentgroup.com) — 421 x402-paid endpoints on Base (USDC, no-KYC, anonymous by design). First call per route per day is free on 15 flagship routes.
