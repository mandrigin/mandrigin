[Gateway.fm](https://gateway.fm) / [Open Privacy Suite](https://gateway.fm/open-privacy-suite/) / [My Website](https://255c.org)

I am CTPO and co-founder at [Gateway.fm](https://gateway.fm), where we build infrastructure for institutions moving finance onchain.

My work sits at the intersection of Ethereum infrastructure, security, privacy, and regulated financial systems. These days I am focused on:

## Building Gateway.fm

Gateway helps institutions launch and operate onchain products: stablecoin payments, tokenized assets, treasury flows, rollups, RPC, indexing, privacy, and compliance infrastructure.

I work across product, engineering, and protocol architecture: turning hard infrastructure problems into systems that can run in production for banks, fintechs, ecosystems, and Web3 builders.

## Open Privacy Suite

I am currently spending a lot of time on privacy infrastructure for EVM chains.

[Open Privacy Suite](https://gateway.fm/open-privacy-suite/) is an open, vendor-lock-in-free privacy layer for public and private EVM networks. It includes a JSON-RPC privacy proxy, role-based access control, selective disclosure, compliance tooling, audit trails, and a privacy-aware block explorer.

The goal is practical privacy: organizations should be able to use Ethereum-compatible infrastructure while controlling who can see what, proving what happened, and meeting real operational and regulatory requirements.

## Ethereum infrastructure and research

I have been working on Ethereum and blockchain infrastructure since 2017: execution clients, rollups, RPC systems, tracing, access control, and production operations.

Earlier research work included Stateless Ethereum and state growth: [Stateless Ethereum: Binary Tries Experiment](https://255c.org/writing/stateless-ethereum-binary-tries/), [Semi-Stateless Initial Sync Experiment](https://255c.org/writing/semi-stateless-initial-sync/), [ReGenesis Explained](https://255c.org/writing/regenesis-explained/), [KV-Witness](https://255c.org/writing/kv-witness/), transaction witnesses, binary tries, witness sizing, and experiments around reducing the operational cost of full nodes. The witness thread runs on: [Stateful vs stateless ZK proving](https://255c.org/notes/stateful-vs-stateless-zk-proving/).

Public Ethereum research and infrastructure artifacts:

- [ethereum-mainnet-kv-witness-data](https://github.com/mandrigin/ethereum-mainnet-kv-witness-data)
- [ethereum-mainnet-resolver-witness-stats](https://github.com/mandrigin/ethereum-mainnet-resolver-witness-stats)
- [ethereum-mainnet-bin-tries-data](https://github.com/mandrigin/ethereum-mainnet-bin-tries-data)
- [turbo-geth-binary-tree-hashes](https://github.com/mandrigin/turbo-geth-binary-tree-hashes)
- [eth-bench](https://github.com/mandrigin/eth-bench)

Before Gateway.fm I worked with teams and projects including Ethereum Foundation / Erigon, Status, StarkWare, and Opera Software.

Earlier mobile and platform work included browser, mobile runtime, and energy-efficiency engineering, including writing on [Mobile Energy Efficiency BOK](https://255c.org/writing/mobile-energy-efficiency-bok/).

## AI-native development

I build with AI agents as a core part of how I work — not as autocomplete, but as an orchestrated fleet: parallel agents for implementation, review, security analysis, test-writing, and full end-to-end certification.

The interesting problem isn't generating code — it's making AI-generated code **production-ready**, and I've built my workflow around that. I treat every AI output as a claim to verify against source-of-truth (specs, on-chain behaviour, real test runs), run adversarial review over AI-suggested changes, and gate everything behind production rigor — real end-to-end tests and loadtests, exact-block completeness checks, and no "green" on a flaky or false-passing test. Just as important is designing around where AI *fails*: confident wrong answers, plausible-but-broken reasoning, and long tasks that quietly stall.

Done this way, AI stops being a demo and becomes a way to ship and operate critical infrastructure with clearer interfaces, better tests, and fewer hidden assumptions.

## Hobby tools and personal experiments

Separate from my Ethereum and Gateway work, I still build small tools for myself, usually with a strong bias toward local-first behavior, privacy, and deliberately constrained product design.

- [LE FLAC](https://github.com/mandrigin/leflac) - a local-first FLAC player for Android / Nothing Phone, with no network permission, no accounts, and no telemetry.
- [RFF](https://github.com/mandrigin/req-of-funds) - a macOS menu bar app for small-consultancy money paperwork: classifying incoming bills with on-device or local AI, tracking them until paid, generating outgoing invoices, and preparing the monthly accountant report.
- [Interfast](https://github.com/mandrigin/interfast) - a small intermittent fasting app that works as a private local scheduler instead of a tracker.

## What I care about

- Secure and scalable infrastructure
- Clear product boundaries for complex systems
- Privacy-preserving applications that are usable in production
- Open standards and avoiding vendor lock-in
- AI-assisted engineering that improves real delivery, not just screenshots
- Building teams that can ship and operate critical systems
