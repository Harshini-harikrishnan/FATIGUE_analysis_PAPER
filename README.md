# 🧠 Neurobehavioral Fatigue Assessment Model (NFAM)
A data-driven, explainable framework for quantifying cognitive fatigue, digital overload, and sleep efficiency in academic populations using behavioral analytics.

📌 Overview
The Neurobehavioral Fatigue Assessment Model (NFAM) is a computational framework designed to assess mental fatigue and neurobehavioral risk among students using non-intrusive, questionnaire-derived behavioral data.
Unlike traditional mental health scales that rely solely on subjective self-reports, NFAM integrates mathematical indices, statistical validation, machine learning, and explainability to provide both risk quantification and actionable insights.

The framework produces:
-Continuous fatigue scores
-Categorical risk levels
-Behavioral archetypes
-Individual-level explanations with recommendations

🎯 Key Contributions:
📐 Mathematical Modeling of neurobehavioral fatigue using:
-Cognitive Fatigue Index (CFI)
-Digital Overload Multiplier (DOM)
-Sleep Efficiency Model (SEM)
🧩 Unified Composite Risk Score (NFAM) with empirically validated weights
🧠 Behavioral Archetype Discovery using clustering and PCA
🤖 High-accuracy Predictive Models for fatigue risk classification
🔍 Explainable AI (LIME) for individual-level reasoning and prescriptive insights
📊 Statistical Validation using regression, ANOVA, correlation analysis, and sensitivity testing

🧠 NFAM Framework Components:
1️⃣ Cognitive Fatigue Index (CFI)
-Quantifies attentional strain, distraction, screen exposure, study inconsistency, and sleep deprivation.
2️⃣ Digital Overload Multiplier (DOM)
-Models the compounding effect of excessive digital usage relative to academic engagement.
3️⃣ Sleep Efficiency Model (SEM)
-Estimates sleep quality using lifestyle indicators such as exercise, screen exposure, daytime sleepiness, and commute burden.
4️⃣ NFAM Composite Score
-A weighted integration of CFI, DOM, and SEM that represents overall neurobehavioral fatigue risk.

📁 Repository Structure:
📦 NFAM
 ┣ 📂 data
 ┃ ┣ Mental_Health_Survey_VIT_1000_FINAL.xlsx
 ┃ ┗ processed_dataset.csv
 ┣ 📂 notebooks
 ┃ ┣ NFAM_Framework_Implementation.ipynb
 ┣ 📂 jpeg
 ┃ ┣ figures
 ┃ ┗ lime_reports
 ┣ 📂 jmp_analysis
 ┃ ┣ jmp_files
 ┃ ┗ sheets
 ┣ README.md
 ┗ requirements.txt

🧪 Methodology Summary:
-Survey-based Data Collection (academic, digital, sleep, lifestyle factors)
-Data Cleaning & Normalization
-Index Computation (CFI, DOM, SEM)
-NFAM Composite Integration
-Risk Stratification (Low, Moderate, High, Critical)
-Behavioral Archetype Clustering
-Predictive Modeling (Random Forest, XGBoost)
-Explainability via LIME
-Statistical Validation (Regression, ANOVA, PCA)

📊 Evaluation Metrics:
-Accuracy & Cross-Validation Accuracy
-Regression R² and significance testing
-Silhouette score (clustering)
-ANOVA p-values for risk separation
-LIME feature contributions for explainability

🔍 Explainability:
The framework incorporates LIME (Local Interpretable Model-Agnostic Explanations) to:
-Explain why an individual was assigned a risk level
-Identify dominant fatigue contributors (risk vs protective factors)
-Generate actionable behavioral recommendations

Each explanation is exported as:
-Interactive HTML visualization
-Textual justification summary

🖥 Tools & Technologies
-Python (pandas, numpy, scikit-learn, xgboost)
-Explainable AI (LIME)
-Statistical Analysis (JMP, Python)
-Visualization (matplotlib, seaborn)
-Dimensionality Reduction (PCA)

📈 Results Snapshot
-High classification accuracy (>98%) using only three NFAM components
-Statistically significant separation between risk groups (p < 0.001)
-Distinct behavioral archetypes identified within moderate-risk populations
-Transparent individual-level explanations enabling targeted interventions

🚀 Applications
-Student mental health monitoring
-Early fatigue risk screening
-Personalized academic and lifestyle interventions
-Institutional wellness analytics
-Educational policy planning
