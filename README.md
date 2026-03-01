# MCP Recipes 🧪

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![MCP](https://img.shields.io/badge/Built%20with-MCP-blue)](https://modelcontextprotocol.io)

> Copy-paste MCP workflows for real developer problems. Each recipe combines multiple MCP servers with Claude to automate tasks that used to take hours.

**[→ Browse all recipes with full guides at MCP Playground Online](https://mcpplaygroundonline.com/recipes)**

---

## What Is an MCP Recipe?

An MCP recipe is a step-by-step workflow that chains multiple MCP servers together with Claude AI to automate a real task. Think of it like a Zapier automation — but running inside Claude, with full context and intelligence at every step.

Each recipe in this repo includes:
- **Which MCP servers** to connect
- **The exact prompts** to use with Claude
- **Architecture diagram** showing how data flows
- **Full written guide** with setup, code, and best practices

> **Test any MCP server from these recipes instantly →**
> [MCP Playground Online](https://mcpplaygroundonline.com/mcp-test-server) — no install, no setup, paste and go.

---

## Contents

- [Developer Workflows](#-developer-workflows)
- [Data & Analytics](#-data--analytics)
- [Productivity & Project Management](#-productivity--project-management)
- [Customer Support & CRM](#-customer-support--crm)
- [Infrastructure & DevOps](#-infrastructure--devops)
- [Marketing & Advertising](#-marketing--advertising)
- [E-commerce & Finance](#-e-commerce--finance)
- [Content & Documentation](#-content--documentation)
- [Community Recipes](#-community-recipes)
- [Coming Soon](#-coming-soon)

---

## 🛠 Developer Workflows

### AI GitHub PR Reviewer
**MCP Servers:** GitHub MCP + Filesystem MCP

Automatically review pull requests using Claude — checks code quality, flags security issues, suggests improvements, and posts structured comments. Turns a 30-minute manual review into a 60-second automated one.

```
Servers:  GitHub MCP + Filesystem MCP
Time:     ~30 min setup | 60 sec per review
Skill:    Intermediate
```

**[→ Full Recipe Guide](https://mcpplaygroundonline.com/blog/build-ai-github-pr-reviewer-mcp-recipe)**

---

### AI Code Documentation Generator
**MCP Servers:** GitHub MCP + Filesystem MCP

Read any codebase via GitHub MCP, generate comprehensive documentation (README, JSDoc, API references), and write it back — all through a Claude conversation. Never write docs manually again.

```
Servers:  GitHub MCP + Filesystem MCP
Time:     ~20 min setup | 5 min per project
Skill:    Intermediate
```

**[→ Full Recipe Guide](https://mcpplaygroundonline.com/blog/code-documentation-generator-github-mcp-recipe)**

---

### Playwright MCP: Browser Automation with AI
**MCP Servers:** Playwright MCP

Use Claude + Playwright MCP to automate browser tasks, run end-to-end tests, scrape structured data, and take screenshots — all through natural language. No Selenium scripts, no XPath selectors.

```
Servers:  Playwright MCP
Time:     ~25 min setup
Skill:    Intermediate
```

**[→ Full Recipe Guide](https://mcpplaygroundonline.com/blog/playwright-mcp-browser-automation-recipe)**

---

## 📊 Data & Analytics

### AI Database Query Assistant (Natural Language SQL)
**MCP Servers:** PostgreSQL MCP + Supabase MCP

Connect Claude to your database and ask questions in plain English — no SQL required. Spot trends, run ad-hoc reports, and debug data issues without writing a single query.

```
Servers:  PostgreSQL MCP or Supabase MCP
Time:     ~20 min setup | instant queries
Skill:    Beginner–Intermediate
```

**[→ Full Recipe Guide](https://mcpplaygroundonline.com/blog/build-ai-database-query-assistant-natural-language-sql)**

---

### PostgreSQL + Claude Analytics Agent
**MCP Servers:** PostgreSQL MCP

Build a fully conversational analytics agent on top of your Postgres database. Includes setup, schema-awareness techniques, safe read-only access patterns, and production deployment.

```
Servers:  PostgreSQL MCP
Time:     ~40 min setup
Skill:    Advanced
```

**[→ Full Recipe Guide](https://mcpplaygroundonline.com/blog/postgres-mcp-claude-analytics-agent-recipe)**

---

### Meta Ads Performance Analyzer
**MCP Servers:** Meta Ads MCP + Google Sheets MCP

Give Claude live access to your Meta ad account. Detect creative fatigue, reallocate budgets based on real-time ROAS, and auto-generate weekly reports — without ever opening Ads Manager.

```
Servers:  Meta Ads MCP + Google Sheets MCP
Time:     ~30 min setup | daily use
Skill:    Intermediate
```

**[→ Full Recipe Guide](https://mcpplaygroundonline.com/blog/automate-meta-ads-claude-ai-mcp)**

---

## 📋 Productivity & Project Management

### Meeting Notes → Jira Tasks (Notion + Jira MCP)
**MCP Servers:** Notion MCP + Jira MCP

Paste meeting notes. Claude reads them, extracts decisions and action items, creates structured Jira tickets with owners and priorities, and saves a summary back to your Notion workspace. What used to take 45 minutes now takes 90 seconds.

```
Servers:  Notion MCP + Jira MCP
Time:     ~25 min setup | 90 sec per meeting
Skill:    Beginner
```

**[→ Full Recipe Guide](https://mcpplaygroundonline.com/blog/automate-jira-tasks-from-meeting-notes-notion-mcp-recipe)**

---

### AI-Powered File Organizer
**MCP Servers:** Filesystem MCP + Google Drive MCP

Claude reads your file names and contents, categorizes everything intelligently, creates organized folder structures, and moves files — all through conversation. Works on local directories or Google Drive.

```
Servers:  Filesystem MCP + Google Drive MCP
Time:     ~15 min setup
Skill:    Beginner
```

**[→ Full Recipe Guide](https://mcpplaygroundonline.com/blog/ai-powered-file-organizer-mcp-recipe)**

---

### Slack + Email Standup Bot
**MCP Servers:** Slack MCP + Gmail MCP

Claude reads your team's Slack messages, pulls relevant emails, and drafts a daily standup summary — automatically. Posts it to your standup channel at a set time, formatted and ready to read.

```
Servers:  Slack MCP + Gmail MCP
Time:     ~30 min setup
Skill:    Intermediate
Status:   🔜 Coming Soon
```

---

## 🎧 Customer Support & CRM

### AI Customer Support Summarizer
**MCP Servers:** Intercom MCP + Zendesk MCP

Automatically summarize open support tickets, group by theme, detect urgent issues, and generate a triage report — every morning. Compresses 2 hours of ticket review into 5 minutes.

```
Servers:  Intercom MCP + Zendesk MCP
Time:     ~30 min setup | 5 min daily
Skill:    Intermediate
```

**[→ Full Recipe Guide](https://mcpplaygroundonline.com/blog/customer-support-summarizer-intercom-zendesk-mcp-recipe)**

---

### Salesforce Lead Enrichment Agent
**MCP Servers:** Salesforce MCP + Fetch MCP

Claude reads new leads in Salesforce, researches their company via the web, enriches the record with context (company size, tech stack, recent news), and scores the lead — automatically on every new entry.

```
Servers:  Salesforce MCP + Fetch MCP
Time:     ~40 min setup
Skill:    Advanced
Status:   🔜 Coming Soon
```

---

## ☁️ Infrastructure & DevOps

### Multi-Cloud Deploy Assistant
**MCP Servers:** AWS MCP + Cloudflare MCP

Describe a deployment in plain English — Claude plans it, stages it across AWS and Cloudflare, validates the config, and executes. Full audit trail, rollback support, and plain-language status updates.

```
Servers:  AWS MCP + Cloudflare MCP
Time:     ~60 min setup
Skill:    Advanced
Status:   🔜 Coming Soon
```

---

### AI Incident Response Agent
**MCP Servers:** PagerDuty MCP + Datadog MCP + Slack MCP

When an alert fires, Claude reads the incident details, queries your metrics for root cause signals, drafts an incident summary, and posts it to your #incidents channel — before your on-call engineer has even opened their laptop.

```
Servers:  PagerDuty MCP + Datadog MCP + Slack MCP
Time:     ~45 min setup
Skill:    Advanced
Status:   🔜 Coming Soon
```

---

## 📣 Marketing & Advertising

### Meta Ads Full Campaign Automator
**MCP Servers:** Meta Ads MCP

End-to-end Meta campaign management through Claude — from audience discovery and creative validation to live performance monitoring and budget reallocation. Verified results: 90% reduction in operational time, 15% ROAS increase.

```
Servers:  Meta Ads MCP
Time:     ~30 min setup
Skill:    Intermediate
```

**[→ Full Recipe Guide](https://mcpplaygroundonline.com/blog/automate-meta-ads-claude-ai-mcp)**

---

### SEO Content Research Agent
**MCP Servers:** Brave Search MCP + Filesystem MCP + Notion MCP

Claude researches keyword opportunities, analyzes top-ranking content, identifies gaps, and writes a structured content brief — saved directly to your Notion workspace.

```
Servers:  Brave Search MCP + Filesystem MCP + Notion MCP
Time:     ~25 min setup
Skill:    Beginner
Status:   🔜 Coming Soon
```

---

## 🛒 E-commerce & Finance

### AI E-commerce Order Manager
**MCP Servers:** Stripe MCP + Shopify MCP

Monitor orders, flag fulfillment delays, detect payment issues, and draft customer response templates — all from a Claude conversation. Claude sees your Stripe payments and Shopify orders side by side.

```
Servers:  Stripe MCP + Shopify MCP
Time:     ~35 min setup
Skill:    Intermediate
```

**[→ Full Recipe Guide](https://mcpplaygroundonline.com/blog/ecommerce-order-manager-stripe-shopify-mcp-recipe)**

---

### Financial Report Generator
**MCP Servers:** Stripe MCP + Google Sheets MCP + Notion MCP

Claude pulls Stripe revenue data, calculates MRR, ARR, churn, and LTV, formats it into a board-ready report in Google Sheets, and posts a summary to your Notion dashboard — on demand or on a schedule.

```
Servers:  Stripe MCP + Google Sheets MCP + Notion MCP
Time:     ~30 min setup
Skill:    Intermediate
Status:   🔜 Coming Soon
```

---

## ✍️ Content & Documentation

### Research Paper Analyzer
**MCP Servers:** Fetch MCP + Filesystem MCP

Give Claude a list of URLs or PDFs. It reads every paper, extracts key findings, identifies contradictions across sources, and writes a synthesized research brief — saved to your local filesystem.

```
Servers:  Fetch MCP + Filesystem MCP
Time:     ~15 min setup
Skill:    Beginner
Status:   🔜 Coming Soon
```

---

### Technical Blog Post Generator
**MCP Servers:** GitHub MCP + Filesystem MCP + Notion MCP

Claude reads your codebase, understands what you built, and drafts a technical blog post explaining it — with code examples pulled directly from your repo. Saves to Notion for editing.

```
Servers:  GitHub MCP + Filesystem MCP + Notion MCP
Time:     ~20 min setup
Skill:    Beginner
Status:   🔜 Coming Soon
```

---

## 🌍 Community Recipes

> Built something with MCP? Share it here. Community recipes are marked with 🌍.

| Recipe | MCP Servers | Author | Link |
|--------|-------------|--------|------|
| *Your recipe here* | | | Submit a PR |

**To submit your recipe:** See [CONTRIBUTING.md](CONTRIBUTING.md)

---

## 🔜 Coming Soon

Vote on which recipes to prioritize by opening an issue with the recipe name.

| Recipe | MCP Servers | Votes |
|--------|-------------|-------|
| Slack + Email Standup Bot | Slack MCP + Gmail MCP | |
| Salesforce Lead Enrichment | Salesforce MCP + Fetch MCP | |
| Multi-Cloud Deploy Assistant | AWS MCP + Cloudflare MCP | |
| AI Incident Response Agent | PagerDuty + Datadog + Slack | |
| SEO Content Research Agent | Brave Search + Notion MCP | |
| Financial Report Generator | Stripe + Sheets + Notion | |
| Research Paper Analyzer | Fetch MCP + Filesystem MCP | |
| Technical Blog Post Generator | GitHub + Filesystem + Notion | |

[→ Open an issue to vote or request a recipe](https://github.com/your-org/mcp-recipes/issues/new)

---

## Quick Start

**Step 1 — Pick a recipe** from the list above

**Step 2 — Install the required MCP servers**
```bash
# Example: GitHub MCP
npm install -g @modelcontextprotocol/server-github

# Example: Filesystem MCP
npm install -g @modelcontextprotocol/server-filesystem
```

**Step 3 — Add servers to Claude Desktop config**
```json
{
  "mcpServers": {
    "github": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-github"],
      "env": { "GITHUB_PERSONAL_ACCESS_TOKEN": "your_token" }
    },
    "filesystem": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem", "/path/to/dir"]
    }
  }
}
```

**Step 4 — Test your server connection**
Before using any server in production, verify it's working correctly at
**[MCP Playground Online](https://mcpplaygroundonline.com/mcp-test-server)** — paste your server URL, inspect all available tools, and run a live test request.

**Step 5 — Follow the recipe guide** at [mcpplaygroundonline.com/recipes](https://mcpplaygroundonline.com/recipes)

---

## How Recipes Are Structured

Each recipe follows the same format so you can go from zero to running in one session:

```
recipe-name/
├── README.md          ← Architecture, tools used, and what it does
├── prompt.md          ← The exact Claude prompts to use
├── config/
│   └── claude.json    ← Ready-to-paste MCP server config
└── examples/
    └── output.md      ← Sample Claude output for this workflow
```

---

## MCP Servers Directory

Need to find a specific MCP server for your recipe idea?

**[→ Browse 100+ MCP Servers at MCP Playground Online](https://mcpplaygroundonline.com/mcp-registry)**

Covers databases, communication tools, cloud platforms, CRMs, dev tools, and more — with direct links to each server's repo and documentation.

---

## Contributing

Contributions welcome! The most valuable contributions are:

1. **New recipes** — A workflow you've built that saves you real time
2. **Improvements to existing recipes** — Better prompts, edge case handling, alternative server options
3. **Vote on coming-soon recipes** — Open an issue with the recipe name you want most

### How to add a recipe

1. Fork this repo
2. Create a folder: `recipes/your-recipe-name/`
3. Add `README.md` with: what it does, MCP servers needed, setup steps, prompt examples
4. Add `config/claude.json` with the MCP server configuration
5. Open a pull request — include a short description of the problem it solves

### Recipe quality bar

- Must work with Claude Desktop or Claude API
- Must use at least one MCP server
- Must solve a real, recurring problem (not a toy example)
- Config and prompts must be tested and working

See [CONTRIBUTING.md](CONTRIBUTING.md) for full guidelines.

---

## Related Resources

- **[MCP Playground Online](https://mcpplaygroundonline.com)** — Test any MCP server in your browser, free
- **[MCP Recipes Page](https://mcpplaygroundonline.com/recipes)** — Full written guides for every recipe in this repo
- **[MCP Servers Directory](https://mcpplaygroundonline.com/mcp-registry)** — Browse 100+ production-ready MCP servers
- **[Prompt Library](https://mcpplaygroundonline.com/prompt-library)** — Reusable prompts for MCP workflows
- **[MCP Official Docs](https://modelcontextprotocol.io)** — Protocol specification and SDK guides
- **[awesome-mcp-servers](https://github.com/your-org/awesome-mcp-servers)** — Curated list of MCP servers by category

---

## License

MIT — free to use, modify, and share.

---

<p align="center">
  <sub>
    Each recipe links to a full written guide at
    <a href="https://mcpplaygroundonline.com/recipes">mcpplaygroundonline.com/recipes</a>
    with architecture diagrams, working code, and best practices.
  </sub>
</p>
