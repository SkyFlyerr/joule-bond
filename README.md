<p align="center">
  <img src="https://img.shields.io/badge/blockchain-Polygon-8247E5?style=for-the-badge&logo=polygon" alt="Polygon">
  <img src="https://img.shields.io/badge/token-ERC--20-3C3C3D?style=for-the-badge&logo=ethereum" alt="ERC-20">
  <img src="https://img.shields.io/badge/license-Apache%202.0-blue?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/badge/status-In%20Development-yellow?style=for-the-badge" alt="Status">
</p>

<h1 align="center">⚡ Joule Bond</h1>

<p align="center">
  <strong>The Universal Energy Standard. Not Crypto. Pure Energy.</strong>
</p>

<p align="center">
  <a href="https://joule.bond">Website</a> •
  <a href="./LITEPAPER.md">Litepaper</a> •
  <a href="#quick-start">Quick Start</a> •
  <a href="#contributing">Contributing</a>
</p>

---

## What is Joule Bond?

**Joule Bond (eJLE)** is a Real World Asset (RWA) token where each unit is hard-pegged to **1 kWh** of verified energy generation — whether from a nuclear plant, a solar panel, or human labor.

```
1 eJLE = 1 kWh = 1000 kJ = 3.6 MJ
```

eJLE creates a **universal unit of account** for all forms of energy and work, enabling a fully decentralized marketplace where anyone can mint, trade, and redeem tokens backed by their validated productive capacity.

## The Big Idea

> "Everything is energy. Money should reflect that."

- Power plants sell electricity as tokens
- Solar panels monetize their output directly
- **Humans sell their labor measured in energy units**
- All goods and services priced in kWh

## Who Can Participate?

| Generator Type | Example | Can Mint |
|---------------|---------|----------|
| Power Plants | Nuclear, Hydro, Solar, Wind | ✓ |
| Home Solar | Rooftop panels | ✓ |
| **Individuals** | Freelancers, consultants | ✓ |
| **Companies** | Agencies, factories | ✓ |
| **Organizations** | Non-profits, DAOs | ✓ |

**Any entity** — individual, company, or organization — with validated productive capacity can mint, sell, and accept eJLE.

## How It Works

```
┌─────────────────────────────────────────────────────────────┐
│                    THE eJLE CYCLE                           │
│                                                             │
│   1. VALIDATE ──→ Prove your generation capacity            │
│         ↓                                                   │
│   2. MINT ──────→ Create eJLE (max 100 days of capacity)   │
│         ↓                                                   │
│   3. SELL ──────→ Trade on CEX/DEX or direct               │
│         ↓                                                   │
│   4. BURN ──────→ Accept eJLE for goods/services           │
│         ↓                                                   │
│   5. MINT AGAIN → Burning unlocks new minting capacity     │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

**Example — Freelancer:**
1. Validate: 8 kWh/day capacity (consulting)
2. Mint: up to 800 eJLE (100 days × 8 kWh)
3. Sell: list on exchange
4. Client burns 80 eJLE → you deliver 10 hours of work
5. 80 burned → can mint 80 more

## Key Features

| Feature | Description |
|---------|-------------|
| ⚡ **Energy-Backed** | 1:1 peg to verified kWh |
| 🔄 **Burn-to-Mint** | Must burn to unlock new minting |
| 🌍 **Universal** | Any generator type: plants, panels, humans |
| 🛒 **Marketplace** | Decentralized economy in kWh |
| 🔒 **Privacy** | Pseudonymous by default, optional KYB |

## Use Cases

- **⚡ Energy** — Sell electricity, EV charging, peer-to-peer solar
- **👤 Freelance** — Price your services in kWh
- **🏭 Industrial** — B2B settlements, supply chain
- **💰 Store of Value** — Energy-backed savings
- **🌍 Global Trade** — Universal unit, no FX risk

## Tech Stack

| Layer | Technology |
|-------|------------|
| **Blockchain** | Polygon (PoS/zkEVM) |
| **Token** | ERC-20 |
| **Frontend** | Next.js 14+, TypeScript, Tailwind |
| **Web3** | Wagmi, Viem, RainbowKit |
| **Oracles** | Custom validator network |

## Smart Contracts

| Contract | Purpose |
|----------|---------|
| `eJouleBond.sol` | Core token (mint, burn, transfer) |
| `GeneratorRegistry.sol` | Capacity validation |
| `SupplierBurn.sol` | Redemption logic |
| `ValidatorConsensus.sol` | Revalidation scheduling |
| `KYBAttestation.sol` | Optional identity verification |
| `Marketplace.sol` | Listings, orders, escrow |

## Quick Start

```bash
# Clone
git clone https://github.com/SkyFlyerr/joule-bond.git
cd joule-bond

# Install
npm install

# Dev
npm run dev

# Build
npm run build
```

## Roadmap

| Phase | Milestone | Status |
|-------|-----------|--------|
| Q1 2025 | MVP, Testnet, Core contracts | 🔄 In Progress |
| Q2 2025 | Oracle network, First generators | ⏳ Planned |
| Q3 2025 | Mainnet, Marketplace beta | ⏳ Planned |
| Q4 2025 | Mobile app, Onboarding tools | ⏳ Planned |
| 2026 | Enterprise, Multi-chain | ⏳ Planned |

## Contributing

1. Fork the repo
2. Create feature branch (`git checkout -b feature/amazing`)
3. Commit (`git commit -m 'Add amazing feature'`)
4. Push (`git push origin feature/amazing`)
5. Open PR

## Security

- **No Admin Keys** — Immutable contracts
- **Burn-to-Mint** — Prevents inflation
- **Oracle Multisig** — 3/5 consensus required

Found a vulnerability? → security@joule.bond

## License

**Apache License 2.0** — see [LICENSE](LICENSE)

---

<p align="center">
  <strong>⚡ Joule Bond — Energy is Money</strong>
</p>

<p align="center">
  <a href="https://joule.bond">joule.bond</a> •
  <a href="mailto:team@joule.bond">team@joule.bond</a>
</p>
