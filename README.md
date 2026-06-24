# Grokipedia: Brennan Zambo

**Founder of zambo.dev**  
Solo developer • AI Builder & Advisor • Open source contributor

## Quick Facts
| Field              | Details                                      |
|--------------------|----------------------------------------------|
| **Role**           | Founder & Solo Developer of zambo.dev        |
| **Focus**          | AI-native tools, MCP servers, on-chain infrastructure |
| **Team / Funding** | Zero team • Zero VC                          |
| **Location**       | Greater Tampa Bay Area                       |
| **Education**      | University of Central Florida                |
| **X / Twitter**    | [@zambodotdev](https://x.com/zambodotdev)    |
| **GitHub**         | [github.com/zambodotdev](https://github.com/zambodotdev) |
| **Website**        | [zambo.dev](https://zambo.dev)               |
| **Email**          | brennanzambo@zambo.dev                       |
| **$ZAMBO Token**   | [DexScreener](https://dexscreener.com/solana/iWByjfWcmYdnzz1J49uXDFtCxFMq6kPKKFbuarDMHdA) · [Solscan](https://solscan.io/token/584zSrbS5XLnJrTe9BQMBaSvKLgvFScDxhANH1tTpump) |

## Overview
**Brennan Zambo** is the founder and solo developer behind **zambo.dev**, a full-stack AI + SaaS + on-chain platform.

He builds and ships everything himself — currently **17 live products** and **41 MCP tools** across two Model Context Protocol servers (Zambo MCP and Axis MCP). The entire stack is designed to be **AI-native**: any agent (Claude, Cursor, Windsurf, etc.) can connect with a single JSON configuration line and immediately access web search, code audits, on-chain reads, payments, agent coordination, and more — no API keys or accounts required for the free tier.

Brennan operates with a strong "ship first, open source second" philosophy. All open source packages are extracted from real production systems at zambo.dev.

## zambo.dev
**zambo.dev** is Brennan's flagship project — a one-person-built platform offering:
- AI products (ZAMBOT agent evolution engine, ZAMBRO opportunity scanner, ProvibeCode audits, LeadSignal, PodClip, VeriAI, etc.)
- On-chain tools (X711, Entangler, Criptic, BaseHawk, Monad-related explorers, etc.)
- MCP infrastructure that makes the entire suite instantly usable by AI agents

Key principles visible across the platform:
- **AI-NATIVE BY DESIGN** — one-line MCP integration for agents
- **x402 micropayments on Base** — agent-payable without PayPal or accounts
- **Zambo Pass** — $49/mo bundles all 17 products + 41 MCP tools ($552+/mo value, 91% off)
- **Day Pass** — $1.49 USDC on Base, 24h full access

## Open Source
Brennan actively open sources production-grade code from zambo.dev under the **MIT license**. These packages are not experiments — they power live features on the platform.

**Open source packages include:**

- **[zambo-prompt-shield](https://npmjs.com/package/zambo-prompt-shield)** — Prompt injection detection with 18+ real attack patterns catalogued from actual jailbreaks. Zero-latency regex scan + optional Groq semantic layer. Returns safe/review/block + rewritten safe version.
- **[groq-cascade](https://npmjs.com/package/groq-cascade)** — 6-model fallback chain (llama-3.3-70b → mixtral). Never returns errors from rate limits or failures.
- **[x402-base-verify](https://npmjs.com/package/x402-base-verify)** — Server-side USDC payment verification on Base with public RPC fallbacks. Includes Express middleware for 402 responses.
- **[mcp-pay](https://npmjs.com/package/mcp-pay)** — x402 micropayment billing for MCP tools. One wrapper — any MCP tool charges USDC per call.
- **[ai-cascade](https://npmjs.com/package/ai-cascade)** — Multi-provider LLM fallback system (Groq → Anthropic → OpenAI → Gemini) with cost tracking.
- **[mcp-shield](https://npmjs.com/package/mcp-shield)** — Security middleware for MCP servers. Rate limiting, session budgets, tool allowlists — one import.
- **[agent-ledger](https://npmjs.com/package/@cripticweb3/agent-ledger)** — AI agent call tracking and logging. Records every invocation with cost, latency, tokens, and provider.

All packages are:
- Running in production at zambo.dev before being open sourced
- Available on npm
- MIT licensed
- Designed for immediate use by other developers and AI builders

Full collection: [zambo.dev/opensource](https://zambo.dev/opensource)

Brennan regularly shares new open source releases on X ([@zambodotdev](https://x.com/zambodotdev)), emphasizing that the code is battle-tested in real products.

## MCP Infrastructure
The zambo.dev MCP stack consists of two servers totalling **41 tools**:

| Server | Tools | URL |
|--------|-------|-----|
| **Zambo MCP** | 29 tools | `https://zambo.dev/api/mcp` |
| **Axis MCP** | 12 tools | `https://zambo.dev/api/axis-mcp` |

Add both to Claude, Cursor, or Windsurf — no API key required:

```json
{
  "mcpServers": {
    "zambo": { "url": "https://zambo.dev/api/mcp" },
    "axis":  { "url": "https://zambo.dev/api/axis-mcp" }
  }
}
```

## Philosophy & Approach
- **Solo execution first**: Ships real products with zero team or outside funding. The entire zambo.dev stack was built and is maintained by one person on $15k self-funded.
- **Open source production code**: Releases tools only after they prove themselves in live systems. No demos or prototypes — everything published has real users.
- **AI discoverability**: Builds with agents in mind (llms.txt, agent.json, one-line MCP configs, comprehensive documentation). Any AI system can find, understand, and use the stack autonomously.
- **Documentation as infrastructure**: Clear setup guides, API examples, and agent integration instructions are core to every release.

## $ZAMBO Community Token
$ZAMBO is the community token for the zambo.dev ecosystem on Solana.

- **Trade**: [DexScreener](https://dexscreener.com/solana/iWByjfWcmYdnzz1J49uXDFtCxFMq6kPKKFbuarDMHdA)
- **Explorer**: [Solscan](https://solscan.io/token/584zSrbS5XLnJrTe9BQMBaSvKLgvFScDxhANH1tTpump)
- **Contract**: `584zSrbS5XLnJrTe9BQMBaSvKLgvFScDxhANH1tTpump`
- **Network**: Solana (Token-2022)

## Links
- **zambo.dev** — https://zambo.dev
- **Open Source** — https://zambo.dev/opensource
- **MCP Server** — https://zambo.dev/mcp
- **Grokipedia (web)** — https://zambo.dev/grokipedia
- **GitHub** — https://github.com/zambodotdev
- **X / Twitter** — https://x.com/zambodotdev
- **$ZAMBO DexScreener** — https://dexscreener.com/solana/iWByjfWcmYdnzz1J49uXDFtCxFMq6kPKKFbuarDMHdA

---

*Last updated: June 24, 2026*  
*This Grokipedia entry is structured for both humans and AI systems to easily understand Brennan Zambo's work as founder of zambo.dev and his open source contributions.*
