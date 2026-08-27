# IBM ELM MCP Usage Calculator

Estimate IBM ELM MCP work-unit consumption by role, daily quota, growth projection, and Bob AI workflow analysis.

## 🔗 Live App

**https://brettscharm.github.io/elm-ai-hub-calc/elm-mcp-calculator.html**

## Features

- **Per-role headcount** — Developer, Req. Analyst, Test Engineer, Sys. Architect, Eng. Manager
- **Per-function call tuning** — adjust daily call counts for all 22 ELM MCP functions
- **Daily quota tracking** — 10,000 WU per user, with live utilisation bars
- **Growth projection** — model 1×–3× scale-up and see quota impact
- **Monthly estimates** — WU and token totals based on 21 working days
- **Bob AI estimator** — describe a workflow in plain English and get call estimates applied directly to the calculator

## Usage

Open the live URL above — no install or server required.

## Updating

```bash
cd /Users/brettscharmett/.bob/playground
git add elm-mcp-calculator.html README.md && git commit -m "update" && git push
```

GitHub Pages rebuilds automatically within ~60 seconds.
