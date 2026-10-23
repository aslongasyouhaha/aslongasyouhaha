# Jiuzhou Chen

Quantitative research · Asset pricing · Financial machine learning

I build research code to study financial markets, reproduce empirical findings, and evaluate predictive models. My projects span equity factors, commodity futures, volatility surfaces, path-dependent option pricing, and return prediction.

## Selected projects

| Project | Research question | Implementation |
| --- | --- | --- |
| [Volatility Surface Research](https://github.com/aslongasyouhaha/xtx_vol_surface) | How can option quotes be calibrated into a continuous surface under no-arbitrage constraints? | SANOS replication, joint linear-programming calibration, surface diagnostics, and extensions to dynamic local volatility. |
| [Path-Dependent Option Pricing](https://github.com/aslongasyouhaha/pinn-bsde) | How do PDE constraints and path-history representations affect option pricing and hedging? | Single-asset lookback and barrier options, heat-kernel and LSTM-PINNs, Signature/raw-history BSDE experiments, and three-seed evaluation of prices, Greeks, and hedge coefficients. |
| [Equity Factor Research](https://github.com/aslongasyouhaha/factors_framework) | How do published equity factors perform under a consistent data and evaluation framework? | Shared factor construction, matrix-based backtesting, point-in-time data handling, and statistical evaluation. |
| [Chinese Futures Research](https://github.com/aslongasyouhaha/china_futures_replication) | Which empirical findings from the literature carry over to Chinese futures markets? | Paper replications covering risk premia, trend, volatility, and market structure, with research reports and references. |
| [QRT Return Prediction](https://github.com/aslongasyouhaha/qrt_competition) | When do shared models, local residuals, and heterogeneous ensembles improve return-direction prediction? | CatBoost and GRU training, hierarchical residual models, component ablations, and an executable presentation notebook. |
| [Monte Carlo Methods](https://github.com/aslongasyouhaha/Monte_Carlo) | How can stochastic simulation methods be implemented and explored numerically? | A collection of Monte Carlo implementations. |

## Research interests

- **Empirical asset pricing:** factor construction, portfolio evaluation, and replication of published results.
- **Derivatives and volatility:** option pricing and hedging, calibration, no-arbitrage constraints, and volatility dynamics.
- **Financial machine learning:** sequence models, local experts, residual learning, and ensemble evaluation.

## How I approach research

I aim to connect each implementation to a clear research question and an economic hypothesis. I compare methods against explicit baselines, document data availability and validation choices, and separate predictive accuracy from evidence of tradable returns.

Project READMEs explain the inputs, commands, and outputs. Notebooks and research summaries present the methods, experiments, and limitations. Each repository documents its current scope and reproduction requirements.

## Tools

Python · NumPy · pandas · SciPy · scikit-learn · PyTorch · CatBoost · Matplotlib · Jupyter

Start with the project links above for code, notebooks, and research notes.
