# STAT-ARB

Most trading strategies try to predict where prices go. Statistical arbitrage doesn't. It finds two assets that move together, waits for them to diverge, and bets on convergence. No forecast required -- just the assumption that a historically stable relationship will hold.

That's what makes it elegant: it's grounded in cointegration tests and mean-reversion statistics rather than speculation about the future.

This project is a research platform for building, testing, and visualizing stat arb strategies. Pairs selection via cointegration analysis. Spread modeling. Entry/exit signal generation. Backtesting with realistic assumptions about slippage and costs.

Early stage -- the repo is scaffolded but the research tooling isn't built yet.

```bash
npm install && npm run dev
```
