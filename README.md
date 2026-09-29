# Awesome-Customs-Management

## Top Customs Management Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Customs Declaration Processing, Tariff Classification, Trade Compliance & Cargo Clearance*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Customs Management**. These tools help importers, exporters, customs brokers, and trade compliance teams process customs declarations, classify goods, calculate duties, screen against sanctions lists, and ensure regulatory compliance across international borders.



**Examples** include WiseTech CargoWise, Descartes, E2open Customs Management, Thomson Reuters ONESOURCE, Livingston, CustomsNow, Microlistics, EstaSys, Precision Software, and Magaya Customs (the category leaders).



**Open-source emphasis**: Customs management has a **strong open-source foundation** driven by international organizations. **ASYCUDA** (UNCTAD's customs management system) is deployed in over 100 countries and is now open-source . **eTIR National Application** (UNECE) is an open-source reference implementation adopted by 6 contracting parties with 25+ more expressing interest . However, **commercial platforms** dominate the enterprise customs broker and trade compliance market, with open-source alternatives primarily serving national customs administrations and government agencies.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[WiseTech CargoWise](https://www.cargowise.com/)**  

  The dominant platform for global freight forwarding and customs brokerage. Provides end-to-end logistics execution, customs declaration processing, tariff classification, and trade compliance across 160+ countries.



- **[Descartes](https://www.descartes.com/)**  

  Global trade intelligence and customs compliance platform. Provides tariff classification, duty calculation, denied party screening, and customs filing automation.



- **[E2open Customs Management](https://www.e2open.com/)**  

  Supply chain and trade compliance platform with customs management capabilities. Handles import/export declarations, tariff classification, and regulatory compliance across global markets.



- **[Thomson Reuters ONESOURCE](https://tax.thomsonreuters.com/)**  

  Global trade and tax compliance platform. Provides customs duty calculation, tariff classification, free trade agreement management, and regulatory reporting.



- **[Livingston](https://www.livingstonintl.com/)**  

  Canadian customs brokerage and trade compliance provider. Offers customs clearance, tariff classification, duty relief programs, and consulting services.



- **[CustomsNow](https://www.customsnow.com/)**  

  Cloud-based customs management platform. Provides declaration processing, tariff management, and compliance workflows for brokers and importers.



- **[Microlistics](https://www.microlistics.com/)**  

  Warehouse management and customs compliance platform for the Australian and New Zealand markets.



- **[EstaSys](https://www.estasys.com/)**  

  Turkish customs management and foreign trade automation platform. Provides customs declaration processing and trade compliance for the Turkish market.



- **[Precision Software](https://www.ptc.com/)**  

  Global trade management platform (PTC). Provides customs declaration, tariff classification, and restricted party screening.



- **[Magaya Customs](https://www.magaya.com/)**  

  Logistics and customs management platform for freight forwarders and customs brokers. Provides customs declaration processing and compliance workflows.



## Open-Source GitHub Projects



### National Customs Management Systems



- **[ASYCUDA (UNCTAD)](https://asycuda.org/)**  

  **The most widely deployed open-source customs management system in the world.** Developed by UNCTAD and implemented in **100+ countries** . The **New Generation** suite is built as an open-source platform, reinforcing transparency and public sector empowerment . **Architecture**: Java with Quarkus framework, Jakarta EE, VueJS frontend, cloud-native microservices . **Features**: Cargo management, customs declarations, risk management (WCO SAFE Framework), AI/ML integration for anomaly detection and risk profiling, configurable workflows, role-based access, and alignment with WCO Data Model version 4.0 . **Open source** (source code available to member countries). The suite includes ASY5, ASYHUB, ASYREC, eCITES, and enhanced Single Window Framework .



- **[eTIR National Application (UNECE)](https://etir.org/etir-national-application)**  

  **Open-source reference implementation for electronic TIR (Transit International Routier) procedures.** Developed by the UNECE TIR Secretariat to facilitate implementation of the eTIR procedure . **Adopted by 6 contracting parties**, with **25+ others expressing interest** including the EU, EAEU, and Russian Federation . **Features**: Electronic TIR procedures, standardized eTIR message exchange, integration with International TIR Data Bank (ITDB), automatic accompanying document generation, multilingual support, and customs union mode . **Tech stack**: Spring Boot 3.0, ReactJS 18.2, PostgreSQL 15.2, Apache CXF, Bootstrap 5 . **Apache-2.0 license**. Deployable via Docker containers with 5-step installation .



### Customs Declaration Processing



- **[logiic-ltd/customs](https://github.com/logiic-ltd/customs)**  

  **Configurable customs declaration processing module for Frappe/ERPNext.** Built for import/export workflows with automated tax assessment and cargo clearance . **Features**: Single Administrative Document (SAD), Cargo Manifests, Waybills, Tax Assessment, Cargo Release Orders, automated duty/VAT/excise calculation, role-based access control (Customs Officers, Shipping Agents, Importers) . **MIT License**.



- **[HMRC customs-declarations](https://github.com/hmrc/customs-declarations)**  

  **UK HMRC's open-source Customs Declarations Service API.** Receives, validates, and processes customs declarations conforming to WCO DMS 3.6 schema . **Features**: Submit declarations, amend/cancel declarations, file upload for supporting documents, arrival notifications . **Tech stack**: Scala, MongoDB, SBT . **Open source**.



- **[HMRC customs-movements-frontend](https://github.com/hmrc/customs-movements-frontend)**  

  **UK HMRC's open-source frontend for Export Movements UI.** Allows users to submit Movements and Consolidations for Export Declarations . **Tech stack**: Scala, Play Framework, MongoDB. **Apache 2.0 license** .



### AI-Powered Trade Compliance & Classification



- **[Tariff Oracle / TariffBrain](https://github.com/RumetoBr/tariff-oracle)**  

  **AI-powered customs classification and trade compliance platform (2026).** Four-phase engine: **Classification, Calculation, Screening, Explanation** . **Features**: Autonomous HTS classification across 217 jurisdictions, real-time duty calculation (ad valorem, specific, compound, mixed), PGA screening against FDA/FCC/CPSC/REACH/WEEE/METI/MHLW, AI-powered reasoning with citations and confidence scores . **Tech stack**: Python 3.10-3.12, Docker, supports Linux/macOS/Windows . **Open source**.



- **[Global Trade Compliance AI Assistant](https://github.com/devandop/global-trade-compliance-ai-assistance)**  

  **Conversational AI interface for trade compliance.** Automates HS code classification, sanctions screening, and Xero invoice generation using Portia AI, Gemini LLM, and Slack for approvals . **Features**: Dynamic AI planning, HS code lookup, sanctions screening, real-time Xero integration, Slack approval workflows . **Tech stack**: FastAPI, Gemini LLM, Xero, Slack, Redis, PostgreSQL, Docker . **Open source**.



- **[customs-mcp-server](https://github.com/yak33/customs-mcp-server)**  

  **14 customs and trade capabilities as Model Context Protocol (MCP) tools.** Works with Claude Desktop, Claude Code, Cursor, Windsurf, Trae, and any MCP-compatible AI client . **Features**: Declarations, ship tracking, tariff lookup, dual-use screening, AI-powered document parsing . **Tech stack**: Node.js 18+, TypeScript, zero runtime dependencies . **Open source**.



### Tariff & Trade Data Management



- **[uktrade/tamato (Tariff Management Tool)](https://github.com/uktrade/tamato)**  

  **UK government's open-source Tariff Management Tool.** Stores and manages tariffs and controls applied on imports and exports at the UK border . **Tech stack**: Python, Django. **Open source**.



- **[pdf-xml-asycuda](https://github.com/kkzakaria/pdf-xml-asycuda)**  

  **PDF RFCV → XML ASYCUDA converter for Côte d'Ivoire customs automation.** Automates customs declaration data entry by converting PDF import verification certificates to ASYCUDA-compatible XML . **Features**: Synchronous and asynchronous conversion, batch processing API, OpenAPI/Swagger documentation, Docker deployment . **Tech stack**: Python 3.8+, FastAPI, Docker. **Open source**.



### Additional Strong Open-Source Options



- **National Customs Systems**: **ASYCUDA** (UNCTAD, 100+ countries, open-source), **eTIR National Application** (UNECE, Apache-2.0) .

- **Declaration Processing**: **logiic-ltd/customs** (Frappe/ERPNext module, MIT), **HMRC customs-declarations** (UK, Scala), **HMRC customs-movements-frontend** (UK, Scala/Play) .

- **AI Classification**: **Tariff Oracle/TariffBrain** (217 jurisdictions), **Global Trade Compliance AI** (Portia AI + Gemini), **customs-mcp-server** (14 MCP tools) .

- **Tariff Data**: **uktrade/tamato** (UK tariffs), **pdf-xml-asycuda** (Côte d'Ivoire automation) .



**Frameworks for building custom systems**: Combine **ASYCUDA** for national customs administration workflows, **eTIR National Application** for transit procedures, **logiic-ltd/customs** for declaration processing on Frappe/ERPNext, **Tariff Oracle** for AI-powered HS classification, and **customs-mcp-server** for LLM-integrated trade compliance. Add **PostgreSQL** for persistence and **Docker** for deployment.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Customs management platforms handle sensitive trade and regulatory data; ensure compliance with WCO standards, national customs regulations, and relevant trade laws.

- **Open-source reality**: The open-source ecosystem for customs management is **strong at the national/government level** (ASYCUDA, eTIR) but **limited for enterprise customs brokers**. **ASYCUDA** is the dominant open-source customs system globally , and **eTIR** provides a government-backed transit solution . For **commercial customs brokerage and trade compliance**, commercial platforms (CargoWise, Descartes, E2open) remain the primary choice. AI-powered classification tools (Tariff Oracle, Global Trade Compliance AI) represent an emerging open-source alternative for specific compliance tasks .



---



**Made for customs brokers, trade compliance managers, import/export operations teams, and government customs administrations.**

Let's make customs management more open, transparent, and trade-facilitating.
