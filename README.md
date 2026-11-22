# MercuryPay — Vendor Risk & PCI Due Diligence

**Academic third-party risk and compliance exercise | June 2026 | Jack W. Danford Jr.**

## Project overview

Prepared a vendor compliance checklist for a fictional payment-processing engagement between **Violet Crown Collective** and **MercuryPay Solutions**. The worksheet reviews a draft and revised vendor agreement, identifies unresolved evidence requests, and tracks risk ownership and follow-up before a proposed marketplace launch.

**This is an academic contract-review exercise, not an assessment of an actual payment processor, PCI DSS audit, or certification.**

## Deliverable

**[Vendor Compliance Checklist (Excel)](MercuryPay_Vendor_Compliance_Checklist.xlsx)**

The source spreadsheet records the compliance item, a review status, contractual notes/evidence, source clauses, potentially relevant law or standard, risk, owner, timing, priority, and requested follow-up.

## Example review decision

| Contract requirement | Evidence to request | Proposed decision |
| --- | --- | --- |
| The payment processor commits to PCI DSS compliance. | Request its current PCI DSS Attestation of Compliance (AoC) and check that the scope covers the services the marketplace would use. | Keep the PCI evidence request open before launch until the attestation is received and its scope is confirmed. Record who owns the follow-up in the checklist. |

## GRC topics demonstrated

| Review area | Focus |
| --- | --- |
| Data processing agreement | Require a documented DPA and confirm parties' processing responsibilities |
| Payment security / PCI DSS | Request current Attestation of Compliance rather than accept a contractual promise alone |
| Security assurance | Request available reports or questionnaires and confirm audit-review rights |
| Incident response | Review suspected/confirmed incident notification, escalation contacts, and timing |
| Subprocessors | Obtain a current subprocessor list and confirm contractual accountability |
| Privacy and data use | Evaluate purpose limitations, secondary use, consent, and opt-out requirements |
| Data lifecycle | Request retention, deletion, and data return procedures |
| Service continuity | Review SLAs, support escalation, and disaster recovery evidence |
| Risk register workflow | Assign follow-up, owners, due points, and priorities |

## Notable observations

- The worksheet distinguishes **contract wording** from **supporting evidence** still needed before launch.
- It includes unresolved **Unclear** items concerning consent / opt-out implementation and sandbox data protections.
- Proposed high-priority follow-ups include collecting a PCI DSS AoC, DPA, incident response policy, subprocessor list, and retention/deletion schedule.

## Important interpretation of the spreadsheet

Several entries show **“Yes”** because an agreement or revision **addresses the requested term**. That does **not** mean the vendor supplied independent evidence or that the control is operating effectively. Required documents and attestations remain listed in the follow-up column. Legal applicability must be established for actual processing activities and jurisdictions; references to GDPR, CCPA/CPRA, and the Texas Data Privacy and Security Act are course research, not a definitive legal determination.

## Skills demonstrated

Third-party/vendor risk review; security and privacy contract analysis; PCI DSS evidence requests; audit readiness; gap tracking; risk prioritization; ownership assignment; and structured follow-up in Excel.

## Scope and transparency

- The engagement and company context are fictional and course-based.
- No actual MercuryPay systems, payment flows, production environment, or security controls were tested.
- “Yes,” “Unclear,” and the risk rankings describe the academic checklist review, not a real vendor certification.
- No remediation was independently verified or completed.
- This work is not legal advice or evidence of paid GRC employment.

**Author:** Jack W. Danford Jr.  
AAS Cybersecurity, Austin Community College | BAS Cybersecurity in progress
