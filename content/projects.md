---
title: "Projects"
url: "/projects/"
showToc: false
summary: "Statistical learning, machine learning, and computational biology projects."
---

<section class="project-item">
  <h2 class="project-title">Multi-Omics Prognostic Biomarker Identification (Master’s Thesis)</h2>
  <div class="project-skills">
    <span class="skill-tag">R</span>
    <span class="skill-tag">Survival Analysis</span>
    <span class="skill-tag">Machine Learning</span>
  </div>
  <ul class="project-bullets">
    <li>Preprocessed 57,000 multi-omics features across 439 Lung Adenocarcinoma (LUAD) patients, applying Cox Sure Independence Screening (Cox-SIS) to filter high-dimensional noise down to 288 candidate targets.</li>
    <li>Trained penalized Cox regression and ensemble survival models using 100-subsample Stability Selection to reliably isolate robust prognostic biomarkers.</li>
    <li>Derived a 9-gene consensus biomarker panel and validated patient risk stratification through cross-validated Harrell's C-Index and log-rank tests.</li>
  </ul>
</section>

<section class="project-item">
  <h2 class="project-title">Stacked Ensemble Prediction of Fatal Myocardial Infarction Complications</h2>
  <div class="project-skills">
    <span class="skill-tag">R</span>
    <span class="skill-tag">Machine Learning</span>
  </div>
  <ul class="project-bullets">
    <li>Addressed severe clinical outcome class imbalance using SMOTE and selected the top 22 most informative predictors from 111 variables via LASSO and Random Forest Recursive Feature Elimination (RF-RFE).</li>
    <li>Trained multiple baseline models (Logistic Regression, kNN, Gradient Boosting, Random Forest, and XGBoost) with 10-fold cross-validation, ensembling predictions via GLM and Random Forest meta-learners.</li>
    <li>Achieved 0.87 test accuracy, 0.93 F1-score, and 0.81 ROC-AUC with the stacked Random Forest architecture, attaining 97.4% sensitivity in identifying fatal cases.</li>
  </ul>
</section>

<section class="project-item">
  <h2 class="project-title">Unsupervised Transcriptomic Subgroup Discovery in Leukemia</h2>
  <div class="project-skills">
    <span class="skill-tag">Python</span>
    <span class="skill-tag">Machine Learning</span>
  </div>
  <ul class="project-bullets">
    <li>Filtered 22,000 microarray gene probes down to the top 1,000 high-variance features and extracted lower-dimensional transcriptomic embeddings using PCA, t-SNE, and UMAP.</li>
    <li>Clustered the reduced feature space using K-Means, Agglomerative Hierarchical Clustering, and Gaussian Mixture Models (GMM), reaching 0.85 Normalized Mutual Information (NMI) with a BIC-optimized 8-cluster GMM.</li>
    <li>Identified 988 statistically significant subgroup biomarker probes via ANOVA F-testing with Benjamini-Hochberg False Discovery Rate (FDR) correction.</li>
  </ul>
</section>

<section class="project-item">
  <h2 class="project-title">Survival Analysis of Systolic Blood Pressure & Mortality</h2>
  <div class="project-skills">
    <span class="skill-tag">SAS</span>
    <span class="skill-tag">Survival Analysis</span>
  </div>
  <ul class="project-bullets">
    <li>Analyzed 22-year longitudinal mortality data across 2,000 Framingham Heart Study cohort patients using multivariate Cox Proportional Hazards modeling and AIC-driven stepwise selection.</li>
    <li>Evaluated Proportional Hazards assumptions via Schoenfeld residuals and time-varying diagnostic plots, resolving detected violations through age stratification.</li>
    <li>Estimated an adjusted Hazard Ratio (aHR) of 1.014 (p &lt; 0.0001), quantifying a 1.4% increase in mortality risk per unit increase in systolic blood pressure.</li>
  </ul>
</section>

<section class="project-item">
  <h2 class="project-title">Financial Time Series Forecasting and Risk Analysis</h2>
  <div class="project-skills">
    <span class="skill-tag">Python</span>
    <span class="skill-tag">Time Series</span>
    <span class="skill-tag">Deep Learning</span>
  </div>
  <ul class="project-bullets">
    <li>Preprocessed and engineered 10 years of historical market data for equity and fixed-income assets (TSLA, SPY, and BND), computing rolling volatility and return statistics.</li>
    <li>Built and tuned comparative time series forecasting pipelines evaluating classical statistical models (ARIMA and SARIMA) against deep learning architectures (LSTM).</li>
  </ul>
</section>
