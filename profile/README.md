<div align="center">
  <img src="https://raw.githubusercontent.com/NovadaLabs/.github/main/profile/logo.png" alt="Novada" height="56">

  <h3>Agent-first web data infrastructure</h3>
  <p>One MCP server for everything an AI agent needs from the web — search, scrape, crawl, proxy, monitor, and more.<br>
  Built so agents do the web busywork and the people behind them ship faster and make better calls.<br>
  Powered by our own network of 100M+ residential IPs across 195 countries.</p>

  <a href="https://www.novada.com">
    <img src="https://img.shields.io/badge/Get_Started-6C40E2?style=for-the-badge" alt="Get Started">
  </a>
  <a href="https://developer.novada.com">
    <img src="https://img.shields.io/badge/Documentation-0F0C1E?style=for-the-badge" alt="Documentation">
  </a>
  <a href="https://www.npmjs.com/package/novada-mcp">
    <img src="https://img.shields.io/badge/npx_novada--mcp-CB3837?style=for-the-badge&logo=npm&logoColor=white" alt="npm">
  </a>

  <br><br>

  <a href="https://www.npmjs.com/package/novada-mcp"><img src="https://img.shields.io/npm/v/novada-mcp?color=6C40E2&label=novada-mcp" alt="npm version"></a>
  <a href="https://www.npmjs.com/package/novada-mcp"><img src="https://img.shields.io/npm/dm/novada-mcp?color=6C40E2" alt="npm downloads"></a>
  <a href="https://github.com/NovadaLabs/novada-mcp/blob/main/LICENSE"><img src="https://img.shields.io/npm/l/novada-mcp" alt="License"></a>
  <a href="https://x.com/Novada_Proxy"><img src="https://img.shields.io/twitter/follow/Novada_Proxy?style=social" alt="Follow on X"></a>
</div>

## What Novada does

| Capability | What your agent can do |
| --- | --- |
| **Search & research** | Search across 5 engines, run cited multi-source research, and fact-check claims. |
| **Extract & scrape** | Any URL → clean Markdown or JSON. 129 structured platforms (Amazon, LinkedIn, TikTok, YouTube…). Batch and async jobs. |
| **Crawl & map** | Walk a whole site, discover its structure, and build a corpus. |
| **Monitor** | Detect when a page changes (field-level diffs) — and how AI models describe your brand. |
| **Proxy network** | Residential, ISP, datacenter, mobile, static & dedicated IPs — 100M+ pool, 195 countries. |
| **Unblock & browse** | Anti-bot bypass, JS rendering, geo-routing, and a session-persistent cloud browser. |
| **Account & ops** | Wallet, usage, and per-product balances — agents can watch their own spend. |

One API key. One output format. One vendor for the whole web-data surface.

## Built agent-first

- **Agent-first by design.** A native MCP server with prompts, reference resources, and structured outputs across a tight tool surface — agents pick the right tool the first time and spend tokens on the task, not the plumbing.
- **Everything in one place.** Search, scrape, crawl, proxy, monitor, and browse — one install, no stitching vendors together.
- **We own the network.** 100M+ residential IPs across 195 countries, built and run by us — higher success rates, lower cost, no reseller markup.
- **Sees what others miss.** Detect when a page changes, and track how AI models — ChatGPT, Perplexity, Claude, Gemini, Grok — describe your brand.
- **In service of the business.** The point isn't the tools — it's the people behind the agents shipping faster and making better calls. Novada handles the web busywork so they don't have to.

## Access layers

Novada is a hosted platform — start at **[novada.com](https://www.novada.com)** with one API key, then reach it however you build. Full docs at **[developer.novada.com](https://developer.novada.com)**.

### Unified MCP Server
<a href="https://github.com/NovadaLabs/novada-mcp">
  <img align="right" src="https://img.shields.io/github/stars/NovadaLabs/novada-mcp?style=for-the-badge&logo=github&logoColor=white&label=Stars&color=6C40E2" alt="Stars">
</a>

**[novada-mcp](https://github.com/NovadaLabs/novada-mcp)** — all web data in one install
Search, scrape, crawl, map, research, proxy, unblock, monitor, and browse — one MCP server, one API key. The flagship and the fastest way to start.

```bash
npx novada-mcp
```

<br clear="right"/>

### Search & Scraping MCP
<a href="https://github.com/NovadaLabs/novada-search-mcp">
  <img align="right" src="https://img.shields.io/github/stars/NovadaLabs/novada-search-mcp?style=for-the-badge&logo=github&logoColor=white&label=Stars&color=6C40E2" alt="Stars">
</a>

**[novada-search-mcp](https://github.com/NovadaLabs/novada-search-mcp)** — search, extract, crawl, research
The focused MCP when you only need the web-data side. On npm as `novada-search`.

<br clear="right"/>

### Proxy MCP
<a href="https://github.com/NovadaLabs/novada-proxy">
  <img align="right" src="https://img.shields.io/github/stars/NovadaLabs/novada-proxy?style=for-the-badge&logo=github&logoColor=white&label=Stars&color=6C40E2" alt="Stars">
</a>

**[novada-proxy](https://github.com/NovadaLabs/novada-proxy)** — residential proxy tools for AI agents
Bypass Cloudflare and anti-bot walls from inside your agent. On npm as `novada-proxy-mcp`.

<br clear="right"/>

## SDKs & official libraries

First-party clients, maintained by Novada.

- **[novada-python](https://github.com/NovadaLabs/novada-python)** — official Python client for the Novada API.
- **[novada-go](https://github.com/NovadaLabs/novada-go)** — official Go client for the Novada API.

## Integrations & extensions

- **[novada-proxy-extension](https://github.com/NovadaLabs/novada-proxy-extension)** — route browser traffic through Novada's proxy network (Chrome, Manifest V3).
- **[novada-scraper-skill](https://github.com/NovadaLabs/novada-scraper-skill)** — agent skill: turn any website into structured data.
- **[novada-webunblocker-skill](https://github.com/NovadaLabs/novada-webunblocker-skill)** — agent skill: reach sites that fight back.

_Coming soon: LangChain · CrewAI · n8n · Zapier._

## Connect

<div align="center">
  <a href="https://developer.novada.com">
    <img src="https://img.shields.io/badge/Documentation-6C40E2?style=for-the-badge&logo=book&logoColor=white" alt="Documentation">
  </a>
  <a href="https://discord.gg/DgmrpTs86c">
    <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord">
  </a>
  <a href="https://x.com/Novada_Proxy">
    <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X">
  </a>
  <a href="https://www.linkedin.com/company/novadalabs">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
</div>

<div align="center">
  <br>
  <strong>Agent-first web data — in service of the people behind the agents.</strong><br>
  <a href="https://www.novada.com">Get your API key</a> and start in minutes.
  <br><br>
  <a href="https://github.com/NovadaLabs/novada-mcp">Star the flagship</a> ·
  <a href="https://www.novada.com">Get an API key</a> ·
  <a href="https://developer.novada.com">Read the docs</a>
</div>
