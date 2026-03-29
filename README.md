# Awesome Midnight dApps

(EDIT: There's now also an official repo: https://github.com/midnightntwrk/midnight-awesome-dapps )

---

## Build on Midnight — Ship in Minutes

**The fastest way to go from zero to a live Midnight dApp:**

1. Install the [1AM Wallet](https://1am.xyz) — your users get **gas-free transactions** out of the box. No dust tokens needed. No proof server to run. The wallet handles ZK proving, fee sponsorship, and transaction submission automatically.

2. Use [1AM ProofStation](https://api.1am.xyz/docs) — hosted ZK proof generation that balances transactions with dust so your users never touch gas fees. Your DApp talks to the wallet, the wallet talks to ProofStation. Three API endpoints: [preview](https://api-preview.1am.xyz), [preprod](https://api-preprod.1am.xyz), [mainnet](https://api.1am.xyz).

3. Clone the [ZKMint starter template](https://github.com/webisoftSoftware/zk-mint) — a production-ready Next.js DApp with wallet connection, contract deployment, and ZK proofs already wired. Study it, fork it, build on top of it.

4. Or use [1AM AI Builder](https://build.1am.xyz) to generate Compact smart contracts with AI, or install [Midnight Agent Skills](https://github.com/UvRoxx/midnight-agent-skills) (`npx midnight-agent-skills`) to extend Claude Code, Cursor, or Copilot with Midnight development patterns.

**The key insight:** Your DApp never calls the proof server directly. Route everything through the [1AM Wallet DApp Connector](https://1am.xyz/developers) — no CORS issues, no API keys, no server setup. Users click approve, the wallet does the rest.

---

## 1AM Ecosystem

### [1AM Wallet](https://1am.xyz) — Browser Extension
The privacy-first wallet for Midnight Network. DApp Connector API (`window.midnight['1AM']`), built-in ZK proving via ProofStation, dust sponsorship (users pay zero gas), multi-network (Preview, Preprod, Mainnet), side panel support. ([Install](https://1am.xyz/install-beta) | [Developer Docs](https://1am.xyz/developers))

### [1AM ProofStation](https://api.1am.xyz/docs) — Hosted ZK Proving
Every Midnight transaction needs a ZK proof. ProofStation generates them in <1 second. It also balances transactions with dust so users don't need gas tokens. DApps never call it directly — the wallet handles it. Free tier for the ecosystem.

### [ZKMint](https://zkmint.1am.xyz) — Night-ID & Token Launchpad
Register `.night` names on-chain with zero-knowledge proofs. Shared registry contracts on Preview and Preprod — users register, not deploy. Also features bonding curve token launches with optional privacy. Full source available as a starter template for developers. ([Source](https://github.com/webisoftSoftware/zk-mint))

### [1AM Explorer](https://explorer.1am.xyz) — Block Explorer
View transactions, contracts, and blocks across Preview, Preprod, and Mainnet. Direct links with network parameter: `explorer.1am.xyz/tx/{hash}?network=preview`.

### [1AM AI Builder](https://build.1am.xyz) — AI Contract Builder
Write Midnight Compact smart contracts with AI assistance. Generate, compile, test, and deploy — all from the browser.

### [Midnight Agent Skills](https://github.com/UvRoxx/midnight-agent-skills) — AI Dev Tools
Extend your AI coding agent with Midnight development skills. Covers Compact contracts, wallet integration, deployment, testing, and infrastructure setup. ([npm](https://www.npmjs.com/package/midnight-agent-skills))

### [Dominion](https://dominion.fun) — On-Chain Poker
Mental poker cryptography with ZK proofs on Midnight. Provably fair card dealing without a trusted dealer.

### [1AM App Registry](https://github.com/webisoftSoftware/1AM-app-registery) — DApp Directory
Open registry of dApps compatible with the 1AM wallet. Submit your DApp via PR.

---

## Community dApps

* [Counter Dapp example](https://github.com/midnightntwrk/example-counter) + [tutorial]( https://docs.midnight.network/develop/tutorial/building/counter-build )

* Compact counter: https://github.com/claudebarde/compact-counter-test

* Bulletin Board example: https://docs.midnight.network/develop/tutorial/creating/scenario

* Hello World starter template https://github.com/CylinderAdmin/midnight-starter

* Anonymous Q+A dashboard https://github.com/ErickRomeroDev/hackathon-midnight-2

* Overcollateralised privacy preserving stablecoin: https://github.com/LucentLabss/statera-protocol

## ZK Identity Hackathon entries:

* https://github.com/bricktowers/midnight-identity

* https://github.com/ErickRomeroDev/midnight-identity-token

* https://github.com/HeikkiRuhanen/ethiopian-identity-wallet

* https://github.com/midnames-protocol/MidnightHackathon

* https://github.com/bytewizard42i/SentinelDID-poc

* https://github.com/laughtt/face-recognition-midnight

## Battleships Implementations:
 
* https://github.com/bricktowers/midnight-seabattle

* https://github.com/eddex/midnight-sea-battle-hackathon

* https://github.com/mediocrehacker/midnight-battleship

* https://github.com/ErickRomeroDev/naval-battle-game_v2

## NFTs

* [Midnight Kitties](https://github.com/riusricardo/midnight-kitties/blob/main/packages/contracts/kitties/src/kitties.compact)

## Indexers / Block exploerers / Visualisations

* https://github.com/mediocrehacker/Midnightscan (Rust / Leptos)

* https://github.com/AIQUANT-Tech/explorer (JS / Next.js)
 
* Fork of midnight-indexer adding an MCP server: https://github.com/semsorock/midnight-indexer

* [Midnight Live View](https://github.com/Midnight-Scripts/Midnight-Live-View) (for SPO runners)
 
* [Midnight Side Chain Monitoring](https://github.com/Midnight-Scripts/Midnight-Side-Chain-Monitoring)

* Staking pool visualisation: https://midnight.poolinfo.me/ ( https://github.com/Midnight-Scripts/push-status )

* Check registration: https://github.com/Midnight-Scripts/Check_Registration

## Contracts

* Open Zeppelin contracts for ERC20 tokens and more: https://github.com/OpenZeppelin/compact-contracts

## Tooling

* Midnight quick started: https://github.com/luislucena16/midnight-quick-starter
  
* dapp development framework: https://github.com/kaleababayneh/create-midnight-app
 
* dapp development framework: https://github.com/kaleababayneh/scaffold-midnight

* [midnightpy - Python SDK](https://github.com/Techgethr/midnightpy)
  
* Helm chart to install all components required to run a Midnight SPO: https://github.com/0xstrong/midnight-mnn-helm

## Tutorials:

* [Midnight Forge](https://github.com/bytewizard42i/MidnightForge)
  * Decentralised Identity, NFTs and tutorials. 

* Midnight Tutorial in Korean https://github.com/jungmyeong96/midnight_tutorial/tree/main


## Example Apps Repo

A historical repo of the midnight example dapps is maintained here until an official one exists:

https://github.com/gilescope/midnight-example-applications

( https://github.com/midnightntwrk/example-counter has now been put in a repo!)
