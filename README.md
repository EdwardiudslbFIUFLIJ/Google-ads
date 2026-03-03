# Google Ads Data Hub

Central repository for Google Ads analysis across multiple accounts.

## Accounts

| Folder | Account | Description |
|--------|---------|-------------|
| `porthousedean/` | Porthouse Dean | Architecture firm ads |
| `fluent-ads/` | Fluent | Marketing agency campaigns |
| `calcs-online/` | Calcs Online | Calculator tool promotion |

## MCP Connection

This repo is connected to Google Ads via MCP (Model Context Protocol). You can query all accounts through VS Code Copilot.

### Example Queries
- "Show campaign performance for porthousedean"
- "Compare CTR across all accounts"
- "What's our total spend this month?"

## Structure

Each account folder contains:
- `findings/` - Analysis and insights
- `reports/` - Generated reports
- `queries/` - Saved GAQL queries
- `data/` - Exported data snapshots

## Getting Started

1. Open this folder in VS Code
2. The MCP server auto-connects via `.vscode/mcp.json`
3. Start chatting with your ads data!
