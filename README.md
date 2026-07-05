# Daily Life Insurance AI News

This repository contains a daily HTML brief tracking AI news in the US life insurance market.

## Local Files

- `index.html` is the report hub.
- `reports/YYYY-MM-DD.html` contains each daily brief.
- `agent-config.json` defines source policy, tracked companies, filtering rules, and publishing settings.
- `agent-prompt.md` is the operating prompt for the scheduled Codex agent.

## GitHub Pages Publishing

To publish the reports:

1. Create a GitHub repository.
2. Add it as the `origin` remote for this local repository.
3. Push the `master` branch.
4. In GitHub, enable Pages from the root of the `master` branch.

After `origin` is configured, the daily Codex automation will commit generated reports and push them to GitHub.
