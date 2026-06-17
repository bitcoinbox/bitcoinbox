# bitcoinbox

Applied AI engineer. I build LLM apps and the tooling around them: RAG, agents, evals, and the
parts that keep them running. I like small, practical projects that ship.

## JobProof

[JobProof](https://github.com/bitcoinbox/jobproof) is the one I'd show first. It scores how well
a job fits a candidate, then drafts a tailored application with every claim backed by a source. It
never auto-applies. It's open source and runs out of the box:

- Hybrid retrieval (dense + BM25, fused with RRF, then MMR reranking) over a local vector store
- A tool-using agent, structured outputs, and an eval suite (retrieval metrics plus an LLM judge)
- Token, cost, and latency tracking, with a FastAPI dashboard
- 140 tests and a 30-second offline demo: clone it and the dashboard fills in with no API key

## Other work

I run [IslandLabs](https://islandlabs.studio), a premium web studio. We build custom, fast
websites for clients, with real attention to type, motion, and performance. Happy to share work
if you ask.

## Tools

Python, TypeScript, FastAPI, Fastify, Next.js, React, Postgres, SQLite, Redis, the Anthropic API,
Chroma, Docker, Railway, Vercel.

Still learning. More at [islandlabs.studio](https://islandlabs.studio).
