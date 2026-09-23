# Awesome-Advanced-Distribution-Management-System

# Top Advanced Distribution Management System (ADMS) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Electric Distribution Grid Operations, Outage Management, DER Integration, Network Analysis, SCADA/OMS/DMS Convergence & Utility Control Room Platforms*  
**Last updated: September 2026**

This repository tracks notable **commercial platforms** and **open-source projects** for **Advanced Distribution Management Systems (ADMS)**. ADMS platforms integrate SCADA, outage management (OMS), distribution management (DMS), and increasingly DER management to give utilities real-time situational awareness, network analysis, switching, restoration, and optimization of the electric distribution grid.

**Examples** include GE GridOS ADMS, Schneider Electric EcoStruxure ADMS, Siemens Spectrum Power, Oracle ADMS / Network Management, Open Systems International (OSI), ETAP ADMS, Hitachi Energy, Survalent, Hexagon ADMS, and Milsoft (the category leaders).

**Open-source emphasis**: Production ADMS platforms used by large utilities are almost exclusively commercial. Significant open-source foundations exist for research, application development, and simulation—especially **GridAPPS-D**, **GridLAB-D**, and **OpenDSS**. This section lists every major relevant project found.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[GE Vernova GridOS ADMS](https://www.gevernova.com/)**  
  Modern ADMS platform emphasizing modular, microservices-oriented architecture, outage management, network operations, and support for distributed energy resources and grid modernization.

- **[Schneider Electric EcoStruxure ADMS](https://www.se.com/)**  
  Comprehensive modular ADMS covering monitoring, outage response, network analysis, optimization, and DER integration for electric distribution utilities.

- **[Siemens Spectrum Power ADMS](https://www.siemens.com/)**  
  ADMS built on the Spectrum Power control system platform, providing real-time operations, analysis, optimization, and restoration tools for distribution grids.

- **[Oracle Utilities Network Management / ADMS](https://www.oracle.com/)**  
  Network management and ADMS capabilities integrated with Oracle’s broader utilities suite for outage, network, and grid-edge device management.

- **[OSI (Open Systems International), Survalent, ETAP ADMS, Hitachi Energy, Hexagon, Milsoft](https://www.osii.com/)**  
  Additional commercial ADMS, DMS, and related distribution management and SCADA platforms serving utilities of varying sizes.

- **[Other commercial ADMS & distribution management platforms](https://www.gevernova.com/)**  
  Solutions focused on real-time grid operations, switching management, load flow, and DER visibility.

## Open-Source GitHub Projects

- **[GridAPPS-D](https://github.com/GRIDAPPSD)**  
  Open-source, standards-based platform (led by PNNL with DOE support) designed to accelerate development and deployment of portable advanced distribution applications. Provides data models (CIM), APIs, and a reference environment separating data management from application logic—explicitly aimed at ADMS-style application development.

- **[GridLAB-D](https://github.com/gridlab-d/gridlab-d)**  
  Open-source distribution system simulation and analysis tool (DOE/PNNL origins) widely used for research, planning, and co-simulation of distribution networks with high DER penetration.

- **[OpenDSS](https://github.com/EPRI-Engineering/OpenDSS)**  
  Open-source distribution system simulator from EPRI, extensively used for power flow, fault studies, and DER impact analysis on distribution feeders.

- **[Related open distribution modeling & co-simulation](https://github.com/NREL/ditto)**  
  Tools such as NREL’s DiTTo and HELICS-compatible frameworks for converting and co-simulating distribution models across OpenDSS, GridLAB-D, and other environments.

- **[Power grid management conceptual / emerging projects](https://github.com/worlds-biggest-software-project/374-power-grid-management)**  
  Early open initiatives exploring modern EMS/ADMS-style platforms for generation, demand, and outage workflows with open standards (CIM, IEC 61850, DNP3, etc.).

- **[Open SCADA & protocol stacks](https://github.com/search?q=open+SCADA+OR+DNP3+OR+IEC+61850+open+source)**  
  Open implementations of SCADA components and industrial protocols that form building blocks of distribution control systems.

- **[DER & grid-edge open tools](https://github.com/search?q=DERMS+OR+OpenADR+OR+IEEE+2030.5)**  
  Projects supporting DER communication and control standards often integrated with or alongside ADMS functions.

- **[Power system analysis open libraries](https://github.com/search?q=power+flow+OR+distribution+system+analysis+open+source)**  
  Additional open libraries for load flow, state estimation concepts, and network analysis usable in research or custom tools.

### Additional Strong Open-Source Options

- **GridAPPS-D**: The primary open reference platform for developing standards-based ADMS applications.
- **Simulation foundations**: GridLAB-D and OpenDSS for detailed distribution network modeling and studies.
- **Model exchange**: CIM-oriented and converter tools (e.g., DiTTo) for portable network models.
- **Composable research stacks**: GridAPPS-D + OpenDSS/GridLAB-D + open protocol stacks for lab and pilot environments.
- Full production ADMS used in utility control rooms remains commercial.

**Frameworks for building custom systems**:  
**GridAPPS-D** is the most important open-source project explicitly targeting advanced distribution management application development.  
**GridLAB-D** and **OpenDSS** provide world-class open distribution simulation.  
Together they enable research, pilots, and application prototyping.  
Commercial ADMS platforms (GE GridOS, Schneider EcoStruxure, Siemens Spectrum Power, Oracle, OSI, Survalent, etc.) deliver the real-time SCADA integration, high-availability control room features, outage management workflows, and vendor support required by operating utilities.  
Most utilities run commercial ADMS for live operations and use open tools (GridAPPS-D, OpenDSS, GridLAB-D) for research, planning, and advanced application development. Fully open production ADMS stacks are not yet practical for large regulated utilities.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's commercial/SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- ADMS platforms are safety- and reliability-critical operational technology. Incorrect configuration or failure can affect grid reliability, public safety, and regulatory compliance. Only qualified, validated systems should be used for live distribution operations.
- Open-source tools are excellent for research, simulation, and application development but generally lack the real-time performance, redundancy, certification, and support required for production utility control rooms. Do not deploy unvalidated open-source software for live grid operations without thorough engineering and regulatory review.

---

**Made for utility distribution operators, grid modernization engineers, DER integration teams, and power systems researchers.**  
Let's expand open platforms for advanced distribution applications while recognizing the operational maturity, reliability, and support that leading commercial ADMS platforms deliver.
