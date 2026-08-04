# Business Case: Adopt NIST Cybersecurity Framework (CSF)

Organization: Maple Health Connect
Repository: FRAMEWORK-SELECTION-BUSINESS-CASE

## Executive summary

Maple Health Connect (MHC) should adopt the NIST Cybersecurity Framework (CSF), mapped to Canadian privacy obligations (PIPEDA and Quebec Law 25). NIST CSF offers a flexible, risk‑based roadmap—organized around Identify, Protect, Detect, Respond, Recover—that fits MHC’s current size and growth plan (50 employees; target: expand to 200 clinics over two years). It supports incremental implementation, strengthens customer trust, reduces legal and financial risk, and prepares the company for scale without the overhead and cost of formal certification such as ISO 27001.

## Why NIST CSF is the best fit

- Risk‑based and flexible: Prioritizes controls based on assets and threats rather than a one‑size‑fits‑all checklist.
- Practical for small/fast‑growing SaaS: Enables incremental improvements without mandatory audits.
- Recognized in North America: Credible to insurers and customers and suitable for RFP/compliance responses.
- Privacy alignment: Can be mapped to PIPEDA and Quebec’s Law 25 (breach notification, accountability, documentation).
- Operational fit: Small GRC program or a junior Compliance/GRC coordinator can manage the framework's day‑to‑day.

## Organizational context (fictional)

Maple Health Connect is a Canadian SaaS company providing secure patient messaging and appointment scheduling for small-to-medium clinics (e.g., dentists, physiotherapists, family practices). They handle limited personal health information (names, appointment notes, some clinical messages), employ about 50 people, and plan to expand to 200 clinics over two years.

## What risks NIST CSF addresses

- Data breach of patient messages
  - NIST CSF Protect controls: access controls, encryption (in transit & at rest), MFA, staff training.
  - Detect controls: logging, centralized monitoring, alerting for unusual access patterns.

- Ransomware or system outage (appointment system down)
  - Identify: asset inventory and risk assessment to know what must be protected.
  - Recover: backups, tested recovery procedures, DR plan, and RTO/RPO definitions.

- Non‑compliance with PIPEDA / Law 25
  - Aligns controls and processes for breach notifications, consent/processing records, and privacy governance.

- Vendor and third‑party risk (clinics connecting their own devices)
  - Introduce third‑party risk assessments, contractual security clauses, segmentation and onboarding requirements.

- No formal incident response plan
  - Respond function provides roles, communications, playbooks, and lessons‑learned processes.

## Business benefits

- Customer trust & sales enablement: Clinics and procurement teams recognize NIST CSF as a strong security baseline.
- Scalable security program: Repeatable processes for growth to 200 clinics.
- Insurance & contractual clarity: Easier conversations with cyber insurers and enterprise customers.
- Cost effective: No expensive mandatory certification; phased investment is possible.
- Legal alignment: Defensible posture for PIPEDA & Law 25 obligations.
- Talent & roles: Creates an appropriate entry‑level GRC/Compliance role, aligned with hiring plans.

## High‑level implementation roadmap (12–18 months)

Phase 0 — Approval & quick wins (0–2 months)
- Deliverables: Executive approval, budget allocation, appoint Framework Owner, hire/assign junior GRC coordinator.
- Quick wins: Enforce MFA, enable encryption, enable centralized logging, baseline access controls, quick vendor questionnaire.
- Estimate: $10k–$25k (policy and tooling tweaks, staff time).

Phase 1 — Foundational program (2–6 months)
- Deliverables: Asset inventory, risk assessment, prioritized control list, core policies (access, IR, backup, vendor management).
- Controls: least privilege, endpoint management, secure SaaS configuration hardening.
- Estimate: $25k–$75k (logging/monitoring tools, part‑time consultant, training).

Phase 2 — Detection & preparedness (6–12 months)
- Deliverables: Basic SIEM/monitoring, incident response playbooks, backup & DR testing, tabletop exercises, vendor risk process.
- Controls: monitoring/alerting, IR runbook, defined RTO/RPO.
- Estimate: $50k–$150k (monitoring tooling, backups, testing, consultant support).

Phase 3 — Maturing & continuous improvement (12–18 months)
- Deliverables: Continuous risk management, KPI dashboard, periodic testing, privacy program alignment (PIPEDA/Law 25 mapping).
- Controls: periodic audits, SOC‑style reporting for enterprise customers, ongoing vendor assurance.
- Estimate: ongoing $50k+/yr (staffing, subscriptions, audits).

## Resourcing & hiring

- Short term: Appoint a senior owner (existing leader, part‑time) and hire/assign a junior GRC/Compliance Coordinator (0.5–1.0 FTE).
- Medium term: Add a security engineer or DevSecOps resource (0.5–1.0 FTE) and/or contract with an MSSP for monitoring.
- Optional: Use privacy legal counsel and a consultant for the initial risk assessment and mapping to PIPEDA/Law 25.

## Estimated investment and ROI considerations

- One‑time setup & initial tooling: ~$50k–$150k (depending on tooling and consultant usage).
- Annual recurring: ~$40k–$120k (salaries pro‑rated, monitoring, backups, training).
- ROI: Reduced breach probability/impact, faster recovery from incidents, fewer contractual/insurance friction points; likely cost‑effective if it prevents a single moderate breach or downtime event.

## Measurable outcomes & KPIs

- % of critical assets inventoried (target 100% within 3 months).
- Mean time to detect (MTTD) and mean time to recover (MTTR).
- % of employees completing security & privacy training (target 90% within 90 days, 100% annually).
- % of critical vendors assessed and with security SLAs.
- Number of tabletop exercises completed and remediation completion rate.

## Privacy & regulatory alignment

Map NIST CSF controls to PIPEDA and Quebec Law 25 requirements:
- Accountability & governance: CSF Identify + policies.
- Safeguards & security: CSF Protect (technical, administrative safeguards).
- Breach response & notifications: CSF Respond + documented timelines and procedures consistent with PIPEDA/Law 25.
- Data minimization & retention: CSF Identify/Protect with data maps and retention policies.

## Implementation risks and mitigations

- Underinvestment or scope creep
  - Mitigation: Use phased approach, focus on high‑risk/high‑impact controls first.

- People and culture resistance
  - Mitigation: Leadership sponsorship, training, change communications.

- Tooling mismatch or overbuying
  - Mitigation: Pilot an MVP, prefer cloud native tools initially, validate before large purchases.

- Third‑party dependencies (clinic devices)
  - Mitigation: Onboarding controls, segmentation guidance, contractual requirements.

## Recommended next steps (actionable)

1. Obtain executive approval for the framework and a 12‑month budget (suggest initial $50k–$100k).
2. Appoint a Framework Owner and hire/assign a junior GRC Coordinator (or approve a contracting budget for 3–6 months).
3. Run a rapid risk assessment (30–45 day sprint) to identify the top 10 assets and top 5 risks; use findings to prioritize Phase 1.
4. Implement quick wins: enforce MFA, encryption, central logging, and basic vendor questionnaires.
5. Add this document to the repository (completed). Consider a follow‑up mapping matrix (NIST CSF → technical controls → PIPEDA/Law 25).

---

Prepared for: Maple Health Connect
Prepared by: Security & Compliance (recommended owner: Head of Security or VP Operations)

Date: 2026‑08‑04
