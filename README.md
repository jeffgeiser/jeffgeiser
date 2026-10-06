### Jeff Geiser

VP, Customer Engineering at [Zenlayer](https://zenlayer.com). I work on where AI actually runs: multi-megawatt GPU clusters, edge inference, and the operator layer underneath it.

The interesting problem right now isn't the models. It's running them on hardware you own, efficiently, and proving the data stayed home. Most enterprise inference is moving on-prem, and the layer that measures a sovereign stack, routes across it, and proves it held is mostly unbuilt. That's what I build (under Noorth Labs).

**Building**

- **[Wicklee](https://wicklee.dev)** — observability and cost governance for self-hosted inference. Watts and tokens in one datastore, so you get real cost per token and tokens-per-watt across a fleet. The MPG for local AI.
- **[bordercheck](https://github.com/jeffgeiser/bordercheck)** — a test harness that checks whether data in your AI stack actually stays inside the border you drew. Runs a canary through the real stack, stresses it, and inspects every layer data lands in (logs, caches, vector stores, egress). Residency proven by behavior, not by diagram.
- **hiipo** — the proof layer for sovereign AI. You moved AI in-house for sovereignty and compliance; hiipo proves you got it. bordercheck is its first tool.
- Small expert models — judges and signal producers built to run on owned hardware as components in compound-AI pipelines.
- - **[ARP](https://github.com/jeffgeiser/arp-spec)** — the Agentic Resource Protocol. Sense, Score, Commit, Reconcile: how an agent reasons about inference compute it controls. More a named pattern than a standard I'm pushing, but the vocabulary holds up and it's the spine of the decision-loop writing.

**Writing**

I write about the operator layer of sovereign AI at [jeffgeiser.dev](https://jeffgeiser.dev): compound AI on hardware you own, routing on silicon state, tokens-per-watt, and proving your stack stayed sovereign.

The throughline: measure it, route it, prove it stayed home. The operator layer for AI you run yourself.
