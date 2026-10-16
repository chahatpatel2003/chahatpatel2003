# Chahat Patel

Computer Science graduate with a focus on quantitative research, financial market analysis, and data-driven software development.

I develop Python-based systems for financial data processing, quantitative analysis, backtesting, and statistical validation. My work spans futures-market research, data engineering, risk-aware modeling, and the evaluation of trading hypotheses using historical data.

I also have a broader technical background in software engineering, machine learning, algorithms, and predictive analytics.

## Financial markets research

**How I work**

- **Data engineering:** tick-level futures data (trades and top-of-book quotes), Parquet and DuckDB pipelines, contract-roll handling and data-quality audits.
- **Backtesting:** event-driven and tick-level fill simulation, explicit transaction costs, and models of prop-firm account rules.
- **Statistical validation:**
  - pre-registered hypotheses and sealed holdouts;
  - walk-forward and out-of-sample testing;
  - bootstrap confidence intervals and permutation nulls;
  - multiple-testing correction.
- **Risk-aware evaluation:** drawdown analysis and Monte Carlo simulation of account survival and payouts.

**Research approach:** My projects emphasize reproducibility, rigorous out-of-sample evaluation, statistical validation, and risk-aware analysis. Research findings—including unsuccessful hypotheses, overfitting, and data-leakage discoveries—are documented transparently in their respective repositories. All trading results represent historical research or paper simulations, not verified live profitability.

| Project | What it demonstrates |
|---|---|
| [nq-strategy-research](https://github.com/chahatpatel2003/nq-strategy-research) | Seven pre-registered strategy tests on Nasdaq-100 futures tick data. Specs are frozen with SHA-256 manifests, the holdout is enforced in code, fills are simulated from the tape, and results face matched-random controls and permutation nulls. All seven were rejected by their own gates. |
| [nq-trading-system](https://github.com/chahatpatel2003/nq-trading-system) | A typed Python research platform: a point-in-time feature store, an event-driven backtester and a Monte Carlo prop-firm account simulator, with 59 documented research phases. The most robust strategy met forward-paper conditions, but its estimated ceiling of about $400 a month per account fell short of the target. |
| [nqgc-research](https://github.com/chahatpatel2003/nqgc-research) | A leak-safe framework built to re-audit earlier work. It showed that a previous +0.19 to +0.31 R per-trade result came from a lookahead (chronology) leak; the corrected strategy had no edge. |
| [gc-intraday-zones](https://github.com/chahatpatel2003/gc-intraday-zones) | 44 pre-registered tests of supply-and-demand zones in gold futures, each against two independent controls, plus a selection-bias null benchmark. |
| [nq-daily-levels](https://github.com/chahatpatel2003/nq-daily-levels) | Tests whether pre-open price levels predict where Nasdaq-100 futures react, with leakage proofs that rebuild results from a truncated tape. Both sealed holdouts failed. |
| [topstep-quant](https://github.com/chahatpatel2003/topstep-quant) | A strategy search ranked by payout before account blow-up, with purged walk-forward validation and multiple-testing correction. Nothing survived out-of-sample validation. |

Also in this area:

- [nq-topstep-system](https://github.com/chahatpatel2003/nq-topstep-system): 13 strategy-discovery passes and an analysis of why each failed.
- [gold-trading-agent](https://github.com/chahatpatel2003/gold-trading-agent): a gold paper-trading agent with live trading gated off.
- [Ai-trading-agent-](https://github.com/chahatpatel2003/Ai-trading-agent-): an archive of my first trading repository and its tick-data pipeline.

## Software engineering, machine learning and computer science

- **Engineering practice in the research code:**
  - typed Python checked with `mypy --strict`;
  - pytest suites, including property-based tests with Hypothesis;
  - command-line tools;
  - reproducible pipelines with hash manifests.
- [image-captioning-transformers](https://github.com/chahatpatel2003/image-captioning-transformers): image captioning with pretrained Hugging Face vision-language models.
- [sliding-puzzle-search](https://github.com/chahatpatel2003/sliding-puzzle-search): breadth-first search versus A* with misplaced-tile and Manhattan-distance heuristics.
- [deep-learning-coursework](https://github.com/chahatpatel2003/deep-learning-coursework): neural networks from NumPy implementations to PyTorch CNNs, self-attention and GPT-2 decoding.
- [wine-classification-quality-prediction](https://github.com/chahatpatel2003/wine-classification-quality-prediction): classification and regression with cross-validation and hyperparameter search.
- [dqn-space-invaders](https://github.com/chahatpatel2003/dqn-space-invaders): a Deep Q-Network agent for Atari Space Invaders.

## Skills

- **Languages:** Python, C++, SQL
- **Quantitative methods:** hypothesis testing, bootstrap and permutation tests, walk-forward validation, Monte Carlo simulation, risk and drawdown analysis
- **Data and analytics:**
  - pandas, Polars, NumPy, SciPy, Matplotlib;
  - PyArrow / Parquet, DuckDB, MySQL;
  - Excel, Power BI.
- **Machine learning:** scikit-learn, LightGBM, PyTorch, Hugging Face Transformers
- **Software engineering:** data structures and algorithms, pytest, mypy, ruff, uv, Git and GitHub, Jupyter

## Education

**B.S. in Computer Science**, California State University, Fresno, May 2026

## Contact

[LinkedIn](https://www.linkedin.com/in/chahatpatel2003)
