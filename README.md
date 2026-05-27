# The Beaks NFT - Minter Sales & Distribution Dashboard

This repository contains the verified post-mint sales, transfers, and wallet distribution data for **The Beaks** NFT collection on Ethereum. It features a standalone, interactive, glassmorphic web dashboard allowing real-time search, sorting, and classification audits.

> **Data Snapshot**: May 27, 2026, 20:30 UTC

👉 **Live Dashboard Demo**: [manfromhellxbt.github.io/beaks-nft-dashboard](https://manfromhellxbt.github.io/beaks-nft-dashboard/)

---

## 📈 Audited Minter Activity & Supply Breakdown

Through smart contract ownership audits, we verified the exact distribution of the collection's supply:
*   **Community Mints**: **1,081 unique wallets** minted exactly **1 NFT** each.
*   **Developer Reserve**: **1 developer wallet** (the verified contract owner: `0x44b8b8e5ca0c8f16eef957a744b9c5c8b899e402`) minted exactly **30 NFTs** (Tokens `#1` to `#30`) as a reserve.
*   **Developer Status**: The developer wallet is currently **holding all 30 of its reserved NFTs** (0.0% sold/transferred).

### Consolidated Activity & Distribution Summary:
*   **Sold**: **536 NFTs** (representing 536 unique community wallets) — **49.5%** of minters.
*   **Transferred**: **173 NFTs** (representing 173 unique community wallets) — **16.0%** of minters.
*   **Still Holding (Community)**: **372 NFTs** (held by 372 unique community wallets) — **34.4%** of minters.
*   **Still Holding (Developer)**: **30 NFTs** (held by the 1 contract owner wallet) — **0.1%** of minters.
*   **Total Collection Stats**: **1,111 NFTs** minted by **1,082 unique wallets**.
*   **Total Verified Sales Volume**: **84.36 ETH/WETH**

---

## 🛍️ Marketplace Distribution Summary

All 536 verified sales were settled via public marketplaces (OpenSea / Blur) utilizing the Seaport 1.6 protocol.

### Settlement Tokens:
*   **Native ETH Settlements**: **377 sales** (70.3%) — paid directly in Ether (including 19 sales executed via smart contract wallets utilizing ERC-4337 Account Abstraction).
*   **WETH Settlements**: **159 sales** (29.7%) — paid in Wrapped Ether (settled from accepted collection bids or offers).

---

## 💻 Dashboard Features

*   **Interactive Search**: Instantly filter by Wallet Address, Recipient Address, or Token ID.
*   **Segment Tabs**: Filter easily between **All**, **Sold**, **Transferred** (pure transfers without sale payouts), and **Holding** (minters still holding their minted assets).
*   **Price Metrics**: Tracks detailed transacted price (Average: `0.157 ETH/WETH`, Min: `0.121 ETH/WETH`, Max: `0.220 ETH/WETH`).
*   **Multi-Snapshot Support**: Dynamically switch between multiple historical snapshots (May 26, May 27) with instantaneous on-the-fly summary recalculations.
*   **Zero Dependencies**: Standalone HTML/CSS/JS file requiring no installation or setups. Double-click `index.html` to run.

---

## 📁 Repository Structure

*   `index.html` - Standalone interactive dashboard file.
*   `data.json` - Raw audited dataset containing all 1,111 tokens, minter addresses, status, transaction hashes, and transacted prices.
