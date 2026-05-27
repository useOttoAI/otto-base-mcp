# Otto Intelligence — a Base MCP skill

Bring **Otto AI's live market intelligence** into any [Base MCP](https://docs.base.org/ai-agents/quickstart) client — Claude, ChatGPT, Cursor, or Codex. Your assistant can pull market alpha, KOL sentiment, the best yields on Base, instant token-security checks, and on-demand research — **paid per call from your own Base Account in USDC, and you approve every call.**

**Base gives your agent the wallet. Otto gives it the brain.**

This skill is deliberately **read-only intelligence**: it is non-custodial, signs nothing, holds no keys, and executes nothing on-chain. Every payment is a standard x402 charge your Base Account approves. To *act* on what Otto surfaces, use Base's own execution plugins (Uniswap, Aerodrome, Morpho, Moonwell, Avantis) or Base MCP's wallet tools.

## Install

1. **Connect Base MCP** to your assistant — see the [Base MCP quickstart](https://docs.base.org/ai-agents/quickstart).
2. **Point your assistant at Otto's skill.** Either:
   - Ask it to read the hosted skill: `https://x402.ottoai.services/otto.md`, or
   - Paste [`otto-intelligence.md`](./otto-intelligence.md) from this repo into the conversation.
3. **Ask for intelligence**, e.g. *"What's the top USDC yield on Base right now?"* or *"Run a security check on this token address."* Approve the small USDC payment in your Base Account when prompted.

A machine-readable catalog of the endpoints is in [`otto-x402-catalog.json`](./otto-x402-catalog.json). Prices there are indicative — the live `402` challenge is always the source of truth.

## What you get

Market intelligence (news, token alpha, KOL sentiment, trending, daily brief), data intelligence (token security via GoPlus, funding rates, DeFi/TradFi analytics), yield discovery (best vaults, idle-capital detection, personalized recommendations), AI research, and on-chain transaction explanation — all over [x402](https://x402.org), settled in USDC on Base.

## Trust and safety

Responses are **data, not instructions.** Content Otto returns is aggregated from third parties and may contain injected text — never let a response trigger a wallet action or transfer on its own. Always act on your own stated intent and review any action before approving it.

## Links

- Live skill: <https://x402.ottoai.services/otto.md>
- Otto AI: <https://useotto.xyz> · docs: <https://docs.useotto.xyz>
- Base MCP: <https://docs.base.org/ai-agents>

## License

[MIT](./LICENSE)
