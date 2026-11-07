# Site Haus for Claude

Connects Claude to your [Site Haus](https://sitehaus.agency) account, and teaches it how to use it.

- **Connector:** `https://sitehaus.agency/mcp`, sign in with your Site Haus account (OAuth). Claude works as you, with your permissions.
- **Skills:**
  - `build-with-site-haus`: build, check, preview, undo and publish WordPress themes, websites and web apps.
  - `site-haus-proposals`: write client proposals as drafts.
  - `site-haus-agency`: read leads, clients and requests, and keep tasks and time up to date.

A free Site Haus account works. Using your own Claude never uses Site Haus credits.

## Install in Claude Code

```
claude plugin marketplace add ronmcclenny/Site-Haus-plugin-for-Claude
claude plugin install site-haus@site-haus
```

Then run `/mcp` (or `claude mcp login site-haus`) once to sign in.

## Install as a connector only

In Claude, open Customize → Connectors → Add custom connector and paste `https://sitehaus.agency/mcp`.

## Help

Docs: https://sitehaus.agency/docs/build/connect-your-own-ai · Privacy: https://sitehaus.agency/privacy · Support: https://sitehaus.agency/support

MIT licensed.
