# Navnoor Bawa

**Quantitative researcher and research engineer focused on derivatives, volatility, fixed income, and statistical arbitrage.**

I build and audit empirical research systems. My work emphasizes point-in-time data, executable timing, realistic costs, leakage controls, multiple-testing discipline, and reproducible metrics. When a result does not survive review, I publish the failure and correct the claim.

I am the founder and quantitative researcher at **Navnoor Bawa Research LLC**, a freelance markets analyst at **[FX Empire][fx-empire]**, and a Computer Science and Engineering undergraduate at **Thapar Institute of Engineering & Technology** (May 2027). Previously, I worked at Quant Insider and as a WorldQuant BRAIN Research Consultant.

[Research writing][writing] | [LinkedIn][linkedin] | [Medium][medium] | [YouTube][youtube] | [Email][email]

## Selected research

- **[Russell 3000 Statistical Arbitrage][stat-arb]** ([research site][stat-arb-site])

  Kalman-spread and regime-gated pairs research with five cost profiles and 19 walk-forward windows. Only the final 10 windows are treated as clean out-of-sample evidence because earlier windows inherit future universe selection. Under realistic next-day fills, the OOS result is statistically insignificant (`p = 0.83`); the negative conclusion is retained rather than presented as deployable alpha.

- **[Joint SPX/VIX Calibration and Volatility System][vol-system]** ([live system][vol-system-live])

  Joint Heston/Bates calibration, path-dependent volatility research, and 637 automated tests. The audit trail records four corrections - look-ahead bias, a circular feature, label noise, and a strike-rolling bug - and explicitly separates model-implied P&L from traded fills.

- **[WTI Crude Oil Volatility Research][wti]** ([live system][wti-live])

  The original direction edge was identified as look-ahead leakage and retracted. The surviving HAR-IV model reaches 72.7% next-week volatility-direction accuracy versus a 65.1% mean-reversion baseline across 439 purged OOS weeks; its level forecast records `R^2 = 0.50` versus `0.32` for persistence.

- **[U.S. Treasury Rates Monitor][treasury]** ([live system][treasury-live])

  Official U.S. Treasury CMT observations, Federal Reserve H.15 history, curve spreads, event windows, and ex-post regime analysis. Delayed CBOT futures proxies remain explicitly separate from the official daily curve, and deterministic release checks independently verify data lineage and calculations.

Additional derivatives work: [SABR interest-rate volatility smile engine][sabr] | [options pricing and strategy analyzer][options]

## Recognition

**[Winner, Trilemma Beta Global Data Science Tournament][trilemma] (2024)** - probabilistic Bitcoin-return modeling in a field of 214 teams.

## Research standard

Every result should make the information set, execution timestamp, sample window, missing-data treatment, trading costs, baselines, and validation protocol explicit. I prefer a reproducible negative result to a profitable backtest that depends on hidden assumptions.

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
