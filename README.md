# Trading Workspace

## Structure
- `daily_stock_analysis/` — LLM-powered daily signals for US + HK stocks
- `openbb/` — Research terminal (Bloomberg alternative)
- `freqtrade/` — Crypto signal bot (Binance)
- `ai-hedge-fund/` — Multi-agent investor simulation
- `config/` — API keys and shared config
- `logs/` — Output logs

## Setup Status
- [ ] daily_stock_analysis — needs: LLM key + financial data key
- [ ] OpenBB — needs: financial data key (Alpha Vantage free tier OK)
- [ ] freqtrade — needs: Binance API key
- [ ] ai-hedge-fund — needs: LLM key + financial data key

## API Keys to Get
1. LLM: https://platform.openai.com/api-keys (OpenAI) OR https://console.anthropic.com (Anthropic)
2. Financial data: https://www.alphavantage.co/support/#api-key (free, instant)
3. Binance: Binance app > Profile > API Management > Create API
