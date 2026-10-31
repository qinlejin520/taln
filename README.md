# TALN

**$TALN** — a fixed-supply token minted on BNB Smart Chain, built for holders of `.ai` Agent IDs (Binance Agentic Wallet / SPACE ID).

- Website: https://taln.live
- Whitepaper: https://taln.live/whitepaper
- Guide for AI agents: https://taln.live/llms.txt (also in this repo as `llms.txt`)
- X: https://x.com/TALN_official
- Telegram: https://t.me/+Vpn-bY2r3LIxOGY1

## How it works

$TALN has a fixed supply of 444 trillion, released only through its on-chain mint contract on BNB Smart Chain (chainId 56). Verified Agent ID holders mint shares at a tiered USDT price starting at 1 USDT per share; every share pays exactly **100,000,000 $TALN**. 100% of mint payments go directly to the project treasury wallet.

Wallet-to-wallet transfers and trading stay locked until **10,000 shares** have been minted in total, then unlock permanently. Identity verification, quotas (10 shares per Agent ID, +1 per invite or completed social task) and the 353-step pricing ladder (1U → 8.07U) are all enforced on-chain by the contracts.

## Contracts (BNB Smart Chain)

| Contract | Address |
| --- | --- |
| $TALN token | `0x2417629B090D811FE64271D010986b0dE81FA9e5` |
| Mint | `0x045e7aAf012e906830b9B6550755440338C20cb4` |
| Identity verifier | `0x70f0987F7eB1dC137Ca778cA821922F0ba95Ecc3` |
| Treasury | `0x8d2f8b1f8a02474447025bdd34b06a8a95b41643` |
| USDT (payment) | `0x55d398326f99059fF775485246999027B3197955` |

Only send payments to the mint contract, and only through its mint functions or the website — a plain transfer to any contract does not mint.

## Status

Live on BNB Smart Chain mainnet since 2026-10-31. Live mint stats: https://taln.live/api/stats
