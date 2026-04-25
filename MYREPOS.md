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
**Technology area:** Microsoft Entra ID, Conditional Access, PowerShell, ARM
**Purpose:** Infrastructure-as-Code automation for Entra ID Conditional Access policies, providing a managed baseline deployment.
**Practical use:** Automate the deployment and management of Conditional Access policies across Entra ID tenants. Useful for maintaining consistent policy baselines at scale.

---

## Endpoint and Device Management

### Intune

**Repository:** [Intune](https://github.com/madhuperera/Intune)
**Technology area:** Microsoft Intune, PowerShell
**Purpose:** Microsoft Intune baselines, policies, and configuration scripts.
**Practical use:** Reference baseline policies and scripts for managing Windows devices through Microsoft Intune.

---

### MEM

**Repository:** [MEM](https://github.com/madhuperera/MEM)
**Technology area:** Microsoft Endpoint Manager (Intune), PowerShell
**Purpose:** Scripts and resources for Microsoft Endpoint Manager covering Win32 application deployment and Proactive Remediations.
**Contents:**
- Win32 app packaging and deployment scripts (EXE deployment, printer installation, file distribution)
- Proactive Remediation script pairs (Detection + Deployment) for automated endpoint compliance

**Practical use:** Deploy complex Win32 applications through Intune, or implement Proactive Remediations to detect and fix endpoint configuration drift automatically.

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
**Technology area:** Microsoft 365, PowerShell
**Purpose:** Administration, configuration, and automation scripts for Microsoft 365 services.
**Practical use:** Reference scripts for managing Microsoft 365 tenants, including service configuration and operational tasks.

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
