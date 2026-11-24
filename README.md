## Jihun Baek

Cyber security analyst in Sydney. I harden live systems, attack them, and publish what is still open.

[jihun.me](https://jihun.me) &nbsp;&nbsp; [LinkedIn](https://www.linkedin.com/in/jihun-baek-505544270) &nbsp;&nbsp; [Email](mailto:bjhbrian916@gmail.com)

### Now

**Cyber Security Analyst at Gomaps Trading**, since November 2025. Identity and access hardening (Active Directory, Intune, Entra Conditional Access), Microsoft Defender incident response, email security (SPF, DKIM, DMARC), log auditing on OCI, and the move to an Azure AI platform.

Also at Gomaps: building **GoRP**, our in-house ERP, with OpenAI Codex as an AI pair programmer (private, in development), and running an authorised LLM-assisted security assessment of company web assets.

### Selected work

| Project | What it is | Stack |
| --- | --- | --- |
| **[Korean Pages Platform](https://github.com/JihunB/korean-pages-platform)** | Migrated a live directory of 11,000+ businesses from a legacy PHP CMS to a hardened AWS stack: CloudFront-only origin, private encrypted RDS, Secrets Manager, CI secret and dependency scanning. Found and fixed an SSRF and an image-parser exposure; open findings are published with a plan. | Django, PostgreSQL, AWS, Bedrock |
| **[CyberShield](https://github.com/JihunB/CyberShield)** | Website security scanner for small businesses: about 60 checks across 7 categories, a 14-pattern code analyser and a real-time dashboard. [Case study](https://jihun.me/cybershield.html) | FastAPI, Supabase, Vercel |
| **[LAMP bulletin board pentest](https://github.com/JihunB/KnockOn)** | A PHP bulletin board I built, then attacked. Black-box and gray-box testing found 11 vulnerabilities (RCE, SQLi, stored XSS, IDOR), each with a CVSS score and a fix. [Report](https://jihun.me/pentest-report.html) | PHP, MySQL, Docker, Burp Suite |
| **[AI network attack classifier](https://github.com/JihunB/AI-Based-Network-Attack-Classification)** | Multi-class classifier labelling raw HTTP payloads (SQLi, XSS, command injection, brute force) at 92.6% accuracy across 220,000 samples, with its weak classes documented. [Write-up](https://jihun.me/ai-attack-classifier.html) | Python, scikit-learn, XGBoost |
| **[Hack MAC 2025](https://jihun.me/#projects)** | Co-developed 38 Dockerised CTF challenges across 5 categories for Macquarie University's competition. Source under NDA. | Docker, Python |

### Background

- **B.IT in Cyber Security, Macquarie University.** WAM 81.9. Previously AI Computer Science at Handong Global University (1.5 years, credit transferred).
- **Challenge Developer and Technical Mentor, KnockOn** (2025). Built 10+ CVE-based CTF challenges for three cohorts of the Elite White Hacker Bootcamp, where I also graduated in the top 7.
- **Communications and Information Systems Specialist, US 8th Army (KATUSA)** (2022 to 2024). Ran secure LAN/WAN, server and radio systems under DoD security controls.

### Certifications

- AWS Certified Solutions Architect, Professional (2025)
- AWS Certified Solutions Architect, Associate (2025)
- Google Cybersecurity Professional Certificate (2026)

Security training: KnockOn Elite White Hacker Bootcamp (3rd batch, top 7); KISA AI Security Monitoring Specialist Training Program (3rd batch); K-Shield Jr. Start-Up.

Next: CompTIA Security+, CCNA and an Azure certification.

### Tools I use

**Security:** Burp Suite, Wireshark, Microsoft Defender, Intune, Entra ID, OWASP Testing Guide, bandit, pip-audit, gitleaks
**Cloud and infrastructure:** AWS, Azure, OCI, Docker, Linux, Active Directory
**Code:** Python, Django, FastAPI, PostgreSQL, JavaScript, Bash
