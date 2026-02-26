---
name: Ops Ticket
about: Operational ticket created by AI monitoring or self-healing systems
title: "[OPS] "
labels: ops-ticket
assignees: ''
---

## Severity

<!-- Select one: tier-0 (critical), tier-1 (high), tier-2 (medium), tier-3 (low) -->
- [ ] Tier 0 — Critical (auto-remediate immediately)
- [ ] Tier 1 — High (remediate within 15 minutes)
- [ ] Tier 2 — Medium (remediate within 1 hour)
- [ ] Tier 3 — Low (remediate within 24 hours)

## Detection

- **Detected by:** <!-- e.g., Cortex health check, Gatus monitor, CloudWatch alarm, self-healing protocol -->
- **Detection time (ET):** <!-- YYYY-MM-DD HH:MM ET -->
- **Alert source:** <!-- e.g., ops@altspassport.com, Langfuse trace, UptimeRobot -->

## Description

<!-- What happened? What is the impact? -->

## Root Cause

<!-- Known or suspected root cause. Reference BF-NNN if applicable. -->

## Remediation

- **Auto-remediated:** Yes / No
- **Playbook used:** <!-- e.g., BF-025-aurora-credentials.yaml -->
- **Steps taken:**
  1.
  2.
  3.

## Verification

- [ ] Service restored
- [ ] Root cause addressed (not just symptoms)
- [ ] Monitoring confirms resolution
- [ ] BF entry created/updated if novel pattern

## Related

- **BF ID:** <!-- BF-NNN if applicable -->
- **Playbook:** <!-- Link to YAML playbook if used -->
- **Trace ID:** <!-- Langfuse trace ID if applicable -->
