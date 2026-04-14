# Tool Recipes

## Verified Flows
- Run `python D:\AI\agent-memory\scripts\agent_memory.py light-sync` for daytime incremental capture.
- Run `python D:\AI\agent-memory\scripts\agent_memory.py nightly-merge` for full consolidation and mirror refresh.
- Run `python D:\AI\agent-memory\scripts\agent_memory.py skills-synthesis` to refresh generated workflow skills and backup exports.
- Run `python D:\AI\agent-memory\scripts\reporting.py prepare --kind weekly` or `--kind monthly` to build conclusion-only private reports.
- Run `python D:\AI\agent-memory\scripts\reporting.py dispatch-plan --channel gmail` or `--channel weixin` to recover pending report deliveries.
- Run `python D:\AI\agent-memory\scripts\reporting.py health-check` to generate exception-only alert payloads.
- When referencing a local file in responses, include a plain-text absolute Windows path so it is easy to find in Explorer.
