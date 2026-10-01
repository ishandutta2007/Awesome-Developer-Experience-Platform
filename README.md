# Awesome-Developer-Experience-Platform

## Top Developer Experience (DevEx) Platform Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Engineering Metrics, Developer Surveys & Productivity Analytics*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Developer Experience (DevEx)**. These tools measure and improve how developers work by combining quantitative engineering metrics (DORA, PR throughput) with qualitative developer surveys to identify friction and drive improvements.



**Examples** include DX (getdx), LinearB, Swarmia, Jellyfish, Harness IDP, Port, Cortex, OpsLevel, Roadie, and Humanitec (the category leaders).



**Open-source emphasis**: The open-source ecosystem for DevEx is anchored by **Apache DevLake** (dev data platform with DORA dashboards), **CDviz** (event-driven pipeline observability), and **Middleware** (open-source DORA metrics). While commercial platforms lead in survey frameworks and benchmark data, open-source tools provide strong quantitative foundations with data ownership.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[DX (getdx)](https://getdx.com/)**  

  Research-backed DevEx platform centered on the **Developer Experience Index (DXI)** — a validated measure of engineering effectiveness with over 4 million benchmark samples from 800+ organizations . DXI is proven to correlate with business outcomes: a single-point increase correlates to 0.7% increased engineering efficiency in reduced time loss . Combines quarterly developer surveys (Snapshots) with system metrics from SCM, CI/CD, and issue trackers . The **DX Core 4** framework unifies DORA, SPACE, and DevEx into Speed, Effectiveness, Quality, and Impact .



- **[LinearB](https://linearb.io/)**  

  Engineering intelligence platform with strong workflow automation (WorkerB) and PR cycle time optimization. Recent 2026 releases add **MCP Server** for natural language engineering data access, **AI Insights dashboard** tracking 24+ AI tools (GitHub Copilot, Cursor, Claude Code, etc.), and **DevEx surveys** — all included in the $29/contributor/month Essentials plan . Free tier for up to 8 contributors .



- **[Swarmia](https://www.swarmia.com/)**  

  Engineering effectiveness analytics platform combining DORA metrics, developer experience, investment balance, and AI adoption insights . Publishes transparent pricing: **Standard** at $45/developer/month (all four modules) and **Enterprise** at $55 (adds on-prem integrations, HR systems) . Free for teams under 10 developers. SOC 2 Type 2 compliant.



- **[Jellyfish](https://jellyfish.co/)**  

  Enterprise engineering management platform positioning itself around investment allocation and business alignment. Stronger executive reporting and portfolio management features than Swarmia or LinearB, targeting organizations with 100+ developers . Pricing typically $500–800 per developer annually .



- **[Harness IDP](https://www.harness.io/)**  

  Internal developer portal integrated with Harness's broader software delivery platform.



- **[Port](https://www.port.io/)**  

  Managed, API-first internal developer portal with flexible blueprints for modeling entities. Self-service actions trigger GitHub Actions, Terraform, or webhooks. Free tier up to 15 seats .



- **[Cortex](https://www.cortex.io/)**  

  Service catalog and engineering intelligence platform with the deepest scorecard engine. AI engine (Magellan) assists catalog auditing. Pricing approximately $65–69 per user/month .



- **[OpsLevel](https://www.opslevel.com/)**  

  Managed service catalog with automated service discovery and simpler data model than Port's blueprint system.



- **[Roadie](https://roadie.io/)**  

  Fully managed, hosted Backstage. Teams plan at $24 per developer/month for 50–150 developers .



- **[Humanitec](https://humanitec.com/)**  

  Platform orchestrator centered on the open-source **Score** workload specification, focused on environment drift and provisioning rather than service cataloging.



## Open-Source GitHub Projects



- **[Apache DevLake](https://github.com/apache/incubator-devlake)**  

  Open-source dev data platform that ingests, analyzes, and visualizes fragmented data from DevOps tools. Provides DORA dashboards, SDLC data integration, Grafana dashboards, custom metrics, and extensibility via SQL . **Requires internal ownership** — someone must manage setup, integrations, data definitions, dashboard governance, upgrades, and interpretation . Best for organizations with data engineering capacity and open-source preference.



- **[CDviz](https://cdviz.dev/)**  

  Open-source platform (Apache 2.0) with self-hosted and SaaS options for CI/CD pipeline observability and DORA metrics. Built on **CDEvents** open standard for portable event data . Events can trigger downstream workflows — the same event stream drives observability and automation . Self-hosted is free (infra costs only); Cloud option at €20/month, Pro at €200/month with commercial support . **Quantitative-only** — does not run developer experience surveys .



- **[Middleware](https://github.com/middlewarehq/middleware)**  

  Open-source DORA metrics platform for engineering teams . Lightweight alternative for teams wanting basic DORA tracking without the complexity of DevLake.



- **[java-local-metrics (Agoda)](https://github.com/agoda-com/java-local-metrics)**  

  Open-source library measuring the **F5 Experience** — local development workstation performance. Captures test execution time, build times, and system resource usage for JUnit and ScalaTest . Helps teams identify local iteration bottlenecks (slow tests, sluggish builds) that impact developer flow. Apache-2.0 licensed.



- **[DevEx Resources](https://github.com/shaharia-lab/devex-resources)**  

  Curated collection of frameworks, research papers, articles, and tools for improving developer experience and measuring productivity. Includes DORA, SPACE, and DevEx research .



- **[Awesome Developer Experience](https://github.com/prokopsimek/awesome-developer-experience)**  

  Curated list of DX resources including documentation tools, API platforms, automation, knowledge management, and local development tools .



### Additional Strong Open-Source Options



- **DX Core 4 Open Framework** — The DX Core 4 methodology (Speed, Effectiveness, Quality, Impact) is publicly documented and can be implemented with open-source data sources .

- **Grafana + Prometheus** — Community-favored stack for building custom engineering metrics dashboards from CI/CD and SCM data.

- **OpenTelemetry** — Vendor-neutral instrumentation for collecting pipeline and deployment telemetry that can feed DevEx analytics.



**Frameworks for building custom DevEx solutions**: Combine **Apache DevLake** for comprehensive SDLC data ingestion and DORA dashboards with **CDviz** for event-driven pipeline observability and workflow automation . Use **Middleware** for lightweight DORA tracking. Integrate **java-local-metrics** for measuring local iteration speed (F5 Experience) . For survey-based qualitative data, organizations typically build custom survey pipelines using tools like **Google Forms** paired with the DX Core 4 framework for structured measurement . Note that true enterprise DevEx platforms with validated benchmark data (DX's 4M+ sample DXI), built-in survey frameworks, and AI tool tracking remain primarily commercial territory; open-source stacks provide strong quantitative foundations with data ownership that require integration for complete DevEx programs .



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- DevEx platforms collect data from source control, CI/CD, and issue trackers, and may survey developers about their work experience. Self-hosted solutions require proper security hardening and compliance with data privacy regulations (GDPR, CCPA).

- Engineering metrics can be misused. DORA metrics and PR throughput should inform improvement conversations, not individual performance evaluation. The DX Core 4 explicitly notes that PR throughput is "not at individual level" for good reason .

- The open-source ecosystem provides strong quantitative foundations and data ownership, but validated benchmark data (DX's DXI), built-in survey frameworks, and AI tool tracking remain primarily commercial offerings.



---



**Made for engineering leaders, developer experience teams, platform engineers, and DevEx researchers.**

Let's make developer experience more open, transparent, and developer-centric.
