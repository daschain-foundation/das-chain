<p align="center">
  <img src="https://raw.githubusercontent.com/daschain-foundation/.github/main/assets/DAS_Banner1.png" alt="DAS Chain Banner" />
</p>

---

# 🪙 DAS Chain  
### A Decentralized Ecosystem for Human Empowerment  
Built by the **[DAS Foundation](https://das-foundation.org)**  

---

## 🧭 Overview

**DAS Chain** is a sovereign, application-specific blockchain built using the **Cosmos SDK**.  
It powers a decentralized ecosystem where **self-development, education, and financial empowerment** converge through transparent, reward-based participation.

The network’s native token, **DST**, fuels every aspect of the system — from transaction fees and staking to governance and community rewards.

---

## ⚙️ Technology Stack

| Layer | Component | Description |
|-------|------------|-------------|
| **Consensus** | [CometBFT](https://cometbft.com) | Byzantine Fault Tolerant consensus (fast finality) |
| **Framework** | [Cosmos SDK](https://github.com/cosmos/cosmos-sdk) | Modular blockchain development framework |
| **Interoperability** | [IBC Protocol](https://ibcprotocol.org) | Enables cross-chain communication with the Cosmos ecosystem |
| **VM Compatibility** | Future **EVM module** (Evmos-based) | Runs Solidity smart contracts alongside native modules |
| **Modules** | Auth, Bank, Staking, Governance, Mint, Distribution, Vesting, DAS | Core and custom logic powering the DAS economy |

---

## 🪙 Token (DST)

| Parameter | Value |
|------------|-------|
| **Symbol** | DST |
| **Base Denom** | `udst` (1 DST = 1,000,000 udst) |
| **Genesis Supply** | 1,000,000,000 DST |
| **Inflation (initial)** | 0% – adjustable via DAO proposal |
| **Roles** | Gas, Staking, Governance, Rewards |

DST is designed for **utility and participation**, not speculation — empowering users to transact, learn, and earn transparently.

---

## 🧩 Tokenomics

| Allocation | % | Vesting / Notes |
|-------------|---|----------------|
| Community & Ecosystem Rewards | 30% | Airdrops, quests, education, referrals |
| Staking Rewards (Inflation) | 25% | Activated via DAO governance |
| Ecosystem Growth Fund | 20% | Grants, builder incentives, partnerships |
| **Founder** | 10% | 6-month cliff, 3-year linear vesting |
| **Advisors** | 5% | 6-month cliff, 2-year linear vesting |
| **Treasury / DAO Reserve** | 10% | On-chain governed reserves |

---

## 🔧 Local Development

### 1️⃣ Prerequisites
- [Go 1.22+](https://go.dev/dl/)
- [Ignite CLI](https://ignite.com)
- Git

### 2️⃣ Build the Chain
```bash
git clone https://github.com/daschain-foundation/das-chain.git
cd das-chain
ignite chain build


