# AltsPassport, Inc.

This enterprise is the governance boundary for AltsPassport engineering and operating assets.

## Scope
This enterprise is used for:
- Product code (client-facing platform and internal services)
- Internal operating assets (prompts, workflows, decision logs, revisions)
- Lightweight scripts and automations that connect our tools
- Security policy, access control, and auditability across the organization

## Operating principles (non-negotiable)
- **No silent writes:** the system stages changes; we approve; then it writes.
- **Version everything that matters:** prompts, workflow logic, schemas/assumptions, key decisions.
- **Live today vs in development:** clearly label what is operational vs planned.
- **Auditability and provenance:** outputs should be explainable and reversible.
- **Founder-operable:** minimal tooling and minimal configuration.

## How work should flow
- **Issues** for proposals, context, and decisions
- **Pull Requests** for meaningful changes (even when working solo)
- **Reviews** required for high-impact changes (security, access, schemas, OS logic)
- **Main stays clean:** avoid direct pushes for anything material

## Minimum security baseline (expected)
- 2FA is required for enterprise members and collaborators.
- Default repository visibility is private.
- Public repository creation is restricted to owners.
- Third-party app access and token usage are governed.

## Quick links
- **Enterprise policies:** Policies tab (top navigation)
- **Security posture:** Security tab (top navigation)
- **Billing/licensing:** Billing and licensing tab (top navigation)
- **Primary organization:** Organizations → AltsPassport
