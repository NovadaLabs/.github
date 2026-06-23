<!-- agent-metadata
name: NovadaLabs
primary-package: novada-mcp
install: npx -y novada-mcp
env-required: NOVADA_API_KEY
tools: novada_search, novada_research, novada_verify, novada_extract, novada_scrape, novada_crawl, novada_map, novada_discover, novada_monitor, novada_ai_monitor, novada_unblock, novada_browser, novada_browser_flow, novada_proxy, novada_wallet_balance, novada_account_summary, novada_health
categories: mcp-server, web-scraping, search, proxy, browser-automation
-->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/NovadaLabs/.github/main/profile/logo-dark.png">
    <img src="https://raw.githubusercontent.com/NovadaLabs/.github/main/profile/logo-light.png" alt="Novada" height="48">
  </picture>

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

## Quick Start

**One API key unlocks everything** — search, scrape, proxy, browser, monitor, and AI brand tracking.

**1. Get your API key** at [novada.com](https://www.novada.com) — copy your `NOVADA_API_KEY` from the dashboard.

**2. Add to your MCP client:**

**Claude Code** (one command):
```bash
claude mcp add novada -e NOVADA_API_KEY=your_key -- npx -y novada-mcp
```

**Claude Desktop · Cursor · VS Code · Windsurf** — paste into your MCP config:
```json
{
  "mcpServers": {
    "novada": {
      "command": "npx",
      "args": ["-y", "novada-mcp"],
      "env": { "NOVADA_API_KEY": "your_key" }
    }
  }
}
```

**3. Try it:**
```
novada_search({query: "latest AI news", num: 5})
novada_extract({url: "https://example.com"})
novada_research({question: "what is Novada?", depth: "deep"})
```

## Tools

| Tool | What it does |
| --- | --- |
| **Search & research** | |
| `novada_search` | Query across 5 engines, return ranked results. |
| `novada_research` | Multi-source cited research on any topic. |
| `novada_verify` | Fact-check a claim against live sources. |
| **Extract & scrape** | |
| `novada_extract` | Any URL → clean Markdown or structured JSON. |
| `novada_scrape` | 129 structured platforms (Amazon, LinkedIn, YouTube…). |
| `novada_scraper_submit` | Submit a batch scrape job asynchronously. |
| `novada_scraper_status` | Poll status of a submitted scrape job. |
| `novada_scraper_result` | Fetch results of a completed scrape job. |
| **Crawl & map** | |
| `novada_crawl` | Walk an entire site, collect every page. |
| `novada_map` | Return site structure as a URL tree. |
| `novada_discover` | Find URLs matching a pattern or topic. |
| **Monitor** | |
| `novada_monitor` | Detect field-level changes on any page. |
| `novada_ai_monitor` | Track how AI models describe a brand or topic. |
| **Unblock & browse** | |
| `novada_unblock` | Anti-bot bypass with JS rendering and geo-routing. |
| `novada_browser` | Session-persistent cloud browser, single action. |
| `novada_browser_flow` | Multi-step browser automation as a flow. |
| **Proxy** | |
| `novada_proxy` | Residential, ISP, datacenter, mobile, static, dedicated — 100M+ IPs, 195 countries. |
| **Account & ops** | |
| `novada_wallet_balance` | Current wallet credit balance. |
| `novada_account_summary` | Usage and per-product spend summary. |
| `novada_health` | Live API and service health status. |

One API key. One output format. One vendor for the whole web-data surface.

## Built agent-first

- **Agent-first by design.** A native MCP server with prompts, reference resources, and structured outputs across a tight tool surface — agents pick the right tool the first time and spend tokens on the task, not the plumbing.
- **Everything in one place.** Search, scrape, crawl, proxy, monitor, and browse — one install, no stitching vendors together.
- **We own the network.** 100M+ residential IPs across 195 countries, built and run by us — higher success rates, lower cost, no reseller markup.
- **Sees what others miss.** Detect when a page changes, and track how AI models — ChatGPT, Perplexity, Claude, Gemini, Grok — describe your brand.
- **In service of the business.** The point isn't the tools — it's the people behind the agents shipping faster and making better calls. Novada handles the web busywork so they don't have to.

## Which package?

| If you need… | Install |
| --- | --- |
| Everything (recommended) | `npx novada-mcp` |
| Search, scrape, crawl, research only | `npx novada-search` |
| Proxy credentials inside your agent only | `npx novada-proxy-mcp` |

Not sure? Use `novada-mcp` — it includes all tools and uses the same single API key.

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

_Coming soon: LangChain · CrewAI · n8n · Zapier — and more._

**Building with Novada?** We're happy to integrate with any agent framework, MCP client, or automation platform — if you're building it, we want to support it. [Open an issue](https://github.com/NovadaLabs/novada-mcp/issues) or reach us at [novada.com](https://www.novada.com).

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
