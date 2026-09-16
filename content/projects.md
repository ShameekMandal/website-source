---
title: "Academic Projects"
cover: "images/IMG_3971.jpeg"
coverMode: portrait
aliases:
  - /projects/distribution-shift/
---

> **Application of Power K Means for Multiview Data** | Master's Final Year Project

Formulated a novel clustering framework - Cluster Weighted Kernel Power K Means extending Multiview Kernel Power K-Means to optimize non-convex objective functions and mitigate local minima limits. 

*   **Framework:** Kernelized data projections via Reproducing Kernel Hilbert Space (RKHS).
*   **Optimization:** Solved non-convexity constraints utilizing the Majorization-Minimization (MM) algorithm to dynamically weight inner clusters across multiple views.
*   **Benchmarks:** Validated clustering accuracy on simulated frameworks and Caltech 101 dataset using NMI and ARI metrics.

[Project Link](https://drive.google.com/file/d/17_mGBzR3D4C8VCESyLus0LdRMwQsmauO/view)

> **Stochastic Modeling of Ecological Systems: Beyond Lotka-Volterra**

*   **Objective:** Model predator-prey population dynamics by transitioning from rigid deterministic frameworks to stochastic biological systems, accounting for conservation-driven resource injections.
*   **Methodology & Theory:** 
    *   Introduced stochastic perturbations into the classic *Lotka-Volterra* differential equations to derive conditions for long-term population equilibrium versus systemic extinction.
    *   Addressed the structural limitations of Lotka-Volterra (which assumes isolated ecosystems) by fitting a non-linear *Rosenzweig-MacArthur* model. This integrated external resource variables (additional food supplied to stabilize the ecosystem).
*   **Simulation & Analytics:** Conducted comprehensive time-series simulation studies to evaluate predator-prey frequencies over time, mapping out phase portraits and bifurcation behaviors across varied birth, death, and supplemental feeding rates.

[Project Link](https://drive.google.com/file/d/18plzWA5c0zRwRFjto8SDByG5h_ARm1fV/view)

> **Clinical Data Analysis: Dietary Impacts on CKD-Induced Constipation**

*   **Objective:** Investigate the causal relationship between dietary habits and secondary constipation in patients suffering from Chronic Kidney Disease (CKD).
*   **Statistical Methodology:** 
    *   Evaluated initial baselines using linear regression across ordinal survey responses, applying Box-Cox transformations and Quantile-Quantile ($Q\text{-}Q$) plots to address non-normality.
    *   Advanced the architecture by fitting an **Ordinal Logistic Regression Model** to properly treat the discrete, ordered nature of the response variables. 
    *   Executed hyperparameter tuning to mitigate overfitting, verified structural integrity via Variance Inflation Factor ($VIF$) to rule out multicollinearity, and maximized the adjusted $R^2$.
*   **Impact:** The validated statistical insights and risk factors were directly utilized by clinical nephrologist to establish dietary causality guidelines for CKD patient care.

[Project Link](https://drive.google.com/file/d/1YbHxkyktcczFsXRf8M3T_xT-Xd_GMgjB/view?usp=sharing)

> **Predictive Modeling: US Healthcare Insurance Cost Dynamics**

*   **Objective:** Construct a predictive pipeline to estimate healthcare insurance premiums across diverse demographic profiles.
*   **Statistical Methodology:** 
    *   Executed rigorous Exploratory Data Analysis (EDA) using stratified boxplots and scatter matrices to map multi-variable correlations (Age, BMI, Sex, Region, Offspring count).
    *   Evaluated initial baselines with a Linear Regression model, identifying high predictive accuracy for the smoker cohort but severe heteroscedasticity and outlier density within the non-smoker cohort.
    *   Pivoted to a non-parametric **$K$-Nearest Neighbor (KNN)** framework to better capture non-linear interactions and structural anomalies without distributional assumptions.
*   **Optimization:** Employed $k$-fold cross-validation to algorithmically determine the optimal hyperparameter value for $K$, minimizing root-mean-square error (RMSE).