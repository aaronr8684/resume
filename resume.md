<style>
@page { size: Letter; margin: 0.5in 0.6in; }
html, body { margin: 0 !important; padding: 0 !important; }
body { font-family: Calibri, Carlito, "Segoe UI", Arial, sans-serif !important; font-size: 10pt !important; line-height: 1.27 !important; color: #1a1a1a !important; }
h1 { font-size: 23pt !important; line-height: 1.1 !important; font-weight: 700 !important; text-align: center; color: #1F3864 !important; letter-spacing: 1.5px; margin: 0 0 3px 0 !important; padding: 0 !important; border: 0 !important; }
h1 + p { text-align: center; font-size: 10pt !important; color: #1F3864 !important; margin: 0 0 2px 0 !important; }
h1 + p + p { text-align: center; font-size: 9.5pt !important; margin: 0 0 2px 0 !important; }
h2 { font-size: 11pt !important; line-height: 1.2 !important; font-weight: 700 !important; color: #1F3864 !important; text-transform: uppercase; letter-spacing: 0.8px; border: 0 !important; border-bottom: 1.3px solid #1F3864 !important; padding: 0 0 1px 0 !important; margin: 9px 0 4px 0 !important; }
p { margin: 0 0 3px 0 !important; }
ul { margin: 2px 0 5px 0 !important; padding-left: 17px !important; }
li { margin: 0 0 2px 0 !important; padding: 0 !important; }
a { color: inherit !important; text-decoration: none !important; }
</style>

# AARON ROBINSON

*Cloud Product Security Engineer | Azure, GCP | Identity and Endpoint Security Automation | Up to 75% Faster Ansible Jobs*

Greenville, SC • 330-620-6093 • robinsonam@gmail.com • [linkedin.com/in/aaron-m-robinson](https://linkedin.com/in/aaron-m-robinson)

## Summary

Software and automation engineer with 5 years building and operating production platforms in Azure and GCP, and 15 years in engineering roles at Aetna / CVS Health. Led development of an Active Directory-backed colleague platform on an in-house GKE platform that grew active users 43% in one quarter, and automated endpoint security agent deployment with Ansible alongside security teams. Writes production Python, JavaScript, and Bash, and owns services from design through deployment and production support as technical lead for six engineers. Strongest in identity and access, vulnerability management with Snyk and Qualys, and CI/CD-driven security automation.

## Skills

**Cloud Security:** Identity and access (Entra ID, Active Directory, LDAP), privileged-access workflows, vulnerability management and remediation (Snyk, Qualys), endpoint security agent deployment and initial configuration (Qualys, CrowdStrike, DLP), SOX-compliant reporting and export APIs

**Monitoring & Response:** Grafana and XMatters alerting and paging, ServiceNow ticket integration, production support, certificate-expiry dashboards (PowerBI, MSSQL)

**Software Engineering:** Python, JavaScript, Bash, PowerShell, SQL, Groovy, Django and Django REST Framework, FastAPI, REST APIs, Pytest and automated testing, code review, pair programming, SDLC, Git

**Cloud & Platform:** Azure (Entra ID), GCP (GKE-hosted applications), Docker, CI/CD (GitHub Actions, Jenkins), Ansible (lead developer), Terraform (foundational), Linux and Windows

## Selected Projects

- Remote access design (personal): Designed Tailscale remote access for a home network using 2 subnet routers in failover, chosen over a reverse proxy and Cloudflare Tunnel for the smallest attack surface, with no inbound ports opened for remote access.
- Pi-hole watchdog (personal): Built a watchdog for a home DNS filter using systemd timers, DNS-over-HTTPS retries, and ntfy alerts, detecting and alerting on 2 distinct failure modes (database access loss after a power brownout and an FTL process crash).
- Protocol reverse engineering (personal): Patched a custom CA certificate into device firmware and rebuilt its checksums, then intercepted API traffic through a MitM proxy to reverse engineer NFC and ESP32-based hardware and mobile app REST APIs with Ghidra, Frida, and Burp Suite.

## Professional Experience

**Sr Software Development Engineer / Team Lead** | CVS Health | Greenville, SC | *January 2022 - Present*

- Led development of CAT, an Active Directory-backed colleague platform on an in-house GKE cluster, shipping SOX-compliant reporting APIs and authenticated automation workflows and growing active users 43% in one quarter.
- Led migration of ADHelp password reset, OU modification, quota, and privileged read functions into CAT, moving over 90% of functionality with full decommission targeted for year end.
- Mentored engineers through design, planning, implementation, and deployment of Qualys automation on GitHub Actions pipelines, extending coverage to new locations and OS types within an automation portfolio that reached 132% of its Q3 time-savings target.
- Took over lead development of the Ansible codebase within a year of first exposure, cutting multi-machine job runtime by up to 75%, and engineered a role framework that automates endpoint configuration changes and security agent decommissioning through a vendor REST API, working directly with security teams.
- Remediated 100% of critical and high Snyk findings across CAT and legacy platforms, plus vulnerabilities surfaced by AI code analysis, and led a tactical team that deployed a PowerBI and MSSQL dashboard to catch expiring certificates before they caused outages.
- Cut perceived LDAP search latency from 10-15 seconds to under 2 seconds with async results that update live and instrumented CAT with Grafana and XMatters alerting and paging.
- Led a five-engineer team as technical lead (a junior developer mentored through pair programming and code review, four contractors directed day to day), enforcing test and PR review standards and building the Python, SQL, JavaScript, and Go exercise suite used in technical hiring evaluations.

**Systems Engineer** | Aetna / CVS Health | Greenville, SC | *March 2019 - January 2022*

- Reworked audit scripts for efficiency and raised environment coverage from 25% to 96%.
- Engineered and documented application packages for development teams and CI/CD pipelines.
- Led the application team through weekly approvals and process tracking, automating repetitive steps to reduce manual effort while coordinating engineering, packaging, and deployment teams.

**Data Analytics Engineer** | Aetna Life Insurance | Renton, WA | *June 2017 - March 2019*

- Reduced a critical Python script's runtime by 97% through threading, working with data scientists to refine and optimize data processes.
- Led a team delivering Tableau and Python data solutions that identified business risk and supported decisions.

**Quality Assurance Engineer** | Aetna Life Insurance | Richfield, OH | *April 2011 - June 2017*

- Built a custom internal issue tracking solution that improved defect management and team efficiency.
- Developed and maintained AutoIt automation plugins for an in-house workstation support utility and designed test plans that supported software reliability.

## Education

Bowling Green State University | B.S., Computer Science | Bowling Green, OH

## Certifications

Microsoft Azure Fundamentals (AZ-900) | ISTQB Foundation Level | SAFe DevOps | Fortinet NSE 4

In progress: CompTIA Security+ | Microsoft SC-300 Identity and Access Administrator

Training completed, exam not taken: Cisco CCNA | Microsoft AZ-400
