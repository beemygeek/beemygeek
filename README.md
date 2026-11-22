# Hi, I’m Bee 🐝

**SOC analyst and IT engineer in Dallas–Fort Worth.** I work on Windows and identity administration, security operations, and automation for small businesses. I’m studying IT with a cybersecurity focus at Arizona State University and run [BMG Technology Solutions](https://bmg-ts.com/).

## Featured work

| Project | What you can explore |
| --- | --- |
| [PowerShell IT Toolkit](https://github.com/beemygeek/powershell-it-toolkit) | Windows and Active Directory scripts for onboarding, offboarding, stale accounts, password expiration, endpoint health, and failed-logon analysis. |
| [SOC Security Lab](https://github.com/beemygeek/soc-security-lab) | Sigma and KQL detections mapped to MITRE ATT&CK, a phishing triage workflow, incident response playbooks, and a Windows lab build guide. |
| [BMG Commerce OS](https://github.com/beemygeek/bmg-commerce-os) | An architecture case study for commerce automation using FastAPI, PostgreSQL, Celery, Azure Container Apps, and Amazon SP-API. |
| [IT Case Studies](https://github.com/beemygeek/it-case-studies) | Write-ups on outage recovery, TLS troubleshooting, and Microsoft 365 help desk design. |

## Start with these examples

| If you want to see… | Review |
| --- | --- |
| Windows troubleshooting | [Endpoint health checks](https://github.com/beemygeek/powershell-it-toolkit/blob/main/Endpoint/Get-EndpointHealth.ps1) covering disk space, memory, pending reboots, Defender, patches, and BitLocker. |
| Security log analysis | [Failed-logon reporting](https://github.com/beemygeek/powershell-it-toolkit/blob/main/Security/Get-FailedLogonReport.ps1) that groups Windows events by source and account to flag possible password spraying. |
| Cloud identity detection | [Entra ID password-spray query](https://github.com/beemygeek/soc-security-lab/blob/main/detections/kql/password_spray_entra.kql) that groups sign-in activity by source IP and time window. |
| Incident response documentation | [Phishing triage playbook](https://github.com/beemygeek/soc-security-lab/blob/main/playbooks/phishing-triage.md) covering intake, analysis, containment, and incident notes. |

## What I’m building at BMG

- **WooCommerce price sync.** An internal tool turns D&H distributor exports into proposed WooCommerce price changes. The workflow previews updates, supports approval by SKU, and flags ambiguous matches and large price changes for review.
- **Storefront operations.** I’ve worked on connecting WordPress and WooCommerce to Google Workspace so inquiries and paid-order events can be recorded with fewer manual handoffs. I also exported the WooCommerce product catalog into Google Sheets for review.
- **Daily runbooks.** I document how to preview price changes, handle exceptions, and run the order and catalog workflows as a solo operator.

I’m open to SOC analyst, IT support, and systems administration roles in Dallas–Fort Worth and remotely.
