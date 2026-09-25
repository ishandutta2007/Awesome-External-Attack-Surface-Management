# Awesome-External-Attack-Surface-Management

# Top External Attack Surface Management (EASM) Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Internet-Facing Asset Discovery, Shadow IT, Exposure Validation, Continuous Monitoring & Attack Surface Reduction*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **External Attack Surface Management (EASM)**. These systems discover and continuously monitor an organization’s internet-facing assets (domains, IPs, cloud resources, APIs, certificates), identify shadow IT and subsidiaries, validate exposures, and help prioritize remediation.

**Examples** include Palo Alto Cortex Xpanse, Microsoft Defender EASM, Censys, Detectify, IONIX, UpGuard, Hadrian, Assetnote, SOCRadar, CyCognito, Shodan Enterprise, Randori, Rapid7, and Tenable (the category leaders).

**Open-source emphasis**: This domain has a strong open-source ecosystem. **OWASP Amass**, the **ProjectDiscovery** suite (Subfinder, httpx, Nuclei, Chaos), and related recon tools provide production-grade discovery and scanning that many security teams self-host. Commercial platforms mainly add scale, continuous internet-wide data, attribution, and enterprise workflows. This section heavily expands the open options.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Palo Alto Cortex Xpanse](https://www.paloaltonetworks.com/)**  
  Enterprise EASM module within the Cortex platform—massive-scale internet scanning, continuous exposure tracking, and tight integration for Cortex-standardized organizations.

- **[Microsoft Defender EASM](https://www.microsoft.com/)**  
  Microsoft’s external attack surface management capability integrated with Defender and Azure security services for discovery and exposure insights.

- **[Censys](https://censys.com/)**  
  Internet-wide scanning and asset intelligence platform providing exceptional data breadth, research-grade visibility, and attack-surface analytics.

- **[Detectify](https://detectify.com/)**  
  External attack surface and vulnerability scanning platform with continuous monitoring and a strong focus on web application exposures.

- **[IONIX](https://www.ionix.io/)**  
  EASM platform emphasizing rapid exposure identification, validation, and mitigation workflows (including supply-chain and dependency context).

- **[UpGuard](https://www.upguard.com/)**  
  Security ratings and attack-surface platform used for external posture, third-party risk, and continuous monitoring.

- **[Hadrian](https://www.hadrian.io/)**  
  Autonomous external attack surface and penetration-testing-oriented platform focused on continuous discovery and validated findings.

- **[Assetnote](https://www.assetnote.io/)**  
  Attack surface management and continuous monitoring platform popular with security teams for asset discovery and change detection.

- **[SOCRadar](https://socradar.io/)**  
  Extended threat intelligence and digital risk platform with external attack surface, dark web, and brand monitoring capabilities.

- **[CyCognito, Shodan Enterprise, Randori, Rapid7, Tenable and related platforms](https://www.example.com/)**  
  Additional EASM and exposure-management offerings—seedless discovery (CyCognito), internet search/enterprise (Shodan), continuous assessment (Randori), and ecosystem solutions from Rapid7 and Tenable.

## Open-Source GitHub Projects
- **[OWASP Amass](https://github.com/owasp-amass/amass)**  
  Flagship open-source framework for in-depth attack surface mapping and external asset discovery using OSINT and active reconnaissance (Apache 2.0). Includes collection engine, asset database, and Open Asset Model.

- **[ProjectDiscovery suite](https://github.com/projectdiscovery)**  
  Widely used open-source toolkit for external recon and exposure discovery:
  - **Subfinder** — fast passive subdomain discovery  
  - **httpx** — HTTP probing and tech detection  
  - **Nuclei** — template-based vulnerability and exposure scanning  
  - **Chaos / dnsx / naabu** and related tools for DNS, port, and asset enumeration  

- **[Open Asset Model (OWASP Amass)](https://github.com/owasp-amass/open-asset-model)**  
  Community effort to uniformly describe internet-facing assets and their relationships for attack-surface representation and exchange.

- **[Amass Asset DB and supporting components](https://github.com/owasp-amass)**  
  Storage, navigation, and tooling around the Open Asset Model for persistent attack-surface inventories.

- **[theHarvester and classic OSINT recon tools](https://github.com/)**  
  Open information-gathering utilities for emails, subdomains, hosts, and related external intelligence.

- **[Certificate transparency and subdomain open collectors](https://github.com/)**  
  Tools that mine CT logs (crt.sh and others) and public sources for newly issued certificates and hostnames.

- **[Port and service discovery open scanners](https://github.com/)**  
  Masscan, Nmap, and community wrappers used for large-scale external port and service enumeration.

- **[Cloud and SaaS asset open enumerators](https://github.com/)**  
  Scripts and tools for discovering public cloud storage, misconfigured services, and SaaS exposures.

- **[Continuous monitoring open pipelines](https://github.com/)**  
  Cron/CI-based workflows that periodically re-run Amass, Subfinder, httpx, and Nuclei and diff results over time.

- **[Documentation and EASM open playbooks](https://github.com/)**  
  Guides for building a self-hosted external attack surface program with open tools.

### Additional Strong Open-Source Options
- Building a continuous discovery pipeline with **Amass + ProjectDiscovery** tools and storing results in a simple asset database.
- Combining passive OSINT sources with active probing and Nuclei templates for validated exposure detection.
- Accepting that global internet-wide continuous scanning, automated subsidiary/attribution mapping, enterprise dashboards, and managed remediation workflows still favor commercial platforms (Cortex Xpanse, CyCognito, Censys, IONIX, Microsoft Defender EASM, etc.).
- Focusing open-source efforts on transparency, customizability, and zero licensing cost for security engineering teams.

**Frameworks for building custom systems**: Seed with known domains and ASNs → run Amass / Subfinder for discovery → probe with httpx and port scanners → validate exposures with Nuclei → store and diff assets over time → feed high-priority findings into ticketing. Suitable for security teams with engineering capacity. Many enterprises still adopt commercial EASM platforms for scale, attribution, and operational integration.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Attack surface discovery and scanning must be performed only on assets you own or are explicitly authorized to test. Unauthorized scanning can be illegal. Open-source tools are powerful; use them responsibly and within legal and organizational policy. This list is not legal or security advice.

---
**Made for security engineers, ASM practitioners, and open-source recon advocates.**
Let's keep external surfaces visible, validated, and as open as practical.
