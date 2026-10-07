<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.svg">
    <img alt="Hunter Smith: AI Engineer at LKG, Melbourne, Australia" src="assets/banner-light.svg" width="100%">
  </picture>
</p>

I build AI systems for operational problems: LLM agents, retrieval pipelines, and the evals and tests that show whether they work. Each project below has tests, CI on GitHub Actions, and a written Limitations section.

### Featured projects

<table>
<tr>
<td width="50%" valign="top">
  <a href="https://github.com/SmitHunter/rag-forge"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/thumb-rag-forge-dark.png"><source media="(prefers-color-scheme: light)" srcset="assets/thumb-rag-forge-light.png"><img src="assets/thumb-rag-forge-light.png" alt="Retrieval eval chart comparing BM25, dense, hybrid and rerank on recall, MRR and latency" width="100%"></picture></a><br>
  <a href="https://github.com/SmitHunter/rag-forge"><b>rag-forge</b></a><br>
  Measures chunking, hybrid retrieval and reranking on a 76-question eval set.<br>
  <sub>Python · FAISS · BM25 · SentenceTransformers · FastAPI</sub>
</td>
<td width="50%" valign="top">
  <a href="https://github.com/SmitHunter/llm-regress"><img src="assets/thumb-llm-regress.png" alt="LLM Regress HTML report of a failing mock-provider run" width="100%"></a><br>
  <a href="https://github.com/SmitHunter/llm-regress"><b>llm-regress</b></a><br>
  YAML regression suites for prompts; <code>compare</code> fails CI on a regression.<br>
  <sub>Python · asyncio · GitHub Actions · LLM-as-judge</sub>
</td>
</tr>
<tr>
<td width="50%" valign="top">
  <a href="https://github.com/SmitHunter/trace-agent"><img src="assets/thumb-trace-agent.png" alt="Trace Agent comparing weather in three cities with the MCP tool trace" width="100%"></a><br>
  <a href="https://github.com/SmitHunter/trace-agent"><b>trace-agent</b></a><br>
  MCP server and MCP-client agent; the UI traces every <code>tools/list</code> and <code>tools/call</code>.<br>
  <sub>Python · MCP · FastAPI · Next.js · Docker</sub>
</td>
<td width="50%" valign="top">
  <a href="https://github.com/SmitHunter/Daily-Ops-Briefing"><img src="assets/thumb-daily-ops.png" alt="Daily Ops Briefing dashboard for a synthetic store network" width="100%"></a><br>
  <a href="https://github.com/SmitHunter/Daily-Ops-Briefing"><b>Daily-Ops-Briefing</b></a><br>
  Analyst and Writer Claude agents turn synthetic store data into a daily briefing (example output is illustrative).<br>
  <sub>Python · Claude tool use · SQLite · Flask</sub>
</td>
</tr>
</table>

### Stack

| Area | Tools |
|------|-------|
| AI / LLM | Claude API (tool use), OpenAI API, Ollama, MCP, SentenceTransformers, FAISS |
| Backend | Python, FastAPI, Flask, SQLite |
| Frontend and infra | Next.js, TypeScript, Docker, GitHub Actions, Render, Make.com |

---
<p align="center"><a href="https://www.linkedin.com/in/hunter-sm/">LinkedIn</a></p>
