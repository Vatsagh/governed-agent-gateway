# Governed Agent Gateway

## Problem
AI agents fail at the integration and trust layer. This project connects agents
to Jira and ServiceNow through MCP servers with scoped identity, policy,
audit trails and evals in CI.

## Plan
- [ ] Month 1: MCP server for Jira (read tools), containerised
- [ ] Month 2: OAuth 2.1, per-tool scopes, ServiceNow integration
- [ ] Month 3: Eval suite gating CI
- [ ] Month 4: Threat model and red-team report
- [ ] Month 5: Tracing, cost dashboard, governance control map
- [ ] Month 6: Demo video, case-study write-up

## Build log
- Day 1: Toolchain set up; explored the MCP filesystem server in MCP Inspector;
  notes in docs/notes/day01-mcp.md
