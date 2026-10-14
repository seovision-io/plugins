# SeoVision plugins

The SeoVision plugin for Claude Code and Codex: your site's audits, AI-search visibility, articles and backlinks from your SeoVision account, with three ready workflows. What the plugin does and connects to: [seovision/README.md](seovision/README.md).

## Claude Code

```bash
claude plugin marketplace add seovision-io/plugins
claude plugin install seovision@seovision
```

Inside a session, `/plugin install seovision --marketplace seovision-io/plugins` does both in one step. On first use, run `/mcp` and sign in to SeoVision in your browser.

## Codex

```bash
codex plugin marketplace add seovision-io/plugins
```

Then open `/plugins`, install SeoVision, and sign in to SeoVision in your browser.

## Without the plugin

Any MCP client can connect to `https://app.seovision.io/api/directory/mcp` and sign in with OAuth. Setup for each assistant: https://seovision.io/mcp.

## Support

support@seovision.io
