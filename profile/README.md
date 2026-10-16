<p align="center">
  <a href="https://github.com/bonnard-data/mcp-charts">
    <img src="https://github.com/bonnard-data/.github/raw/main/profile/logo.png" alt="Bonnard" width="80" />
  </a>
</p>

<p align="center">
  <strong>Interactive charts for your MCP server, in a few lines.</strong>
</p>

<p align="center">
  <a href="https://github.com/bonnard-data/mcp-charts">mcp-charts</a> &middot;
  <a href="https://www.npmjs.com/package/@bonnard/mcp-charts">npm</a> &middot;
  <a href="https://docs.bonnard.dev/mcp-charts/chart-types">Docs</a> &middot;
  <a href="https://discord.com/invite/RQuvjGRz">Discord</a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/bonnard-data/mcp-charts/main/assets/hero-bubble.png" alt="A chart rendered inside Claude from a visualize tool call" width="820">
</p>

**[@bonnard/mcp-charts](https://github.com/bonnard-data/mcp-charts)** adds a `visualize` tool plus an embedded chart widget to any MCP server. The agent writes SQL, your database returns the rows, and the result renders as an interactive chart inside the host (Claude, ChatGPT, and other MCP Apps clients). You write no frontend code.

- **Grounded in real data.** Charts render the rows your query returned, not numbers the model typed into a tool call. No hallucinated figures.
- **A few lines, no frontend.** One function, one widget that works across every MCP Apps host.
- **Interactive, not static images.** Tooltips, legends, and axis formatting, native to the client.

```bash
npm install @bonnard/mcp-charts
```
