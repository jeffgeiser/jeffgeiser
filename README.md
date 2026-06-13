## Jeff Geiser

VP Customer Engineering at [Zenlayer](https://zenlayer.com) · I work on where AI runs —
multi-MW GPU clusters, edge inference, and model gateways by day; open tooling for
AI on hardware you own at Noorth Labs, nights and weekends.

The interesting problems live in the layer between model weights and production —
the inference stack, the runtime, the memory, the governance. That's what gets built here.

---

### Active projects

| | |
|---|---|
| **[Wicklee](https://wicklee.dev)** | Single-binary observability for self-hosted inference (Ollama, vLLM, llama.cpp). Tracks tok/W, WES score, thermal state, and routing signals across multi-node setups. Community tier free. |
| **[hiipo](https://hiipo.io)** | A local proxy that gives your models persistent memory, enforced standards, and a full audit trail. One command. Nothing leaves your machine. |
| **[ARP](https://github.com/jeffgeiser/arp-spec)** | The Agentic Resource Protocol — how agents negotiate with the infrastructure they run on. Sense → Score → Commit → Reconcile. Spec + essay; reference implementation in Wicklee. |
| **[compass-md](https://github.com/jeffgeiser/compass-md)** | Open spec for portable AI context — the files that tell any AI tool who you are, how you work, and what you care about. MIT. |
| **[elm-research](https://github.com/jeffgeiser/elm-research)** | Open methodology for small expert models — specialized, private, runs on your infrastructure. Current run: a fine-tuned 7B for enterprise account intelligence, evaluated honestly against a frontier baseline. |
| **[compass-dash](https://github.com/jeffgeiser/compass-dash)** | Local dashboard for reviewing compass-md refinements — accept, reject, and apply agent-proposed context changes without leaving your machine. |
| **[Taarn](https://taarn.ai)** | Personal AI OS — local-first, runs on your hardware. Coming later; Wicklee and hiipo first. |

---

### What I'm thinking about

The placement question — frontier API, GPU cluster, edge region, your own hardware,
or a small expert model trained for the job? Most teams decide on instinct;
I think you can decide on data.

Tokens per watt — I authored **WES**, an efficiency score for inference
(throughput per watt, with a thermal penalty), because speed is visible and watts aren't.

The context portability problem — why agents lose who you are between sessions,
and what a real fix looks like.

---

### Writing

**[The Inference Layer](https://jeffgeiser.substack.com)** — notes on running AI
on infrastructure you own: benchmarks, runtime architecture, honest failures.
