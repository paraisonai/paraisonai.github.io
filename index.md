---
layout: default
title: Paraison AI
description: AI ticket routing for support teams. We build the Agent Control Plane (ACP) — classify, route, and auto-resolve support tickets on Zendesk-class helpdesks.
---

# Paraison AI

AI ticket routing for support teams.

We build the **Agent Control Plane (ACP)** — a system that takes incoming support tickets, classifies them with AI, routes them to the right agent or group, and auto-resolves low-risk requests.

ACP runs in production for B2B SaaS support teams. It is also the platform we use to run our own support desk — every feature ships only after we depend on it ourselves.

## How ACP works

1. **Ingest.** A webhook from your helpdesk (Zendesk first; others on the roadmap) delivers each new ticket to ACP in real time.
2. **Classify.** Claude models score the ticket across intent, urgency, sensitivity, and routing destination.
3. **Route.** High-confidence tickets go straight to the correct group or agent. Low-confidence tickets are flagged for human review with full context.
4. **Audit.** Every decision is logged with confidence scores, model reasoning, and override hooks.

## Why it is different

- **Operator-first.** Built by an operator who uses it every day for real support work. No theoretical AI demos.
- **Auditable.** Every classification surfaces the reasoning. You can review, override, and retrain on disagreements.
- **Single-tenant data.** Your tickets stay in your database. No cross-tenant training data.
- **Production-grade.** Live deployments handling real B2B support traffic since day one.

## Roadmap

- **Now:** Zendesk integration, classification and routing, audit dashboard.
- **Next:** Auto-reply for high-confidence categories, expanded helpdesk integrations.
- **Soon:** Self-serve onboarding, public API.

## Get in touch

- Product details: [paraison.io](https://paraison.io)
- Technical product overview: [paraison.io/product-overview](https://paraison.io/product-overview)
- ROI calculator: [paraison.io/roi](https://paraison.io/roi)
- Email: [sales@paraison.io](mailto:sales@paraison.io)

---

Paraison AI · Headquartered in New Jersey · Founded by Ron Paraison
