# Policy Playbook (ISO 27001 Aligned)

This playbook outlines key organizational security policies mapped to ISO 27001 Annex A controls.  
Each policy lists purpose, controls, and sample evidence for audit readiness.

---

## Access Control Policy
**Purpose:** Ensure least privilege and appropriate user access.  
**Scope:** All employees, contractors, and systems.  
**Controls:**  
- Role-Based Access Control (RBAC)  
- Multi-Factor Authentication (MFA)  
- Joiner-Mover-Leaver (JML) process  
- Quarterly access reviews  

**Evidence:** [Access Review Report.md](https://github.com/Bendleym/GRC-Lab/blob/main/docs/Access_Review_Report.md)  
**Owner:** Security Manager | **Reviewed:** Oct 2025  

---

## Data Protection Policy
**Purpose:** Protect sensitive data at rest and in transit.  
**Controls:**  
- Data classification and labeling  
- AES-256 encryption and TLS 1.2+  
- Secure data disposal and backup rotation  
- File integrity monitoring  

**Evidence:** Backup reports, encryption configs  
**Owner:** IT Manager | **Reviewed:** Oct 2025  

---

## Incident Response Policy
**Purpose:** Define a clear process for detecting, containing, and recovering from security incidents.  
**Controls:**  
- 4-tier severity classification  
- Incident response escalation flow  
- 24-hour initial notification  
- Root cause analysis after closure  

**Evidence:** Incident response plan, mock test logs  
**Owner:** SOC Lead | **Reviewed:** Oct 2025  

---

## Vendor Risk Management Policy
**Purpose:** Evaluate and monitor third-party risk before and after engagement.  
**Controls:**  
- Vendor risk questionnaire  
- Security attestation (SOC 2 / ISO 27001)  
- Annual risk reassessment  
- Contract security clause verification  

**Evidence:** [Vendor_Assessment_Template.md](https://github.com/Bendleym/GRC-Lab/blob/main/docs/Vendor_Assessment_Template.md)  
**Owner:** Compliance Analyst | **Reviewed:** Oct 2025  

---

## Change Management Policy
**Purpose:** Ensure all system changes are authorized, tested, and documented.  
**Controls:**  
- CAB approval and rollback procedures  
- Version control for changes  
- Testing in staging before production  
- Change logs stored in Jira or GitHub  

**Evidence:** Change control log, CAB approval form  
**Owner:** IT Admin | **Reviewed:** Oct 2025
