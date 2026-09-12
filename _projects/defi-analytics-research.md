---
name: DeFi Analytics Research
track: Finance Analytics
tools: [Python, Pandas, Scikit-learn, Matplotlib, DeFiLlama]
image: /assets/img/pairplot.png
description: A transparent DeFi-pool research workflow that collects snapshots, ranks pools using a documented liquidity-and-yield score, visualises the current universe, and provides time-aware ML evaluation foundations.
external_url: https://github.com/RazDwa1923/defi-analytics-research
---

## DeFi Analytics Research

I consolidated earlier DeFi visualisation, pool-ranking, and machine-learning experiments into a single reproducible research workflow.

The score combines cross-sectional TVL and seven-day mean APY percentiles. It is descriptive, not a return forecast: protocol risk, impermanent loss, emissions, fees, liquidity, and execution assumptions remain outside its scope.

The project deliberately replaces random row-level train/test splits with chronological evaluation utilities for any future predictive work.
