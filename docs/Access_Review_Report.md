# Access Review Report (Quarterly User Access Audit)

This report documents results from a mock access review conducted across critical systems to ensure least privilege and compliance with ISO 27001 control A.9.

---

## 1. Review Summary
| Field | Description |
|-------|--------------|
| Review Period | Q3 2025 |
| Reviewer | Bendley Milord |
| Systems in Scope | Active Directory, File Shares, Splunk, SharePoint |
| Review Type | Privilege & Account Validation |
| Completion Date | Oct 2025 |

---

## 2. Findings Summary
| Account | System | Role | Finding | Action Taken |
|----------|---------|------|----------|---------------|
| admin01 | Active Directory | Domain Admin | Excessive privileges | Downgraded to Tier 2 Support |
| svcBackup | File Share | Backup Operator | No issue | Retained |
| analyst01 | Splunk | Power User | Inactive 90+ days | Disabled account |
| user77 | SharePoint | Site Owner | Inherited permissions | Reviewed and approved |

---

## 3. Remediation Actions
- Disabled inactive or unnecessary accounts.  
- Adjusted admin permissions to enforce least privilege.  
- Verified MFA enforcement for all privileged users.  
- Logged remediation details in tracking sheet.  

---

## 4. Sign-Off
| Role | Name | Signature | Date |
|------|------|------------|------|
| Reviewer | Bendley Milord | ✅ | Oct 2025 |
| Security Manager | [Alex Rivera] | ✅ | Oct 2025 |

---
