# Chahat Patel

Computer Science graduate (B.S., California State University, Fresno, May 2026), based in San Jose, California.

I work across software engineering, data analytics, quantitative research and machine learning. Most of my recent work is a set of Python research systems for financial markets. They include tick-data pipelines, leakage-audited backtesters, and statistical tests that decide whether a trading idea holds up out of sample.

Most of the strategies I tested did not hold up, and I publish those results with their evidence. The value of the work is in the method:

- pre-registered hypotheses and sealed holdouts;
- walk-forward and out-of-sample validation;
- comparisons against matched random entries;
- audits that caught lookahead leaks in my own earlier results.

## Quantitative research

| Project | What it demonstrates |
|---|---|
| [nq-strategy-research](https://github.com/chahatpatel2003/nq-strategy-research) | Seven pre-registered strategy tests on Nasdaq-100 futures tick data, covering trades and top-of-book quotes: <br>• Specs are frozen with SHA-256 manifests. <br>• The sealed holdout is enforced in code. <br>• Fills are simulated from the tape. <br>• Results are compared against matched-random controls and permutation nulls. <br>All seven hypotheses were rejected by their own pre-registered gates. |
| [nq-trading-system](https://github.com/chahatpatel2003/nq-trading-system) | A typed Python research platform: a point-in-time feature store, an event-driven backtester and a Monte Carlo prop-firm account simulator. It records 59 research phases. The most robust strategy met forward-paper conditions, but its estimated income ceiling, about $400 a month per account, fell short of the target. |
| [nqgc-research](https://github.com/chahatpatel2003/nqgc-research) | A leak-safe backtest framework built to re-audit earlier work. It showed that a previous +0.19 to +0.31 R per-trade result came from a lookahead (chronology) leak; the corrected strategy had no edge. |
| [gc-intraday-zones](https://github.com/chahatpatel2003/gc-intraday-zones) | 44 pre-registered tests of supply-and-demand zones in gold futures. Each is measured against two independent controls and checked with a selection-bias null benchmark. |
| [nq-daily-levels](https://github.com/chahatpatel2003/nq-daily-levels) | Asks whether price levels chosen before the open predict where Nasdaq-100 futures react. It includes leakage proofs that rebuild results from a truncated tape. Both sealed holdouts failed; one real location effect survived but was not tradable. |
| [topstep-quant](https://github.com/chahatpatel2003/topstep-quant) | A strategy search ranked by payout before account blow-up, using purged and embargoed walk-forward validation and multiple-testing correction. Nothing survived out-of-sample validation. |
| [nq-topstep-system](https://github.com/chahatpatel2003/nq-topstep-system) | Thirteen strategy-discovery passes on leakage-audited features, followed by a written analysis of why each class of idea failed. |
| [gold-trading-agent](https://github.com/chahatpatel2003/gold-trading-agent) | A risk-first gold (XAUUSD) paper-trading agent with 16 rule-based strategies and walk-forward and Monte Carlo backtests. Live trading is gated off. |
| [Ai-trading-agent-](https://github.com/chahatpatel2003/Ai-trading-agent-) | An archive of my first trading repository, including a resumable tick-data download and validation pipeline. |

## Computer science and machine learning

- [image-captioning-transformers](https://github.com/chahatpatel2003/image-captioning-transformers): image captioning with pretrained Hugging Face vision-language models.
- [deep-learning-coursework](https://github.com/chahatpatel2003/deep-learning-coursework): neural networks built from NumPy implementations up to PyTorch CNNs, self-attention and GPT-2 decoding (CSCI 167).
- [sliding-puzzle-search](https://github.com/chahatpatel2003/sliding-puzzle-search): breadth-first search versus A* with misplaced-tile and Manhattan-distance heuristics.
- [wine-classification-quality-prediction](https://github.com/chahatpatel2003/wine-classification-quality-prediction): classification (logistic regression, k-NN, ROC/AUC) and quality regression (linear, MLP), with cross-validation and hyperparameter search.
- [dqn-space-invaders](https://github.com/chahatpatel2003/dqn-space-invaders): a Deep Q-Network agent for Atari Space Invaders, with training videos.

## Skills

- **Languages:** Python, C++, SQL
- **Data and analytics:**
  - pandas, Polars, NumPy, SciPy, Matplotlib;
  - PyArrow / Parquet, DuckDB;
  - MySQL and relational database design;
  - Excel, Power BI.
- **Machine learning:** scikit-learn, LightGBM, PyTorch, Hugging Face Transformers
- **Research methods:**
  - walk-forward, out-of-sample and sealed-holdout validation;
  - pre-registration;
  - bootstrap confidence intervals and permutation tests;
  - multiple-testing correction;
  - Monte Carlo simulation;
  - leakage audits.
- **Software engineering:**
  - data structures and algorithms;
  - pytest (including property-based tests with Hypothesis), mypy, ruff, uv;
  - Git and GitHub, Jupyter;
  - reproducible pipelines with hash manifests.

## Education

**B.S. in Computer Science**, California State University, Fresno, May 2026

## Contact

[LinkedIn](https://www.linkedin.com/in/chahatpatel2003)
