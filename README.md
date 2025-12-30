# TxchyaAI

A specialized Solana DeFi research assistant built on ElizaOS framework.

## � Phase 1: Solana Research Assistant
- **Telegram bot:** @Txchya_Bot
- **Focus:** Solana blockchain analytics
- **Function:** Market analysis, wallet research, price monitoring
- **Status:** In development

## � Commands
- `!price SOL` - Current Solana price
- `!price JUP` - Any token price
- `!wallet <address>` - Analyze wallet holdings
- `!top tokens` - Trending tokens
- `!dex volume` - DEX volume analysis
- `!nft <collection>` - NFT floor price
- `@txchyaai help` - Show all commands

## � Architecture

## 🚀 Quick Start
```bash
# Clone
git clone https://github.com/0xNefu/TxchyaAI.git
cd TxchyaAI

# Install
bun install

# Configure
cp .env.example .env
# Edit .env with your API keys

# Run
bun run dev

🔧 Tech Stack

    Framework: ElizaOS

    Blockchain: Solana (@solana/web3.js)

    AI: OpenAI GPT-4

    APIs: CoinGecko, Birdeye, DEX Screener

    Voice: ElevenLabs (coming soon)

📁 Project Structure

TxchyaAI/
├── agents/
│   └── txchyaai/          # Agent configuration
├── plugins/
│   └── txc-solana/        # Solana plugin (in progress)
├── .env.example           # Configuration template
└── README.md              # This file

📈 Development Roadmap

    ✅ Agent foundation & Telegram integration

    🚧 Solana price commands (!price SOL)

    🔜 Wallet analysis (!wallet <address>)

    🔜 DEX analytics (!dex volume)

    🔜 NFT research (!nft <collection>)

📝 License

Built on ElizaOS - MIT License
