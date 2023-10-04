# ML-based Test Scenario Prioritization for Autonomous Vehicle Software
## Introduction
Autonomous vehicles are software-intensive systems, and ensuring their safety through extensive testing is crucial. Traditional testing approaches can be expensive and time-consuming. This project explores the use of Machine Learning (ML) to predict and prioritize critical test scenarios for autonomous driving software (ADS). By doing so, it aims to reduce testing costs and detect faults early in the development process.

## Objectives
1. To identify efficient ML algorithms for predicting critical test scenarios.
2. To analyze the impact of different features on test scenario prediction.


## Dataset
The project uses a publicly available dataset containing 60,000 test scenarios collected from Baidu Apollo, a simulation platform for testing ADS. The dataset includes ego vehicle and environment information.

## Methodology
The project evaluates various supervised ML algorithms to predict critical test scenarios. It assesses the performance of different ML models and features to identify the most impactful ones. The selected ML model is then used to prioritize test scenarios.

## Results
- The project compares the performance of common ML algorithms and identifies EasyEnsemble as the best performer.
- Features related to traffic rules and obstacles have the highest impact on model prediction.
- Prioritizing test scenarios using ML improves the Average Percentage of Faults Detected (APFD) score compared to random prioritization by 32%.

## Conclusion
This project demonstrates the effectiveness of ML-based test scenario prioritization for autonomous vehicle software testing. It provides valuable insights into selecting the right ML algorithms and features to achieve early fault detection and reduce testing costs.
