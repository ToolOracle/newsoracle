# 📰 newsOracle

**Consumer MCP Server** — 9 tools | Part of [ToolOracle](https://tooloracle.io)

![Tools](https://img.shields.io/badge/MCP_Tools-9-10B898?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-00C853?style=flat-square)
![Tier](https://img.shields.io/badge/Tier-Free-2196F3?style=flat-square)

## Quick Connect

```bash
# Claude Desktop / Cursor / Windsurf
npx -y mcp-remote https://tooloracle.io/news/mcp/
```

```json
// claude_desktop_config.json
{
  "mcpServers": {
    "newsoracle": {
      "command": "npx",
      "args": ["-y", "mcp-remote", "https://tooloracle.io/news/mcp/"]
    }
  }
}
```

## Tools (9)

| Tool | Description |
|------|-------------|
| `top_news` | Top headlines by country and topic. Topics: business, technology, sports, health |
| `search_news` | Search news articles by keyword with time filter. |
| `trending_topics` | What is trending right now on Google in a country. |
| `topic_deep_dive` | Deep analysis: articles, source diversity, interest trend over time. |
| `compare_coverage` | How different news sources cover the same story. |
| `trend_over_time` | Google Trends interest over time for 1-5 keywords. Compare search interest. |
| `related_queries` | What people also search for around a keyword. Rising + top queries. |
| `breaking_now` | Latest breaking/developing stories — combines trending searches + top headlines. |
| `health_check` | Server status, API connectivity. |

## Pricing

| Tier | Rate Limit | Price |
|------|-----------|-------|
| Free | 100 calls/day | €0 |
| Pro | 10,000 calls/day | €29/month |
| Enterprise | Unlimited | Custom |

> Free tier includes all tools with rate limiting. Upgrade for higher limits and priority support.

## Part of ToolOracle

newsOracle is one of **42 specialized MCP servers** in the [ToolOracle](https://tooloracle.io) ecosystem — the largest collection of production-ready MCP tools for AI agents.



**Related Oracles:**
- [FeedOracle](https://feedoracle.io) — Evidence-grade compliance data infrastructure
- [ToolOracle](https://tooloracle.io) — 42 Oracles, 390+ MCP Tools

## Links

- 🌐 Live: `https://tooloracle.io/news/mcp/`
- 📚 Docs: [tooloracle.io/docs](https://tooloracle.io/docs)
- 🏠 Platform: [tooloracle.io](https://tooloracle.io)

---

*Built by [FeedOracle](https://feedoracle.io) — Evidence by Design*
