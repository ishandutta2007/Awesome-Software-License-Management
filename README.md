# Awesome-Software-License-Management

# Top Software License Management Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Software License Compliance, Asset Management & Open-Source License Scanning*  
**Last updated: October 2026**

This repository tracks notable **commercial license management platforms** and **open-source projects** that help organizations track software licenses, ensure open-source compliance, and manage license obligations across their software supply chain. These tools range from IT asset management systems to dedicated license compliance scanners.

**Examples** include AWS License Manager, Flexera One, Snow Software, ServiceNow SAM, USU License Management, Certero, Zylo, Productiv, Torii, and Cleanshelf (the category leaders).

**Open-source emphasis**: License management is a strong open-source domain with two distinct sub-categories. **IT Asset Management (ITAM)** tools like **GLPI**, **Snipe-IT**, and **OCS Inventory** track purchased software licenses and seat counts . **Open-source license compliance scanners** like **FOSSology**, **ORT**, and **ScanCode** detect license obligations in source code and dependencies . **Eclipse SW360** bridges both worlds as a centralized component management hub .

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[AWS License Manager](https://aws.amazon.com/license-manager/)**  
  AWS's managed service for tracking and managing software licenses across AWS and on-premises environments. **Best for AWS-centric organizations** wanting license tracking integrated with cloud resources.

- **[Flexera One](https://www.flexera.com/)**  
  **The enterprise standard for ITAM and SAM** — software license optimization, cloud cost management, and vulnerability management. **The most comprehensive commercial platform** for software asset management.

- **[Snow Software](https://www.snowsoftware.com/)**  
  **The leading SAM platform** — discover, manage, and optimize software licenses across hybrid environments. **Best for large enterprises** with complex licensing.

- **[ServiceNow SAM](https://www.servicenow.com/)**  
  Software Asset Management within the ServiceNow platform — license reconciliation, compliance, and optimization.

- **[USU License Management](https://www.usu.com/)**  
  Enterprise software license management with discovery, compliance, and optimization capabilities.

- **[Certero](https://www.certero.com/)**  
  Unified ITAM and SAM platform with SaaS management and license optimization.

- **[Zylo](https://zylo.com/)**  
  **SaaS management platform** — discover, manage, and optimize SaaS subscriptions. **Best for SaaS sprawl management**.

- **[Productiv](https://productiv.com/)**  
  SaaS management and engagement analytics — track application usage and optimize spend.

- **[Torii](https://www.toriihq.com/)**  
  SaaS management platform for discovering, managing, and optimizing SaaS applications.

- **[Cleanshelf](https://www.cleanshelf.com/)**  
  SaaS spend management and license optimization platform.

## Open-Source GitHub Projects

### IT Asset & License Management (ITAM/SAM)

- **[GLPI](https://github.com/glpi-project/glpi)**  
  **The leading open-source IT asset management platform**, GPL-3.0 licensed . **Manages software licenses with seat tracking, expiration alerts, financial information, and license-to-asset relationships** . **License management is linked to GLPI's inventory module** — tracks which computers have which software requiring licenses . **Supports child/parent licenses, over-quota allowances, and automated renewal notifications** . **The de facto open-source ServiceNow alternative** — used by thousands of organizations worldwide . **Best for comprehensive ITAM with integrated helpdesk** .

- **[Snipe-IT](https://github.com/snipe-it-org/snipe-it)**  
  **The most widely adopted open-source IT asset management system**, AGPL-3.0 licensed with **331+ contributors** . **Built on Laravel 11 with a full REST API** — license management with seat assignments, check-in/check-out, expiration tracking, and depreciation . **Docker deployment recommended** — runs on Linux, macOS, Windows, or cloud . **The best starting point for IT hardware and software license tracking** — simplest to adopt and most mature . **Best for SMBs to enterprises needing straightforward asset tracking** .

- **[OCS Inventory](https://github.com/OCSInventory-NG/OCSInventory-Server)**  
  **The leading open-source inventory and deployment solution**, GPL-2.0 licensed . **Agent-based inventory for hardware and software** — automatically discovers installed software across the fleet . **SNMP scans for network devices** — copiers, switches, routers without agents . **CVE detection via CVE-Mitre cross-reference** — identifies vulnerable software . **REST API for integration with GLPI, iTOP, and ITSM-NG** . **The "eye" to observe and the "hand" to act on your network** . **Best as a data feeder for GLPI or Snipe-IT** .

- **[Ralph](https://github.com/allegro/ralph)**  
  **Open-source DCIM and asset management** — data center infrastructure management with rack visualization and cable tracing . **Best for data center and colocation operators** .

- **[openMAINT](https://github.com/openMAINT/openMAINT)**  
  **Open-source facility and infrastructure asset management** — space hierarchy, maintenance plans, work orders, and GIS integration . **Best for facilities, campuses, and industrial sites** managing physical infrastructure .

### Open-Source License Compliance (SCA)

- **[FOSSology](https://github.com/fossology/fossology)**  
  **The veteran open-source license compliance system and toolkit**, GPL-2.0 licensed . **License, copyright, and export control scans from the command line** . **Web UI with database backend for compliance workflow** — one-click SPDX file generation and ReadMe with all copyright notices . **Triggers clearing processes in Eclipse SW360** . **The reference open-source license scanner** — used by enterprises for license detection and compliance . **Best for comprehensive license, copyright, and export control scanning** .

- **[OSS Review Toolkit (ORT)](https://github.com/oss-review-toolkit/ort)**  
  **The most comprehensive open-source license compliance suite**, Apache-2.0 licensed, Linux Foundation project . **Analyzer resolves complete dependency trees** — supports 20+ package managers including npm, pip, Maven, Gradle, Cargo, and Go modules . **Scanner detects actual licenses in source code** — goes beyond declared licenses to detect what's in the files . **Evaluator applies policy-as-code rules** — acceptable, review-required, prohibited licenses and incompatibility checks . **Reporter generates SPDX, CycloneDX, notice files, and Excel reports** . **Advisor checks vulnerabilities** via OSV and NVD . **The best open-source tool for enterprise-scale license compliance** — handles multiple ecosystems and hundreds of projects .

- **[ScanCode Toolkit](https://github.com/aboutcode-org/scancode-toolkit)**  
  **The leading open-source license detection engine**, Apache-2.0 licensed . **Detects licenses, copyrights, and package manifests** — supports SPDX license keys . **Extensible license database** — add custom licenses with YAML frontmatter . **Used as a scanning backend by ORT** . **The most accurate open-source license detector** — comprehensive license and rule database . **Best for integrating license detection into custom workflows** .

- **[Eclipse SW360](https://github.com/eclipse-sw360/sw360)**  
  **Open-source component management hub**, EPL-2.0 licensed . **Collects, organizes, and makes software component information available** — centralized hub for supply chain visibility . **Tracks components in projects, assesses security vulnerabilities, maintains license obligations, enforces policies, and generates legal documents** . **Integrates with FOSSology for clearing processes** . **API-first for DevOps integration** . **Best for organizations needing a centralized component inventory with compliance workflows** .

- **[Rudder](https://github.com/Normation/rudder)**  
  **Open-source configuration management and compliance**, GPL-3.0 licensed . **Security benchmarks and license status integration** — recent bug fix ensures license status updates flow to security benchmarks menu . **Best for infrastructure compliance alongside license tracking** .

### Additional Strong Open-Source Options

- **ITSM-NG** — Complete ITSM solution with asset management, contract and license management, and statistics .
- **CMDBuild** — Open-source CMDB with asset and license management .
- **iTOP** — Open-source IT operations portal with asset and license management .
- **Safeguard** — SBOM-first license management with provenance verification .
- **Mend.io** — Commercial SCA with mature license policy engine .
- **Licensee** — Lightweight license detection for JavaScript projects .
- **license-checker** — Simple license detection for npm projects .

**Frameworks for building custom license management solutions**: Choose based on your need. For **IT asset and purchased license tracking**, combine **GLPI** for comprehensive ITAM with helpdesk integration , **Snipe-IT** for the easiest starting point , and **OCS Inventory** as a data feeder for automated discovery . For **open-source license compliance**, use **ORT** for enterprise-scale policy enforcement across multiple ecosystems , **FOSSology** for detailed license and copyright scanning , and **ScanCode** as the detection engine . **Eclipse SW360** bridges both worlds as a centralized component hub . Note that true enterprise license management with vendor-supported SLAs, global compliance coverage, and SaaS spend optimization (Flexera, Snow, ServiceNow) remains primarily commercial territory; open-source stacks provide strong ITAM, license scanning, and compliance foundations that require integration for complete software asset management.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Software license management involves legal compliance obligations. **Open-source license scanners do not give legal advice** . Consult legal counsel for license compliance decisions.
- **ITAM tools (GLPI, Snipe-IT) track purchased licenses** — they manage seat counts and renewals but do not detect open-source license obligations in source code . **SCA tools (ORT, FOSSology) detect license obligations** — they analyze source code and dependencies but do not track purchased seat licenses .
- **Open-source ITAM requires operational responsibility** — installation, maintenance, security, and agent deployment are your responsibility. Managed platforms shift this to the vendor .
- The open-source ecosystem provides strong ITAM, license scanning, and compliance foundations, but **global compliance coverage, SaaS spend optimization, and vendor-supported SLAs** remain primarily commercial offerings.

---

**Made for IT asset managers, compliance officers, and organizations seeking license management sovereignty.**  
Let's make software license management more open, transparent, and compliant.
