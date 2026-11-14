# Awesome-Embedded-Business-Intelligence-Analytics

## Top Embedded Business Intelligence & Analytics Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on White-Label Dashboards, Multi-Tenant RLS & Self-Hosted Embedding*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Embedded Business Intelligence & Analytics**. These tools let you drop dashboards, charts, and self-service exploration directly into your own product—covering everything from per-viewer SaaS SDKs to open-source engines you self-host with zero per-seat licensing.

**Examples** include Looker Embedded, Power BI Embedded, Tableau Embedded, Sisense, GoodData, Domo Everywhere, Zoho Analytics, Apache Superset, Metabase, and Cube (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted embedded BI, open-source semantic layers, and community-driven white-label analytics—ideal for SaaS builders seeking to avoid per-viewer pricing that scales against revenue. The open-source landscape is genuinely functional: **Apache Superset** provides a zero-license-fee BI engine you can embed and white-label , **Metabase** offers the fastest path to a working dashboard but gates embedding behind its Pro plan , and **Cube** delivers a semantic layer and caching API that sits beneath your own UI .

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global embedded analytics and business intelligence market is estimated between **$27 billion and $86+ billion** (with broad BI and analytics implementations projected to surpass **$200 billion** by the 2030s at an annual growth rate of ~13–16%). The sector exhibits a **barbell dynamic**: it is **concentrated at the macro-infrastructure and platform suite level** (dominated by cloud hyperscalers and enterprise giants like Microsoft, Google Cloud, and Salesforce with high ecosystem lock-in), but remains **moderately-to-highly fragmented at the application execution and ISV layer**, where specialized vendors and developer-first frameworks cater to thousands of bespoke multi-tenant SaaS integration requirements.

## SaaS/Hosted Platforms

| Product | Company Size (Valuation / Revenue) | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|------------------------------------|-------------|-------------------|--------------------------|
| **[Power BI Embedded (Microsoft)](https://azure.microsoft.com/en-us/pricing/details/power-bi-embedded/)** | **~$3.1 Trillion** market cap / **~$245B+** annual revenue (Microsoft) | Capacity-based embedding via **Microsoft Fabric F-SKUs**. **App-Owns-Data** model covers external viewers through capacity without per-user viewer licenses; report authors require Power BI Pro licenses. | **$262/month PAYG** ($156/mo reserved) for Fabric F2 capacity; report creators at **$14/user/month** | **60-day free trial** of Microsoft Fabric capacity (F4/F64 equivalent) with up to **1 TB OneLake storage** |
| **[Looker Embedded (Google Cloud)](https://looker.com/)** | **~$2.1 Trillion** market cap / **~$350B+** annual revenue (Alphabet/Google) | Enterprise semantic modeling (LookML) with embed SDKs, version-controlled analytics, and full governance across multi-cloud databases. | **$5,000/month** ($60,000/year) baseline platform instance fee (includes 10 standard users, 2 developers); additional viewers ~$30/user/mo | **90-day free trial** instance via Google Cloud core; includes **$300 welcome credits** on Google Cloud |
| **[Tableau Embedded (Salesforce)](https://www.tableau.com/)** | **~$280 Billion** market cap / **~$38B+** annual revenue (Salesforce) | Deep data visualization and dashboarding with OEM embedding APIs, SSO, and fine-grained permissions. | **$15/user/month** (billed annually at $180/yr) for Standard Viewer seats; dedicated OEM/ISV embedded contracts start from **~$60,000/year** | **14-day free trial** of Tableau Cloud/Desktop Creator; indefinite **Tableau Desktop Free Edition** (local saves only, no cloud publishing) |
| **[Zoho Analytics](https://www.zoho.com/analytics/)** | **~$12.5 Billion** valuation / **~$1.4B+** annual revenue (Zoho Corp, bootstrapped) | Full white-label and multi-tenant reporting platform supporting iframe embedding, JavaScript SDK, and headless APIs. | **$145/month** (billed annually) for White-Label / Embedded plan; standard analytics tiers start at **$30/month** (Basic) | **Free-for-ever plan** (up to 2 users, 5 workspaces, and 10,000 rows); **15-day free trial** with unlimited access to premium tiers |
| **[ThoughtSpot Everywhere](https://www.thoughtspot.com/)** | **~$4.2 Billion** valuation / **~$150M+** ARR (ThoughtSpot) | Search-driven conversational embedded analytics, natural-language query generation, and interactive data apps via embed SDK. | **$25/user/month** (billed annually) for internal essentials; embedded production deployments start from **~$2,500/month** (custom tiered contract) | **1-year free Developer tier** (supports up to 10 users and 25 million rows); standard SaaS trial is **14 days** |
| **[Sisense](https://www.sisense.com/)** | **~$1.1 Billion** valuation / **~$140M+** ARR (Sisense) | Code-first embedding toolkit and Compose SDK with columnar ElastiCube data engine, AI capabilities, and tenant-level data security. | **$2,083/month** (entry contract floor starting at **~$25,000–$40,000/year**) | **7-day free trial** (test drive) with full dashboard creation, data modeling, and embedded SDK features |
| **[Domo Everywhere](https://www.domo.com/)** | **~$160 Million** market cap / **~$318M** annual revenue (Domo, Inc. NASDAQ: DOMO) | Cloud-native end-to-end data integration, dashboarding, and external embedding driven by credit consumption. | **$300/month** base platform plan ($3,000/month typical entry for full embedded credit tiers) | **30-day free trial** with full enterprise platform features, unlimited test seats, and unmetered credit sandbox |
| **[GoodData](https://www.gooddata.com/)** | **~$300 Million** valuation / **~$60M+** ARR (GoodData) | Headless BI platform with semantic layer, React/Python SDKs, and multi-tenant workspace isolation. | **$1,500/month** base fee for Professional Plan (workspace-based model with unlimited users and data) | **30-day free trial** capped at 10 workspaces, 10 users, and 10 exports per workspace per 24 hours |
| **[Qrvey](https://www.qrvey.com/)** | **~$80 Million–$100 Million** valuation / **~$20M** ARR (Qrvey) | Full-stack embedded analytics and data engine purpose-built for multi-tenant SaaS applications, deployed in AWS/cloud VPCs. | **$2,083/month** (flat-rate platform pricing starting at **~$25,000–$35,000/year** with unlimited users and tenants) | **14-to-30 day scoped Proof of Concept (POC)** sandbox environment with assisted engineering deployment (no self-serve free trial) |
| **[Luzmo](https://www.luzmo.com/)** | **~$50 Million–$100 Million** valuation / **~$5M+** ARR (Luzmo) | Developer-focused embedded analytics UI components, fast API connectors, and modular charts built specifically for SaaS apps. | **€495/month (~$540/month)** for Starter tier; **€995/month (~$1,085/month)** for Growth tier | **10-day free trial** with full access to white-labeling, chart customization, and API embedding |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Apache Superset](https://github.com/apache/superset)** | [![Stars](https://img.shields.io/github/stars/apache/superset?style=social&color=white)](https://github.com/apache/superset/stargazers) | **The most capable open-source BI engine for embedding and white-labeling.** **Zero software licensing fees**—you pay only for infrastructure . Deep SQL flexibility, extensible architecture for custom visuals, and connectors to dozens of data sources. **Supports iframe, SDK, and API-driven embedding** with row-level security. Technical teams own the stack and avoid vendor lock-in . **Trade-off**: requires engineering effort for theming, multi-tenant isolation, and operational maintenance—but it is the only open-source option that matches commercial BI depth without per-viewer costs . **Best for SaaS builders with engineering capacity who want zero per-seat licensing.** |
| **[Metabase](https://github.com/metabase/metabase)** | [![Stars](https://img.shields.io/github/stars/metabase/metabase?style=social&color=white)](https://github.com/metabase/metabase/stargazers) | **The fastest open-source path to a working dashboard—but embedding is a paid feature.** The **Open Source edition is free and unlimited-user**, but **embedding, SSO, row-level security, tenants, and white-labeling all require the Pro plan** . The intuitive Question builder lets non-technical users build reports without SQL. **Best for startups and mid-market teams needing internal reporting today**—evaluate Pro pricing before planning external embedding . |
| **[Cube](https://github.com/cube-io/cube)** | [![Stars](https://img.shields.io/github/stars/cube-io/cube?style=social&color=white)](https://github.com/cube-io/cube/stargazers) | **The strongest non-BI building block for productizing a dashboard offering.** **Cube Core is Apache 2.0 and fully free to self-host**—provides a semantic layer, caching, and API layer rather than a chart library . **Cube Cloud: Free → Starter $40/dev/mo → Premium $80/dev/mo (Premium includes embedded dashboards)** . 2026 additions include Cube Copilot, Tesseract modeling engine, and Data Access Policies . **Best for teams that want to own the UI and use Cube purely as the query/semantic backend.** |
| **[Helical Insight](https://github.com/helicalinsight/helicalinsight)** | [![Stars](https://img.shields.io/github/stars/helicalinsight/helicalinsight?style=social&color=white)](https://github.com/helicalinsight/helicalinsight/stargazers) | **Full-featured open-source BI with AI conversational analytics, pixel-perfect paginated reports, interactive dashboards, SSO, embedding, multi-tenancy, and row-level security—every feature free in Community Edition** . Self-hosted and Docker-ready. Connects to virtually any database via native connectors, JDBC, and REST APIs. Positioned as a complete alternative to Superset/Metabase with reporting capabilities included . **Best for teams wanting embedding and reporting in one free self-hosted package.** |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Lotus](https://github.com/elixir-lotus/lotus)** | [![Stars](https://img.shields.io/github/stars/elixir-lotus/lotus?style=social&color=white)](https://github.com/elixir-lotus/lotus/stargazers) | **Elixir library for building analytics features programmatically—not a BI UI.** Read-only query execution with three-level visibility (schema, table, column) and `:omit`/`:mask`/`:error` policies . Middleware hooks for auditing and per-tenant rewriting. AI query generation via BYOK and an MCP server. **Best for Elixir teams embedding query logic into their own product** rather than adopting a full BI platform . |
| **[DataClarity Unlimited Analytics](https://sourceforge.net/software/embedded-analytics/saas/)** | — | **Free modern embeddable analytics platform** with 80 visualizations, geospatial maps, drill-down, and real-time analysis. APIs, flexible embedding, multi-tenancy, row-level security, and SSO. **Starting price: FREE** . **Best for teams wanting a free commercial-grade embedding layer** without self-hosting a Superset stack . |

**Frameworks for building custom systems**: Choose **Apache Superset** for full BI depth with zero licensing and iframe/SDK/API embedding , **Metabase** for fastest internal reporting (budget Pro for embedding) , **Cube** for a semantic layer beneath your own UI , and **Helical Insight** for embedding plus pixel-perfect reporting in one free package —all without per-viewer pricing that compounds as your customer base grows.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Embedded analytics platforms handle customer data and must enforce **row-level security, per-tenant authentication, and audit logging**—a single RLS misconfiguration can leak one tenant's data to another . **Never embed production credentials in client-side code.**
- **Pricing models in this category are a minefield.** **Looker and Tableau** charge per-viewer fees that scale with every customer who sees a chart—real embedded deployments reach **$200K–$300K+/year** . **Power BI Embedded** avoids per-viewer costs via capacity, but requires Microsoft ecosystem commitment and report builders still pay Pro licenses . **Domo Everywhere's credit-based model** makes forecasting "notoriously hard" . **Open-source has different trade-offs**: Superset is free but requires engineering for theming and multi-tenancy ; Metabase's **embedding is gated behind Pro** despite the free core ; Cube provides a semantic layer, not a UI . **Validate RLS implementation, tenant isolation, and total cost of ownership** (including infrastructure and engineering time) before committing.

---

**Made for SaaS product teams, data engineers, and developers building white-label analytics.**  
Let's make embedded business intelligence more open, tenant-safe, and cost-predictable.
