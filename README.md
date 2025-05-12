# 🔁 Uniswap-Style AMM (Constant Product) – LUNE Ecosystem

This is a simplified **Uniswap-style Automated Market Maker (AMM)** smart contract built from scratch using pure Solidity, without any external libraries or imports (e.g., OpenZeppelin). It implements the **x * y = k** constant product formula and supports **two custom ERC-20 tokens**.

Part of the broader **LUNE ecosystem**, this contract demonstrates core DeFi mechanics with transparency and modularity in mind.

---

## 🚀 Features

- 🧮 **Constant Product AMM**: Implements Uniswap V2's `x * y = k` formula.
- 🔀 **Token Swaps**: Enables swapping between two ERC-20 tokens.
- 🏦 **Liquidity Provisioning**: Users can add/remove liquidity.
- 🧾 **LP Share Tracking**: Manual tracking of LP token shares (no ERC-20 minting).
- 📦 **Zero Dependencies**: No OpenZeppelin or external contracts used.

---

## 📂 Files

- `AMM.sol` – Core AMM contract
- `LUNE.sol` – Renamed duplicate of LUNE 
- `TokenB.sol` – An NFT that reflects staking rights, token-gated access, or yield reputation

---

## 🛠️ Deployment

Deployed via [Remix IDE](https://remix.ethereum.org)  
Network: **Sepolia Testnet**

You can find the deployed contracts and interactions in the Remix workspace or test them on Sepolia.

---

## 🧠 Purpose

This repo is part of my on-chain proof-of-work:  
> *I’m not just learning DeFi — I’m rebuilding it from first principles.*

It’s a self-contained, transparent build showing:
- Deep understanding of DeFi math and mechanics
- Comfort with Solidity without abstractions
- Early infrastructure for a modular DeFi + space data protocol: **LUNE**

---

## 📌 Next Steps

- Simulate token liquidity and swap scenarios
- Expand LP logic to ERC-20 LP tokens
- Gas optimization
- Integrate into LUNE dashboard in future phase

---

## 📜 License

MIT

---

## 🤝 Connect

Feel free to fork, test, and contribute.  
Let’s build smarter, not noisier.

> Built with ❤️ using Remix, Notion, ChatGPT, and grit.


