---
layout: post
title: DataGuard Retail PostgreSQL Security Architecture
date: 2026-01-30 15:37:00 +0000
categories: [University, Year 2]
tags: [Coursework, Report, Information Management]
media_subpath: /assets/img/photos/
---


Modern retail architectures must evolve from passive data repositories to active enablers of security and integrity. This report presents the back-end infrastructure for "DataGuard Retail," a robust PostgreSQL prototype engineered to secure Personally Identifiable Information (PII) while establishing the foundation for a multi-tenant marketplace.

Adopting a "Zero Trust" philosophy, the solution enforces security controls within the database kernel rather than relying on the application layer. This ensures that even if the web API is compromised, attackers cannot bypass fundamental access controls to exfiltrate data.

The system addresses the CIA triad (Confidentiality, Integrity, Availability) through four functional pillars:
- **Deep-Layer Access Control**: Customised Role-Based Access Control (RBAC) enhanced by Row Level Security (RLS) for strict tenant isolation.
- **Marketplace Scalability**: A partitioned inventory schema allowing third-party vendors to manage products securely.
- **Forensic Resilience**: An immutable auditing system ensuring non-repudiation, compatible with GDPR compliance.
- **Atomic Business Logic**: Encapsulated complex workflows to prevent logic drift and ensure consistency.

This is a coursework that was submitted as part of a Information Management module from Year 2 as a part of the Cyber Security Degree at University of Warwick 

[Download the Report](/assets/files/coursework/year2/IM/CW1/IM_cw1_u5602780.pdf){: download="IM_cw1_u5602780.pdf"}

[Download the SQL Prototype / Database Scripts](https://drive.google.com/file/d/1E1bEdWTtB_Zzanu7KrOuw9nlZahFW69d/view?usp=drive_link)

[Download the Feedback](/assets/files/coursework/year2/IM/CW1/5602780.docx){: download="5602780.docx"}

Grade: Pending
