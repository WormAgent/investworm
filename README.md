# 🪱 InvestWorm

**An open-source AI agent that researches investments for you.**

InvestWorm digs through market data, news and filings so you don't have to. It summarizes what matters, tracks your watchlist and explains its reasoning — you make the decisions.

> ⚠️ **Not financial advice.** InvestWorm is a research tool. It does not execute trades and its output should not be taken as investment advice. Always do your own research.

Part of the [<org>](https://github.com/<org>) family of open-source AI agents, alongside [WorkWorm](https://github.com/<org>/workworm).

---

## Features

- 📊 **Market research** — pulls prices, fundamentals and news for any ticker
- 📰 **News digest** — summarizes relevant news and filings for your watchlist
- 🧠 **Explainable analysis** — every conclusion comes with its sources and reasoning
- 👀 **Watchlist tracking** — alerts you when something changes
- 🔌 **Bring your own model** — works with <Claude / OpenAI / local models>

> 🚧 Early development. Features marked above may be in progress.

## Quickstart

```bash
git clone https://github.com/<org>/investworm.git
cd investworm
pip install -r requirements.txt
cp .env.example .env   # add your API keys
python -m investworm
```

## Configuration

| Variable | Description |
|---|---|
| `ANTHROPIC_API_KEY` | API key for the LLM provider |
| `<DATA_API_KEY>` | API key for market data |

## Roadmap

- [ ] Ticker research agent
- [ ] Watchlist + alerts
- [ ] Portfolio overview
- [ ] Web UI

## Contributing

Contributions are welcome! Open an issue to discuss what you'd like to change, or send a PR. See [CONTRIBUTING.md](https://github.com/<org>/.github/blob/main/CONTRIBUTING.md).

## License

[Apache-2.0](LICENSE)
