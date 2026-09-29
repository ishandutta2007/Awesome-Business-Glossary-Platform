# Awesome-Business-Glossary-Platform

# Top Business Glossary Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Data Governance, Business Semantics & Metadata Management*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Business Glossary Management**. These tools establish a shared vocabulary for business terms, metrics, and KPIs across an organization, bridging the gap between technical data assets and business understanding.

**Examples** include Collibra, Alation, Microsoft Purview, Informatica EDC, Atlan, DataGalaxy, Alex Solutions, DataHub, OvalEdge, and erwin Data Intelligence (the category leaders).

**Open-source emphasis**: This section is expanded with active projects for self-hosting, custom metadata workflows, and transparent data governance — ideal for organizations seeking vendor-independent solutions. The open-source ecosystem for business glossaries is closely tied to data catalog platforms, with several mature projects offering glossary capabilities as part of broader metadata management suites.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Collibra](https://www.collibra.com/)**  
  Enterprise data intelligence platform with comprehensive Business Glossary supporting configurable asset types (Business Term, Measure, KPI, Acronym), approval workflows, and semantic layer linking to physical data assets .

- **[Alation](https://www.alation.com/)**  
  Data catalog with Glossary Hub and Lexicon features, enabling automatic expansion of abbreviations found in data object names and suggested terms based on metadata context .

- **[Microsoft Purview](https://purview.microsoft.com/)**  
  Data governance platform with Business Glossary supporting rich-text definitions, CSV import/export, approval workflows, and term hierarchy with parent-child relationships .

- **[Informatica EDC](https://www.informatica.com/)**  
  Enterprise Data Catalog with business glossary management including categories, policies, business rules, and stewardship roles for terms and related assets .

- **[Atlan](https://atlan.com/)**  
  Modern data catalog with programmatic glossary management via Python SDK, supporting glossaries, categories, and terms with relationships and custom metadata .

- **[DataGalaxy](https://www.datagalaxy.com/)**  
  Data knowledge platform with Business Glossary featuring AI-assisted term discovery, automated relationship detection, certification campaigns, and direct linking to data assets .

- **[Alex Solutions](https://alexsolutions.com/)**  
  Data intelligence platform emphasizing bidirectional lineage between glossary terms and technical assets, ownership accountability, and embedding governance into existing tools .

- **[OvalEdge](https://www.ovaledge.com/)**  
  Data catalog with Business Glossary domains, categories, subcategories, governance role inheritance, and domain relationship dashboards visualizing term connections .

- **[erwin Data Intelligence](https://erwin.com/)**  
  Data governance suite with Business Glossary Manager supporting catalogs, sub-catalogs, business terms, policies, rules, and stewardship assignments with workflow management .

## Open-Source GitHub Projects

- **[DataHub](https://github.com/datahub-project/datahub)**  
  The leading open-source metadata platform, built at LinkedIn and organized around a real-time metadata graph. Business Glossary capabilities include creating glossaries as containers, adding terms with definitions, organizing terms hierarchically with parent-child relationships, and linking terms to datasets and individual columns . Supports developer automation via REST API and Python SDK for bulk imports . The mcp-datahub project extends glossary management with MCP server integration for AI agents . Largest community in the open-source catalog space .

- **[OpenMetadata](https://github.com/open-metadata/OpenMetadata)**  
  Open-source platform for data discovery, observability, and governance built around a central metadata repository . Covers the stewardship workflow in one package including search, column-level lineage, automated quality checks, no-code profiling, and classification. Recent releases added data contracts for machine-readable schema and quality guarantees . Together with DataHub, leads the open-source catalog space in community size and release cadence .

- **[Intugle Data Tools](https://github.com/intugle/data-tools)**  
  Open-source Python library of AI tools that helps build a semantic layer over fragmented datasets. Auto-profiles and links siloed datasets, **generates a business glossary from raw tables**, creates smart SQL and reusable data products, and powers semantic search and natural language queries on top of data . Perfect for data teams delivering data products and engineering teams implementing natural language to SQL .

- **[Apache Gravitino](https://github.com/apache/gravitino)**  
  Open-source metadata lake that federates metadata across data warehouses, lakehouses, streaming platforms, and AI systems under a single API . Graduated to Apache Top-Level Project in June 2025 . Rather than crawling metadata into a separate repository, it fronts existing systems (Apache Iceberg, Hive, Kafka, MySQL, PostgreSQL, file storage) and exposes them through a consistent REST interface, so policies apply at the point of access . Recent releases added OpenLineage-compliant lineage, role-based access control, policy and jobs system, and an MCP server for AI agent metadata queries .

- **[Unity Catalog](https://github.com/unitycatalog/unitycatalog)**  
  Open-source catalog for data and AI assets, open-sourced by Databricks in 2024 and hosted by LF AI & Data Foundation . Three-level namespace covers tabular data (Delta Lake and Apache Iceberg), unstructured volumes, ML models, and functions under one permission model. Implements Iceberg REST catalog API for engine interoperability. Enforcement-first governance model with access control and temporary credential vending at the catalog layer .

- **[NADA Catalog](https://github.com/ihsn/nada)**  
  Open-source suite for managing and disseminating research data metadata compliant with DDI standards . Catalog/Repository enables publishing, maintaining, and exploring metadata references via APIs with R support. Metadata Editor facilitates metadata creation and publication. Built on PHP, Apache/NGINX, and MySQL with Docker deployments and documentation .

### Additional Strong Open-Source Options

- **Amundsen** — Data discovery and metadata engine originally from Lyft, with glossary capabilities through community extensions. Predecessor to many modern catalog features.
- **Apache Atlas** — Metadata and governance framework with business glossary support, though development has slowed in favor of newer projects .
- **Marquez** — Open-source metadata service with lineage and dataset discovery, complementing glossary implementations.
- **OpenLineage** — Open standard for lineage metadata collection, often integrated with glossary platforms for end-to-end data context.

**Frameworks for building custom business glossary solutions**: Combine **DataHub** for a full-featured metadata platform with glossary, lineage, and search capabilities . Use **OpenMetadata** for an API-first, single-platform approach covering discovery through governance . Leverage **Intugle Data Tools** to automatically generate glossaries from raw tables using AI . For federated metadata across heterogeneous systems, **Apache Gravitino** provides policy application at the point of access . For lakehouse-centric teams, **Unity Catalog** offers enforcement-first governance with engine interoperability . Note that true enterprise business glossary platforms with sophisticated approval workflows, stakeholder notifications, and deep integration with BI tools remain primarily commercial territory; open-source stacks provide strong glossary foundations within broader metadata management platforms.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Business glossary tools must comply with data governance policies, regulatory requirements (GDPR, CCPA), and industry-specific compliance standards.
- Self-hosted open-source solutions require proper infrastructure, metadata management expertise, and ongoing maintenance. Glossary adoption depends on organizational commitment to standardization and stewardship.

---

**Made for data stewards, governance teams, data architects, and metadata professionals.**  
Let's make business glossary management more open, transparent, and collaborative.
