# Vaultfire Protocol — Base

> KYA — Know Your Agent. The trust and accountability standard for the AI age.

Base is the primary hub chain for the Vaultfire Protocol. This repo is a partner-facing reference for everything deployed and live on Base mainnet today.

For the full multi-chain protocol source (Base, Avalanche, Ethereum), see the [main Vaultfire repository](https://github.com/Ghostkey316/ghostkey-316-vaultfire-init).

---

## What is Vaultfire?

The AI age has a trust problem. AI agents make decisions, handle money, and operate autonomously — with zero verifiable accountability. No identity. No track record. No skin in the game.

**KYA (Know Your Agent)** is the answer. A privacy-first, on-chain trust standard that lets you verify what an agent stands for, what it has done, and whether it has accountability — without exposing private data.

Vaultfire is the trust infrastructure for the AI agent economy — what HTTPS was to web security. This is infrastructure, not an application. Vaultfire is the layer that other protocols, platforms, and agents build on top of.

---

## Live on Base Today

| Feature | Status | Details |
|---------|--------|---------|
| ERC-8004 Identity Registry | **LIVE** | 9 agents registered on Base mainnet |
| Partnership Bonds | **LIVE** | Mutual economic stakes between agents and humans |
| VNS Names (.vns) | **LIVE** | Human-readable names for agents |
| Street Cred Scoring (0–95) | **LIVE** | Composite on-chain reputation from identity + bonds + peer feedback |
| On-Chain Rating (0–10,000) | **LIVE** | Peer feedback via ERC8004ReputationRegistry |
| Agent Discovery | **LIVE** | Lookup by wallet address |
| x402 Trust-Gated Payments | **LIVE** | Full on-chain USDC settlement on Base |
| Wallet Connect | **LIVE** | Coinbase Wallet, Base Wallet, MetaMask, WalletConnect |
| Accountability Bonds | **Deployed** | Requires yield pool funding before activation |
| Cross-Chain Trust Sync | **Deployed** | Full Base ↔ Avalanche ↔ Ethereum sync in v1.0 |
| Quantum-Resistant Attestations | **Deployed** | CRYSTALS-Dilithium via DilithiumAttestor |
| ZK Proofs | **Architecture** | Verification contracts in place — full ZK in v1.0 |

---

## Key Features

- **On-Chain Identity (ERC-8004)** — Verifiable agent identity standard, not a username.
- **Partnership Bonds** — Mutual economic stakes between agents and humans. Both parties profit only if the partnership thrives.
- **Accountability Bonds** — AI companies stake capital proportional to their risk. Misalignment has a cost.
- **Street Cred Scoring** — Composite on-chain reputation (0–95) from identity, bonds, and peer feedback.
- **VNS Names** — Human-readable `.vns` names for agents, like ENS but purpose-built for trust.
- **Privacy by Design** — Zero-knowledge proofs and protocol-level anti-surveillance constraints.
- **Quantum Resistance** — CRYSTALS-Dilithium attestations today, full protocol hardening on roadmap.

---

## Deployed Contracts — Base Mainnet (Chain ID: 8453)

16 contracts deployed and verified on Base.

| Contract | Address | Status |
|----------|---------|--------|
| ERC8004IdentityRegistry | [`0x35978DB675576598F0781dA2133E94cdCf4858bC`](https://basescan.org/address/0x35978DB675576598F0781dA2133E94cdCf4858bC) | **LIVE** |
| AIPartnershipBondsV2 | [`0xC574CF2a09B0B470933f0c6a3ef422e3fb25b4b4`](https://basescan.org/address/0xC574CF2a09B0B470933f0c6a3ef422e3fb25b4b4) | **LIVE** |
| AIAccountabilityBondsV2 | [`0xf92baef9523BC264144F80F9c31D5c5C017c6Da8`](https://basescan.org/address/0xf92baef9523BC264144F80F9c31D5c5C017c6Da8) | Deployed |
| ERC8004ReputationRegistry | [`0xdB54B8925664816187646174bdBb6Ac658A55a5F`](https://basescan.org/address/0xdB54B8925664816187646174bdBb6Ac658A55a5F) | **LIVE** |
| ERC8004ValidationRegistry | [`0x54e00081978eE2C8d9Ada8e9975B0Bb543D06A55`](https://basescan.org/address/0x54e00081978eE2C8d9Ada8e9975B0Bb543D06A55) | Deployed |
| VaultfireERC8004Adapter | [`0xef3A944f4d7bb376699C83A29d7Cb42C90D9B6F0`](https://basescan.org/address/0xef3A944f4d7bb376699C83A29d7Cb42C90D9B6F0) | Deployed |
| VaultfireNameService | [`0x1437c4081233A4f0B6907dDf5374Ed610cBD6B25`](https://basescan.org/address/0x1437c4081233A4f0B6907dDf5374Ed610cBD6B25) | **LIVE** |
| FlourishingMetricsOracle | [`0x83dd216449B3F0574E39043ECFE275946fa492e9`](https://basescan.org/address/0x83dd216449B3F0574E39043ECFE275946fa492e9) | Deployed |
| MultisigGovernance | [`0x8B8Ba34F8AAB800F0Ba8391fb1388c6EFb911F92`](https://basescan.org/address/0x8B8Ba34F8AAB800F0Ba8391fb1388c6EFb911F92) | Deployed |
| VaultfireTeleporterBridge | [`0x94F54c849692Cc64C35468D0A87D2Ab9D7Cb6Fb2`](https://basescan.org/address/0x94F54c849692Cc64C35468D0A87D2Ab9D7Cb6Fb2) | Deployed |
| DilithiumAttestor | [`0xBBC0EFdEE23854e7cb7C4c0f56fF7670BB0530A4`](https://basescan.org/address/0xBBC0EFdEE23854e7cb7C4c0f56fF7670BB0530A4) | Deployed |
| ProductionBeliefAttestationVerifier | [`0xa5CEC47B48999EB398707838E3A18dd20A1ae272`](https://basescan.org/address/0xa5CEC47B48999EB398707838E3A18dd20A1ae272) | Deployed |
| BeliefAttestationVerifier | [`0xD9bF6D92a1D9ee44a48c38481c046a819CBdf2ba`](https://basescan.org/address/0xD9bF6D92a1D9ee44a48c38481c046a819CBdf2ba) | Deployed |
| MissionEnforcement | [`0x8568F4020FCD55915dB3695558dD6D2532599e56`](https://basescan.org/address/0x8568F4020FCD55915dB3695558dD6D2532599e56) | Deployed |
| AntiSurveillance | [`0x722E37A7D6f27896C688336AaaFb0dDA80D25E57`](https://basescan.org/address/0x722E37A7D6f27896C688336AaaFb0dDA80D25E57) | Deployed |
| PrivacyGuarantees | [`0xE2f75A4B14ffFc1f9C2b1ca22Fdd6877E5BD5045`](https://basescan.org/address/0xE2f75A4B14ffFc1f9C2b1ca22Fdd6877E5BD5045) | Deployed |

---

## Quick Start

Register an agent and check its Street Cred in under 5 minutes. Everything hits live Base mainnet contracts.

**Prerequisites:** Node.js 18+, a wallet with a small amount of ETH on Base for gas.

### Check an Agent's Street Cred (no wallet needed)

```bash
curl https://theloopbreaker.com/api/agent/status/0xYourAgentAddress
```

Returns:

```json
{
  "address": "0xYourAgentAddress",
  "streetCred": 55,
  "tier": "silver",
  "hasIdentity": true,
  "hasBond": true,
  "bondActive": true,
  "onChainRating": 7200
}
```

### Register an Agent On-Chain

```javascript
import { createWalletClient, http } from 'viem'
import { base } from 'viem/chains'
import { privateKeyToAccount } from 'viem/accounts'

const account = privateKeyToAccount(process.env.AGENT_PRIVATE_KEY)
const client = createWalletClient({ account, chain: base, transport: http('https://mainnet.base.org') })

const IDENTITY_REGISTRY = '0x35978DB675576598F0781dA2133E94cdCf4858bC'

const hash = await client.writeContract({
  address: IDENTITY_REGISTRY,
  abi: [{
    name: 'registerAgent',
    type: 'function',
    inputs: [
      { name: 'name', type: 'string' },
      { name: 'agentType', type: 'string' },
      { name: 'description', type: 'string' },
    ],
    outputs: [],
    stateMutability: 'nonpayable',
  }],
  functionName: 'registerAgent',
  args: ['my-agent', 'autonomous', 'My agent description'],
})

console.log('Registered! Tx:', hash)
console.log('View on BaseScan: https://basescan.org/tx/' + hash)
```

### Create a Partnership Bond

```javascript
import { parseEther } from 'viem'

const PARTNERSHIP_BONDS = '0xC574CF2a09B0B470933f0c6a3ef422e3fb25b4b4'

const hash = await client.writeContract({
  address: PARTNERSHIP_BONDS,
  abi: [{
    name: 'createBond',
    type: 'function',
    inputs: [
      { name: 'partner', type: 'address' },
      { name: 'partnershipType', type: 'string' },
    ],
    outputs: [],
    stateMutability: 'payable',
  }],
  functionName: 'createBond',
  args: ['0xPartnerAddress', 'collaboration'],
  value: parseEther('0.01'), // Bronze tier
})
```

**Partnership types:** collaboration, delegation, service-provider, data-sharing, oracle-consumer

**Bond tiers:** Bronze (0.01 ETH), Silver (0.05 ETH), Gold (0.1 ETH), Platinum (0.5 ETH)

---

## Street Cred Scoring

Composite on-chain reputation score (0–95 max) computed from live Base mainnet data.

| Component | Max Points | Description |
|-----------|-----------|-------------|
| ERC-8004 Identity Registered | 30 pts | Registered = 30, unregistered = 0 |
| Partnership Bond Exists | 25 pts | Has at least one bond |
| Partnership Bond Active | 15 pts | Bond is currently active |
| Bond Tier Bonus | 20 pts | Bronze +5, Silver +10, Gold +15, Platinum +20 |
| Multiple Bonds | 5 pts | More than one active partnership bond |

**Tiers:** Bronze (20+), Silver (40+), Gold (60+), Platinum (80+)

---

## Hub API

The Vaultfire hub runs at [theloopbreaker.com](https://theloopbreaker.com) on Base mainnet.

| Endpoint | Method | Description |
|----------|--------|-------------|
| `/api/hub/stats` | GET | Protocol stats — agent count, active bonds, ETH bonded |
| `/api/agent/status/:address` | GET | Street Cred score and tier for a wallet |
| `/api/agent/register` | POST | Register an agent on ERC-8004 |
| `/api/agent/bond` | POST | Create a partnership bond |
| `/api/contracts` | GET | All 16 Base contract addresses and ABIs |

---

## SDK

```bash
npm install @vaultfire/agent-sdk
```

Documentation: [github.com/Ghostkey316/vaultfire-sdk](https://github.com/Ghostkey316/vaultfire-sdk)

---

## Architecture

```
┌──────────────────────────────────────────────────────┐
│                    VAULTFIRE ON BASE                  │
├──────────────────────────────────────────────────────┤
│                                                      │
│  ┌─────────────┐  ┌──────────────┐  ┌────────────┐ │
│  │  ERC-8004    │  │  Partnership │  │ Accounta-  │ │
│  │  Identity    │  │  Bonds       │  │ bility     │ │
│  │  Registry    │  │  (LIVE)      │  │ Bonds      │ │
│  │  (LIVE)      │  │              │  │ (Deployed) │ │
│  └──────┬───────┘  └──────┬───────┘  └─────┬──────┘ │
│         │                 │                │         │
│         ▼                 ▼                ▼         │
│  ┌──────────────────────────────────────────────┐   │
│  │           Street Cred Engine (0–95)          │   │
│  │     Identity + Bonds + Peer Feedback         │   │
│  └──────────────────────────────────────────────┘   │
│                        │                             │
│         ┌──────────────┼──────────────┐              │
│         ▼              ▼              ▼              │
│  ┌────────────┐ ┌────────────┐ ┌────────────────┐  │
│  │    VNS     │ │  Reputation│ │   Flourishing  │  │
│  │   Names    │ │  Registry  │ │   Metrics      │  │
│  │  (LIVE)    │ │  (LIVE)    │ │   Oracle       │  │
│  └────────────┘ └────────────┘ └────────────────┘  │
│                                                      │
│  ┌──────────────────────────────────────────────┐   │
│  │              Security Layer                   │   │
│  │  Dilithium (Quantum) · Multisig Governance   │   │
│  │  Mission Enforcement · Privacy Guarantees     │   │
│  └──────────────────────────────────────────────┘   │
│                                                      │
│  ┌──────────────────────────────────────────────┐   │
│  │           Cross-Chain Bridge                  │   │
│  │     VaultfireTeleporterBridge (v1.0)         │   │
│  │     Base ↔ Avalanche ↔ Ethereum              │   │
│  └──────────────────────────────────────────────┘   │
│                                                      │
└──────────────────────────────────────────────────────┘
```

---

## Explore

- **Hub:** [theloopbreaker.com](https://theloopbreaker.com)
- **Main Protocol Repo:** [ghostkey-316-vaultfire-init](https://github.com/Ghostkey316/ghostkey-316-vaultfire-init)

### Vaultfire Packages

| Package | Description |
|---------|-------------|
| [`@vaultfire/x402`](https://github.com/Ghostkey316/vaultfire-x402) | x402 payment protocol — USDC micropayments on Base & Avalanche |
| [`@vaultfire/xmtp`](https://github.com/Ghostkey316/vaultfire-xmtp) | Trust-gated encrypted agent messaging |
| [`@vaultfire/vns`](https://github.com/Ghostkey316/vaultfire-vns) | On-chain `.vns` name service — deployed on Base |
| [`@vaultfire/sdk`](https://github.com/Ghostkey316/vaultfire-sdk) | Core SDK — belief verification & attestations |
| [`vaultfire-contracts`](https://github.com/Ghostkey316/vaultfire-contracts) | All deployed ABIs and contract addresses |
| [`@vaultfire/arbitrum`](https://github.com/Ghostkey316/vaultfire-arbitrum) | Arbitrum One — 16 contracts deployed |
| [`@vaultfire/polygon`](https://github.com/Ghostkey316/vaultfire-polygon) | Polygon PoS — 16 contracts deployed |

---

## Mission

> Morals over metrics.
> Privacy over surveillance.
> Freedom over control.
> Making human thriving more profitable than extraction.

---

## License

MIT — Vaultfire Protocol is open source.
