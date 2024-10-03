# Awesome Epidemic Modeling Papers
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Stars](https://img.shields.io/github/stars/Emory-Melody/awesome-epidemic-modeling-papers?color=yellow)


📢📢📢 [KDD 2024] This repository keeps track of the latest papers on epidemic modeling with deep learning methods. We categorize them based on individual tasks.

If you want to add new entries, please make PRs with the same format.


You can follow our latest survey to stay updated with the most recent advancements:

🔥🔥🔥[[A Review of Graph Neural Networks in Epidemic Modeling]](https://arxiv.org/abs/2403.19852)

We also recommend 🔥[*EpiLearn*](https://github.com/Emory-Melody/EpiLearn), a python library dedicated to boosting epidemic modeling and analysis with machine learning.

<div align=center><img src="https://github.com/Emory-Melody/awesome-epidemic-modeling-papers/blob/main/figs/episurvey.png" width="1000" /></div>





If you find this repo helpful, we would appreciate it if you could kindly cite our survey.

```
@article{liu2024review,
  title={A Review of Graph Neural Networks in Epidemic Modeling},
  author={Zewen Liu, Guancheng Wan, B. Aditya Prakash, Max S. Y. Lau, Wei Jin},
  journal={Proceedings of the 30th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD)},
  year={2024}
}
```


## Notes:
The current version only includes papers related to GNNs and we are working on adding more nonGNN papers.

This repo will be consistently updated to keep track of the latest papers related to deep learning in epidemic modeling.


## Catalog
- [Awesome Epidemic Modeling Papers](#awesome-epidemic-modeling-papers)
  - [Notes:](#notes)
  - [Catalog](#catalog)
  - [Toolkit/Library/Package](#toolkitlibrarypackage)
    - [Python](#python)
    - [R](#r)
  - [Detection](#detection)
  - [Surveillance](#surveillance)
  - [Projection](#projection)
  - [Prediction](#prediction)
  - [Classic Methods](#classic-methods)
  - [Other Related Surveys](#other-related-surveys)


## Toolkit/Library/Package
### Python
1. [2024] 🔥**EpiLearn: A Python Library for Machine Learning in Epidemic Modeling** [[paper]](https://github.com/Emory-Melody/EpiLearn) [[code]](https://github.com/Emory-Melody/EpiLearn)
   - EpiLearn is a Pytorch-based machine learning tool-kit for epidemic data modeling and analysis. We provide numerour features including:
     - Implementation of Epidemic Models
     - Simulation of Epidemic Spreading
     - Visualization of Epidemic Data
     - Unified Pipeline for Epidemic Tasks
2. [2021] **Eir: a python package for epidemic simulation** [[paper]](https://joss.theoj.org/papers/10.21105/joss.03247.pdf) [[code]](https://github.com/mjacob1002/Eir)
   
3. [2020] **Eon (epidemics on networks): a fast, flexible python package for simulation, analytic approximation, and analysis of epidemics on networks** [[paper]](https://arxiv.org/abs/2001.02436) [[code]](https://github.com/springer-math/Mathematics-of-Epidemics-on-Networks)

### R
1. [2022] EpiEstim [[paper]](https://cran.uib.no/web/packages/EpiEstim/EpiEstim.pdf) [[code]](https://github.com/mrc-ide/EpiEstim)
2. [2018] EpiModel: An R Package for Mathematical Modeling of Infectious Disease over Networks [[paper]]() [[code]]()
3. [2018] Epinet [[paper]](https://www.jstatsoft.org/article/view/v083i11) [[code]](https://cran.r-project.org/web/packages/epinet/index.html)
4. [2016] Epifit [[code]](https://github.com/cran/epifit)
5. [2015] EpiDynamics [[code]](https://github.com/oswaldosantos/EpiDynamics)



## Detection
1. [2023] **Inferring Patient Zero on Temporal Networks via Graph Neural Networks** [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/26152)
2. [2021] **Source Detection on Networks Using Spatial Temporal Graph Convolutional Networks** [[paper]](https://scholarworks.iupui.edu/server/api/core/bitstreams/3d2e45a4-76b6-40ee-a51f-24348db5cdd2/content) [[code]](https://github.com/anonymous-anuthor/SD-STGCN)
3. [2020] **Finding Patient Zero: Learning Contagion Source with Graph Neural Networks** [[paper]](https://arxiv.org/abs/2006.11913)

## Surveillance
1. [2023] **WDCIP: spatio-temporal AI-driven disease control intelligent platform for combating COVID-19 pandemic** [[paper]](https://www.tandfonline.com/doi/full/10.1080/10095020.2023.2182236)
2. [2023] **COVID-19 infection inference with graph neural networks** [[paper]](https://www.nature.com/articles/s41598-023-38314-3)
3. [2023] **Detection of Patients at Risk of Enterobacteriaceae Infection Using Graph Neural Networks: a Retrospective Study** [[paper]](https://www.medrxiv.org/content/10.1101/2023.06.01.23290386v1)
4. [2023] **Devil in the Landscapes: Inferring Epidemic Exposure Risks from Street View Imagery** [[paper]](https://dl.acm.org/doi/abs/10.1145/3589132.3625596)
5. [2023] **Novel Graph Topology Learning for Spatio-Temporal Analysis of COVID-19 Spread** [[paper]](https://ieeexplore.ieee.org/abstract/document/10106414)

## Projection
1. [2023] **Contact Tracing and Epidemic Intervention via Deep Reinforcement Learning** [[paper]](https://dl.acm.org/doi/full/10.1145/3546870)
2. [2021] **Effective vaccination strategy using graph neural network ansatz** [[paper]](https://arxiv.org/abs/2111.00920)
3. [2021] **Controlling Graph Dynamics with Reinforcement Learning and Graph Neural Networks** [[paper]](https://proceedings.mlr.press/v139/meirom21a.html)
4. [2020] **Reinforced Epidemic Control: Saving Both Lives and Economy** [[paper]](https://arxiv.org/abs/2008.01257) [[code]](https://github.com/anyleopeace/DURLECA)


## Prediction
1. [2024] **Privacy-preserving individual-level covid-19 infection prediction via federated graph learning** [[paper]](https://dl.acm.org/doi/abs/10.1145/3633202) [[code]](https://github.com/wjfu99/FL-epidemic)
1. [2023] **Research on the Forecast of the Spread of COVID-19** [[paper]](https://dl.acm.org/doi/abs/10.1145/3460238.3460246)
1. [2023] **RESEAT: Recurrent Self-Attention Network for Multi-Regional Influenza Forecasting** [[paper]](https://ieeexplore.ieee.org/abstract/document/10050036)
2. [2023] **EINNs: Epidemiologically-informed Neural Networks** [[paper]](http://arxiv.org/abs/2202.10446)
3. [2023] **A Graph Based Deep Learning Framework for Predicting Spatio-Temporal Vaccine Hesitancy** [[paper]](https://www.medrxiv.org/content/10.1101/2023.10.24.23297488v1)
4. [2023] **HOPE: High-order Graph ODE For Modeling Interacting Dynamics** [[paper]](https://proceedings.mlr.press/v202/luo23f/luo23f.pdf)
5. [2023] **Epidemiology-Aware Deep Learning for Infectious Disease Dynamics Prediction** [[paper]](https://dl.acm.org/doi/abs/10.1145/3583780.3615139)
6. [2023] **MepoGNN: Metapopulation Epidemic Forecasting with Graph Neural Network** [[paper]](https://2022.ecmlpkdd.org/wp-content/uploads/2022/09/sub_954.pdf)[[code]](https://github.com/deepkashiwa20/MepoGNN)
7. [2023] **Metapopulation Graph Neural Networks: Deep Metapopulation Epidemic Modeling with Human Mobility** [[paper]](https://arxiv.org/abs/2306.14857)
8. [2023] **Forecasting Infections with Spatio-Temporal Graph Neural Networks: A Case Study of the Dutch SARS-CoV-2 Spread** [[paper]](https://www.frontiersin.org/articles/10.3389/fphy.2023.1277052/full)
9. [2023] **MSGNN: Multi-scale Spatio-temporal Graph Neural Network for Epidemic Forecasting** [[paper]](https://arxiv.org/abs/2308.15840)
10. [2023] **Dynamic Adaptive Spatio--Temporal Graph Network for COVID-19 Forecasting** [[paper]](https://ietresearch.onlinelibrary.wiley.com/doi/10.1049/cit2.12238)
11. [2023] **Predicting COVID-19 pandemic by spatio-temporal graph neural networks: A New Zealand's study** [[paper]](https://arxiv.org/abs/2305.07731) [[code]](https://github.com/HySonLab/pandemic_tgnn)
12. [2023] **Graph Neural Network Modeling of Web Search Activity for Real-time Pandemic Forecasting** [[paper]](https://ieeexplore.ieee.org/abstract/document/10337253)
13. [2023] **Enhancing Spatial Spread Prediction of Infectious Diseases through Integrating Multi-scale Human Mobility Dynamics** [[paper]](https://dl.acm.org/doi/abs/10.1145/3589132.3625586)
14. [2023] **Predicting Influenza with Pandemic-Awareness via Dynamic Virtual Graph Significance Networks** [[paper]](https://www.sciencedirect.com/science/article/pii/S001048252300272X)
15. [2023] **DeepDynaForecast: Phylogenetic-informed Graph Deep Learning for Epidemic Transmission Dynamic Prediction** [[paper]](https://www.biorxiv.org/content/10.1101/2023.07.17.549268v1.abstract) [[code]](https://github.com/lab-smile/DeepDynaForecast.)
16. [2023] **Human Mobility Modeling during the COVID-19 Pandemic via Deep Graph Diffusion Infomax** [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/26678)
17. [2022] **EpiGNN: Exploring Spatial Transmission with Graph Neural Network for Regional Epidemic Forecasting** [[paper]](https://2022.ecmlpkdd.org/wp-content/uploads/2022/09/sub_829.pdf) [[code]](https://github.com/Xiefeng69/EpiGNN)
18. [2022] **Self-Attention-Based Deep Learning Network for Regional Influenza Forecasting** [[paper]](https://ieeexplore.ieee.org/abstract/document/9470981)
19. [2022] **Estimating the State of Epidemics Spreading with Graph Neural Networks** [[paper]](https://link.springer.com/article/10.1007/s11071-021-07160-1) [[code]](http://github.com/DiLauroF/gnninferenceepid)
20. [2022] **Adaptively Temporal Graph Convolution Model for Epidemic Prediction of Multiple Age Groups** [[paper]](https://www.sciencedirect.com/science/article/pii/S2667325821001369)
21. [2022] **CausalGNN: Causal-Based Graph Neural Networks for Spatio-Temporal Epidemic Forecasting** [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/21479)
22. [2022] **Visualization Method for the Spreading Curve of COVID-19 in Universities Using GNN** [[paper]](https://ieeexplore.ieee.org/abstract/document/9736549)
23. [2022] **Combining Graph Neural Networks and Spatio-Temporal Disease Models to Improve the Prediction of Weekly COVID-19 Cases in Germany** [[paper]](https://www.nature.com/articles/s41598-022-07757-5)
24. [2022] **Hierarchical Spatio-Temporal Graph Neural Networks for Pandemic Forecasting** [[paper]](https://dl.acm.org/doi/pdf/10.1145/3511808.3557350)
25. [2021] **HierST: A Unified Hierarchical Spatial-temporal Framework for COVID-19 Trend Forecasting** [[paper]](https://dl.acm.org/doi/abs/10.1145/3459637.3481927) [[code]](https://github.com/dolphin-zs/HierST/tree/main)
26. [2021] **A Human Mobility Data Driven Hybrid GNN+RNN Based Model For Epidemic Prediction** [[paper]](https://ieeexplore.ieee.org/abstract/document/9671474)
27. [2021] **Integrating LSTMs and GNNs for COVID-19 Forecasting** [[paper]](https://arxiv.org/abs/2108.10052) [[code]](https://github.com/jjgarau/GNND)
28. [2021] **Prediction of the Effects of Epidemic Spreading with Graph Neural Networks** [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-65347-7_35) [[code]](https://github.com/smeznar/Epidemic-spreading-CN2020)
29. [2021] **Deep learning of contagion dynamics on complex networks** [[paper]](https://www.nature.com/articles/s41467-021-24732-2) [[code]](https://github.com/DynamicaLab/code-dynalearn/tree/v1.0) [[data]](https://github.com/DynamicaLab/data-dynalearn/tree/v1.0)

30. [2021] **Transfer Graph Neural Networks for Pandemic Forecasting** [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/16616) [[code]](https://github.com/geopanag/pandemic_tgnn)
31. [2021] **Coupled Graph ODE for Learning Interacting System Dynamics** [[paper]](https://dl.acm.org/doi/abs/10.1145/3447548.3467385) [[code]](https://github.com/ZijieH/CG-ODE)
32. [2021] **Predicting the Dynamics of the COVID-19 Pandemic in the United States Using Graph Theory-Based Neural Networks** [[paper]](https://www.mdpi.com/1660-4601/18/7/3834) [[code]](https://github.com/RezaDavahli/Graph_neural_networks)
33. [2020] **An Epidemiological Neural Network Exploiting Dynamic Graph Structured Data Applied to the COVID-19 Outbreak** [[paper]](https://ieeexplore.ieee.org/document/9234698) [[code]](https://github.com/marcopost-it/epidemiological-gcn)
34. [2020] **STAN: Spatio-Temporal Attention Network for Pandemic Prediction Using Real-World Evidence** [[paper]](https://arxiv.org/abs/2008.04215)
35. [2020] **Examining COVID-19 Forecasting Using Spatio-Temporal Graph Neural Networks** [[paper]](https://arxiv.org/abs/2007.03113)
36. [2019] **A Study on Graph-Structured Recurrent Neural Networks and Sparsification with Application to Epidemic Forecasting** [[paper]](https://arxiv.org/abs/1902.05113)



## Classic Methods
1. [2023] **EpiMob: Interactive Visual Analytics of Citywide Human Mobility Restrictions for Epidemic Control** [[paper]](https://ieeexplore.ieee.org/document/9750868/)
2. [2021] **Countrywide Origin-Destination Matrix Prediction and Its Application for COVID-19** [[paper]](https://link.springer.com/10.1007/978-3-030-86514-6_20)
3. [2021] **Networks and the epidemiology of infectious disease** [[paper]](https://pubmed.ncbi.nlm.nih.gov/21437001/)
4. [2020] **Modelling the impact of testing, contact tracing and household quarantine on second waves of COVID-19** [[paper]](https://www.nature.com/articles/s41562-020-0931-9)
5. [2020] **Modelling transmission and control of the COVID-19 pandemic in Australia** [[paper]](https://www.nature.com/articles/s41467-020-19393-6)
6. [2020] **Inferring change points in the spread of COVID-19 reveals the effectiveness of interventions** [[paper]](https://www.science.org/doi/10.1126/science.abb9789)
7. [2020] **Monitoring Italian COVID-19 spread by a forced SEIRD model** [[paper]](https://dx.plos.org/10.1371/journal.pone.0237417)
8. [2018] **Real-time forecasting of infectious disease dynamics with a stochastic semi-mechanistic model** [[paper]](https://www.sciencedirect.com/science/article/pii/S1755436516300445)
9. [2017] **Ethics of Epidemics, Research and Surveillance: a WHO Workshop Report** [[paper]](https://doi.org/10.1007/s41649-017-0024-x)
10. [2017] **Reproduction numbers of infectious disease models** [[paper]](https://linkinghub.elsevier.com/retrieve/pii/S2468042717300209)
11. [2013] **Forecasting methods and models of disease spread** [[paper]](https://www.researchgate.net/publication/335165992_Forecasting_methods_and_models_of_disease_spread)
12. [2009] **Multiscale mobility networks and the spatial spreading of infectious diseases** [[paper]](https://pnas.org/doi/full/10.1073/pnas.0906910106)
13. [2008] **Mathematical models of infectious disease transmission** [[paper]](https://www.nature.com/articles/nrmicro1845)
14. [1927] **A contribution to the mathematical theory of epidemics** [[paper]](https://royalsocietypublishing.org/doi/10.1098/rspa.1927.0118)


## Other Related Surveys
1. [2022] **Data-Centric Epidemic Forecasting: A Survey** [[paper]](http://arxiv.org/abs/2207.09370)
2. [2022] **Machine Learning, Deep Learning, and Mathematical Models to Analyze Forecasting and Epidemiology of COVID-19: A Systematic Literature Review** [[paper]](https://www.mdpi.com/1660-4601/19/9/5099)
3. [2022] **Significance of deep learning for Covid-19: state-of-the-art review** [[paper]](https://doi.org/10.1007/s42600-021-00135-6)
4. [2022] **Deep learning for Covid-19 forecasting: State-of-the-art review** [[paper]](10.1016/j.neucom.2022.09.005)
5. [2022] **A Survey on Mathematical, Machine Learning and Deep Learning Models for COVID-19 Transmission and Diagnosis** [[paper]](https://ieeexplore.ieee.org/abstract/document/9387581)
6. [2021] **Deep Learning applications for COVID-19** [[paper]](https://doi.org/10.1186/s40537-020-00392-9)
7. [2021] **Deep Learning for Virus-Spreading Forecasting: a Brief Survey** [[paper]](http://arxiv.org/abs/2103.02346)
