# The Beaks NFT - Minter Sales & Distribution Dashboard

This repository contains the verified post-mint sales, transfers, and wallet distribution data for **The Beaks** NFT collection on Ethereum. It features a standalone, interactive, glassmorphic web dashboard allowing real-time search, sorting, and classification audits.

> **Data Snapshot**: May 26, 2026, 19:30 UTC

👉 **Live Dashboard Demo**: [manfromhellxbt.github.io/beaks-nft-dashboard](https://manfromhellxbt.github.io/beaks-nft-dashboard/)

---

## 📈 Audited Sales & Distribution Metrics

*   **Total Collection Supply**: 1,111 NFTs
*   **Unique Minter Wallets**: 1,082
*   **Total Transacted Volume**: **66.41 ETH/WETH**
*   **Minter Wallets Who Sold**: **407 Wallets** (37.6%)
*   **Minter Wallets Still Holding**: **161 Wallets** (14.9%)

---

## 🛍️ Marketplace Distribution Summary

All 407 verified sales were settled via public marketplaces (OpenSea / Blur) utilizing the Seaport 1.6 protocol.

### Settlement Tokens:
*   **Native ETH Settlements**: **269 sales** (66.1%) — paid directly in Ether (including 29 sales executed via smart contract wallets utilizing ERC-4337 Account Abstraction).
*   **WETH Settlements**: **138 sales** (33.9%) — paid in Wrapped Ether (settled from accepted collection bids or offers).

---

## 💻 Dashboard Features

*   **Interactive Search**: Instantly filter by Wallet Address, Recipient Address, or Token ID.
*   **Segment Tabs**: Filter easily between **All**, **Sold**, **Transferred** (pure transfers without sale payouts), and **Holding** (minters still holding their minted assets).
*   **Price Metrics**: Tracks detailed transacted price (Average: `0.163 ETH/WETH`, Min: `0.121 ETH/WETH`, Max: `0.220 ETH/WETH`).
*   **Zero Dependencies**: Standalone HTML/CSS/JS file requiring no installation or setups. Double-click `index.html` to run.

---

## 📁 Repository Structure

*   `index.html` - Standalone interactive dashboard file.
*   `data.json` - Raw audited dataset containing all 1,111 tokens, minter addresses, status, transaction hashes, and transacted prices.
