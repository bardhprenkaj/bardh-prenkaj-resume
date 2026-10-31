---
title: 'TRADES: Generating Realistic Market Simulations with Diffusion Models'

authors:
  - Leonardo Berti
  - Bardh Prenkaj
  - Paola Velardi

date: '2025-10-25T00:00:00Z'
doi: '10.3233/FAIA251249'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

publication: 'In *Proceedings of the 28th European Conference on Artificial Intelligence*'
publication_short: 'In *ECAI 2025*'

abstract: 'Financial markets are complex systems characterized by high statistical noise, nonlinearity, volatility, and constant evolution. Thus, modeling them is extremely hard. Here, we address the task of generating realistic and responsive Limit Order Book (LOB) market simulations, which are fundamental for calibrating and testing trading strategies, performing market impact experiments, and generating synthetic market data. We propose a novel TRAnsformer-based Denoising Diffusion Probabilistic Engine for LOB Simulations (TRADES). TRADES generates realistic order flows as time series conditioned on the state of the market, leveraging a transformer-based architecture that captures the temporal and spatial characteristics of high-frequency market data. There is a notable absence of quantitative metrics for evaluating generative market simulation models in the literature. To tackle this problem, we adapt the predictive score, a metric measured as an MAE, to market data by training a stock price predictive model on synthetic data and testing it on real data. We compare TRADES with previous works on two stocks, reporting a 3.27 and 3.48 improvement over SoTA according to the predictive score, demonstrating that we generate useful synthetic market data for financial downstream tasks. Furthermore, we assess TRADES''s market simulation realism and responsiveness, showing that it effectively learns the conditional data distribution and successfully reacts to an experimental agent, giving sprout to possible calibrations and evaluations of trading strategies and market impact experiments. To perform the experiments, we developed DeepMarket, the first open-source Python framework for LOB market simulation with deep learning. In our repository, we include a synthetic LOB dataset composed of TRADES''s generated simulations.'

tags: ['diffusion models','finance','time series']

featured: false

url_pdf: 'https://arxiv.org/pdf/2502.07071'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
