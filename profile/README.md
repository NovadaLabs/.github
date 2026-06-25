<!-- agent-metadata
name: NovadaLabs
description: Web data and proxy infrastructure platform for AI agents and developers
primary-package: novada-mcp
hosted-endpoint: https://mcp.novada.com/YOUR_KEY/mcp
install: npx -y novada-mcp
env-required: NOVADA_API_KEY
tools: novada_search, novada_research, novada_verify, novada_ai_monitor, novada_monitor, novada_discover, novada_extract, novada_scrape, novada_unblock, novada_crawl, novada_map, novada_scraper_submit, novada_scraper_status, novada_scraper_result, novada_browser, novada_browser_flow, novada_proxy, novada_proxy_residential, novada_proxy_isp, novada_proxy_datacenter, novada_proxy_mobile, novada_proxy_static, novada_proxy_dedicated, novada_wallet_balance, novada_account_summary, novada_health
integrations: Claude Desktop, Claude Code, Cursor, OpenAI Agents SDK, LangChain, LlamaIndex, CrewAI, n8n, Windsurf, Cline, Codex CLI
categories: web-data-platform, proxy-network, mcp-server, web-scraping, search, browser-automation
-->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/NovadaLabs/.github/main/profile/logo-dark.png">
    <img src="https://raw.githubusercontent.com/NovadaLabs/.github/main/profile/logo-light.png" alt="Novada" height="48">
  </picture>

  <h3>Web data & proxy infrastructure for AI agents</h3>
  <p>Search, scrape, crawl, proxy, monitor, and browse — 35 tools, 6 proxy types, 129 structured platforms.<br>
  Built on our own network of 100M+ residential IPs across 195 countries. One API key for all of it.</p>

  <a href="https://www.novada.com">
    <img src="https://img.shields.io/badge/Get_Started-6C40E2?style=for-the-badge" alt="Get Started">
  </a>
  <a href="https://developer.novada.com">
    <img src="https://img.shields.io/badge/Documentation-0F0C1E?style=for-the-badge" alt="Documentation">
  </a>
  <a href="https://dashboard.novada.com">
    <img src="https://img.shields.io/badge/Dashboard-6C40E2?style=for-the-badge" alt="Dashboard">
  </a>

  <br><br>

  <a href="https://www.npmjs.com/package/novada-mcp"><img src="https://img.shields.io/npm/v/novada-mcp?color=6C40E2&label=novada-mcp" alt="npm version"></a>
  <a href="https://www.npmjs.com/package/novada-mcp"><img src="https://img.shields.io/npm/dm/novada-mcp?color=6C40E2" alt="npm downloads"></a>
  <a href="https://github.com/NovadaLabs/novada-mcp/blob/main/LICENSE"><img src="https://img.shields.io/npm/l/novada-mcp" alt="License"></a>
  <a href="https://x.com/Novada_Proxy"><img src="https://img.shields.io/twitter/follow/Novada_Proxy?style=social" alt="Follow on X"></a>
</div>

## What Novada offers

| Product | What it does |
| --- | --- |
| **Search & research** | 5-engine web search, SERP data for SEO and competitive intel, multi-source deep research, and live fact-checking. |
| **Scraping & extraction** | Any URL → clean markdown or structured JSON. 129 structured platforms (Amazon, LinkedIn, TikTok, YouTube, Zillow…). Async pipeline for high-volume and slow-rendering targets. |
| **Proxy network** | 100M+ IPs across 195 countries. 6 types: residential, ISP, datacenter, mobile, static, dedicated. We own the network — no reseller markup. |
| **Browser & unblock** | Anti-bot bypass (Cloudflare, DataDome, Kasada). JS rendering, session-persistent CDP browser, multi-step automation flows. |
| **Monitor & verify** | Field-level page change detection. Claim fact-checking with confidence scores. |
| **AI brand monitoring** | Track how ChatGPT, Perplexity, Claude, Gemini, and Grok describe your brand — mentions, sentiment, and positioning. |

One API key. One output format. One vendor for the whole web-data surface.

## Quick Start

Get your key at [novada.com](https://www.novada.com) — free tier, 1,000 calls/month, no credit card.

**Option A — Hosted MCP (zero install, 26 tools):**

Paste your key into the URL. Works in any MCP client in 30 seconds:

```json
{
  "mcpServers": {
    "novada": {
      "url": "https://mcp.novada.com/your_key/mcp"
    }
  }
}
```

```bash
# Claude Code
claude mcp add --transport http novada https://mcp.novada.com/your_key/mcp
```

**Option B — Local npm (all 35 tools, including browser automation):**

```bash
# Claude Code
claude mcp add novada -e NOVADA_API_KEY=your_key -- npx -y novada-mcp
```

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

## MCP Tools

35 tools across 8 categories — one API key unlocks all of them.

| Tool | What it does |
| --- | --- |
| **Search & research** | |
| `novada_search` | 5-engine web search with optional inline extraction of top results. |
| `novada_research` | Multi-source cited research — fan-out search → extract → synthesized report. |
| `novada_verify` | Fact-check a claim via 3 parallel search angles. Returns verdict + confidence. |
| `novada_ai_monitor` | How ChatGPT, Perplexity, Grok, Claude, Gemini mention a brand — mentions, sentiment, positioning. |
| `novada_monitor` | Field-level page change detection between calls. |
| `novada_discover` | Find URLs matching a pattern, topic, or site structure. |
| **Extract & scrape** | |
| `novada_extract` | Any URL → clean markdown or structured JSON. Auto anti-bot escalation. |
| `novada_scrape` | 129 structured platforms (Amazon, Reddit, LinkedIn, TikTok…) → structured records. |
| `novada_unblock` | JS rendering + anti-bot bypass for Cloudflare/DataDome/Kasada-protected pages. |
| `novada_scraper_submit` | Submit a batch scrape job asynchronously — returns `task_id`. |
| `novada_scraper_status` | Poll async job status by `task_id`. |
| `novada_scraper_result` | Fetch completed async job result. |
| **Crawl & map** | |
| `novada_crawl` | BFS/DFS walk up to 20 pages — extract content from each. |
| `novada_map` | Return a site's URL structure without reading content. |
| **Browser** | |
| `novada_browser` | Session-persistent CDP cloud browser — navigate, click, type, screenshot. _(local npm only)_ |
| `novada_browser_flow` | Multi-step browser automation flow. _(local npm only)_ |
| **Proxy** | |
| `novada_proxy` | Universal proxy credential router — pick type, country, session. |
| `novada_proxy_residential` | 100M+ home ISP IPs — geo-sensitive and heavily protected targets. |
| `novada_proxy_isp` | ISP-assigned static IPs — residential trust, datacenter stability. |
| `novada_proxy_datacenter` | Fastest and cheapest — bulk crawls and speed-sensitive jobs. |
| `novada_proxy_mobile` | 4G/5G mobile IPs — mobile-first platforms and apps. |
| `novada_proxy_static` | Static ISP IP — consistent session identity across calls. |
| `novada_proxy_dedicated` | Exclusive datacenter IP — not shared with any other user. |
| **Account & ops** | |
| `novada_wallet_balance` | Master wallet credit balance. |
| `novada_account_summary` | One-shot: wallet + per-product plan balances + recent spend. |
| `novada_traffic_daily` | Daily traffic consumption across proxy products. |
| `novada_health` | Which Novada API products are active on your key. |

Full tool reference at **[developer.novada.com](https://developer.novada.com)**.

## Built agent-first

- **Agent-first by design.** A native MCP server with structured outputs across a tight tool surface — agents pick the right tool the first time and spend tokens on the task, not the plumbing.
- **Everything in one place.** Search, scrape, crawl, proxy, monitor, and browse — one install, no stitching vendors together.
- **We own the network.** 100M+ residential IPs across 195 countries, built and run by us — higher success rates, lower cost, no reseller markup.
- **Sees what others miss.** Track how AI models describe your brand, detect page changes field by field, and fact-check claims against live sources.
- **In service of the business.** The point isn't the tools — it's the people behind the agents shipping faster and making better calls. Novada handles the web busywork so they don't have to.

## Which package?

| If you need… | Use |
| --- | --- |
| Everything — hosted, zero install (recommended) | `https://mcp.novada.com/your_key/mcp` |
| Everything — local, all 35 tools + browser | `npx novada-mcp` |
| Search, scrape, crawl, research only | `npx novada-search` |
| Proxy credentials inside your agent only | `npx novada-proxy-mcp` |

## Access layers

Novada is a hosted platform — start at **[novada.com](https://www.novada.com)** with one API key. Full docs at **[developer.novada.com](https://developer.novada.com)**.

### Hosted MCP
<a href="https://mcp.novada.com">
  <img align="right" src="https://img.shields.io/badge/Zero_Install-6C40E2?style=for-the-badge" alt="Zero Install">
</a>

**[mcp.novada.com](https://mcp.novada.com)** — remote Streamable-HTTP endpoint, 26 tools, no npm
Paste one URL into your MCP client and you're live. Always up to date — tools update server-side, no client redeploy needed.

```
https://mcp.novada.com/your_key/mcp
```

<br clear="right"/>

### Unified MCP (npm)
<a href="https://github.com/NovadaLabs/novada-mcp">
  <img align="right" src="https://img.shields.io/github/stars/NovadaLabs/novada-mcp?style=for-the-badge&logo=github&logoColor=white&label=Stars&color=6C40E2" alt="Stars">
</a>

**[novada-mcp](https://github.com/NovadaLabs/novada-mcp)** — all 35 tools including browser automation
Local install via npm. The full surface — including CDP browser and browser flow — that requires native deps.

```bash
npx novada-mcp
```

<br clear="right"/>

### Search & Scraping MCP
<a href="https://github.com/NovadaLabs/novada-search-mcp">
  <img align="right" src="https://img.shields.io/github/stars/NovadaLabs/novada-search-mcp?style=for-the-badge&logo=github&logoColor=white&label=Stars&color=6C40E2" alt="Stars">
</a>

**[novada-search-mcp](https://github.com/NovadaLabs/novada-search-mcp)** — search, extract, crawl, research
Focused install when you only need the web-data side. On npm as `novada-search`.

<br clear="right"/>

### Proxy MCP
<a href="https://github.com/NovadaLabs/novada-proxy">
  <img align="right" src="https://img.shields.io/github/stars/NovadaLabs/novada-proxy?style=for-the-badge&logo=github&logoColor=white&label=Stars&color=6C40E2" alt="Stars">
</a>

**[novada-proxy](https://github.com/NovadaLabs/novada-proxy)** — proxy credentials for AI agents
6 proxy types from inside your agent. On npm as `novada-proxy-mcp`.

<br clear="right"/>

## SDKs & official libraries

First-party clients, maintained by Novada.

- **[novada-python](https://github.com/NovadaLabs/novada-python)** — official Python client for the Novada API.
- **[novada-go](https://github.com/NovadaLabs/novada-go)** — official Go client for the Novada API.

## Works with

Novada works with every major AI agent framework and IDE via the hosted MCP endpoint or local npm package.

| Tool | How |
| --- | --- |
| Claude Desktop | MCP config — paste hosted URL or local stdio config |
| Claude Code | `claude mcp add --transport http novada https://mcp.novada.com/your_key/mcp` |
| Cursor / Windsurf / Cline | MCP config — paste hosted URL |
| OpenAI Agents SDK | `MCPServerHTTP("https://mcp.novada.com/your_key/mcp")` |
| LangChain | `langchain-mcp-adapters` → hosted URL |
| LlamaIndex | `llama-index-tools-mcp` → hosted URL |
| CrewAI | `MCPServerAdapter` → hosted URL |
| n8n | MCP node → hosted URL |
| Codex CLI | `--mcp-server https://mcp.novada.com/your_key/mcp` |

Full integration guides at **[developer.novada.com](https://developer.novada.com)**.

## Integrations & extensions

- **[novada-proxy-extension](https://github.com/NovadaLabs/novada-proxy-extension)** — route browser traffic through Novada's proxy network (Chrome, Manifest V3).
- **[novada-scraper-skill](https://github.com/NovadaLabs/novada-scraper-skill)** — agent skill: turn any website into structured data.
- **[novada-webunblocker-skill](https://github.com/NovadaLabs/novada-webunblocker-skill)** — agent skill: reach sites that fight back.

_Coming soon: deeper LangChain · CrewAI · n8n · Zapier integrations — and more._

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
  <strong>Web data & proxy infrastructure — in service of the people behind the agents.</strong><br>
  <a href="https://www.novada.com">Get your API key</a> and start in minutes.
  <br><br>
  <a href="https://mcp.novada.com">Hosted MCP</a> ·
  <a href="https://github.com/NovadaLabs/novada-mcp">Star the flagship</a> ·
  <a href="https://developer.novada.com">Read the docs</a>
</div>
