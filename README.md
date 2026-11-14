# Awesome-Embedded-Business-Intelligence-Analytics

# Top Embedded Business Intelligence & Analytics Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on White-Label Dashboards, Multi-Tenant RLS & Self-Hosted Embedding*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Embedded Business Intelligence & Analytics**. These tools let you drop dashboards, charts, and self-service exploration directly into your own product—covering everything from per-viewer SaaS SDKs to open-source engines you self-host with zero per-seat licensing.

**Examples** include Looker Embedded, Power BI Embedded, Tableau Embedded, Sisense, GoodData, Domo Everywhere, Zoho Analytics, Apache Superset, Metabase, and Cube (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted embedded BI, open-source semantic layers, and community-driven white-label analytics—ideal for SaaS builders seeking to avoid per-viewer pricing that scales against revenue. The open-source landscape is genuinely functional: **Apache Superset** provides a zero-license-fee BI engine you can embed and white-label , **Metabase** offers the fastest path to a working dashboard but gates embedding behind its Pro plan , and **Cube** delivers a semantic layer and caching API that sits beneath your own UI .

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Looker Embedded (Google Cloud)](https://looker.com/)** | Governed semantic modeling (LookML) with embed SDKs. **Base platform ~$60K/yr; viewers ~$400/yr each; developers ~$1,665/yr**. Real embedded deployments typically reach **$200K–$300K+ annually** . | Quote-only (base ~$60K/yr + per-viewer fees) | No free tier; trial via Google Cloud sales |
| **[Power BI Embedded (Microsoft)](https://azure.microsoft.com/en-us/pricing/details/power-bi-embedded/)** | Capacity-based embedding via **Microsoft Fabric F-SKUs**. **F2 starts at $262/mo PAYG (~$156/mo reserved)**. **App-Owns-Data** means end users need no individual licenses—capacity covers them. Report builders still need Power BI Pro at **$14/mo** . | F2: **$262/mo PAYG** (~$156 reserved) | No free tier for production; Fabric trial available |
| **[Tableau Embedded (Salesforce)](https://www.tableau.com/)** | Deep visualization with OEM embedding. **Custom-quoted; reportedly $60K–$150K/yr year-one floor**; per-viewer ~$420/yr (OEM SKU not publicly priced) . | Quote-only (OEM floor ~$60K–$150K/yr) | No free tier; demo via sales |
| **[Sisense](https://www.sisense.com/)** | Code-first embedding toolkit with strong multi-tenant isolation. **Quote-only; ~$40K–$90K in year one**. Add-on plans for AI and natural-language questions . | Quote-only (~$40K–$90K year one) | No free tier; demo via sales |
| **[GoodData](https://www.gooddata.com/)** | Headless BI with React/Python SDKs and white-label support. **Workspace-based pricing starting $1,500/mo with unlimited users** . | **$1,500/mo** (workspace, unlimited users) | No free tier; demo via sales |
| **[Domo Everywhere](https://www.domo.com/)** | Credit-based embedding where every customer view/filter burns credits. **~$3,000/mo starting**. Forecasting cost is notoriously hard . | **~$3,000/mo** (credit-based) | No free tier; demo via sales |
| **[Zoho Analytics](https://www.zoho.com/analytics/)** | Full white-label embedding via iframe, SDK, and headless integration. **Published from $145/month**—the lowest commercial entry point for white-label reporting . | **$145/mo** (published) | No free tier for white-label; trial available |
| **[Luzmo](https://www.luzmo.com/)** | Usage-based embedding with ready-made components for smaller SaaS teams. **Starter from ~€495/mo** . | Starter: **~€495/mo** | No free tier; trial via sales |
| **[ThoughtSpot Everywhere](https://www.thoughtspot.com/)** | Search-driven embedded analytics with AI. **$25–$50/user/month; embedded use quoted** . | $25–$50/user/mo (embedded quoted) | No free tier; demo via sales |
| **[Qrvey](https://www.qrvey.com/)** | Full-stack embedded analytics built for multi-tenant SaaS with a built-in data layer. **Flat-rate pricing** keeps costs stable as users grow . | Quote-only (flat-rate) | No free tier; demo via sales |

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
