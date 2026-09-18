# AI Crypto Sniper MCP

**Autonomous Solana trading bot with 331 MCP tools for AI-assisted control across four trading modes.**

Four trading modes. One Windows desktop app. Full MCP integration for Claude, Cursor, Devin, and any MCP-compatible AI assistant.

## IMPORTANT: Requires the AI Crypto Sniper V5 Windows Application

This MCP server is **useless on its own**. It requires the **AI Crypto Sniper V5** Windows GUI application to be installed and running.

**Download the Windows executable from [aicryptosniper.com](https://aicryptosniper.com/download.html).**

## What It Does

The AI Crypto Sniper watches the Solana blockchain for trading opportunities across four modes:

1. **Meme / New-Token Sniping** — Detects new Pump.fun token launches, applies safety/liquidity/market-cap/volume/holder/age/creator-holding filters, executes buys through Pump.fun bonding curves or Jupiter, and manages positions with take-profit ladders, trailing stops, rug detection, volume-death detection, and momentum-reversal detection.

2. **Spot Trading** — General spot trading via the Jupiter DEX aggregator with market/limit orders, DCA, portfolio rebalancing, risk-level presets, and slippage control.

3. **Perpetual Futures** — Long and short positions with configurable leverage, margin trading, funding-rate controls, liquidation avoidance, market discovery, and signal generation.

4. **Mirror Mode** — Whale-wallet copy trading with proportional sizing, configurable limits, token filtering, and dry-run support.

Using the 331 MCP tools, your AI agent can start/stop bots, execute trades, configure safety filters, query positions and P&L, manage wallets, analyze market data, and fine-tune strategy across all four trading modes.

## Pricing

- **7-day free trial** (168 hours of actual bot running time)
- **First month: $49.99** (50% off with promo code `SOLV4FIRST50`)
- **$99.99/month** thereafter
- **Cancel anytime**

Subscribe at: [https://buy.stripe.com/dRm14ngiB5MBfIK6QM7bW07](https://buy.stripe.com/dRm14ngiB5MBfIK6QM7bW07?prefilled_promo_code=SOLV4FIRST50)

## Installation

```bash
pip install ai-crypto-sniper-mcp
```

## Client Configuration

```json
{
  "mcpServers": {
    "ai-crypto-sniper": {
      "command": "python",
      "args": ["-m", "ai_crypto_sniper_mcp"],
      "env": {
        "AI_CRYPTO_SNIPER_DIR": "P:\\snipe-bot"
      }
    }
  }
}
```

## Links

- **Website:** [https://aicryptosniper.com/](https://aicryptosniper.com/)
- **Download:** [https://aicryptosniper.com/download.html](https://aicryptosniper.com/download.html)
- **MCP Landing Page:** [https://aicryptosniper.com/mcp/](https://aicryptosniper.com/mcp/)
- **PyPI:** [https://pypi.org/project/ai-crypto-sniper-mcp/](https://pypi.org/project/ai-crypto-sniper-mcp/)
- **MCP Registry:** `com.aicryptosniper/ai-crypto-sniper-mcp`

## License

Proprietary. Membership required for live trading after the 7-day trial. Use at your own risk. On-chain trading is risky.
