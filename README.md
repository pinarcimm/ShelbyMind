[ShelbyMind_README.md](https://github.com/user-attachments/files/26116531/ShelbyMind_README.md)
# ShelbyMind

> The first decentralized AI model marketplace built on [Shelby Protocol](https://shelby.xyz) — deploy your model once, earn APT every time someone runs inference. No cloud. No middleman. No censorship.

🟢 **[Live Demo →](https://izmiradami.github.io/shelbymind)**

---

## What is ShelbyMind?

ShelbyMind is a decentralized AI model marketplace built on top of the Shelby Protocol. Developers and researchers upload their model weights to the Shelby blob network, where they are stored permanently with cryptographic commitments on the Aptos blockchain. Every inference request triggers a micropayment — the model owner earns APT automatically, with no platform taking a cut.

No company controls your model. No algorithm can remove it. Your intelligence, your earnings, forever.

---

## The Problem

Today's AI infrastructure is broken:

- Models are hosted on centralized servers controlled by a handful of corporations
- Access can be revoked, APIs can be deprecated, prices can change overnight
- Model creators earn nothing when their work is used by others
- There is no true ownership — your model can be taken down at any time

---

## Why Shelby?

Shelby's infrastructure makes ShelbyMind possible:

- **Blob storage** — Model weights stored permanently, no single point of failure
- **Paid reads** — Every inference generates a micropayment directly to the model owner
- **Dedicated fiber network** — Fast weight retrieval for low-latency inference
- **Aptos blockchain** — Cryptographic commitments ensure permanent availability and provable ownership
- **Erasure coding** — Model weights are redundantly encoded across the network

---

## Features

- 🧠 **AI Model Marketplace** — Browse LLMs, image generators, audio models, and code models
- 📤 **Model Upload** — Deploy model weights to Shelby network with custom pricing
- ⚡ **Inference Engine** — Run prompts against any model, pay APT per inference
- 💰 **Micropayment System** — Petra wallet integration, APT flows directly to creators
- 📊 **Earnings Dashboard** — Track total earned, inferences sold, storage used
- 📋 **Transaction History** — Every payment recorded on Aptos blockchain
- 🔍 **Filter by Type** — LLM, Image Generation, Audio, Code

---

## Roadmap

### Phase 1 — Core (Current)
- [x] AI model marketplace UI with cyberpunk design
- [x] Model upload flow with Shelby blob simulation
- [x] Inference engine with typing animation output
- [x] Micropayment modal with Petra wallet
- [x] Earnings dashboard and transaction history

### Phase 2 — Real Shelby Integration
- [ ] Full Shelby TypeScript SDK integration (pending early access)
- [ ] Real model weight storage on Shelby testnet
- [ ] Live Aptos micropayment channels per inference
- [ ] On-chain model ownership via Move smart contracts

### Phase 3 — Inference Infrastructure
- [ ] Actual model execution layer (WASM / remote compute)
- [ ] Streaming inference output via Shelby RPC
- [ ] Model versioning and updates
- [ ] Benchmark leaderboard

### Phase 4 — Ecosystem
- [ ] DAO-based model curation
- [ ] Fine-tuning marketplace
- [ ] Dataset storage and monetization
- [ ] API for third-party integrations

---

## Tech Stack

| Layer | Technology |
|---|---|
| Storage | Shelby Protocol |
| Blockchain | Aptos |
| SDK | `@shelby-protocol/sdk` |
| Wallet | Petra (Aptos native) |
| Smart Contracts | Move |
| Frontend | HTML · CSS · Vanilla JS |

---

## Getting Started

> ⚠️ Shelby is currently running on testnet. Full SDK integration pending early access approval.

```bash
# Install Shelby SDK (when early access is granted)
npm install @shelby-protocol/sdk

# Install Shelby CLI
npm install -g @shelby-protocol/cli
```

Or just open `index.html` in your browser to try the demo.

---

## Why This Matters

The $200B AI industry runs on centralized infrastructure. Every model you use today can be taken offline tomorrow. ShelbyMind is the foundation for a world where AI models are public goods — permanently stored, freely accessible, and fairly compensated through cryptographic micropayments.

This is not just a product. It is a new primitive for the AI economy.

---

## Contributing

This project is in early development. Contributions, ideas, and feedback are welcome. Open an issue or submit a pull request.

---

## License

MIT

---

*Built during Shelby Early Access Testnet — powered by Shelby Protocol & Aptos*
