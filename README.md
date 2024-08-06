# Simulation Data Analysis with Predict Students' Dropout and Academic Success Dataset

## 📚 Abstract

This project explores the intricacies of various continuous and discrete random variable distributions through simulation, focusing on normal, log-normal, Bernoulli, and binomial distributions, among others. By simulating randomly distributed data, performing statistical tasks, and visualizing data distributions, we gain insights into data characteristics. Outlier detection is used to highlight significant features and eliminate irrelevant data. The project also delves into Markov chains, examining properties such as recurrent events, ergodicity, sensitivity analysis, and variance reduction techniques. Finally, we analyze the "Predict Students' Dropout and Academic Success" dataset using factor analysis, joint distribution analysis, and Bayes' Theorem.

## 📖 Table of Contents

1. [Introduction](#introduction)
2. [Data Description](#data-description)
3. [Methodology, Analysis, and Results](#methodology-analysis-and-results)
   - [Simulation Data Analysis](#simulation-data-analysis)
   - [Markov Chain](#markov-chain)
   - [Variance Reduction Techniques](#variance-reduction-techniques)
   - [Simulation for Combinatorial Analysis](#simulation-for-combinatorial-analysis)
   - [Real Data Analysis](#real-data-analysis)
4. [Conclusion](#conclusion)
5. [References](#references)

## 🎯 Introduction

Simulating data provides a robust method for understanding data characteristics when original data is not accessible. This project simulates popular distributions, performs statistical analysis, and visualizes data distributions. Key techniques include:

- Statistical analysis and visualization for continuous and discrete distributions
- Markov chains to study state transitions and ergodicity
- Variance reduction techniques like importance sampling and control variates
- Real-world data analysis using factor analysis and Bayes' Theorem

## 📊 Data Description

The dataset, "Predict Students' Dropout and Academic Success," aims to identify students at risk of academic failure in higher education. It includes 36 features and one target variable, capturing data on student demographics, academic paths, and socio-economic factors. The target variable classifies students into three categories: dropout, enrolled, and graduate.

## 🔬 Methodology, Analysis, and Results

### Simulation Data Analysis

**Continuous Random Variables:**
- Simulated distributions such as normal and log-normal.
- Conducted statistical analysis, visualizations, skewness and kurtosis evaluations, Central Limit Theorem verification, and outlier detection.

**Discrete Distributions:**
- Simulated Bernoulli and binomial distributions.
- Similar analysis and visualization as with continuous variables.

### Markov Chain

**Concept:**
- A Markov chain models state transitions based on the current state, with probabilities dictating state changes.

**Simulation:**
- Example: A cafe with menus changing daily. Simulated a transition matrix to analyze state changes over time.

**Key Properties:**
- **Steady State:** Achieved when transition probabilities stabilize over time.
- **Recurrent vs. Transient States:** Identified states that either return or do not return to their original position.
- **Ergodicity:** Analyzed state communication within the chain.
- **Sensitivity Analysis:** Studied the effect of small changes in transition probabilities on the Markov chain.

### Variance Reduction Techniques

- **Importance Sampling:** Focused on influential data to improve accuracy.
- **Control Variates:** Used known variables to control the behavior of target variables and reduce variance.

### Simulation for Combinatorial Analysis

- Solved problems like calculating the probability of getting a specific number of heads in a series of coin flips using combinatorial methods.

### Real Data Analysis

**Factor Analysis:**
- Reduced dimensionality by grouping related features, evaluated using Bartlett’s Test and Kaiser-Meyer-Olkin Test.
- Identified three significant factors from 36 features.

**Bayes' Theorem:**
- Applied to calculate posterior probabilities.

**Joint Distribution Analysis:**
- Analyzed the joint probability of two random variables.

## 🏁 Conclusion

This project demonstrates the power of simulation in understanding data distributions and statistical properties. By applying Markov chains and variance reduction techniques, we gained insights into state transitions and improved simulation accuracy. The analysis of real-world data through factor analysis and Bayes' Theorem provided practical applications of these methods. Future work could include developing a machine learning pipeline to enhance the project’s scalability and impact.

## 📚 References

1. [Predict Students' Dropout and Academic Success Dataset](https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success)
2. [Introduction to Factor Analysis](https://www.datacamp.com/tutorial/introduction-factor-analysis)
3. [Video Explanation of Project](https://stevens.zoom.us/rec/share/yz0ug9W3JkhyVZjHWehZEmNh7d4IDntRW3iHgdAk5Iug9Ay3-SRPdPAZotOAHjk2.OtlNl9Fgk-8Fzf0-)
