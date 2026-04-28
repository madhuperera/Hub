# Public Repository Catalogue

All repositories listed here are explicitly defined in `.github/public-repos.yml`. No private or undisclosed repositories are included.

---

## Security Operations

### Microsoft_Sentinel

**Repository:** [Microsoft_Sentinel](https://github.com/madhuperera/Microsoft_Sentinel)
**Technology area:** Microsoft Sentinel, Azure Monitor, KQL
**Purpose:** Security detection and investigation assets for Microsoft Sentinel, organized by security threat domain.
**Contents:**
- Scheduled detection rules as ARM templates, covering identity security and related domains
- Reusable KQL queries for incident investigation, organized by domain and data source
- Sentinel workbooks for production dashboards and development visualizations
- Watchlists and reference data, including emergency breakglass account monitoring

**Practical use:** Deploy scheduled Sentinel alerts using the provided ARM templates. Use KQL investigation queries during incident response. Workbooks provide visual overviews for ongoing security monitoring.

---

### CA-Automation-01

**Repository:** [CA-Automation-01](https://github.com/madhuperera/CA-Automation-01)
**Technology area:** Microsoft Entra ID, Conditional Access, PowerShell, Microsoft Graph
**Purpose:** Infrastructure-as-Code automation for Entra ID Conditional Access policies, providing a managed baseline deployment using Microsoft Graph.
**Contents:**
- Policy definitions stored as code under `data/ca_policies/`, version-controlled and reviewable
- Core and Advanced deployment tiers to suit both baseline and mature environments
- Dedicated exclusion group per policy using a consistent naming pattern
- Break-glass emergency access groups created first and excluded from all policies to reduce lockout risk
- Dynamic runtime resolution of group and named location IDs to avoid hardcoded tenant-specific values

**Practical use:** Automate the deployment and management of Conditional Access policies across Entra ID tenants using a repeatable, code-driven approach. Supports report-only validation before enforcement. Useful for maintaining consistent policy baselines at scale across Microsoft 365 environments.

---

## Endpoint and Device Management

### Intune

**Repository:** [Intune](https://github.com/madhuperera/Intune)
**Technology area:** Microsoft Intune, PowerShell
**Purpose:** Microsoft Intune baselines, policies, and configuration resources for Windows and Apple device management.
**Contents:**
- Windows device configuration baselines and policies
- Apple device configuration resources

**Practical use:** Reference baseline policies and scripts for managing Windows and Apple devices through Microsoft Intune.

---

### MEM

**Repository:** [MEM](https://github.com/madhuperera/MEM)
**Technology area:** Microsoft Endpoint Manager (Intune), PowerShell
**Purpose:** Scripts and resources for Microsoft Endpoint Manager covering Win32 application deployment, Proactive Remediations, compliance policies, and general endpoint management.
**Contents:**
- Win32 app packaging and deployment scripts (EXE deployment, printer installation, file distribution)
- Proactive Remediation script pairs (Detection + Remediation) for automated endpoint compliance
- Custom compliance policy scripts for enforcing device standards beyond built-in baselines
- Detection scripts for identifying device configuration state
- Reusable PowerShell functions for use across endpoint management scripts
- General-purpose PowerShell scripts for Windows device tasks

**Practical use:** Deploy complex Win32 applications through Intune, implement Proactive Remediations to detect and fix endpoint configuration drift automatically, and enforce custom compliance requirements across managed Windows devices.

---

### Datto_RMM

**Repository:** [Datto_RMM](https://github.com/madhuperera/Datto_RMM)
**Technology area:** Datto RMM, PowerShell
**Purpose:** PowerShell scripts and monitoring components for use with Datto RMM environments.
**Contents:**
- Reusable PowerShell functions for script output and UDF management
- Monitoring scripts for deployment as Datto RMM monitoring components
- General-purpose scripts for Windows device tasks
- Miscellaneous utilities including bulk warranty update via CSV

**Practical use:** Extend Datto RMM with custom monitoring policies, automation scripts, and reusable function libraries for managed service environments.

---

## Microsoft 365

### Microsoft365

**Repository:** [Microsoft365](https://github.com/madhuperera/Microsoft365)
**Technology area:** Microsoft 365, Entra ID, Exchange Online, PowerShell, Microsoft Graph
**Purpose:** Administration, reporting, and security tooling for Microsoft 365 tenants. Covers identity, Exchange Online, licensing, email security, and incident response.
**Contents:**
- Entra ID reporting: member and guest users, devices, application registrations, administrator role memberships, authentication methods, MFA status, inactive accounts
- Exchange Online reporting: mailbox quota, calendar permissions, unused mailboxes
- Exchange Online administration: bulk calendar permission management, transport rule assets, anti-malware policy configuration
- Licensing reporting: Microsoft 365 plan and SKU seat counts
- DNS and email security reporting: DKIM, DMARC, and SPF record verification for accepted domains
- Intune reporting: managed application inventory
- Incident response scripts: audit log analysis by IP address, interactive sign-in investigation

**Practical use:** Use the reporting scripts to produce tenant health and compliance reports for Entra ID, Exchange Online, and Microsoft 365 licensing. Use the incident response scripts during security investigations to query audit logs and sign-in data. Use the Exchange Online scripts to manage calendar permissions and validate email security posture.

---

## Standards and Reference

### naming-conventions

**Repository:** [naming-conventions](https://github.com/madhuperera/naming-conventions)
**Technology area:** Microsoft 365, Azure, Intune, Entra ID, Defender XDR
**Purpose:** Comprehensive naming convention guidance for Microsoft cloud and security resources, built from enterprise implementations.
**Contents:**
- Naming standards for Azure resources and subscriptions
- Naming guidance for Entra ID, Exchange Online, Intune, Microsoft Teams, and Defender XDR
- Structured for consistency and scalability across cloud infrastructure

**Practical use:** Use as a reference when building or standardizing naming schemes across Microsoft cloud environments. Reduces inconsistency in resource naming at scale.
