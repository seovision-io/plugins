# SeoVision

SeoVision gets a website ranking in Google and cited by AI assistants such as ChatGPT and Claude, and does the work for its customers: site audits, AI-visibility tracking per market and model, articles written and published to the customer's site, and backlinks from real sites.

This plugin connects your SeoVision account to Claude Code and Codex. It adds the SeoVision MCP server and three workflows:

- **get-started**: checks the connection and gives a short status of your project.
- **seo-health-check**: the five things to fix first on your site, from your latest audit, Search Console and AI answers.
- **weekly-report**: a weekly report on search and AI visibility, articles and backlinks, ready to share.

## Install

In Claude Code:

```
/plugin install seovision --marketplace seovision-io/plugins
```

In Codex, run `codex plugin marketplace add seovision-io/plugins`, then install SeoVision from `/plugins`.

On first use, sign in to SeoVision in your browser.

## What it connects to

The plugin declares one remote MCP server, `https://app.seovision.io/api/directory/mcp`. Nothing runs on your machine. On first use you sign in to SeoVision in your browser (OAuth), and every call then runs as your SeoVision user, with the same projects and roles as the SeoVision dashboard. The plugin sends no data anywhere else and reads no credentials from your machine.

Anything that publishes to your live site, deletes, or sends something outside SeoVision shows a preview first and runs only after you confirm in the chat. Plans and payments are managed in the SeoVision dashboard.

## Requirements

An existing SeoVision account. Manage it at https://app.seovision.io.

## Example prompts

- "What should I fix first on my site?"
- "How visible is my brand in AI answers this month, and which competitors are named instead?"
- "Write my weekly SEO report."
- "Which articles go out this week?"

## Support

support@seovision.io · https://seovision.io/contact · Privacy: https://seovision.io/privacy · Terms: https://seovision.io/terms
