# Advanced Loss Distribution Modeling: Bayesian and Composite Methods

## 🎯 Project Objective

This repository contains a specialized quantitative model that implements advanced statistical techniques for actuarial loss distribution modeling and the estimation of Probability of Default (PD). The objective is to demonstrate proficiency in fitting real-world data to complex probability distributions (Binomial, Poisson, Beta-Binomial) and performing parameter estimation, which is crucial for pricing risk, solvency calculations, and credit risk management.

## 🛠️ Key Methodologies and Libraries

The project is built entirely in Python, utilizing high-level statistical libraries:

* **`scipy.stats`**: Heavily utilized for its implementation of **Beta-Binomial, Binomial, and Poisson** distributions, as well as functions for their **convolution** (combining frequency and severity models).
* **Bayesian Estimation**: The methodology relies on Bayesian principles for robust parameter estimation, particularly when dealing with small or complex datasets.
* **`numpy` and `pandas`**: Essential for efficient management of input data (like `grades` and `failures`) and array-based calculations.

## 📊 Core Models and Risk Analysis

The model performs several high-level quantitative tasks:

1.  **Distribution Fitting:** Analyzing and modeling the frequency (e.g., Poisson) and severity (e.g., Beta-Binomial) components of aggregate loss distributions.
2.  **PD Calculation & Adjustment:** Calculating the initial Expected Probability of Default (PD) across various risk grades (AAA, AA, A, BBB, etc.).
3.  **Model Calibration:** Fitting the expected PDs to a theoretical **Exponential Adjustment Model** to calibrate the results, demonstrating an understanding of model calibration techniques.
4.  **Validation:** Presenting a direct comparison between Expected PD and the Adjusted PD, along with the difference, showcasing model performance and goodness-of-fit.

## ✨ Value Proposition for the Analyst Role

* **Deep Statistical Knowledge:** Proven command over advanced actuarial distributions and Bayesian estimation, critical for complex modeling tasks.
* **Credit/Loss Modeling:** Direct experience in the primary methodologies used to quantify credit risk and actuarial losses.
* **Code Proficiency:** Ability to translate theoretical actuarial and statistical literature (like the tables mentioned in the code) into functional and accurate Python code.
