<div align="center">

# Danial Syed

**Senior Full-Stack Engineer** · AI and geospatial SaaS · Lahore, Pakistan

[Portfolio](https://danial-syed.netlify.app) · [LinkedIn](https://www.linkedin.com/in/danial-syed-7897174b/) · [Email](mailto:danialsyed66@gmail.com) · [Work GitHub (@danialsyed6)](https://github.com/danialsyed6)

</div>

I'm a senior full-stack engineer at [MergeStack](https://mergestack.com) in Lahore. I build SaaS products for clients in oil & gas, insurance, freight logistics, retail and e-commerce, mostly ones with a lot of maps, data or AI in them.

Since 2022 I've been the top individual contributor on 19 of the 21 client repositories I've worked in at MergeStack, and the founding engineer on two of the platforms below, Sense and Pedant. I joined as an associate engineer and now lead builds and mentor the engineers on them.

**What I work on**

- **Maps and geospatial data**: Mapbox GL JS, deck.gl, PostGIS and ElasticSearch for wells, parcels, stores and territories.
- **AI features**: document extraction with a human review step, RAG assistants, access control for agents, and usage-based billing for AI.
- **Payments and permissions**: field- and row-level access control, payouts that are safe to retry, signed webhooks, and statements reconciled to the cent.
- **Data-heavy apps**: virtualised grids, 250k-row imports, background jobs and bulk pipelines.
- **Working with AI coding agents**: planner and gate-keeper agents, parallel worktrees, and CI checks on everything they write.

## Selected work

> Client code is private and belongs to the clients. Each project links to a case study with screenshots on my portfolio.
> **Where the commits are:** client work is in private organisation repos on my work account, [@danialsyed6](https://github.com/danialsyed6). Personal products are private repos on this account.

<table>
<tr>
<td width="34%"><a href="https://danial-syed.netlify.app/projects/m1neral"><img src="https://danial-syed.netlify.app/projects/m1neral/cover.webp" alt="M1neral" /></a></td>
<td>

### [M1neral](https://danial-syed.netlify.app/projects/m1neral)
**Oil & gas mineral-rights platform for royalty audits, mapping and deals.** Owners load acreage, wells, interests and check statements, then get a live map, reconciled revenue and a deal pipeline. Underpayments show up in dollars.

**My part:** lead author of the Mapbox GL + deck.gl map and its drawing tools, the virtualised data grid, the Azure Durable Functions import engine, and the review screen for AI-extracted agreements.

`React` `GraphQL` `Azure Functions` `MongoDB` `ElasticSearch` `Mapbox GL` `deck.gl` · <sub>@danialsyed6 · private</sub>

</td>
</tr>
<tr>
<td><a href="https://danial-syed.netlify.app/projects/pedant"><img src="https://danial-syed.netlify.app/projects/pedant/cover.webp" alt="Pedant" /></a></td>
<td>

### [Pedant](https://danial-syed.netlify.app/projects/pedant)
**Operations and commission platform for a US freight brokerage that ran on 1,000+ Excel sheets.** Loads, carriers, sales teams and commission rules in one multi-tenant platform. 250k-row imports are checked before anything is saved, and can be undone later.

**My part:** founding engineer and lead. Wrote the first commit of the API and the web app. Built the import pipeline (Parquet + DuckDB), the commission rules language, the settlement-statement bridge and the AWS infrastructure.

`TypeScript` `React` `NestJS` `MongoDB` `BullMQ` `DuckDB` `AWS CloudFormation` · <sub>@danialsyed6 · private</sub>

</td>
</tr>
<tr>
<td><a href="https://danial-syed.netlify.app/projects/sense"><img src="https://danial-syed.netlify.app/projects/sense/cover.webp" alt="Sense" /></a></td>
<td>

### [Sense](https://danial-syed.netlify.app/projects/sense)
**AI platform that turns oil & gas documents and data into workflows.** Leases, revenue statements and well data become searchable, mappable records that move through approvals. AI extracts the line items, and agents answer questions over the data.

**My part:** founding engineer (first commit, monorepo set-up). Sole author of the authorization engine (access down to fields and rows) and of API-key and machine-to-machine auth. Built the AI document-extraction pipeline and the credit billing for AI usage.

`TypeScript` `React` `NestJS` `Python` `OpenAI` `LangChain` `Redis` `Auth0` · <sub>@danialsyed6 · private</sub>

</td>
</tr>
<tr>
<td><a href="https://danial-syed.netlify.app/projects/centinel"><img src="https://danial-syed.netlify.app/projects/centinel/cover.webp" alt="Centinel" /></a></td>
<td>

### [Centinel](https://danial-syed.netlify.app/projects/centinel)
**Parametric insurance that pays businesses automatically when the power goes out.** Partners can white-label quoting, sales and claims through an API. It launched to production in October 2026.

**My part:** sole author of the Partner API (hashed keys, signed webhooks with secret rotation, idempotent purchases and payouts). Led the pre-launch money and security review. Took a hot query from 231 ms to 1.8 ms.

`Python` `Django REST` `PostgreSQL` `React` `Stripe` `AWS` · <sub>@danialsyed6 · private</sub>

</td>
</tr>
<tr>
<td><a href="https://danial-syed.netlify.app/projects/zen-leaf-muv"><img src="https://danial-syed.netlify.app/projects/zen-leaf-muv/cover.webp" alt="Zen Leaf and MÜV" /></a></td>
<td>

### [Zen Leaf & MÜV](https://danial-syed.netlify.app/projects/zen-leaf-muv)
**Dispensary websites for a multi-state cannabis brand, from one codebase.** 13 states, a map-based store locator, live medical and recreational menus, and per-state compliance rules.

**My part:** built the setup that ships both brands from one codebase, the store-hours and location logic, and the menu flow. Later started and led the Next.js App Router migration.

`Next.js` `React` `Headless WordPress` `GraphQL` `Tailwind` `Mapbox` · <sub>private</sub>

</td>
</tr>
<tr>
<td><a href="https://danial-syed.netlify.app/projects/perigon-ai"><img src="https://danial-syed.netlify.app/projects/perigon-ai/cover.webp" alt="Perigon AI" /></a></td>
<td>

### [Perigon AI](https://danial-syed.netlify.app/projects/perigon-ai)
**Location intelligence for retail: stores, territories and demand on one map.** Ops teams upload large datasets and build their own map layers without engineering.

**My part:** top contributor across all four services. Moved bulk imports onto on-demand AWS ECS tasks, built viewport-bounded PostGIS queries and a no-code deck.gl layer builder, and wrote most of the RBAC service.

`React` `deck.gl` `Google Maps` `NestJS` `PostGIS` `AWS ECS` · <sub>@danialsyed6 · private</sub>

</td>
</tr>
<tr>
<td><a href="https://danial-syed.netlify.app/projects/sales-rep-ai"><img src="https://danial-syed.netlify.app/projects/sales-rep-ai/cover.webp" alt="Sales Rep AI" /></a></td>
<td>

### [Sales Rep AI](https://danial-syed.netlify.app/projects/sales-rep-ai)
**AI sales coach that answers from a company's own training material.** New reps get onboarded without booking time with senior reps. It's sold as a subscription.

**My part:** built most of it: the RAG pipeline, FastAPI and Chainlit app, Stripe subscriptions on LLM usage, and OpenTelemetry tracing.

`Python` `FastAPI` `Chainlit` `OpenAI` `Pinecone` `Stripe` · <sub>@danialsyed6 · private</sub>

</td>
</tr>
<tr>
<td><a href="https://danial-syed.netlify.app/projects/my-expenses"><img src="https://danial-syed.netlify.app/projects/my-expenses/cover.webp" alt="my-expenses" /></a></td>
<td>

### [my-expenses](https://danial-syed.netlify.app/projects/my-expenses) · personal product
**Personal finance and investing app for Pakistani banks, markets and tax rules.** Bank alerts become transactions. Portfolios get FIFO cost basis, XIRR and risk metrics. Capital-gains tax, Zakat and Khums are computed from configurable rules.

**My part:** sole owner of the product, domain model and architecture. Built with a multi-agent Claude Code workflow I designed, including a dedicated money-review agent.

`Next.js 16` `React 19` `TypeScript` `MongoDB` `Vitest` · <sub>this account · private</sub>

</td>
</tr>
</table>

## Tools I use most

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?logo=graphql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL%20%2B%20PostGIS-4169E1?logo=postgresql&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?logo=elasticsearch&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![Mapbox](https://img.shields.io/badge/Mapbox%20GL-000000?logo=mapbox&logoColor=white)
![deck.gl](https://img.shields.io/badge/deck.gl-2D3748)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?logo=stripe&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-0F172A?logo=tailwindcss&logoColor=38BDF8)

## Get in touch

I'm open to full-time roles and to freelance or contract work, especially on products with a lot of maps, data or AI in them.
The quickest way to reach me is [email](mailto:danialsyed66@gmail.com) or [LinkedIn](https://www.linkedin.com/in/danial-syed-7897174b/).
