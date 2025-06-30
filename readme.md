# Study of the theoretical properties of foundational models for time series
<!--# Etude des propriétés théoriques des modèles fondationnels pour les séries temporelles-->
This project investigates theoretical properties of foundation models. The domain to model is a spatial-time series. A foundation model solves the following problems of the domain:
1. Forecasting and generation of time series;
2. Analysis and classification of time series;
3. Detection of change point;
4. Causal inference.
The goal of this project is to compare various architectures of foundation models to select an optimal architecture that solves the listed problems for a wide range of spatial time series.

## News
are in the Telegram channel [FoundationTS](https://t.me/FoundationTS)

## The assumptions about the time series
1. One dataset comprises a set of time series, possibly of different origins and sample rates.
2. The main type of time series is spatial time series. The spatial coordinates could be irregular.
3. Regardless of spatial coordinates, the distance between time series defines Riemannian space.
4. The data format to keep the dataset is [HDF5](https://www.hdfgroup.org/)

## The assumptions about the pipelines
1. PyTorch and [PyG](https://pyg.org/) are the main packages to make models.
2. JAX is welcome if it delivers faster results.

## The basic idea to start with
The paradox of time series forecasting is that a simple model (like Singular Spectrum Analysis, call it a local model) delivers the same or better accuracy of forecasting as a complex LSTM model. So the foundation model finds the optimal pair (data, local model) acting as a mixture of experts. 

## List of candidate models to compare
1. [WaveNet](https://github.com/golbin/WaveNet) – there are various code sources
2. [DRCNN](https://github.com/liyaguang/DCRNN) – diffusion convolution
3. [SSR](https://github.com/QData/spacetimeformer) – multivariate state space reconstruction
4. [Time-SSM](https://arxiv.org/pdf/2405.16312) – comparison of several continuous models

   
