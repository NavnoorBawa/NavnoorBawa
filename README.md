# Navnoor Bawa

**Quantitative researcher and research engineer focused on derivatives, volatility, fixed income, and statistical arbitrage.**

I build and audit empirical research systems. My work emphasizes point-in-time data, executable timing, realistic costs, leakage controls, multiple-testing discipline, and reproducible metrics. When a result does not survive review, I publish the failure and correct the claim.

I am the founder and quantitative researcher at **Navnoor Bawa Research LLC**, a freelance markets analyst at **[FX Empire][fx-empire]**, and a Computer Science and Engineering undergraduate at **Thapar Institute of Engineering & Technology** (May 2027). Previously, I worked at Quant Insider and as a WorldQuant BRAIN Research Consultant.

[Research writing][writing] | [LinkedIn][linkedin] | [Medium][medium] | [YouTube][youtube] | [Email][email]

## Research portfolio

| Program | Validation record | Current conclusion |
| --- | --- | --- |
| **[Russell 3000 Statistical Arbitrage][stat-arb]** ([site][stat-arb-site]) | 19 walk-forward windows; only W10-W19 are selection-clean OOS. Five cost profiles. Survivorship bias is disclosed. | No deployable alpha under next-day execution (`p = 0.83`). The null result is retained. |
| **[Joint SPX/VIX Calibration and Volatility System][vol-system]** ([live][vol-system-live]) | 637 tests. Four audit corrections covering look-ahead, a circular feature, label noise, and strike rolling. | SPX smile RMSE: 0.52 vol points. The VIX-options leg is disabled for structural misspecification; P&L remains model-implied. |
| **[WTI Crude Oil Volatility Research][wti]** ([live][wti-live]) | 439 purged OOS weeks. HAR-IV compared with mean-reversion and persistence baselines. | Volatility direction: 72.7% vs 65.1%. Level `R^2`: 0.50 vs 0.32. The leaked direction strategy was retracted. |
| **[U.S. Treasury Rates Monitor][treasury]** ([live][treasury-live]) | Direct Treasury XML, Federal Reserve H.15 history, and deterministic release checks. | Official daily CMT analytics and delayed CBOT futures proxies remain separate by design. |

Additional derivatives work: [SABR interest-rate volatility smile engine][sabr] | [options pricing and strategy analyzer][options]

## Recognition

**[Winner, Trilemma Beta Global Data Science Tournament][trilemma] (2024)** - probabilistic Bitcoin-return modeling in a field of 214 teams.

## Research standard

I treat the audit trail as part of the result. Every public claim should state its information set, execution timestamp, sample construction, missing-data treatment, costs, baselines, validation protocol, and known failure modes. I prefer a reproducible negative result to a profitable backtest that depends on hidden assumptions.

## Technical focus

- **Research:** time-series analysis, statistical inference, walk-forward validation, factor models, volatility modeling, derivatives pricing, Monte Carlo simulation
- **Engineering:** Python, C++, SQL, NumPy, pandas, SciPy, PyTorch, scikit-learn, XGBoost, QuantLib, TypeScript, React, Linux, Git, CI

Open to quantitative research, derivatives, fixed-income analytics, and research engineering opportunities.

[email]: mailto:navnoorbawa@gmail.com
[fx-empire]: https://www.fxempire.com/author/navnoorbawa
[linkedin]: https://linkedin.com/in/navnoorbawa
[medium]: https://medium.com/@navnoorbawa
[options]: https://github.com/NavnoorBawa/Option-Pricing-and-Strategy-Analyzer
[sabr]: https://github.com/NavnoorBawa/Interest-Rate-Volatility-Smile-Engine
[stat-arb-site]: https://navnoorbawa.github.io/russell3000-pairs-trading/
[stat-arb]: https://github.com/NavnoorBawa/russell3000-pairs-trading
[treasury-live]: https://treasury-rates-monitor.vercel.app/
[treasury]: https://github.com/NavnoorBawa/treasury-rates-monitor
[trilemma]: https://www.trilemma.foundation/tournaments
[vol-system-live]: https://navnoorbawa.me/
[vol-system]: https://github.com/navnoorthapar/vol-system-dashboard
[writing]: https://navnoorbawa.substack.com/
[wti-live]: https://navnoorbawa.github.io/WTI-Crude-Oil-Futures/
[wti]: https://github.com/NavnoorBawa/WTI-Crude-Oil-Futures
[youtube]: https://youtube.com/@TheMathematicalTrader
