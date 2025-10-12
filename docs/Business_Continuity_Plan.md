# Business Continuity Plan (BCP)

This document defines strategies to ensure essential business functions continue during and after disruptive incidents.

---

## 1. Objectives
- Protect life, data, and critical operations.  
- Maintain essential services with minimal downtime.  
- Ensure recovery aligns with RTO/RPO objectives.

---

## 2. Scope
Applies to: IT systems, business applications, and facilities supporting company operations.

---

## 3. Critical Systems & Recovery Priorities
| System | Function | RTO (hrs) | RPO (hrs) | Backup Location |
|---------|-----------|-----------|-----------|-----------------|
| Active Directory | Authentication | 4 | 2 | Local + Cloud |
| SharePoint | Document Storage | 8 | 4 | Cloud Backup |
| Splunk | Log Monitoring | 6 | 3 | Daily Snapshot |
| ERP | Business Operations | 12 | 6 | Offsite DR Site |

---

## 4. Roles & Responsibilities
| Role | Responsibility |
|------|----------------|
| BCP Coordinator | Activate BCP plan; coordinate communication |
| IT Recovery Lead | Restore systems and validate backups |
| HR Lead | Notify staff and ensure welfare |
| Facilities Lead | Coordinate building access and safety |

---

## 5. Communication Plan
- Emergency alerts via email, text, and MS Teams.  
- Status updates every 2 hours during recovery.  
- Post-incident debrief within 48 hours.

---

## 6. Backup & Restoration Procedures
- Perform daily incremental and weekly full backups.  
- Store encrypted copies in AWS S3 and off-site drives.  
- Test data restoration quarterly.

---

## 7. Testing & Maintenance
- Tabletop exercises every 6 months.  
- Full BCP simulation annually.  
- Document lessons learned and update this plan.

---

## 8. Approval
| Role | Name | Date | Signature |
|------|------|------|------------|
| BCP Coordinator | Bendley Milord | Oct 2025 | ✅ |
| IT Manager | [Manager Name] | Oct 2025 | ✅ |

---
