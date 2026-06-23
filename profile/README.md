<div align="center">
  <img src="https://raw.githubusercontent.com/NovadaLabs/.github/main/profile/logo.png" alt="Novada" height="56">

  <h3>One MCP server. All web data.</h3>
  <p>Search, scrape, crawl, proxy, and AI research for AI agents — in a single install.<br>
  Powered by Novada's own network of 100M+ residential IPs across 195 countries.</p>

  <a href="https://www.novada.com">
    <img src="https://img.shields.io/badge/🚀_Get_Started-6C40E2?style=for-the-badge" alt="Get Started">
  </a>
  <a href="https://developer.novada.com">
    <img src="https://img.shields.io/badge/📚_Documentation-0F0C1E?style=for-the-badge" alt="Documentation">
  </a>
  <a href="https://www.npmjs.com/package/novada-mcp">
    <img src="https://img.shields.io/badge/⚡_npx_novada--mcp-CB3837?style=for-the-badge&logo=npm&logoColor=white" alt="npm">
  </a>
</div>

<br>

<div align="center">
  <a href="https://www.npmjs.com/package/novada-mcp">
    <img src="https://img.shields.io/npm/v/novada-mcp?color=6C40E2&label=novada-mcp" alt="npm version">
  </a>
  <a href="https://www.npmjs.com/package/novada-mcp">
    <img src="https://img.shields.io/npm/dm/novada-mcp?color=6C40E2" alt="npm downloads">
  </a>
  <a href="https://github.com/NovadaLabs/novada-mcp/blob/main/LICENSE">
    <img src="https://img.shields.io/npm/l/novada-mcp" alt="License">
  </a>
  <a href="https://x.com/Novada_Proxy">
    <img src="https://img.shields.io/twitter/follow/Novada_Proxy?style=social" alt="Follow on X">
  </a>
</div>

---

## Why Novada?

AI agents need clean, current web data to do real work: research, answering with live sources, monitoring, lead enrichment, competitive intelligence, and dataset building. But the tooling is fragmented and the hard part — actually *reaching* the page — is hidden behind someone else's proxy markup.

- **Tavily** does search, but can't scrape or proxy.
- **Firecrawl** does scrape, but can't search or proxy.
- **Bright Data** does everything — through 69 tools that bloat your agent's context window.
- **Rolling your own** means maintaining proxies, anti-bot bypass, retries, and ten different APIs.

Novada is one MCP server that covers the whole loop — **Find → Reach → Extract → Use** — on top of an unblocking layer we own, not rent.

## What Novada does

| Tool | Job |
| --- | --- |
| **Search** | Find fresh sources across Google, Bing, DuckDuckGo, Yandex, and Yahoo in one call. |
| **Scrape / Extract** | Turn any URL into clean Markdown or structured JSON. Batch up to 10 in parallel. |
| **Crawl** | Walk a whole site to build a corpus. |
| **Map** | Discover a site's structure fast. |
| **Research** | One call → parallel searches → dedup → a cited, multi-source report. |
| **Proxy** | Residential, datacenter, ISP, and mobile IPs across 195 countries — 100M+ pool. |
| **Unblock** | Anti-bot, JS rendering, and geo-bypass for sites that fight back. |
| **Browser** | Click, scroll, fill, and run multi-step flows on dynamic pages. |

One API key. One output format. ~25 focused tools instead of 69.

## Built for production

- **We own the network, not a markup.** The unblocking layer is Novada's own 100M+ residential IP pool across 195 countries — not a reseller wrapper. Better success rates, lower cost.
- **One server replaces the stack.** Teams consolidate Tavily + Firecrawl + a proxy vendor into a single `npx novada-mcp`.
- **Token-efficient by design.** Clean Markdown out, a tight tool surface in — it doesn't blow up your agent's context window.
- **Benchmarked, not asserted.** Measured against Firecrawl, Tavily, and Bright Data on the dimensions buyers actually evaluate.

## Core

### Unified MCP Server
<a href="https://github.com/NovadaLabs/novada-mcp">
  <img align="right" src="https://img.shields.io/github/stars/NovadaLabs/novada-mcp?style=for-the-badge&logo=github&logoColor=white&label=Stars&color=6C40E2" alt="Stars">
</a>

**[novada-mcp](https://github.com/NovadaLabs/novada-mcp)** — All web data in one install
Search, scrape, crawl, map, research, proxy, unblock, and browse — one MCP server, one API key. The flagship and the fastest way to start.

```bash
npx novada-mcp
```

<br clear="right"/>

### Cloud API
<a href="https://www.novada.com">
  <img align="right" src="https://img.shields.io/badge/Cloud_API-0F0C1E?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Cloud API">
</a>

**[novada.com](https://www.novada.com)** — Hosted web-data & proxy platform
The production interface. Get an API key and run search, scraping, and the proxy network at scale — with a dashboard, usage analytics, and support.

<br clear="right"/>

### Search & Scraping MCP
<a href="https://github.com/NovadaLabs/novada-search-mcp">
  <img align="right" src="https://img.shields.io/badge/novada--search-5B2EEB?style=for-the-badge&logo=anthropic&logoColor=white" alt="novada-search">
</a>

**[novada-search-mcp](https://github.com/NovadaLabs/novada-search-mcp)** — Search, extract, crawl, research
The focused MCP for teams that only need the web-data side. Published to npm as `novada-search`.

<br clear="right"/>

### Proxy MCP
<a href="https://github.com/NovadaLabs/novada-proxy">
  <img align="right" src="https://img.shields.io/badge/novada--proxy-9863F0?style=for-the-badge&logo=tor-project&logoColor=white" alt="novada-proxy">
</a>

**[novada-proxy](https://github.com/NovadaLabs/novada-proxy)** — Residential proxy tools for AI agents
Bypass Cloudflare and anti-bot walls from inside your agent. Published to npm as `novada-proxy-mcp`.

<br clear="right"/>

## Ecosystem

### Python SDK
<a href="https://github.com/NovadaLabs/novada-python">
  <img align="right" src="https://img.shields.io/badge/Python_SDK-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python SDK">
</a>

**[novada-python](https://github.com/NovadaLabs/novada-python)** — Official Python client
Call Novada's search, scrape, and proxy APIs from Python.

<br clear="right"/>

### Go SDK
<a href="https://github.com/NovadaLabs/novada-go">
  <img align="right" src="https://img.shields.io/badge/Go_SDK-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go SDK">
</a>

**[novada-go](https://github.com/NovadaLabs/novada-go)** — Official Go client
Idiomatic Go bindings for the Novada API.

<br clear="right"/>

### Chrome Extension
<a href="https://github.com/NovadaLabs/novada-proxy-extension">
  <img align="right" src="https://img.shields.io/badge/Chrome_Extension-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Chrome Extension">
</a>

**[novada-proxy-extension](https://github.com/NovadaLabs/novada-proxy-extension)** — Residential proxy in the browser
Manifest V3 extension to route browser traffic through Novada's proxy network.

<br clear="right"/>

## Skills

### Scraper Skill
<a href="https://github.com/NovadaLabs/novada-scraper-skill">
  <img align="right" src="https://img.shields.io/badge/Scraper_Skill-9061FF?style=for-the-badge&logo=anthropic&logoColor=white" alt="Scraper Skill">
</a>

**[novada-scraper-skill](https://github.com/NovadaLabs/novada-scraper-skill)** — Turn any website into structured data
Drop-in [Agent Skill](https://agentskills.io) for Claude Code, Cursor, and Codex. Teaches coding agents how to scrape with Novada.

<br clear="right"/>

### Web Unblocker Skill
<a href="https://github.com/NovadaLabs/novada-webunblocker-skill">
  <img align="right" src="https://img.shields.io/badge/Unblocker_Skill-9061FF?style=for-the-badge&logo=anthropic&logoColor=white" alt="Unblocker Skill">
</a>

**[novada-webunblocker-skill](https://github.com/NovadaLabs/novada-webunblocker-skill)** — Reach sites that fight back
Agent Skill that wires the Novada Web Unblocker into your agent's workflow.

<br clear="right"/>

## Who builds with Novada

- **AI agent builders** shipping research agents, RAG pipelines, sales/lead enrichment, and competitive intelligence through the API and SDKs.
- **AI agent operators** running Novada inside Claude Code, Cursor, VS Code, and any MCP client.
- **Data and growth teams** that need to reach hard targets at scale without standing up their own proxy and anti-bot stack.

## Community & Support

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

---

<div align="center">
  <p>
    <strong>All web data. One install.</strong><br>
    <a href="https://www.novada.com">Get your API key</a> and start in minutes.
  </p>

  <br>

  <a href="https://github.com/NovadaLabs/novada-mcp">Star the flagship</a> •
  <a href="https://www.novada.com">Get an API key</a> •
  <a href="https://developer.novada.com">Read the docs</a>
</div>
