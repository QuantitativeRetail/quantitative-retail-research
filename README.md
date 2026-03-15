# Quantitative Retail Research

This repository contains the research code for **Quantitative Retail**.

Its purpose is to test retail trading claims under explicit rules, realistic cost assumptions, out-of-sample evaluation, and benchmark comparison.

## Core principles

- precise strategy definition
- realistic execution assumptions
- distributional thinking, not winner selection
- regime-aware evaluation
- comparison against passive benchmarks

## Repository layout

- `configs/` experiment and cost assumptions
- `data/` raw, interim, and processed datasets
- `notebooks/` exploratory analysis and figure generation
- `src/data/` data loaders and preprocessing
- `src/strategies/` explicit strategy rules
- `src/backtest/` backtesting engine and execution logic
- `src/evaluation/` metrics and robustness analysis
- `src/plots/` figure generation
- `outputs/` exported tables, figures, and summaries
- `docs/` technical notes and implementation notes

## Initial project focus

The first major strategy audit is:

- **ICT Fair Value Gap (FVG)**

This audit will study:
- rule formalization
- sensitivity to parameterization
- impact of costs and slippage
- regime dependence
- comparison against passive benchmarks

## Status

Initial repository scaffold.