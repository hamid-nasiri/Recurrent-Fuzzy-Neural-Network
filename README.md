# MFRFNN: Multi-Functional Recurrent Fuzzy Neural Network for Chaotic Time Series Prediction

## Introduction

**MFRFNN: Multi-Functional Recurrent Fuzzy Neural Network for Chaotic Time Series Prediction**

*Authors:* [Hamid Nasiri](https://www.linkedin.com/in/hamid-nasiri-b5555487/), [Mohammad Mehdi Ebadzadeh](https://www.linkedin.com/in/mehdi-ebadzadeh-28bb3b35/)

*Abstract:* Chaotic time series prediction, a challenging research topic in dynamic system modeling, has drawn great attention from researchers around the world. In recent years extensive researches have been done on developing chaotic time series prediction methods, and various models have been proposed. Among them, recurrent fuzzy neural networks (RFNNs) have shown significant potential in this area. Most of the proposed RFNNs learn a single function, but when dealing with chaotic time series, different outputs may be generated for a specific input based on the system’s state. So, a network is required that can learn multiple functions simultaneously. Based on this concept, a novel multi-functional recurrent fuzzy neural network (MFRFNN) is proposed in this paper. MFRFNN consists of two fuzzy neural networks with Takagi-Sugeno-Kang fuzzy rules, one is used to produce the output, and the other to determine the system’s state. There is a feedback loop between these two networks, which makes MFRFNN capable of learning and memorizing historical information of past observations. Employing the states allows the proposed network to learn multiple functions simultaneously. Moreover, a new learning algorithm, which employs the particle swarm optimization algorithm, is developed to train the networks’ weights. The effectiveness of MFRFNN is validated using the Lorenz and Rossler chaotic time series and four real-world datasets, including Box-Jenkins gas furnace, wind speed prediction, Google stock price prediction, and air quality index prediction. Based on the root mean square error, the proposed method shows a decrease of 35.12%, 13.95%, and 49.62% from the second best methods in the Lorenz time series, Box-Jenkins gas furnace, and wind speed prediction dataset, respectively.

This repository contains MATLAB source code of the following paper:

[MFRFNN: Multi-Functional Recurrent Fuzzy Neural Network for Chaotic Time Series Prediction](https://www.sciencedirect.com/science/article/pii/S0925231222010074)

## Source Code and Dataset

To run the code simply execute `main.m`

**Dataset:** 
The [`Benchmarks`](Benchmarks/) folder contains several time series datasets used for testing and evaluating the code. We summarize these files, and provide their original sources, here:

The Air Quality Index dataset employed in this project is collected from 12 observing stations around Beijing from year 2013 to 2017. The data is accessible at The University of California, Irvine (UCI) Machine Learning Repository.

# Citation

This repository accompanies the paper ["MFRFNN: Multi-Functional Recurrent Fuzzy Neural Network for Chaotic Time Series Prediction"](https://www.sciencedirect.com/science/article/pii/S0925231222010074) by Hamid Nasiri and Mohammad Mehdi Ebadzadeh.

If you use either the code, datasets or paper, please consider citing the paper.

```
@article{nasiri2022mfrfnn,
  title={MFRFNN: Multi-Functional Recurrent Fuzzy Neural Network for Chaotic Time Series Prediction},
  author={Nasiri, Hamid and Ebadzadeh, Mohammad Mehdi},
  journal={Neurocomputing},
  year={2022},
  publisher={Elsevier}
}
```
