# Modulr

**An x402 component marketplace built for crypto-native builders and technical users.**

Access premium on-chain tools and receive structured professional output, exportable in any format. No accounts, no subscriptions, no friction.

Live on Solana mainnet. Pay with USDC or $MODU. Permanent report storage.

---

## What is Modulr?

Modulr is a live, functioning on-chain marketplace for crypto infrastructure tools. Users connect a Solana wallet, pay in USDC or $MODU, and receive immediate access to professional-grade reports and analytics generated instantly in-browser and permanently saved to their dashboard.

Every tool on Modulr is pay-per-use. One payment unlocks one generation. Reports are saved to the connected wallet's dashboard and re-downloadable at any time in any of five formats: PDF, HTML, MD, TXT or JSON.

No accounts. No subscriptions. No data sent to a server during tool use.

---

## Live Tools

Five tools are live on Modulr today.

### Wallet Risk Report Generator — 0.25 USDC / $MODU

Fetches up to 1,000 on-chain transactions via Helius RPC and computes a heuristic risk score across five dimensions: wallet age, activity level, token diversity, balance consistency and dormancy. Each dimension includes a confidence label based on available data quality.

Outputs a full report with risk score, wallet type classification (Bot, Whale, DeFi Trader, NFT Collector, Pump.fun Trader and more), detected protocols (Jupiter, Raydium, Orca, Magic Eden, pump.fun, Meteora and more), NFT holdings count via Helius DAS, funding source from oldest transaction, 12-month activity timeline, counterparty analysis with pattern detection and a plain-English analysis verdict. Exportable in PDF, HTML, MD, TXT or JSON.

### Token Launch Checklist Generator — 0.50 USDC / $MODU

Takes structured project inputs and produces a readiness score with section-level analysis, risk flags and recommended next steps. Paste a Solana mint address to trigger on-chain verification via Helius — fetches mint authority, freeze authority, supply, decimals and liquidity pool status directly from chain, then flags discrepancies between what you claimed and what the chain actually shows.

Outputs a launch verdict paragraph with go/no-go assessment, section blockers with Critical, High and Medium impact labels, risk flags and recommended next steps. Works without a mint address for non-Solana or pre-deploy projects.

### Smart Contract Audit Summary — 1.00 USDC / $MODU

Scans pasted Solidity, Rust/Anchor or Move code against 30+ vulnerability patterns across Critical, High, Medium, Low and Informational severity levels. Includes a dedicated gas optimisation section with 8 patterns covering storage loops, redundant writes and type inefficiencies.

Outputs a security risk score, a separate code quality score (0–100) measuring documentation, standards usage and validation patterns, severity-ranked findings, a gas optimisation section, a security checklist, suggested fixes, positive signals and an executive summary with a plain-English deploy recommendation: Deploy, Deploy with caution, Address findings first or Do not deploy.

### Token Website Generator — 3.00 USDC / $MODU

Generates a complete, production-ready token launch website from project details. AI-powered, fully responsive, single HTML file with inline CSS, animations and a copy-CA button. Four style vibes: minimal, aggressive, professional or neon. Supports logo upload and community link detection for Twitter, Telegram and Discord.

### AI Agent Generator — 2.00 USDC / $MODU

Describe the agent you want and get a complete, production-ready TypeScript script back. Specify the agent type, target chain, trigger conditions, parameters and framework — Modulr generates a complete, runnable agent with setup instructions, required environment variables and a dependencies list. Download as a ZIP.

8 agent types: Trading Bot, Wallet Monitor, Price Alert, DeFi Automation, NFT Sniper, Portfolio Tracker, Liquidity Manager and Custom. Supports Solana, Ethereum, Base and Arbitrum. Frameworks: Vanilla TypeScript, Anchor, Ethers.js and Viem.

---

## Modulr SDK

The Modulr SDK is live. Developers can install it with a single command and call Modulr's tools programmatically — no API key, no setup, no browser required.

```bash
npm install @modulr/sdk
```

```ts
import { Modulr } from '@modulr/sdk'

const modulr = new Modulr()

const risk = await modulr.walletRisk.analyze('9apA5U8...')
const agent = await modulr.agent.generate({ agentName: 'Whale Tracker', agentType: 'Wallet Monitor', ... })
```

Full documentation at [modulr402.com/developers](https://modulr402.com/developers). SDK source at [github.com/Modulr402/modulr-sdk](https://github.com/Modulr402/modulr-sdk).

---

## How it Works

**Pay with USDC:**
1. Connect your Solana wallet (Phantom or Solflare)
2. Select a tool and send USDC to the receiver wallet
3. Paste the transaction signature for on-chain verification
4. Generate your report instantly in-browser
5. Export in any format — saved permanently to your dashboard

**Pay with $MODU:**
1. Connect your Solana wallet (Phantom or Solflare)
2. Select a tool — your $MODU balance and discount tier are detected automatically
3. One-click checkout — approve the transaction in your wallet
4. Access granted instantly after on-chain confirmation
5. Generate and export — output saved permanently to your dashboard

---

## Platform Features

- Live on Solana mainnet with USDC and $MODU payments
- One-click $MODU checkout via connected wallet
- On-chain transaction verification via Helius RPC
- Automatic $MODU holder discount tiers: 10% to 30% off
- Keycard integration — hold 500,000+ $MODU for 1 free tool per week
- Pay-per-use access model, no subscriptions
- Permanent report storage tied to connected wallet
- Multi-format export: PDF, HTML, MD, TXT, JSON
- Wallet-authenticated dashboard
- Phantom and Solflare wallet support
- Modulr SDK — programmatic access to all tools
- Listed on Voidly and Meterflow agent marketplaces

---

## $MODU Holder Benefits

Holding $MODU unlocks automatic discounts and free weekly access.

### Discount Tiers

| Tier | Min Balance | Discount |
|---|---|---|
| Holder | 100,000 $MODU | 10% off |
| Supporter | 500,000 $MODU | 15% off |
| Builder | 2,000,000 $MODU | 20% off |
| Architect | 4,000,000 $MODU | 30% off |

### Keycard Free Weekly Credit

Hold 500,000 $MODU or more and receive one free tool generation per week, powered by Keycard. Applies to Wallet Risk Report, Token Launch Checklist and Smart Contract Audit. Resets every 7 days.

---

## Partners

### Meterflow
Modulr tools are listed as official Partner Agent Tools on the Meterflow registry, accessible and payable via the x402 protocol.
- [meterflow.fun/registry](https://www.meterflow.fun/registry)
- [@meterflowsol](https://x.com/meterflowsol)

### Keycard
Keycard is the access layer for Solana projects — gate content, communities and tools behind token ownership, NFT collections or wallet lists. Powers the Modulr free weekly credit system.
- [keycardsol.xyz](https://keycardsol.xyz/)
- [@keycardsol](https://x.com/keycardsol)

### Voidly
Modulr tools are listed in the Voidly Pay marketplace — AI agents can discover and pay for Modulr tools autonomously via x402.
- [voidly.ai/pay/marketplace](https://voidly.ai/pay/marketplace)
- [@Voidly_ai](https://x.com/Voidly_ai)

---

## Roadmap

### Q2 2026 — Foundation Layer (Complete)

- ✓ Marketplace core architecture
- ✓ Wallet infrastructure layer — Phantom and Solflare connectivity
- ✓ Modulr design system
- ✓ $MODU Payment System — one-click checkout, discount tiers, on-chain verification
- ✓ Modulr SDK — programmatic access to all tools, no API key required

### Q3 2026 — Marketplace Systems (Planned)

- Webhook & Event Infrastructure — real-time push notifications for analysis completion, risk threshold breaches and on-chain activity
- $MODU Payment Infrastructure — native payment support with wallet-based checkout flows
- Secure Digital Delivery — wallet-authenticated delivery with protected downloads and ownership verification

### Q4 2026 — Infrastructure Expansion (Research)

- Multi-chain transaction layer
- Modulr API infrastructure
- Advanced creator infrastructure

### Q1 2027 — Intelligent Systems (Planned)

- AI-assisted infrastructure
- Automated marketplace operations
- Smart analytics engine

### Q2 2027 — Ecosystem Scaling

- Enterprise marketplace infrastructure
- External developer ecosystem
- Global infrastructure scaling

---

## $MODU Token

$MODU is the Modulr ecosystem token, launched on pump.fun. The platform is live and generating real revenue at launch. $MODU holders are backing a functioning product, not a roadmap.

### Token Allocation

| Wallet | Allocation | Purpose |
|---|---|---|
| Dev Wallet | 70% | Development, infrastructure, operations and long-term Modulr growth |
| Buyback Wallet | 15% | Weekly $MODU buybacks, bought-back tokens locked for 6 months |
| Giveaway Wallet | 15% | Weekly community giveaways and ecosystem rewards |

### Weekly Schedule

| Day | Event |
|---|---|
| Friday 10:00 CET | Giveaways open for the week |
| Saturday | Creator fees claimed, 15% to buyback wallet, buybacks executed, 15% to giveaway wallet |
| Sunday 20:00 CET | Weekly giveaway winner announced |

### $MODU Utility — Live Now

- One-click $MODU payments across all tools
- Automatic holder discount tiers: 10% to 30% off
- Keycard free weekly credit for 500,000+ holders
- All $MODU payments permanently burned

### $MODU Utility — Coming

- SDK tier gating
- Revenue-funded buyback mechanics
- Governance over marketplace direction

---

## Transparency

Modulr is live infrastructure in active development. The tools available today use heuristic analysis. They are not replacements for professional audits, legal advice or financial due diligence. All reports carry explicit disclaimers and should be used as a starting point for further review, not a final verdict.

$MODU is a utility token, not a financial instrument or investment. Token value is not guaranteed and depends on platform adoption, market conditions and continued development.

---

## Links

- Website: [modulr402.com](https://modulr402.com/)
- Developers: [modulr402.com/developers](https://modulr402.com/developers)
- SDK: [github.com/Modulr402/modulr-sdk](https://github.com/Modulr402/modulr-sdk)
- X: [@Modulr402](https://x.com/Modulr402)
- Token: pump.fun — search $MODU
