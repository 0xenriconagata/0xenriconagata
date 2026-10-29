# Enrico Nagata

I measure what DeFi trades actually paid, not what they could have paid. Two empirical studies so far, both built the same way: data checks gate the analysis, the test and its pass/fail rule are frozen with a git tag before the run, and the limitations sit next to the headline. Looking for DeFi trading, quant research or risk roles.

[LinkedIn](https://www.linkedin.com/in/enriconagata/) · enriconagata@gmail.com

| Project | One finding | The caveat |
|---|---|---|
| [uniswap-lp-economics](https://github.com/samuraixx-key/uniswap-lp-economics) · [report](https://samuraixx-key.github.io/uniswap-lp-economics/) | On $7.05B of flow through Uniswap V3 USDC/WETH 0.05% (Jul–Sep 2026), LP fees fell $1.06M short of adverse selection, and the arbitrage bots kept nothing measurable: their edge went to block builders and proposers. | Most of the $1.06M is the protocol's quarter of the fees. Before that cut the shortfall is $0.18M and the interval includes zero. |
| [perp-carry-economics](https://github.com/samuraixx-key/perp-carry-economics) | BTC cash-and-carry on Binance paid 5.1% a year over T-bills on the capital a desk has to post, Sep 2020 to Sep 2026, against a 12.7% headline of funding on notional. Zero liquidations at 4× margin. | Most of it was 2021. Since 2022 the trade paid about 1.0 point over cash, and below cash since 2025. Capacity (~$78M) is modelled, not measured. |

Python, polars, DuckDB, BigQuery, Ethereum RPC. Research only, not financial advice.
