# Vendor Security Assessment Template

This template is used to assess and document third-party vendor security posture before granting access to company systems or data.

---

## 1. Vendor Overview
| Field | Description |
|-------|--------------|
| Vendor Name | [Example Vendor Inc.] |
| Services Provided | Cloud storage & data analytics |
| Data Accessed | PII, reports, backups |
| Assessment Date | Oct 2025 |
| Reviewer | Compliance Analyst |

---

## 2. Security Attestations
| Attestation | Status | Notes |
|--------------|---------|-------|
| SOC 2 Type II | ✅ Provided (2025 Report) | Meets CC 6, CC 7 |
| ISO 27001 Certification | ✅ Valid until 2026 | Controls A.5–A.18 aligned |
| GDPR Compliance | ✅ Stated | DPA on file |
| HIPAA Compliance | ❌ N/A | Not applicable |

---

## 3. Technical & Administrative Controls
| Category | Questions | Response |
|-----------|------------|-----------|
| Access Control | MFA required for all accounts? | ✅ Yes |
| Encryption | AES-256 for data at rest/in transit? | ✅ Yes |
| Logging & Monitoring | Centralized SIEM enabled? | ✅ Splunk |
| Incident Response | Breach notification window < 24 hours? | ✅ Yes |
| Vendor Risk Mgmt | Annual security review performed? | ✅ Yes |

---

## 4. Risk Rating Summary
| Risk Area | Likelihood | Impact | Score | Status |
|------------|-------------|---------|--------|---------|
| Data Exposure | Low | High | 6 | Acceptable |
| Insider Threat | Medium | Medium | 9 | Mitigated |
| Availability | Low | High | 6 | Acceptable |

**Overall Risk Rating:** **Low**

---

## 5. Approval & Tracking
| Role | Name | Action | Date |
|------|------|---------|------|
| Reviewer | Bendley Milord | Completed Assessment | Oct 2025 |
| Security Manager | [Manager Name] | Approved | Oct 2025 |
| Next Review Date | Apr 2026 |  |  |

---

✅ **Memory Tip:**  
say “I built a vendor assessment form modeled after ISO 27001 Annex A.15 — it captures attestations, technical controls, risk ratings, and sign-off for audit evidence.”  

---

when you finish pasting and committing that, reply **“done w 5”**, and we’ll move to the next piece — the **Access Review Report**.
