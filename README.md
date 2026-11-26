<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img alt="Pedro Kenzo — I build AI agents, WhatsApp automations and security tooling for LLM apps." src="assets/banner-light.svg" width="100%">
</picture>

<p>
  <a href="https://www.linkedin.com/in/pedro-kenzo-sales-kishi-bb4897213/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Pedro_Kenzo-000?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="mailto:pedrokishi@gmail.com"><img alt="Email" src="https://img.shields.io/badge/pedrokishi@gmail.com-e4002b?style=flat-square&logo=gmail&logoColor=white"></a>
  <!-- PORTFOLIO: depois de publicar o site no Netlify, troque o link abaixo e apague este comentário -->
  <!-- <a href="https://SEU-SITE.netlify.app"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-000?style=flat-square&logo=googlechrome&logoColor=white"></a> -->
</p>

Independent developer in Porto Velho, Brazil, and Computer Engineering student at UniSapiens. I ship backends, AI agents and automations for real businesses — engineering, solar energy, healthcare and service companies — and I build my own products on the side.

## What I build

<table>
<tr>
<td width="33%" valign="top">

**AI agents & WhatsApp bots**

LLM assistants that answer customers, open tickets and triage high-volume inboxes over the WhatsApp API.

</td>
<td width="33%" valign="top">

**Process automation**

n8n workflows, dashboards and web systems that replace spreadsheets, copy-paste and manual follow-up.

</td>
<td width="33%" valign="top">

**LLM security**

Red-team tooling that proves whether an AI app leaks its prompt, its secrets or its tools.

</td>
</tr>
<tr>
<td colspan="3" valign="top">

**Data & BI** — Power BI dashboards, DAX and SQL that turn sales data into decisions: margin leaks, seasonality, customer concentration.

</td>
</tr>
</table>

## Featured: [agentsec](https://github.com/Kenzokishi/agentsec)

Red-team scanner for LLM apps, AI agents and MCP servers. It fires real attacks — prompt injection, system-prompt leakage, secret exfiltration, tool abuse — maps every finding to the [OWASP Top 10 for LLM Applications](https://genai.owasp.org/llm-top-10/) and can fail a CI build when the score drops. Runs with zero API keys against a built-in vulnerable agent:

<a href="https://github.com/Kenzokishi/agentsec"><img alt="agentsec scanning its built-in vulnerable demo agent: 4 vulnerabilities, score 0/100" src="assets/agentsec-demo.svg" width="100%"></a>

`TypeScript` `Node 20` `GitHub Actions` `OWASP LLM Top 10`

## Data analysis: [analise-vendas-powerbi](https://github.com/Kenzokishi/analise-vendas-powerbi)

End-to-end sales analysis for a (fictional) building-materials distributor with 6 stores in Rondônia: star-schema model, DAX measures with time intelligence and ABC curve, SQL with window functions, and a Power BI report versioned as a PBIP project. Finding: revenue grew 19% but margin stayed flat at 20.4% because steel discounts doubled.

<a href="https://github.com/Kenzokishi/analise-vendas-powerbi"><img alt="Monthly revenue 2024 vs 2025, peaking in the dry season" src="https://raw.githubusercontent.com/Kenzokishi/analise-vendas-powerbi/main/docs/sazonalidade.svg" width="100%"></a>

`Power BI` `DAX` `SQL` `Python` `Star schema`

## Built for real clients

Client code stays private; these are the problems and what I shipped.

| Project | What it does | Stack | Status |
| --- | --- | --- | --- |
| **WhatsApp ticket desk** | Around 50 registered companies open support tickets over WhatsApp; the bot identifies each one by code or CNPJ and logs the request. | n8n, WAHA, MySQL, Docker | In progress |
| **Inbox triage for a construction-company director** | Filters a WhatsApp Business inbox that gets 5–20 messages a minute: flags urgent ones, sends scheduled digests, suggests meeting slots. | n8n, WhatsApp Cloud API, LLM | In progress |
| **EuroAdega** | Online store for a liquor shop with a stock and finance panel; the storefront only lists what is actually in stock. | Web app | In progress |
| **Resale tracker** | Sales, stock and trade-in control for a PC-parts reseller, replacing a notebook and a spreadsheet. | Web app, Netlify | In use |
| **[Studio F7](https://github.com/Kenzokishi/studio-f7-site)** | Site for a video and motion-design studio with a client panel to manage portfolio, brands and photos without a developer. | React, TypeScript, Supabase | Delivered |
| **Guttoneres Engenharia** | Institutional site for a civil-engineering company in Porto Velho: service pages and a compliance page. | WordPress, HTML/CSS | [Live](https://guttoneres.com.br) |

## Own products

| Project | What it does | Status |
| --- | --- | --- |
| **Vesálio** | 3D human-anatomy atlas for medical students, built around practical-exam drills. | In development |
| **[Atende AI](https://github.com/Kenzokishi/atende-ai-site)** | Landing page for my WhatsApp AI-assistant service, with a chat playground and an ROI calculator (Next.js). | Code public |
| **Balão Bomba** | Interactive game that runs by itself during TikTok LIVEs and reacts to the audience through TikFinity. | Live on Netlify |

## Stack

![Python](https://img.shields.io/badge/Python-000?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-000?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-000?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-000?style=flat-square&logo=supabase&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-000?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=nextdotjs&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-000?style=flat-square&logo=n8n&logoColor=white)
![Evolution API](https://img.shields.io/badge/Evolution_API-000?style=flat-square&logo=whatsapp&logoColor=white)
![LLM APIs](https://img.shields.io/badge/LLM_APIs-000?style=flat-square&logo=openai&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-000?style=flat-square&logo=powerbi&logoColor=white)
![Power Automate](https://img.shields.io/badge/Power_Automate-000?style=flat-square&logo=powerautomate&logoColor=white)
![Git](https://img.shields.io/badge/Git-000?style=flat-square&logo=git&logoColor=white)

**Now learning:** FastAPI in production, Docker, CI/CD, RAG and vector databases, AWS.

<details>
<summary><b>Certifications</b></summary>

- Python Impressionador (Intermediate) — Hashtag Treinamentos, 2026
- Supabase Impressionador — Hashtag Treinamentos, 2026
- AI APIs — Hashtag Treinamentos, 2026
- Artificial Intelligence Impressionador — Hashtag Treinamentos, 2026

</details>

## Contact

Open to developer and data analyst roles: AI, automation, backend and BI. Reach me on [LinkedIn](https://www.linkedin.com/in/pedro-kenzo-sales-kishi-bb4897213/) or at **pedrokishi@gmail.com**.
