<<<<<<< Updated upstream:index.md
# Welcome to Xiangtian's Personal Page

****************************TO BE FINISHED*****************************

=======
---
permalink: /project/
title: "Project"
---
>>>>>>> Stashed changes:_pages/project.md
## Key Research Interests
- Power system dynamics
- Domain knowledge-informed machine learning

### A Cross-Domain Approach to Analyzing the Short-Run Impact of COVID-19 on the US Electricity Sector [[COVID-EMDA](https://github.com/tamu-engineering-research/COVID-EMDA)]
- **Summary**: We release a first-of-its-kind cross-domain open-access data hub, integrating data from across all existing US wholesale electricity markets with COVID-19 case, weather, mobile device location, and satellite imaging data. Leveraging cross-domain insights from public health and mobility data, we rigorously uncover a significant reduction in electricity consumption that is strongly correlated with the number of COVID-19 cases, degree of social distancing, and level of commercial activity.
- **Citation**: Ruan, Guangchun, Dongqi Wu, **Xiangtian Zheng**, Haiwang Zhong, Chongqing Kang, Munther A. Dahleh, S. Sivaranjani, and Le Xie. "A cross-domain approach to analyzing the short-run impact of COVID-19 on the US electricity sector." Joule 4, no. 11 (2020): 2322-2337.

### An Open-Source Extendable Model and Corrective Measure Assessment of the 2021 Texas Power Outage [[2021TXPowerOutage](https://github.com/tamu-engineering-research/2021TXPowerOutage)]
- **Summary**: We collaboratively release an open-source extendable model that is synthetic but nevertheless provides a realistic representation of the actual energy grid, accompanied by open-source cross-domain data sets. This simplified synthetic model is calibrated to the best of our knowledge based on published data resources. Building upon this open-source synthetic grid model, researchers could quantitatively assess the impact of various policies on mitigating the impact of such extreme events. As an example, in this paper we critically assess several corrective measures that could have mitigated the blackout under such extreme weather conditions. We uncover the regional disparity of load shedding. The analysis also quantifies the sensitivity of several corrective measures with respect to mitigating the severity of the power outage, as measured in Energy-not-Served (ENS).
- **Citation**: Wu, Dongqi, **Xiangtian Zheng**, Yixing Xu, Daniel Olsen, Bainan Xia, Chanan Singh, and Le Xie. "An open-source extendable model and corrective measure assessment of the 2021 texas power outage." Advances in Applied Energy 4 (2021): 100056.

### PSML: A Multi-scale Time-series Dataset for Machine Learning in Decarbonized Energy Grids [[Open-source-power-dataset](https://github.com/tamu-engineering-research/Open-source-power-dataset)]
- **Summary**: We present PSML, a first-of-its-kind open-access multi-scale time-series dataset, to aid in the development of data-driven machine learning (ML) based approaches towards reliable operation of future electric grids. The dataset is generated through a novel transmission + distribution (T+D) co-simulation designed to capture the increasingly important interactions and uncertainties of the grid dynamics, containing electric load, renewable generation, weather, voltage and current measurements at multiple spatio-temporal scales. Using PSML, we provide state-of-the-art ML baselines on three challenging use cases of critical importance to achieve: (i) early detection, accurate classification and localization of dynamic disturbance events; (ii) robust hierarchical forecasting of load and renewable energy with the presence of uncertainties and extreme events; and (iii) realistic synthetic generation of physical-law-constrained measurement time series. We envision that this dataset will enable advances for ML in dynamic systems, while simultaneously allowing ML researchers to contribute towards carbon-neutral electricity and mobility.
- **Citation**: **Zheng, Xiangtian**, Nan Xu, Loc Trinh, Dongqi Wu, Tong Huang, S. Sivaranjani, Yan Liu, and Le Xie. "PSML: A Multi-scale Time-series Dataset for Machine Learning in Decarbonized Energy Grids." arXiv preprint arXiv:2110.06324 (2021).

### Synthetic Dynamic PMU Data Generation: Generative Adversarial Nets (GAN)-based Approach
- **Summary**: We propose a machine learning-based approach for creating synthetic eventful phasor measurement unit (PMU) data over time-varying load conditions. This approach leverages the generative adversarial nets (GAN) to create system quasi-steady states under slowly-varying load conditions and incorporates the neural ordinary differential equation (NeuralODE) to capture the transient behaviours of the system transient oscillation.
The numerical example on a large power grid suggests that this approach can  create realistic synthetic eventful PMU voltage measurements based on the associated real PMU data, without any knowledge of the underlying nonlinear dynamic equations. We show that the synthetic voltage measurements possess the key characteristics of the real system behaviour on distinct time scales.
- **Citation**: 
    - **Zheng, Xiangtian**, Bin Wang, and Le Xie. "Synthetic dynamic PMU data generation: A generative adversarial network approach." In 2019 International Conference on Smart Grid Synchronized Measurements and Analytics (SGSMA), pp. 1-6. IEEE, 2019.
    - **Zheng, Xiangtian**, Bin Wang, Dileep Kalathil, and Le Xie. "Generative Adversarial Networks-Based Synthetic PMU Data Creation for Improved Event Classification." IEEE Open Access Journal of Power and Energy 8 (2021): 68-76.
    - **Zheng, Xiangtian**, Andrea Pinceti, Lalitha Sankar, and Le Xie. "Cross time-scale synthetic synchrophasor data creation: A Generative Adversarial Nets (GAN)-based Approach." working paper.

