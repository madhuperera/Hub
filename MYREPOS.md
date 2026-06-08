# Public Repository Catalogue

All repositories listed in this catalogue are explicitly defined in `.github/public-repos.yml`.

No private, hidden, client, or employer repositories are included.

## Security Operations

### Microsoft_Sentinel

- **Repository:** https://github.com/madhuperera/Microsoft_Sentinel
- **Purpose:** Security detection and investigation assets for Microsoft Sentinel, organized by threat domain.
- **Main technology area:** Microsoft Sentinel, KQL, ARM templates, PowerShell
- **Practical use case:** Deploy scheduled detection rules (ARM templates), run incident investigation queries (KQL), maintain watchlists, and use workbooks for SOC visibility. Current content includes 6 detection rules, 32 investigation queries, 1 watchlist, and 8 workbooks (production and development). Covers identity security, email, devices, service accounts, and billing domains.
- **Recent visible activity:** April 2026

### CA-Automation-01

- **Repository:** https://github.com/madhuperera/CA-Automation-01
- **Purpose:** Automate Conditional Access policy deployment for Microsoft Entra ID using policy-as-code patterns with Microsoft Graph.
- **Main technology area:** Microsoft Entra ID, Conditional Access, Microsoft Graph, PowerShell
- **Practical use case:** Roll out and maintain repeatable Conditional Access baselines using Core and Advanced deployment tiers. Report-only mode validates policies before enforcement. Each policy receives a dedicated exclusion group and break-glass accounts are protected before policies are deployed. Object IDs are resolved at runtime, making configurations portable across tenants without modification.
- **Recent visible activity:** June 2026

## Endpoint and Device Management

### Intune

- **Repository:** https://github.com/madhuperera/Intune
- **Purpose:** Baseline configurations and policies for Microsoft Intune device management.
- **Main technology area:** Microsoft Intune
- **Practical use case:** Apply Intune baseline settings and policies as a starting point for endpoint standardization across Windows and Apple (macOS and iOS) devices, including security configurations such as Secure Boot certificate policies, delivery optimization, and browser extension management.
- **Recent visible activity:** March 2026

### MEM

- **Repository:** https://github.com/madhuperera/MEM
- **Purpose:** PowerShell script library for Microsoft Endpoint Manager covering application deployment, remediation, and device compliance.
- **Main technology area:** Microsoft Endpoint Manager (Intune), PowerShell
- **Practical use case:** Package and deploy Win32 apps (including .exe installers, printers, and scheduled scripts), implement proactive remediations with detection and remediation script pairs, and enforce custom compliance workflows.
- **Recent visible activity:** April 2026

### Datto_RMM

- **Repository:** https://github.com/madhuperera/Datto_RMM
- **Purpose:** Datto RMM PowerShell scripts, reusable functions, and monitoring components.
- **Main technology area:** Datto RMM, PowerShell
- **Practical use case:** Extend Datto RMM with reusable PowerShell functions, monitoring policy components (deployed as monitoring scripts), and general device automation scripts. Includes utilities for tasks such as bulk warranty date updates via CSV.
- **Recent visible activity:** March 2026

## Microsoft 365

### Microsoft365

- **Repository:** https://github.com/madhuperera/Microsoft365
- **Purpose:** Microsoft 365 administration and security tooling for reporting, Exchange Online operations, and incident response.
- **Main technology area:** Microsoft 365, Entra ID, Exchange Online, Microsoft Intune, Microsoft Teams, Microsoft Graph, PowerShell
- **Practical use case:** Generate reports across Entra ID, Exchange Online, Intune, licensing, DNS and email security records, and Microsoft Teams. Manage Exchange Online calendar permissions and transport rules. Run investigation scripts during security incidents. Reports are formatted as CSV or HTML. Includes an MFA authentication report with reading guide.
- **Recent visible activity:** June 2026

## Standards and Reference

### naming-conventions

- **Repository:** https://github.com/madhuperera/naming-conventions
- **Purpose:** Standard naming guidance for Microsoft cloud and security resources built from real-world enterprise implementations.
- **Main technology area:** Azure, Defender XDR, Entra ID, Exchange Online, Intune, Microsoft Teams, Microsoft 365
- **Practical use case:** Apply consistent naming structures across cloud resources to improve clarity, governance, and scalability. Covers Azure, Defender XDR, Entra ID, Exchange Online, Intune, and Microsoft Teams resources.
- **Recent visible activity:** March 2026
