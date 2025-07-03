
#  Study of the theoretical properties of foundation models for time series 
**Etude des propriétés théoriques des modèles fondationnels pour les séries temporelles**

## Abstract 
Foundation AI models are universal models to solve a wide set of problems. This project proposes to investigate the theoretical properties of foundation models. The domain to model is a spatial-time series. These data are used in various scientific disciplines and serve to generalise scientific knowledge and make forecasts. The essential problems, formulated as user requests that solve a foundation model, are forecasting and generation of time series; analysis and classification of time series; detection of change point, and causal inference. To solve these problems, the foundation AI models are trained on massive datasets. The main goal of this project is to compare various architectures of foundation models to find an optimal architecture that solves the listed problems for a wide range of spatial time series. 
## State of the art
As of 2025, foundation models for spatial time series analysis are a rapidly developing area. However, there are no well-developed foundation models for the spatial-temporal problems. This distinguishes them from the GPT-like models. The most developed foundation models for time series solve problems of weather forecasting and the Earth system, namely: Foundation Models for Science [1], Foundation Models for the Earth system [2],  Foundation Methods for Scientific Machine Learning [3]. Now, massive datasets are being collected to train foundation models [4]. These datasets have a physics explanation and are supported by mathematical models [5, 6]. The state-of-the-art challenges for new foundation AI models that solve a wide range of problems in spatial time series analysis.  

## Objectives
The goal of the research is to provide a comprehensive theoretical analysis of the properties of foundation models for the spatial time series. It includes a comparison of the model architectures and a series of computational experiments to analyse their accuracy, stability, and complexity. The optimal architecture will be selected and rigorously studied to provide an adequate solution to the problems of time series analysis. 
The difference between text GPT foundation models and time series foundation models is that the latter require a local forecasting model to provide reasoning for their analysis. A foundation model combines various interpretable models, uses them as a mixture of experts, and returns a type of local forecasting model along with the analysis. The last ten years of AI development have brought many new theoretically reasoned models to analyse time series: 1) continuous-time state space models that construct new spaces for time series analysis, 2) physics-iformed and geometric deel learning models that mix several alternative models: like neural ODE and PDE, 3) models that deals with big massives of time series: graph disffution models, Riemannian models and wave models. The role of these new methods in the proposed foundation AI model must be carefully investigated, and their useful properties must be explored. 

## Deliveries
The project delivers: 1) a comparative analysis of the foundation models (as a paper), 2) computational experiments with the foundation model comparison (.ipynb), 3) a selected foundation model of optimal architecture (described in a paper), 4) the model is developed as a software (pytorch or jax pipeline), 5) a basic database of the time series to train the foundation model, 6) a deployment setup (flask, aws), 7) use cases and examples (.ipynb), and 8) theoretical research of the model properties (a submitted paper).

## Technical requirements 
The theoretical analysis is supported by software with an interface and documentation. The main modules are indexed via PyPI. The software requirements are: codestyle at least PEP-8; the code must be commented; there must be an installation file, a requirements file with defined versions. Demo: must be available in .ipynb or .colab.  Tests: coverage 75%.
## Dissipation 
The results of this research project will be presented in scientific papers with a manageable extraction to motivate users to utilize the developed foundation model. The model will be supplied with a user interface and deployed on open resources. 

## References
1. Mahoney, M.W. (2024). Foundation Models for Science: Progress, Opportunities, and Challenges. Advances in Neural Information Processing Systems (NeurIPS).
2. Perdikaris, P. (2024). Foundation models for the Earth system. Advances in Neural Information Processing Systems (NeurIPS).
3. Zanna, L. (2024). AI-Augmented Climate Simulators and Emulators. Advances in Neural Information Processing Systems (NeurIPS).
4. Ohana, R. et al (2025). The Well: A Large-Scale Collection of Diverse Physics Simulations for Machine Learning. arXiv.
5. Cole, F. (2024). Provable in-context learning of linear systems and linear elliptic PDEs with transformers. Advances in Neural Information Processing Systems (NeurIPS).
6. Jing F. et. al. (2024). VSMNO: Solving PDE by Utilizing Spectral Patterns of Different Neural Operators. Advances in Neural Information Processing Systems (NeurIPS).
