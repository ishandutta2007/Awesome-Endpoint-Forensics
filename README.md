# Awesome-Endpoint-Forensics

# Top Endpoint Forensics Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Live Response, Endpoint Artifact Collection, Digital Forensics & Incident Response (DFIR), Remote Triage & Evidence Acquisition*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Endpoint Forensics**. These tools enable remote or local collection of forensic artifacts, live response, timeline analysis, and investigation of endpoints during incident response and digital forensics cases.

**Examples** include Velociraptor, Magnet AXIOM, OpenText EnCase, Exterro FTK, GRR Rapid Response, CrowdStrike Falcon Forensics, Cellebrite Endpoint Inspector, Carbon Black Response, Microsoft Defender Live Response, and Velocidex (the category leaders).

**Open-source emphasis**: Endpoint forensics has one of the strongest open-source communities in security. **Velociraptor**, **GRR**, **The Sleuth Kit / Autopsy**, **osquery**, and related DFIR tooling are widely used in production. This section heavily expands those projects.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Velociraptor](https://docs.velociraptor.app/)**  
  Powerful endpoint visibility and forensic platform (open-source core with commercial support options)—VQL query language, live response, artifact collection, and hunting at scale. Also listed under open-source.

- **[Magnet AXIOM](https://www.magnetforensics.com/)**  
  Comprehensive digital investigations platform for endpoints, mobile, and cloud—strong parsing, visualization, and cross-platform analysis for DFIR teams.

- **[OpenText EnCase](https://www.opentext.com/)**  
  Long-established computer forensics platform with strong court recognition, deep disk analysis, and enterprise investigation capabilities.

- **[Exterro FTK (Forensic Toolkit)](https://www.exterro.com/)**  
  Full-featured forensic suite for acquisition, processing, and analysis of digital evidence from endpoints and storage.

- **[GRR Rapid Response](https://www.grr-response.com/)**  
  Open-source live forensics and remote response framework (with enterprise usage)—file collection, process inspection, and scalable endpoint investigation. Also listed under open-source.

- **[CrowdStrike Falcon Forensics](https://www.crowdstrike.com/)**  
  Forensic and investigation capabilities integrated with the CrowdStrike Falcon platform for endpoint detection and response.

- **[Cellebrite Endpoint Inspector](https://cellebrite.com/)**  
  Endpoint and digital investigation tooling within Cellebrite’s broader forensics portfolio.

- **[Carbon Black Response / related VMware Carbon Black capabilities](https://www.broadcom.com/)**  
  Endpoint response and investigation features historically associated with Carbon Black EDR platforms.

- **[Microsoft Defender Live Response](https://learn.microsoft.com/)**  
  Live response and investigation capabilities within Microsoft Defender for Endpoint for enterprise Windows estates.

- **[Velocidex and related commercial offerings](https://www.velocidex.com/)**  
  Commercial support, training, and enterprise services around the Velociraptor ecosystem.

## Open-Source GitHub Projects
- **[Velociraptor](https://github.com/Velocidex/velociraptor)**  
  Leading open-source endpoint visibility, digital forensics, and incident response platform—powerful VQL language, artifact exchange, live hunting, and scalable collection across Windows, Linux, and macOS.

- **[GRR Rapid Response](https://github.com/google/grr)**  
  Open-source remote live forensics framework for scalable endpoint investigation—file search/collection, process and network enumeration, memory analysis, and osquery integration.

- **[The Sleuth Kit](https://github.com/sleuthkit/sleuthkit)**  
  Foundational open-source library and tools for disk image analysis, file system forensics, and evidence examination.

- **[Autopsy](https://github.com/sleuthkit/autopsy)**  
  Open-source digital forensics platform built on The Sleuth Kit—graphical interface for investigating hard drives, media, and endpoint artifacts.

- **[osquery](https://github.com/osquery/osquery)**  
  Open-source endpoint instrumentation that exposes OS data as SQL tables—widely used for live querying and forensic triage.

- **[Volatility / Volatility 3](https://github.com/volatilityfoundation/volatility3)**  
  Premier open-source framework for memory forensics and analysis of volatile memory dumps from endpoints.

- **[KAPE (Kroll Artifact Parser and Extractor) related open triage tooling](https://github.com/)**  
  Free/community triage and artifact collection tools frequently used alongside open DFIR stacks for rapid endpoint collection.

- **[ForensicArtifacts definitions](https://github.com/ForensicArtifacts/artifacts)**  
  Open repository of forensic artifact definitions used by GRR, Velociraptor, and other collection frameworks.

- **[YARA and detection open rules](https://github.com/)**  
  Open pattern-matching rules and engines used during live response and malware hunting on endpoints.

- **[Documentation and DFIR open playbooks](https://docs.velociraptor.app/)**  
  Guides for deploying Velociraptor, GRR, Autopsy, and related open tools in enterprise incident response.

### Additional Strong Open-Source Options
- Deploying **Velociraptor** as the primary open platform for live response, hunting, and scalable artifact collection.
- Using **GRR** for large-scale remote forensics and automated collection workflows.
- Combining **Autopsy / The Sleuth Kit** for offline disk image analysis with live tools for triage.
- Adding **osquery** and **Volatility** for targeted live queries and memory analysis.
- Accepting that court-validated commercial workflows, advanced mobile/cloud parsing, polished case management, and vendor support still drive many labs and enterprises to Magnet AXIOM, EnCase, FTK, and EDR-integrated forensics.
- Focusing open-source efforts on transparency, custom artifact development, and cost-effective DFIR capability.

**Frameworks for building custom systems**: Deploy Velociraptor or GRR agents → define artifact collections and hunts → triage with VQL/osquery → analyze disks with Autopsy/TSK and memory with Volatility → document in open case notes. Suitable for security teams and DFIR practitioners. Many organizations still use commercial forensics suites for formal investigations and legal proceedings.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Digital forensics tools handle sensitive evidence. Proper chain of custody, legal authorization, and validation are required. Open-source tools must be used responsibly and may need additional validation for court use. This list is not legal or forensic advice.

---
**Made for DFIR practitioners, security engineers, and open-source forensics advocates.**
Let's keep investigations thorough, transparent, and as open as practical.
